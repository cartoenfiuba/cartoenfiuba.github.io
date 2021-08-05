# Propósitos de Enseñanza

Cada vez que alguien nos ofrece una experiencia de aprendizaje, surge una
pregunta muy lógica ¿cómo nos vas a enseñar eso?

Por eso vamos a dejar aquí escritos nuestros propósitos de enseñanza, esas "cosas"
que pensamos hacer para lograr cumplir con los [objetivos de aprendizaje](../objetivos) que
ya les contamos.

Para tener un orden, vamos a contarles un poco de lo que vamos a hacer día por
día. En otro momento vamos a entrar en detalle sobre cada día del curso, adelantándoles
un poco el contenido, para ir poniéndonos en sintonía mientras esperamos a que llegue la fecha.

Esta propuesta que les dejamos trata de ser lo más ordenada posible, poder darles esto
es el objetivo que nos fijamos. En base a la interacción que surja en el curso también esto
puede ir modificándose, el aprendizaje es un proceso eminentemente dinámico y no le tenemos
miedo a eso.

## Dia 1: Introducción y Datos Vectoriales

En el primer día vamos a sentar las bases de todo el trabajo con datos geográficos.
Vamos a hacer primero que nada una introducción al trabajo con coordenadas. El abordaje
va a ser primero conceptual, con un poco de matemática por detrás. La matemática de las
coordenadas no es trivial, pero nosotros vamos a enfocarnos en entender los conceptos.

Con la ayuda de algunos ejemplos geométricos en geogebra y algún notebook en google colab,
que les dejaremos para que puedan revisar con tranquilidad, vamos a contarles cómo se
definen las coordenadas geográficas, cómo se relacionan con el espacio tridimensional,
qué son los marcos de referencia, y que son las proyecciones cartográficas.

Pasando a la práctica, vamos a trabajar primero con algunos ejemplos construidos utilizando
la librería PROJ, para fijar los conceptos teóricos. Y vamos a aprovechar que hablamos
de coordenadas para hacer una primera visita a lo que son los datos vectoriales, aquellos
que se definen directamente por sus coordenadas (y por algunas propiedades mas que oportunamente les mostraremos).

Hasta acá, nos habremos enfocado mucho en temas conceptuales, aunque ya vamos a empezar
a poner las manos en los datos con algunos ejemplos.

También aparecerán este día algunos conceptos menos intuitivos como coordenadas jerárquicas (las que usan implícitamente imágenes por teselas), coordenadas por funciones base (que se usan para definir algunos datos continuos).

## Día 2: Modelos de Terreno y datos Raster.

En el segundo día, para compensar la abstracción del primer día, vamos a pasar a trabajar
con cosas mas concretas, como el terreno.

Los modelos de terreno son el dato de grilla por excelencia, así que vamos a hacer
una revisión bastante amplia de los datos de uso disponible en la web, sus formatos,
su forma de generación, y qué podemos esperar de ellos. Vamos a aprovechar la ocasión
para comprender a fondo lo que es un dato raster -aunque los modelos de terreno no son raster por definición-, y para eso vamos a usar varias herramientas distintas, hasta algunas planillas excel que les vamos a dejar también para que revisen, porque después de todo, un dato raster no es otra cosa que una planilla condimentada.

Van a aparecer conceptos de coordenadas píxel, resolución, georreferenciación,
precisión, ruido, filtrado, vectorización. Haciendo mucho hincapié en aprender a
conocer de donde viene el dato que llega a nosotros, para saber cual es la información
real que nos da.

Pasando a la práctica vamos a comparar varias fuentes y formas en las que pueden
venir los datos. También vamos a trabajar con otros datos raster, como imágenes satelitales, y vamos a revisar sus características

## Día 3: Cartografía de Base - Datos Vectoriales y Raster (Revisita)

Toda salida cartográfica incluye información de contexto que puede venir
dada en distintos formatos. En este caso nos centraremos en los datos
provistos por organismos oficiales y en las bases de datos
específicamente diseñadas para el uso como cartografía de base. También vamos
a dedicar un apartado a las imágenes satelitales como dato raster de base.

Vamos a empezar por completar el marco conceptual sobre tipos de datos vectorial
y raster, apareciendo conceptos (y dando ejemplos) como topología, simplificación,
suavizado de vectores y de grillas, distintas representaciones de datos continuos,
y sobre todo, **escala** -un concepto que solemos pasar de largo pero nos da muchos dolores de cabeza-.

Vamos a revisar diversas fuentes de datos, haciendo énfasis en la cartografía oficial,
incluyendo las cartas topográficas y catastrales.

En los ejemplos prácticos vamos a incluir también casos de compatibilización
de información, para tomar datos de distintas fuentes y llevarlos a una forma
que sea cómoda para el trabajo y coherente para su visualización.

### Día 4: OpenStreetMap, y más y más Datos

OpenStreetMap es una herramienta muy peculiar, tanto por su forma de
generación, como por su característica de base de datos de gran tamaño,
como por su exhaustividad en algunas áreas y su dispersión en otras. Es
por esto que utilizaremos este herramienta como base para mostrar varios
ejemplos sobre la información cartográfica.

Explicaremos conceptos básicos de base de datos
geográfica y de los tipos de datos que pueden hallarse en OpenStreetMap.
Haremos un recuento de las diversas formas de acceso existentes a
los datos de OpenStreetMap.

Pasando al trabajo concreto, se propondrán ejemplos de descarga y uso de
los datos de OpenStreetMap. Finalmente se ejemplificará el uso extensivo
de datos presentando un caso en que derivamos un producto a partir de OSM,
abriendo una ventana a los problemas que surgen cuando se trabaja con grandes
volúmenes de datos.

Luego pasaremos de este caso a otros datos que de alguna manera son
asimilables al concepto de base de datos, en el sentido de que son compilaciones que
no están estrictamente pensadas para ser usadas en forma directa.

### Dia 5: Servicios OGC y otros mapas web.

Una fuente muy difundida y a la vez peculiar de datos son los servicios
OGC. Dada su creciente difusión, se dedicara un lugar privilegiado a este tema.

Hay varios conceptos detrás de los servicios OGC que queremos explicarles siempre
a través de ejemplos, y partiendo solamente del navegador web. Veremos los tipos de datos
que pueden obtenerse de cada servicio y trataremos sobre WMS,
WFS, WMTS y WCS,

El trabajo práctico de este módulo partirá de la revisión de numerosos
ejemplos de servicios implementados por diversos organismos, accediendo
a los mismos de formas diversas.

Dedicaremos buena parte de la clase a, navegador en mano, recorrer visores web
y mostrar qué servicios geoespaciales hay por detrás. No nos vamos a quedar con
los servicios OGC solamente, muchas veces hay otros servicios, incluso sin
protocolos estandarizados, que pueden descubrirse y aprovecharse desde el navegador.

