# Sugerencias para prepararse

Falta menos de una semana, y queremos acercarles algunos recursos para aquellos
que sientan que no están en tema para el curso.

Se trata de algún material que fuimos armando, pero queremos dejar bien claro
que no se trata de un test de conocimientos previos ni de una muestra exacta
de lo que será el curso.

Se trata simplemente de algunos recursos que tratan algunos temas relacionados
al curso, desde una perspectiva que tal vez no es la más difundida en el mundo
de los tutoriales, y está mas alineada a nuestra forma de encarar el
proceso de enseñanza-aprendizaje.

## Algunos recursos para revisar

Les dejamos aquí algunos recursos para revisar como forma de ponerse en tema con
el curso.

Les aclaramos que hay un fuerte sesgo hacia algunos temas (coordenadas por ejemplo).
Esto se debe a que por un lado es una mayormente reelaboración de material que ya teníamos
preparado, y por el otro a que corresponde a las primeras clases del curso, y por
ende a aquellas en las que más conviene ponerse en tema de antemano, para que podamos
tomar el ritmo y no quedarnos por el camino.

### Familiarizarse Google Colab

Primero, dado que los ejemplos los realizaremos en google Colab,
[les dejamos este link para que se familiaricen con la plataforma.](https://colab.research.google.com/gist/jjclavijo/3cf3d32d0a47ad2bc30e03011cdd4ca7)

La plataforma es realmente sencilla, y nos permitirá mostrar varios ejemplos
sobre las propiedades de los datos sin tener que lidiar con problemas de
compatibilidad.

### Videos

Para aquellos que estén interesados en revisar algún material relacionado al curso para
ir preparandose, les dejamos dos videos de clases que dí --yo, Javier-- en algún momento
para la materia Cartografía. Uno con una pequeña y
muy rápida introducción a los datos geográficos, y otro con una clase sobre Marcos de Referencia.
Les pedimos que ignoren los comentarios específicos sobre la cursada de la materia, para
enfocarse en el contenido.

- El primero es interesante porque es esa clase de algún modo la que nos generó la
inquietud para construir este curso. [Link al video](https://www.youtube.com/watch?v=HYxFeeyXkxc)

- El segundo resulta interesante porque es un problema que está en la base del dato
geográfico y nunca está demás dedicarle tiempo a entenderlo. [Link al video](https://www.youtube.com/watch?v=KtIY1eK9Fw8)

Les sugerimos además [mirar este video](https://www.youtube.com/watch?v=GNcFjFmqEc8), donde se trabaja en forma intuitiva el
cálculo de área de la esfera, porque nos parece una muy buena forma de empezar
a pensar en cómo los datos de una esfera se terminan plasmando en un plano.

### Ejemplos interactivo.

Les dejamos algunas planillas de cálculo que construimos a modo de tutorial,
para trabajar con listas y grillas de coordenadas, y también para experimentar un
poco con la naturaleza de los datos raster.

- Un tutorial básico donde además de aprender el manejo básico aprendemos a generar
  grillas regulares de coordenadas. Lo que puede resultar muy util para experimentar
  más adelante con coordenadas. [Link a la planilla](/preparacion_files/Tutor_Planilla.xlsx)

- Una planilla para trabajar con las coordenadas de un archivo raster y su
  Georeferencia. [Link a la planilla](/preparacion_files/Raster_Coordenadas.xlsx)

- Una planilla para trabajar con los valores dentro de un raster, entender
  qué son los filtros matriciales y como se contruye un perfil.[Link a la planilla](/preparacion_files/Raster_Valores.xlsx)

Además, también les dejamos un tutorial para trabajar un poco con la geometría de
las coordenadas geográficas sobre el elipsoide, para resolver en geogebra.
[Link al tutorial](/preparacion_files/Datum_geogebra) [Link al archivo de geogebra resuelto](/preparacion_files/Datum_geogebra.ggb)

## Software

También queremos dejarles algunas recomendaciones sobre el software que puede
llegar a serles util para profundizar en los temas del curso entre sesión y
sesión, o durante la parte práctica.

### Editor de textos

Durante el curso vamos a utilizar muchos ejemplos alojados en la nube. Si
embargo, como vamos a trabajar mucho con archivos de texto --especialmente
estructurados como JSON y XML--, les sugerimos instalar un editor de texto que
pueda manejar archivos pesados y cerrar/abrir bloques de texto.

- Para usuarios en Linux sugerimos [Notepadqq](https://notepadqq.com)
- Para usuarios en Windows sugerimos [Notepad++](https://notepad-plus-plus.org/)
- Otra alternativa que funciona tanto en windows como en linux [Geany](https://www.geany.org/)

### Qgis, Gdal, Proj

Para visualizar y explorar los datos del curso, muchas veces va a resultar útil
tener instalado QGIS. Sugerimos tener instalada la última versión (3.20),
porque hay varias funciones relativas a cambios de coordenadas que son muy
importantes para entender los conceptos iniciales del curso y cambiaron en esta
versión.

- [Link a la página de QGIS](https://qgis.org)

Noten que en Ubuntu, Debian u otras distribuciones con repositorios oficiales,
probablemente la versión del repositorio oficial esté desactualizada. En el
sitio de Qgis están las instrucciones para instalar la versión más actual.

Junto con Qgis se instalan automáticamente las herramientas de las librerías
GDAL y PROJ, que utilizaremos durante el curso. De todos modos, los ejemplos
correspondientes también estarán construidos para funcionar desde la nube.

### Software de imágenes

En parte del curso vamos a trabajar archivos de imagen. Nos parece importante
poder aprender a tratar los datos de imagen también en forma independiente de
su referencia geográfica. Por eso, aunque los ejemplos los trabajaremos en la
nube, mayormente utilizando ImageMagick, sugerimos que tengan a mano algún
visor de imágenes que maneje en forma fluida imágenes grandes.

- Nosotros sugerimos utilizar XnViewMP: [Link a la página](https://www.xnview.com/en/xnviewmp/)

### Libreoffice

Algunos de los ejemplos del curso son fáciles de realizar en planillas de
cálculo. Nosotros trabajamos las planillas con LibreOffice, y para una mejor
compatibilidad les recomendamos tenerlo instalado.

- [Link a la página de libreoffice](https://es.libreoffice.org/)
