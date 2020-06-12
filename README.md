# diplodatos2020

## Título
Ciencias de datos aplicada a diálogos entre estudiantes y docentes

## Mentora
Luciana Benotti https://www.linkedin.com/in/luciana-benotti/

## 1. Descripción
En este proyecto aplicaremos distintas técnicas y conceptos de data science que se  aprenden durante la diplomatura para familiarizarnos con un dataset de diálogos entre estudiantes y docentes e investigaremos las preguntas que se describen en la sección 3. En particular este proyecto se orienta a analizar cuán exitoso es un diálogo entre un estudiante y un docente. El dataset que usaremos en este proyecto consiste de diálogos escritos y sincrónicos entre un docente y un estudiante a través de un app de mensajería instantánea similar a Whatsapp. El dataset fue recolectado por la empresa que contrata a los docentes y los pone en contacto con estudiantes a través de una app que desarrollaron para ese fin. Los docentes son tutores particulares, los estudiantes pueden conectarse en cualquier momento y pedir entrar en contacto con algún tutor a través de la app. Los diálogos son conversaciones cuyo objetivo es ayudar a los estudiantes a resolver las tareas de matemática, química y física de la escuela secundaria.  El dataset completo tiene 18K diálogos que suman 7K horas pero no lo usaremos completo para este proyecto. Como los diálogos se basan en didáctica "inquiry-based" los docentes hacen muchas preguntas. Hay 240K preguntas que anotamos en el dataset. Al finalizar el diálogo los estudiantes evalúan cuán satisfechos están con la clase particular con una nota de 1 a 5. Es un dataset grande, con timestamps en cada turno, con información demográfica de los participantes: género, edad, notas en exámenes, tipo de pago del servicio, país, etc. Los estudiantes son mayormente de Estados Unidos por lo que los diálogos están en inglés, los docentes son de todo el mundo y trabajan 100% remotos.

## 2. Este tema es interesante porque …
Las aplicaciones de mensajería instantánea permiten que los docente y los estudiantes interactúen aunque estén separados físicamente. Proveen un medio que facilita el aprendizaje, sobre todo si involucra un diálogo 1 a 1. Sin embargo, en este medio es difícil para el docente evaluar cuán bien el estudiante está siguiendo la conversación porque falta la co-presencia, las expresiones faciales, el tono de voz, etc. En este proyecto contamos con un gran dataset rico en metadata demográfica que nos permitirá explorar distintas características que influencian en un diálogo educativo exitoso. 
La empresa de Estados Unidos creadora de este dataset puede estar interesada en los resultados que obtengamos. Además, existen muchas plataforma de este tipo de educación a distancia, su cantidad está creciendo mucho.  

## 3. Trataremos de responder algunas de las siguientes preguntas:

A. Cuando uno piensa en el éxito de un diálogo educativo lo primero que consideramos es el desempeño del docente. Sin embargo, por teorías de las ciencias de la educación sabemos que la actitud y predisposición del estudiante juega un rol crucial. ¿Podemos ver en este dataset cómo la participacipación de los estudiantes influencia la nota que los estudiantes asignan a la clase?

B. Contamos con un dataset rico demográficamente. ¿Alguna característica demográfica del docente influencia el éxito de la clase? 

C. En los diálogos educativos ¿la primera impresión es lo que cuenta? Compararemos distintos fragmentos de los diálogos para analizar qué parte de la conversación tiene más influencia sobre el éxito de la clase usando técnicas simples como bolsas de palabras. ¿La cantidad y frecuencia de las preguntas del docente son relevantes? 

D. En ciencias de la educación se estudian diferentes grupos de estudiantes. Por ejemplo, se distingue entre estudiantes tinkerers (que usan mucha prueba y error) vs planners (que son más metódicos y planificados). ¿Podemos identificar en nuestros datos distintos grupos de estudiantes? 

E. En base a lo que aprendimos en las preguntas anteriores ¿Qué características nos ayudan a hacer mejores predicciones sobre el éxito de un diálogo? Aquí se podrían aplicar aprendizaje profundo, pero no es obligatorio.

F. Las ciencias de la educación nos dicen que es normal tener un profesor al que algunos estudiantes le entienden más pero otros no, ese otro grupo de estudiantes prefiere otro estilo de explicaciones. Si podemos identificar grupos de estudiantes, ¿estos grupos nos ayudan a encontrar mejores pares de estudiantes-docentes?

Esta última pregunta es posible trabajo futuro, no sería parte de la mentoría. Es para ejemplificar cómo el proyecto puede seguir. 


## 4. Los datos
Los datos están pre-procesados, tokenizados y ordenados, aunque falta curarlos para los objetivos específicos de este proyecto. Acá incluimos un pequeño fragmento de un diálogo.

TUTOR : I will be your instructor for this session. How far have you gotten in solving
the problem 5? 
(15 sec.)
STUDENT : I know b and d are rught
(15 sec.)
TUTOR : How do you know that? :) 
(67 sec.)
STUDENT : Because graphed it and the y intercept was 01. Also it can’t be a y intercept if it’s not 0.

Si querés inspeccionar el conjunto de datos en csv, encontrarás un fragmento en este link (visible sólo a cuentas @unc o @mi.unc, si tenés otra cuenta pedime permiso). En ese link sólo aparece un fragmento de los diálogos del dataset. No se incluye la información demográfica por cuestiones de privacidad. El dataset completo y anonimizado será compartido con los estudiantes que elijan este proyecto a través de un github privado. Así como la identidad de la empresa. 

## 5. Hitos de la mentoría
A partir del segundo hito (del 19/7) trabajaremos directamente en las preguntas presentadas en la Sección 3 de este documento.
 
29/6 práctico de análisis y visualización, que consistirá en analizar y visualizar estadísticas básicas del dataset. Cuántas conversaciones hay, cuántos mensajes, cuántos docentes, cuántos estudiantes, análisis de cantidad de mensajes por conversación, análisis de cantidad de por mensaje, análisis de datos demográficos de los docentes   
 
19/7 práctico de análisis y visualización, que consistirá en investigar la pregunta A

Los prácticos del 29/6 y del 19/7 serán entregados juntos el 19/7 pero el 19/6 y el 29/6 tendremos entregas parciales.
 
16/8 práctico de introducción al aprendizaje automático, que consistirá en investigar la pregunta B
 
13/9 práctico de aprendizaje supervisado, que consistirá en investigar la pregunta C
 
27/9 práctico de aprendizaje no supervisado, que consistirá en investigar la pregunta D
 
6/11/2020 – 7/11/2020 presentación de mentorías que consistirá en presentar lo que aprendimos sobre la pregunta E

 
