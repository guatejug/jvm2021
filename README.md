# Encuesta JVM GuateJUG 2021

<script src="https://d3js.org/d3.v7.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/nvd3/1.8.6/nv.d3.min.js" integrity="sha512-ldXL88WIgBA+vAsJu2PepKp3VUvwuyqmXKEbcf8rKeAI56K8GZMb2jfKSm1a36m5AfUzyDp3TIY0iVKY8ciqSg==" crossorigin="anonymous" referrerpolicy="no-referrer"></script>
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/nvd3/1.8.6/nv.d3.css" integrity="sha512-sE0lXJVucHTljwWwIjHMf0dUV5EQ+S3FjCsTqWRhXieDW5oJ1ng0bGjLGer6xYF3yRISIptJ5ds64xFG9KSLJg==" crossorigin="anonymous" referrerpolicy="no-referrer" />
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.1/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-F3w7mX95PdgyTmZZMECAngseQB83DfGTowi0iMjiWaeVhAn4FJkqJByhZMI3AhiU" crossorigin="anonymous">
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.1/dist/js/bootstrap.bundle.min.js" integrity="sha384-/bQdsTh/da6pkI1MST/rWKFNjaCP5gBSY4sEBT38Q/9RBh9AH40zEOg7Hlq2THRZ" crossorigin="anonymous"></script>

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

<div class="container">
  <div class="row">
    <div class="col">
        <svg height="300" width="100%" class="nvd3-svg"><g class="nvd3 nv-wrap nv-multiBarWithLegend" transform="translate(60,30)"><g><g class="nv-x nv-axis nvd3-svg" transform="translate(0,220)"><g class="nvd3 nv-wrap nv-axis"><g><g class="tick" style="opacity: 1;" transform="translate(56.801170349121094,0)"><line y2="-220" style="opacity: 1;" x2="0"></line><text dy=".71em" style="text-anchor: middle; opacity: 1;" y="7" transform="translate(0,0)" x="0">1</text></g><g class="tick" style="opacity: 1;" transform="translate(160.07601928710938,0)"><line y2="-220" style="opacity: 1;" x2="0"></line><text dy=".71em" style="text-anchor: middle; opacity: 1;" y="7" transform="translate(0,0)" x="0">2</text></g><g class="tick" style="opacity: 1;" transform="translate(263.35089111328125,0)"><line y2="-220" style="opacity: 1;" x2="0"></line><text dy=".71em" style="text-anchor: middle; opacity: 1;" y="7" transform="translate(0,0)" x="0">3</text></g><g class="tick" style="opacity: 1;" transform="translate(366.625732421875,0)"><line y2="-220" style="opacity: 1;" x2="0"></line><text dy=".71em" style="text-anchor: middle; opacity: 1;" y="7" transform="translate(0,0)" x="0">4</text></g><g class="tick" style="opacity: 1;" transform="translate(469.90057373046875,0)"><line y2="-220" style="opacity: 1;" x2="0"></line><text dy=".71em" style="text-anchor: middle; opacity: 1;" y="7" transform="translate(0,0)" x="0">5</text></g><g class="tick" style="opacity: 1;" transform="translate(573.1754150390625,0)"><line y2="-220" style="opacity: 1;" x2="0"></line><text dy=".71em" style="text-anchor: middle; opacity: 1;" y="7" transform="translate(0,0)" x="0">6</text></g><g class="tick" style="opacity: 1;" transform="translate(676.4503173828125,0)"><line y2="-220" style="opacity: 1;" x2="0"></line><text dy=".71em" style="text-anchor: middle; opacity: 1;" y="7" transform="translate(0,0)" x="0">7</text></g><g class="tick" style="opacity: 1;" transform="translate(779.7251586914062,0)"><line y2="-220" style="opacity: 1;" x2="0"></line><text dy=".71em" style="text-anchor: middle; opacity: 1;" y="7" transform="translate(0,0)" x="0">8</text></g><g class="tick" style="opacity: 1;" transform="translate(883,0)"><line y2="-220" style="opacity: 1;" x2="0"></line><text dy=".71em" style="text-anchor: middle; opacity: 1;" y="7" transform="translate(0,0)" x="0">9</text></g><g class="tick" style="opacity: 1;" transform="translate(986.2748413085938,0)"><line y2="-220" style="opacity: 1;" x2="0"></line><text dy=".71em" style="text-anchor: middle; opacity: 1;" y="7" transform="translate(0,0)" x="0">10</text></g><g class="tick" style="opacity: 1;" transform="translate(1089.5496826171875,0)"><line y2="-220" style="opacity: 1;" x2="0"></line><text dy=".71em" style="text-anchor: middle; opacity: 1;" y="7" transform="translate(0,0)" x="0">11</text></g><g class="tick" style="opacity: 1;" transform="translate(1192.8245849609375,0)"><line y2="-220" style="opacity: 1;" x2="0"></line><text dy=".71em" style="text-anchor: middle; opacity: 1;" y="7" transform="translate(0,0)" x="0">12</text></g><g class="tick" style="opacity: 1;" transform="translate(1296.099365234375,0)"><line y2="-220" style="opacity: 1;" x2="0"></line><text dy=".71em" style="text-anchor: middle; opacity: 1;" y="7" transform="translate(0,0)" x="0">13</text></g><g class="tick" style="opacity: 1;" transform="translate(1399.374267578125,0)"><line y2="-220" style="opacity: 1;" x2="0"></line><text dy=".71em" style="text-anchor: middle; opacity: 1;" y="7" transform="translate(0,0)" x="0">15</text></g><g class="tick" style="opacity: 1;" transform="translate(1502.649169921875,0)"><line y2="-220" style="opacity: 1;" x2="0"></line><text dy=".71em" style="text-anchor: middle; opacity: 1;" y="7" transform="translate(0,0)" x="0">16</text></g><g class="tick" style="opacity: 1;" transform="translate(1605.9239501953125,0)"><line y2="-220" style="opacity: 1;" x2="0"></line><text dy=".71em" style="text-anchor: middle; opacity: 1;" y="7" transform="translate(0,0)" x="0">20</text></g><g class="tick" style="opacity: 1;" transform="translate(1709.1988525390625,0)"><line y2="-220" style="opacity: 1;" x2="0"></line><text dy=".71em" style="text-anchor: middle; opacity: 1;" y="7" transform="translate(0,0)" x="0">24</text></g><path class="domain" d="M0,0V0H1766V0"></path><text class="nv-axislabel" text-anchor="middle" y="36" x="883.0000000000001" style="opacity: 1;"></text></g></g></g><g class="nv-y nv-axis nvd3-svg"><g class="nvd3 nv-wrap nv-axis"><g><g class="tick zero" style="opacity: 1;" transform="translate(0,220)"><line x2="1766" y2="0"></line><text dy=".32em" style="text-anchor: end;" x="-3" opacity="0" y="0">0</text></g><g class="tick" style="opacity: 1;" transform="translate(0,188.57142639160156)"><line x2="1766" y2="0"></line><text dy=".32em" style="text-anchor: end;" x="-3" opacity="1" y="0">2</text></g><g class="tick" style="opacity: 1;" transform="translate(0,157.14285278320312)"><line x2="1766" y2="0"></line><text dy=".32em" style="text-anchor: end;" x="-3" opacity="1" y="0">4</text></g><g class="tick" style="opacity: 1;" transform="translate(0,125.71428680419922)"><line x2="1766" y2="0"></line><text dy=".32em" style="text-anchor: end;" x="-3" opacity="1" y="0">6</text></g><g class="tick" style="opacity: 1;" transform="translate(0,94.28571319580078)"><line x2="1766" y2="0"></line><text dy=".32em" style="text-anchor: end;" x="-3" opacity="1" y="0">8</text></g><g class="tick" style="opacity: 1;" transform="translate(0,62.85714340209961)"><line x2="1766" y2="0"></line><text dy=".32em" style="text-anchor: end;" x="-3" opacity="1" y="0">10</text></g><g class="tick" style="opacity: 1;" transform="translate(0,31.428571701049805)"><line x2="1766" y2="0"></line><text dy=".32em" style="text-anchor: end;" x="-3" opacity="1" y="0">12</text></g><g class="tick" style="opacity: 1;" transform="translate(0,0)" opacity="0"><line x2="1766" y2="0"></line><text dy=".32em" style="text-anchor: end;" x="-3" opacity="0" y="0">14</text></g><path class="domain" d="M0,0H0V220H0"></path><text class="nv-axislabel" style="text-anchor: middle;" transform="rotate(-90)" y="-100" x="-110"></text></g><g class="nv-axisMaxMin nv-axisMaxMin-y nv-axisMin-y" transform="translate(0,220)"><text style="opacity: 1;" dy=".32em" y="0" x="-3" text-anchor="end">0</text></g><g class="nv-axisMaxMin nv-axisMaxMin-y nv-axisMax-y" transform="translate(0,0)"><text style="opacity: 1;" dy=".32em" y="0" x="-3" text-anchor="end">14</text></g></g></g><g class="nv-barsWrap nvd3-svg"><g class="nvd3 nv-wrap nv-multibar" transform="translate(0,0)"><defs><clipPath id="nv-edge-clip-9226"><rect width="1766" height="220"></rect></clipPath></defs><g clip-path="url(#nv-edge-clip-9226)"><g class="nv-groups"><g style="stroke-opacity: 1; fill-opacity: 0.75; fill: rgb(31, 119, 180); stroke: rgb(31, 119, 180);" class="nv-group nv-series-0"><rect class="nv-bar positive" x="0" y="78.57142857142856" height="141.42857142857144" width="92.94736842105264" transform="translate(10.327485380116961,0)" style="fill: rgb(31, 119, 180); stroke: rgb(31, 119, 180);"></rect><rect class="nv-bar positive" x="0" y="94.28571428571429" height="125.71428571428571" width="92.94736842105264" transform="translate(113.60233918128657,0)" style="fill: rgb(31, 119, 180); stroke: rgb(31, 119, 180);"></rect><rect class="nv-bar positive" x="0" y="78.57142857142856" height="141.42857142857144" width="92.94736842105264" transform="translate(216.87719298245617,0)" style="fill: rgb(31, 119, 180); stroke: rgb(31, 119, 180);"></rect><rect class="nv-bar positive" x="0" y="0" height="220" width="92.94736842105264" transform="translate(320.1520467836258,0)" style="fill: rgb(31, 119, 180); stroke: rgb(31, 119, 180);"></rect><rect class="nv-bar positive" x="0" y="78.57142857142856" height="141.42857142857144" width="92.94736842105264" transform="translate(423.42690058479536,0)" style="fill: rgb(31, 119, 180); stroke: rgb(31, 119, 180);"></rect><rect class="nv-bar positive" x="0" y="110" height="110" width="92.94736842105264" transform="translate(526.7017543859649,0)" style="fill: rgb(31, 119, 180); stroke: rgb(31, 119, 180);"></rect><rect class="nv-bar positive" x="0" y="157.14285714285714" height="62.85714285714286" width="92.94736842105264" transform="translate(629.9766081871346,0)" style="fill: rgb(31, 119, 180); stroke: rgb(31, 119, 180);"></rect><rect class="nv-bar positive" x="0" y="94.28571428571429" height="125.71428571428571" width="92.94736842105264" transform="translate(733.2514619883042,0)" style="fill: rgb(31, 119, 180); stroke: rgb(31, 119, 180);"></rect><rect class="nv-bar positive" x="0" y="172.85714285714286" height="47.14285714285714" width="92.94736842105264" transform="translate(836.5263157894738,0)" style="fill: rgb(31, 119, 180); stroke: rgb(31, 119, 180);"></rect><rect class="nv-bar positive" x="0" y="47.142857142857146" height="172.85714285714286" width="92.94736842105264" transform="translate(939.8011695906433,0)" style="fill: rgb(31, 119, 180); stroke: rgb(31, 119, 180);"></rect><rect class="nv-bar positive" x="0" y="188.57142857142858" height="31.428571428571416" width="92.94736842105264" transform="translate(1043.076023391813,0)" style="fill: rgb(31, 119, 180); stroke: rgb(31, 119, 180);"></rect><rect class="nv-bar positive" x="0" y="204.2857142857143" height="15.714285714285694" width="92.94736842105264" transform="translate(1146.3508771929826,0)" style="fill: rgb(31, 119, 180); stroke: rgb(31, 119, 180);"></rect><rect class="nv-bar positive" x="0" y="204.2857142857143" height="15.714285714285694" width="92.94736842105264" transform="translate(1249.6257309941523,0)" style="fill: rgb(31, 119, 180); stroke: rgb(31, 119, 180);"></rect><rect class="nv-bar positive" x="0" y="188.57142857142858" height="31.428571428571416" width="92.94736842105264" transform="translate(1352.9005847953217,0)" style="fill: rgb(31, 119, 180); stroke: rgb(31, 119, 180);"></rect><rect class="nv-bar positive" x="0" y="188.57142857142858" height="31.428571428571416" width="92.94736842105264" transform="translate(1456.1754385964914,0)" style="fill: rgb(31, 119, 180); stroke: rgb(31, 119, 180);"></rect><rect class="nv-bar positive" x="0" y="141.42857142857142" height="78.57142857142858" width="92.94736842105264" transform="translate(1559.4502923976609,0)" style="fill: rgb(31, 119, 180); stroke: rgb(31, 119, 180);"></rect><rect class="nv-bar positive" x="0" y="204.2857142857143" height="15.714285714285694" width="92.94736842105264" transform="translate(1662.7251461988305,0)" style="fill: rgb(31, 119, 180); stroke: rgb(31, 119, 180);"></rect></g></g></g></g></g><g class="nv-legendWrap nvd3-svg" transform="translate(180,-30)"><g class="nvd3 nv-legend" transform="translate(0,5)"><g transform="translate(1525.3333339691162,5)"><g class="nv-series" transform="translate(0,5)"><circle style="stroke-width: 2px; fill: rgb(31, 119, 180); fill-opacity: 1; stroke: rgb(31, 119, 180);" class="nv-legend-symbol" r="5"></circle><text text-anchor="start" class="nv-legend-text" dy=".32em" dx="8" fill="#000">value</text></g></g></g></g><g class="nv-controlsWrap nvd3-svg" transform="translate(0,-30)"><g class="nvd3 nv-legend" transform="translate(0,5)"><g transform="translate(26,5)"><g class="nv-series" transform="translate(0,5)"><circle style="stroke-width: 2px; fill: rgb(68, 68, 68); fill-opacity: 1; stroke: rgb(68, 68, 68);" class="nv-legend-symbol" r="5"></circle><text text-anchor="start" class="nv-legend-text" dy=".32em" dx="8" fill="#000">Grouped</text></g><g class="nv-series" transform="translate(78.66666793823242,5)"><circle style="stroke-width: 2px; fill: rgb(68, 68, 68); fill-opacity: 0; stroke: rgb(68, 68, 68);" class="nv-legend-symbol" r="5"></circle><text text-anchor="start" class="nv-legend-text" dy=".32em" dx="8" fill="#000">Stacked</text></g></g></g></g><g class="nv-interactive"></g></g></g></svg>
    </div>
  </div>
</div>

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

<div class="container">
  <div class="row">
    <div class="col">
        <svg height="300" class="nvd3-svg"><g class="nvd3 nv-wrap nv-multiBarWithLegend" transform="translate(60,30)"><g><g class="nv-x nv-axis nvd3-svg" transform="translate(0,220)"><g class="nvd3 nv-wrap nv-axis"><g><g class="tick zero" style="opacity: 1;" transform="translate(80.27272727272727,0)"><line y2="-220" style="opacity: 1;" x2="0"></line><text dy=".71em" style="text-anchor: middle; opacity: 1;" y="7" transform="translate(0,0)" x="0">Amazon Corretto</text></g><g class="tick zero" style="opacity: 1;" transform="translate(226.22314049586777,0)"><line y2="-220" style="opacity: 1;" x2="0"></line><text dy=".71em" style="text-anchor: middle; opacity: 1;" y="7" transform="translate(0,0)" x="0">Azul Zulu/Zing</text></g><g class="tick zero" style="opacity: 1;" transform="translate(372.1735537190082,0)"><line y2="-220" style="opacity: 1;" x2="0"></line><text dy=".71em" style="text-anchor: middle; opacity: 1;" y="7" transform="translate(0,0)" x="0">Eclipse Adoptium/AdoptOpenJDK</text></g><g class="tick zero" style="opacity: 1;" transform="translate(518.1239669421487,0)"><line y2="-220" style="opacity: 1;" x2="0"></line><text dy=".71em" style="text-anchor: middle; opacity: 1;" y="7" transform="translate(0,0)" x="0">IBM Semeru/Open J9</text></g><g class="tick zero" style="opacity: 1;" transform="translate(664.0743801652892,0)"><line y2="-220" style="opacity: 1;" x2="0"></line><text dy=".71em" style="text-anchor: middle; opacity: 1;" y="7" transform="translate(0,0)" x="0">Liberica JDK</text></g><g class="tick zero" style="opacity: 1;" transform="translate(810.0247933884297,0)"><line y2="-220" style="opacity: 1;" x2="0"></line><text dy=".71em" style="text-anchor: middle; opacity: 1;" y="7" transform="translate(0,0)" x="0">Microsoft build of OpenJDK</text></g><g class="tick zero" style="opacity: 1;" transform="translate(955.9752066115702,0)"><line y2="-220" style="opacity: 1;" x2="0"></line><text dy=".71em" style="text-anchor: middle; opacity: 1;" y="7" transform="translate(0,0)" x="0">Open JDK via sdkman</text></g><g class="tick zero" style="opacity: 1;" transform="translate(1101.9256198347107,0)"><line y2="-220" style="opacity: 1;" x2="0"></line><text dy=".71em" style="text-anchor: middle; opacity: 1;" y="7" transform="translate(0,0)" x="0">OpenJDK en mi distribución Linux</text></g><g class="tick zero" style="opacity: 1;" transform="translate(1247.8760330578511,0)"><line y2="-220" style="opacity: 1;" x2="0"></line><text dy=".71em" style="text-anchor: middle; opacity: 1;" y="7" transform="translate(0,0)" x="0">Oracle GraalVM</text></g><g class="tick zero" style="opacity: 1;" transform="translate(1393.8264462809916,0)"><line y2="-220" style="opacity: 1;" x2="0"></line><text dy=".71em" style="text-anchor: middle; opacity: 1;" y="7" transform="translate(0,0)" x="0">Oracle JDK</text></g><g class="tick zero" style="opacity: 1;" transform="translate(1539.776859504132,0)"><line y2="-220" style="opacity: 1;" x2="0"></line><text dy=".71em" style="text-anchor: middle; opacity: 1;" y="7" transform="translate(0,0)" x="0">Oracle OpenJDK</text></g><g class="tick zero" style="opacity: 1;" transform="translate(1685.7272727272725,0)"><line y2="-220" style="opacity: 1;" x2="0"></line><text dy=".71em" style="text-anchor: middle; opacity: 1;" y="7" transform="translate(0,0)" x="0">Red Hat OpenJDK</text></g><path class="domain" d="M0,0V0H1766V0"></path><text class="nv-axislabel" text-anchor="middle" y="36" x="882.9999999999999" style="opacity: 1;"></text></g></g></g><g class="nv-y nv-axis nvd3-svg"><g class="nvd3 nv-wrap nv-axis"><g><g class="tick zero" style="opacity: 1;" transform="translate(0,220)"><line x2="1766" y2="0"></line><text dy=".32em" style="text-anchor: end;" x="-3" opacity="0" y="0">0</text></g><g class="tick" style="opacity: 1;" transform="translate(0,191.7948717948718)"><line x2="1766" y2="0"></line><text dy=".32em" style="text-anchor: end;" x="-3" opacity="1" y="0">10</text></g><g class="tick" style="opacity: 1;" transform="translate(0,163.5897435897436)"><line x2="1766" y2="0"></line><text dy=".32em" style="text-anchor: end;" x="-3" opacity="1" y="0">20</text></g><g class="tick" style="opacity: 1;" transform="translate(0,135.3846153846154)"><line x2="1766" y2="0"></line><text dy=".32em" style="text-anchor: end;" x="-3" opacity="1" y="0">30</text></g><g class="tick" style="opacity: 1;" transform="translate(0,107.17948717948718)"><line x2="1766" y2="0"></line><text dy=".32em" style="text-anchor: end;" x="-3" opacity="1" y="0">40</text></g><g class="tick" style="opacity: 1;" transform="translate(0,78.97435897435896)"><line x2="1766" y2="0"></line><text dy=".32em" style="text-anchor: end;" x="-3" opacity="1" y="0">50</text></g><g class="tick" style="opacity: 1;" transform="translate(0,50.76923076923076)"><line x2="1766" y2="0"></line><text dy=".32em" style="text-anchor: end;" x="-3" opacity="1" y="0">60</text></g><g class="tick" style="opacity: 1;" transform="translate(0,22.56410256410256)"><line x2="1766" y2="0"></line><text dy=".32em" style="text-anchor: end;" x="-3" opacity="1" y="0">70</text></g><path class="domain" d="M0,0H0V220H0"></path><text class="nv-axislabel" style="text-anchor: middle;" transform="rotate(-90)" y="-100" x="-110"></text></g><g class="nv-axisMaxMin nv-axisMaxMin-y nv-axisMin-y" transform="translate(0,220)"><text style="opacity: 1;" dy=".32em" y="0" x="-3" text-anchor="end">0</text></g><g class="nv-axisMaxMin nv-axisMaxMin-y nv-axisMax-y" transform="translate(0,0)"><text style="opacity: 1;" dy=".32em" y="0" x="-3" text-anchor="end">78</text></g></g></g><g class="nv-barsWrap nvd3-svg"><g class="nvd3 nv-wrap nv-multibar" transform="translate(0,0)"><defs><clipPath id="nv-edge-clip-1865"><rect width="1766" height="220"></rect></clipPath></defs><g clip-path="url(#nv-edge-clip-5772)"><g class="nv-groups"><g style="stroke-opacity: 1; fill-opacity: 0.75; fill: rgb(31, 119, 180); stroke: rgb(31, 119, 180);" class="nv-group nv-series-0"><rect class="nv-bar positive" x="0" y="203.0769230769231" height="16.923076923076906" width="131.35537190082644" transform="translate(14.59504132231405,0)" style="fill: rgb(31, 119, 180); stroke: rgb(31, 119, 180);"></rect><rect class="nv-bar positive" x="0" y="191.7948717948718" height="28.205128205128204" width="131.35537190082644" transform="translate(160.54545454545453,0)" style="fill: rgb(31, 119, 180); stroke: rgb(31, 119, 180);"></rect><rect class="nv-bar positive" x="0" y="174.8717948717949" height="45.12820512820511" width="131.35537190082644" transform="translate(306.495867768595,0)" style="fill: rgb(31, 119, 180); stroke: rgb(31, 119, 180);"></rect><rect class="nv-bar positive" x="0" y="217.17948717948718" height="2.8205128205128176" width="131.35537190082644" transform="translate(452.44628099173553,0)" style="fill: rgb(31, 119, 180); stroke: rgb(31, 119, 180);"></rect><rect class="nv-bar positive" x="0" y="200.25641025641025" height="19.74358974358975" width="131.35537190082644" transform="translate(598.396694214876,0)" style="fill: rgb(31, 119, 180); stroke: rgb(31, 119, 180);"></rect><rect class="nv-bar positive" x="0" y="211.53846153846155" height="8.461538461538453" width="131.35537190082644" transform="translate(744.3471074380165,0)" style="fill: rgb(31, 119, 180); stroke: rgb(31, 119, 180);"></rect><rect class="nv-bar positive" x="0" y="217.17948717948718" height="2.8205128205128176" width="131.35537190082644" transform="translate(890.297520661157,0)" style="fill: rgb(31, 119, 180); stroke: rgb(31, 119, 180);"></rect><rect class="nv-bar positive" x="0" y="78.97435897435896" height="141.02564102564105" width="131.35537190082644" transform="translate(1036.2479338842975,0)" style="fill: rgb(31, 119, 180); stroke: rgb(31, 119, 180);"></rect><rect class="nv-bar positive" x="0" y="194.6153846153846" height="25.384615384615387" width="131.35537190082644" transform="translate(1182.198347107438,0)" style="fill: rgb(31, 119, 180); stroke: rgb(31, 119, 180);"></rect><rect class="nv-bar positive" x="0" y="0" height="220" width="131.35537190082644" transform="translate(1328.1487603305784,0)" style="fill: rgb(31, 119, 180); stroke: rgb(31, 119, 180);"></rect><rect class="nv-bar positive" x="0" y="217.17948717948718" height="2.8205128205128176" width="131.35537190082644" transform="translate(1474.0991735537189,0)" style="fill: rgb(31, 119, 180); stroke: rgb(31, 119, 180);"></rect><rect class="nv-bar positive" x="0" y="211.53846153846155" height="8.461538461538453" width="131.35537190082644" transform="translate(1620.0495867768593,0)" style="fill: rgb(31, 119, 180); stroke: rgb(31, 119, 180);"></rect></g></g></g></g></g><g class="nv-legendWrap nvd3-svg" transform="translate(180,-30)"><g class="nvd3 nv-legend" transform="translate(0,5)"><g transform="translate(1524.6666660308838,5)"><g class="nv-series" transform="translate(0,5)"><circle style="stroke-width: 2px; fill: rgb(31, 119, 180); fill-opacity: 1; stroke: rgb(31, 119, 180);" class="nv-legend-symbol" r="5"></circle><text text-anchor="start" class="nv-legend-text" dy=".32em" dx="8" fill="#000">count</text></g></g></g></g><g class="nv-controlsWrap nvd3-svg" transform="translate(0,-30)"><g class="nvd3 nv-legend" transform="translate(0,5)"><g transform="translate(26,5)"><g class="nv-series" transform="translate(0,5)"><circle style="stroke-width: 2px; fill: rgb(68, 68, 68); fill-opacity: 1; stroke: rgb(68, 68, 68);" class="nv-legend-symbol" r="5"></circle><text text-anchor="start" class="nv-legend-text" dy=".32em" dx="8" fill="#000">Grouped</text></g><g class="nv-series" transform="translate(78.66666793823242,5)"><circle style="stroke-width: 2px; fill: rgb(68, 68, 68); fill-opacity: 0; stroke: rgb(68, 68, 68);" class="nv-legend-symbol" r="5"></circle><text text-anchor="start" class="nv-legend-text" dy=".32em" dx="8" fill="#000">Stacked</text></g></g></g></g><g class="nv-interactive"></g></g></g></svg>
    </div>
  </div>
</div>

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

<div class="container">
  <div class="row">
    <div class="col">
        <svg height="300" class="nvd3-svg"><g class="nvd3 nv-wrap nv-multiBarWithLegend" transform="translate(60,30)"><g><g class="nv-x nv-axis nvd3-svg" transform="translate(0,220)"><g class="nvd3 nv-wrap nv-axis"><g><g class="tick zero" style="opacity: 1;" transform="translate(96.16831683168317,0)"><line y2="-220" style="opacity: 1;" x2="0"></line><text dy=".71em" style="text-anchor: middle; opacity: 1;" y="7" transform="translate(0,0)" x="0">Amazon Corretto</text></g><g class="tick zero" style="opacity: 1;" transform="translate(271.01980198019805,0)"><line y2="-220" style="opacity: 1;" x2="0"></line><text dy=".71em" style="text-anchor: middle; opacity: 1;" y="7" transform="translate(0,0)" x="0">Azul Zulu/Zing</text></g><g class="tick zero" style="opacity: 1;" transform="translate(445.8712871287129,0)"><line y2="-220" style="opacity: 1;" x2="0"></line><text dy=".71em" style="text-anchor: middle; opacity: 1;" y="7" transform="translate(0,0)" x="0">Eclipse Adoptium/AdoptOpenJDK</text></g><g class="tick zero" style="opacity: 1;" transform="translate(620.7227722772278,0)"><line y2="-220" style="opacity: 1;" x2="0"></line><text dy=".71em" style="text-anchor: middle; opacity: 1;" y="7" transform="translate(0,0)" x="0">IBM Semeru/Open J9</text></g><g class="tick zero" style="opacity: 1;" transform="translate(795.5742574257426,0)"><line y2="-220" style="opacity: 1;" x2="0"></line><text dy=".71em" style="text-anchor: middle; opacity: 1;" y="7" transform="translate(0,0)" x="0">LibericaJDK</text></g><g class="tick zero" style="opacity: 1;" transform="translate(970.4257425742575,0)"><line y2="-220" style="opacity: 1;" x2="0"></line><text dy=".71em" style="text-anchor: middle; opacity: 1;" y="7" transform="translate(0,0)" x="0">Microsoft build of OpenJDK</text></g><g class="tick zero" style="opacity: 1;" transform="translate(1145.2772277227723,0)"><line y2="-220" style="opacity: 1;" x2="0"></line><text dy=".71em" style="text-anchor: middle; opacity: 1;" y="7" transform="translate(0,0)" x="0">OpenJDK en mi distribución Linux</text></g><g class="tick zero" style="opacity: 1;" transform="translate(1320.128712871287,0)"><line y2="-220" style="opacity: 1;" x2="0"></line><text dy=".71em" style="text-anchor: middle; opacity: 1;" y="7" transform="translate(0,0)" x="0">Oracle GraalVM</text></g><g class="tick zero" style="opacity: 1;" transform="translate(1494.980198019802,0)"><line y2="-220" style="opacity: 1;" x2="0"></line><text dy=".71em" style="text-anchor: middle; opacity: 1;" y="7" transform="translate(0,0)" x="0">Oracle JDK</text></g><g class="tick zero" style="opacity: 1;" transform="translate(1669.8316831683169,0)"><line y2="-220" style="opacity: 1;" x2="0"></line><text dy=".71em" style="text-anchor: middle; opacity: 1;" y="7" transform="translate(0,0)" x="0">Red Hat OpenJDK</text></g><path class="domain" d="M0,0V0H1766V0"></path><text class="nv-axislabel" text-anchor="middle" y="36" x="883.0000000000001" style="opacity: 1;"></text></g></g></g><g class="nv-y nv-axis nvd3-svg"><g class="nvd3 nv-wrap nv-axis"><g><g class="tick zero" style="opacity: 1;" transform="translate(0,220)"><line x2="1766" y2="0"></line><text dy=".32em" style="text-anchor: end;" x="-3" opacity="0" y="0">0</text></g><g class="tick" style="opacity: 1;" transform="translate(0,185.0793650793651)"><line x2="1766" y2="0"></line><text dy=".32em" style="text-anchor: end;" x="-3" opacity="1" y="0">10</text></g><g class="tick" style="opacity: 1;" transform="translate(0,150.15873015873015)"><line x2="1766" y2="0"></line><text dy=".32em" style="text-anchor: end;" x="-3" opacity="1" y="0">20</text></g><g class="tick" style="opacity: 1;" transform="translate(0,115.23809523809524)"><line x2="1766" y2="0"></line><text dy=".32em" style="text-anchor: end;" x="-3" opacity="1" y="0">30</text></g><g class="tick" style="opacity: 1;" transform="translate(0,80.31746031746033)"><line x2="1766" y2="0"></line><text dy=".32em" style="text-anchor: end;" x="-3" opacity="1" y="0">40</text></g><g class="tick" style="opacity: 1;" transform="translate(0,45.396825396825406)"><line x2="1766" y2="0"></line><text dy=".32em" style="text-anchor: end;" x="-3" opacity="1" y="0">50</text></g><g class="tick" style="opacity: 1;" transform="translate(0,10.476190476190489)"><line x2="1766" y2="0"></line><text dy=".32em" style="text-anchor: end;" x="-3" opacity="1" y="0">60</text></g><path class="domain" d="M0,0H0V220H0"></path><text class="nv-axislabel" style="text-anchor: middle;" transform="rotate(-90)" y="-100" x="-110"></text></g><g class="nv-axisMaxMin nv-axisMaxMin-y nv-axisMin-y" transform="translate(0,220)"><text style="opacity: 1;" dy=".32em" y="0" x="-3" text-anchor="end">0</text></g><g class="nv-axisMaxMin nv-axisMaxMin-y nv-axisMax-y" transform="translate(0,0)"><text style="opacity: 1;" dy=".32em" y="0" x="-3" text-anchor="end">63</text></g></g></g><g class="nv-barsWrap nvd3-svg"><g class="nvd3 nv-wrap nv-multibar" transform="translate(0,0)"><defs><clipPath id="nv-edge-clip-2665"><rect width="1766" height="220"></rect></clipPath></defs><g clip-path="url(#nv-edge-clip-5782)"><g class="nv-groups"><g style="stroke-opacity: 1; fill-opacity: 0.75; fill: rgb(31, 119, 180); stroke: rgb(31, 119, 180);" class="nv-group nv-series-0"><rect class="nv-bar positive" x="0" y="202.53968253968256" height="17.46031746031744" width="157.36633663366337" transform="translate(17.485148514851485,0)" style="fill: rgb(31, 119, 180); stroke: rgb(31, 119, 180);"></rect><rect class="nv-bar positive" x="0" y="192.06349206349208" height="27.936507936507923" width="157.36633663366337" transform="translate(192.33663366336634,0)" style="fill: rgb(31, 119, 180); stroke: rgb(31, 119, 180);"></rect><rect class="nv-bar positive" x="0" y="192.06349206349208" height="27.936507936507923" width="157.36633663366337" transform="translate(367.18811881188117,0)" style="fill: rgb(31, 119, 180); stroke: rgb(31, 119, 180);"></rect><rect class="nv-bar positive" x="0" y="216.5079365079365" height="3.492063492063494" width="157.36633663366337" transform="translate(542.0396039603961,0)" style="fill: rgb(31, 119, 180); stroke: rgb(31, 119, 180);"></rect><rect class="nv-bar positive" x="0" y="206.03174603174602" height="13.968253968253975" width="157.36633663366337" transform="translate(716.8910891089109,0)" style="fill: rgb(31, 119, 180); stroke: rgb(31, 119, 180);"></rect><rect class="nv-bar positive" x="0" y="216.5079365079365" height="3.492063492063494" width="157.36633663366337" transform="translate(891.7425742574258,0)" style="fill: rgb(31, 119, 180); stroke: rgb(31, 119, 180);"></rect><rect class="nv-bar positive" x="0" y="66.34920634920636" height="153.65079365079364" width="157.36633663366337" transform="translate(1066.5940594059407,0)" style="fill: rgb(31, 119, 180); stroke: rgb(31, 119, 180);"></rect><rect class="nv-bar positive" x="0" y="209.52380952380952" height="10.476190476190482" width="157.36633663366337" transform="translate(1241.4455445544554,0)" style="fill: rgb(31, 119, 180); stroke: rgb(31, 119, 180);"></rect><rect class="nv-bar positive" x="0" y="0" height="220" width="157.36633663366337" transform="translate(1416.2970297029703,0)" style="fill: rgb(31, 119, 180); stroke: rgb(31, 119, 180);"></rect><rect class="nv-bar positive" x="0" y="188.57142857142858" height="31.428571428571416" width="157.36633663366337" transform="translate(1591.1485148514853,0)" style="fill: rgb(31, 119, 180); stroke: rgb(31, 119, 180);"></rect></g></g></g></g></g><g class="nv-legendWrap nvd3-svg" transform="translate(180,-30)"><g class="nvd3 nv-legend" transform="translate(0,5)"><g transform="translate(1524.6666660308838,5)"><g class="nv-series" transform="translate(0,5)"><circle style="stroke-width: 2px; fill: rgb(31, 119, 180); fill-opacity: 1; stroke: rgb(31, 119, 180);" class="nv-legend-symbol" r="5"></circle><text text-anchor="start" class="nv-legend-text" dy=".32em" dx="8" fill="#000">count</text></g></g></g></g><g class="nv-controlsWrap nvd3-svg" transform="translate(0,-30)"><g class="nvd3 nv-legend" transform="translate(0,5)"><g transform="translate(26,5)"><g class="nv-series" transform="translate(0,5)"><circle style="stroke-width: 2px; fill: rgb(68, 68, 68); fill-opacity: 1; stroke: rgb(68, 68, 68);" class="nv-legend-symbol" r="5"></circle><text text-anchor="start" class="nv-legend-text" dy=".32em" dx="8" fill="#000">Grouped</text></g><g class="nv-series" transform="translate(78.66666793823242,5)"><circle style="stroke-width: 2px; fill: rgb(68, 68, 68); fill-opacity: 0; stroke: rgb(68, 68, 68);" class="nv-legend-symbol" r="5"></circle><text text-anchor="start" class="nv-legend-text" dy=".32em" dx="8" fill="#000">Stacked</text></g></g></g></g><g class="nv-interactive"></g></g></g></svg>
    </div>
  </div>
</div>

## Version de Java

Vemos que la adopción de Java 11 ha crecido lentamente y (al menos en nuestra muestra) está a punto de igualar a Java 8. También hay una presencia importante de Java 7 a pesar de que lleva bastante tiempo sin soporte.

<div class="container">
  <div class="row">
    <div class="col">
      <svg height="300" class="nvd3-svg"><g class="nvd3 nv-wrap nv-multiBarWithLegend" transform="translate(60,30)"><g><g class="nv-x nv-axis nvd3-svg" transform="translate(0,220)"><g class="nvd3 nv-wrap nv-axis"><g><g class="tick zero" style="opacity: 1;" transform="translate(190.45098039215685,0)"><line y2="-220" style="opacity: 1;" x2="0"></line><text dy=".71em" style="text-anchor: middle; opacity: 1;" y="7" transform="translate(0,0)" x="0">16.0.1</text></g><g class="tick zero" style="opacity: 1;" transform="translate(536.7254901960785,0)"><line y2="-220" style="opacity: 1;" x2="0"></line><text dy=".71em" style="text-anchor: middle; opacity: 1;" y="7" transform="translate(0,0)" x="0">Java 11</text></g><g class="tick zero" style="opacity: 1;" transform="translate(883,0)"><line y2="-220" style="opacity: 1;" x2="0"></line><text dy=".71em" style="text-anchor: middle; opacity: 1;" y="7" transform="translate(0,0)" x="0">Java 17</text></g><g class="tick zero" style="opacity: 1;" transform="translate(1229.2745098039215,0)"><line y2="-220" style="opacity: 1;" x2="0"></line><text dy=".71em" style="text-anchor: middle; opacity: 1;" y="7" transform="translate(0,0)" x="0">Java 7 o anterior</text></g><g class="tick zero" style="opacity: 1;" transform="translate(1575.5490196078429,0)"><line y2="-220" style="opacity: 1;" x2="0"></line><text dy=".71em" style="text-anchor: middle; opacity: 1;" y="7" transform="translate(0,0)" x="0">Java 8</text></g><path class="domain" d="M0,0V0H1766V0"></path><text class="nv-axislabel" text-anchor="middle" y="36" x="882.9999999999999" style="opacity: 1;"></text></g></g></g><g class="nv-y nv-axis nvd3-svg"><g class="nvd3 nv-wrap nv-axis"><g><g class="tick zero" style="opacity: 1;" transform="translate(0,220)"><line x2="1766" y2="0"></line><text dy=".32em" style="text-anchor: end;" x="-3" opacity="0" y="0">0</text></g><g class="tick" style="opacity: 1;" transform="translate(0,164.30379746835442)"><line x2="1766" y2="0"></line><text dy=".32em" style="text-anchor: end;" x="-3" opacity="1" y="0">20</text></g><g class="tick" style="opacity: 1;" transform="translate(0,108.60759493670885)"><line x2="1766" y2="0"></line><text dy=".32em" style="text-anchor: end;" x="-3" opacity="1" y="0">40</text></g><g class="tick" style="opacity: 1;" transform="translate(0,52.91139240506328)"><line x2="1766" y2="0"></line><text dy=".32em" style="text-anchor: end;" x="-3" opacity="1" y="0">60</text></g><path class="domain" d="M0,0H0V220H0"></path><text class="nv-axislabel" style="text-anchor: middle;" transform="rotate(-90)" y="-100" x="-110"></text></g><g class="nv-axisMaxMin nv-axisMaxMin-y nv-axisMin-y" transform="translate(0,220)"><text style="opacity: 1;" dy=".32em" y="0" x="-3" text-anchor="end">0</text></g><g class="nv-axisMaxMin nv-axisMaxMin-y nv-axisMax-y" transform="translate(0,0)"><text style="opacity: 1;" dy=".32em" y="0" x="-3" text-anchor="end">79</text></g></g></g><g class="nv-barsWrap nvd3-svg"><g class="nvd3 nv-wrap nv-multibar" transform="translate(0,0)"><defs><clipPath id="nv-edge-clip-5533"><rect width="1766" height="220"></rect></clipPath></defs><g clip-path="url(#nv-edge-clip-6306)"><g class="nv-groups"><g style="stroke-opacity: 1; fill-opacity: 0.75; fill: rgb(31, 119, 180); stroke: rgb(31, 119, 180);" class="nv-group nv-series-0"><rect class="nv-bar positive" x="0" y="217.21518987341773" height="2.784810126582272" width="311.6470588235294" transform="translate(34.627450980392155,0)" style="fill: rgb(31, 119, 180); stroke: rgb(31, 119, 180);"></rect><rect class="nv-bar positive" x="0" y="64.0506329113924" height="155.9493670886076" width="311.6470588235294" transform="translate(380.9019607843137,0)" style="fill: rgb(31, 119, 180); stroke: rgb(31, 119, 180);"></rect><rect class="nv-bar positive" x="0" y="192.15189873417722" height="27.848101265822777" width="311.6470588235294" transform="translate(727.1764705882352,0)" style="fill: rgb(31, 119, 180); stroke: rgb(31, 119, 180);"></rect><rect class="nv-bar positive" x="0" y="164.30379746835442" height="55.69620253164558" width="311.6470588235294" transform="translate(1073.450980392157,0)" style="fill: rgb(31, 119, 180); stroke: rgb(31, 119, 180);"></rect><rect class="nv-bar positive" x="0" y="0" height="220" width="311.6470588235294" transform="translate(1419.7254901960782,0)" style="fill: rgb(31, 119, 180); stroke: rgb(31, 119, 180);"></rect></g></g></g></g></g><g class="nv-legendWrap nvd3-svg" transform="translate(180,-30)"><g class="nvd3 nv-legend" transform="translate(0,5)"><g transform="translate(1524.6666660308838,5)"><g class="nv-series" transform="translate(0,5)"><circle style="stroke-width: 2px; fill: rgb(31, 119, 180); fill-opacity: 1; stroke: rgb(31, 119, 180);" class="nv-legend-symbol" r="5"></circle><text text-anchor="start" class="nv-legend-text" dy=".32em" dx="8" fill="#000">count</text></g></g></g></g><g class="nv-controlsWrap nvd3-svg" transform="translate(0,-30)"><g class="nvd3 nv-legend" transform="translate(0,5)"><g transform="translate(26,5)"><g class="nv-series" transform="translate(0,5)"><circle style="stroke-width: 2px; fill: rgb(68, 68, 68); fill-opacity: 0; stroke: rgb(68, 68, 68);" class="nv-legend-symbol" r="5"></circle><text text-anchor="start" class="nv-legend-text" dy=".32em" dx="8" fill="#000">Grouped</text></g><g class="nv-series" transform="translate(78.66666793823242,5)"><circle style="stroke-width: 2px; fill: rgb(68, 68, 68); fill-opacity: 1; stroke: rgb(68, 68, 68);" class="nv-legend-symbol" r="5"></circle><text text-anchor="start" class="nv-legend-text" dy=".32em" dx="8" fill="#000">Stacked</text></g></g></g></g><g class="nv-interactive"></g></g></g></svg>
    </div>
  </div>
</div>
