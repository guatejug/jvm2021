# Encuesta JVM GuateJUG 2021

## Datos generales

* **Total de participantes:** 107
* **Fecha de apertura de encuesta:** 2021-10-01
* **Fecha de cierre de encuesta:** 2021-09-21

Todas las preguntas abajo listadas a excepción de la edad aceptaban respuestas multiples (y pueden sumar más de 107), la encuesta se elaboró bajo la premisa de que muchos desarrolladores cuentan con más de un équipo, sistema operativo o máquina virtual de Java.

## Edad participantes

Contrario a lo que muchos piensan, *la comunidad Java de Guatemala es una comunidad relativamente joven*, vemos que existe una alta concentración en personas que tienen menos de 10 años utilizando Java, considerando que Java tiene 26 años esto puede tener diversas interpretaciones, tales como:

* Java no era muy utilizado en sus inicios en Guatemala
* Las personas dejan de programar despues de 10 años

|age|value|
|---|---|
|1|9|
|2|8|
|3|9|
|4|14|
|5|9|
|6|7|
|7|4|
|8|8|
|9|3|
|10|11|
|11|2|
|12|1|
|13|1|
|15|2|
|16|2|
|20|5|
|24|1|

![Edad graph](./edad.svg)
<img src="./edad.svg">

## JVM utilizada en desarrollo

Aca la conclusión es bastante sencilla, a pesar del cambio de licencia de Java 11 la comunidad Guatemalteca sigue prefiriendo la máquina virtual de Java de Oracle. Vale la pena resaltar que las personas que utilizan Linux tambien suelen utilizar la JVM disponible en sus repositorios que generalmente es una compilación de OpenJDK.

|jvmDev|count|
|---|---|
|Amazon Corretto|6|
|Azul Zulu/Zing|10|
|Eclipse Adoptium/AdoptOpenJDK|16|
|IBM Semeru/Open J9|1|
|Liberica JDK|7|
|Microsoft build of OpenJDK|3|
|Open JDK via sdkman|1|
|OpenJDK en mi distribución Linux|50|
|Oracle GraalVM|9|
|Oracle JDK|78|
|Oracle OpenJDK|1|
|Red Hat OpenJDK|3|

![JVM Dev](./jvmdev.svg)
<img src="./jvmdev.svg">

## JVM utilizada en producción

En línea con la pregunta anterior, la comunidad Guatemalteca sigue prefiriendo la máquina virtual de Java de Oracle. Lo resaltable aca es que existe menos diversidad de JVM en producción.

|jvmProd|count|
|---|---|
|Amazon Corretto|5|
|Azul Zulu/Zing|8|
|Eclipse Adoptium/AdoptOpenJDK|8|
|IBM Semeru/Open J9|1|
|LibericaJDK|4|
|Microsoft build of OpenJDK|1|
|OpenJDK en mi distribución Linux|44|
|Oracle GraalVM|3|
|Oracle JDK|63|
|Red Hat OpenJDK|9|

![JVM Prod](./jvmprod.svg)
<img src="./jvmprod.svg">