# BOLETÍN 5. EJERCICIOS BÁSICOS DISEÑO WEB

## Ejercicio 1

En el código base que se te proporciona debes realizar los siguientes cambios:

* Las siglas HTML deben aparecer como texto destacado en toda la página.
* Tim Berners-Lee debe aparecer como texto enfatizado en toda la página.

Debes añadir el siguiente contenido:
* Un encabezado de nivel 1 con el texto "HTML" antes de "HTML son las siglas de..."
* Un encabezado de nivel 2 con el texto "Historia de HTML" antes de "Los inicios del lenguaje HTML..."
* Un encabezado de nivel 2 con el texto "Versiones de HTML" antes de dos nuevos párrafos que contienen el texto "Tim Berners-Lee definió la primera versión de HTML en el año 1991" y "En la actualidad, la última versión de HTML es HTML5".

El resultado final debe ser una página web que tenga el mismo aspecto que la siguiente imagen:




![](../b5/res/b5.e1.png)<br><br><br>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML Ejercicio 1</title>
</head>
<body>
<h1><b>HTML</b></h1>
<p><b>HTML</b> son las siglas de <i>Hyper Text Language</i>,que puede traducirse como lenguaje de marcas o marcado de hipertexto.</p>
<p>El lenguaje <b>HTML</b> se emplea para crear las paginas web.Es muy facil ver el codigo <b>HTML</b>,de una pagina web,la opcion exacta cambia de un navegador a otro y tambien puede cambiar de una version a otro y tambien puede cambiar de una version a otra de un mismo avegador,pero sulen tener un nombre similar</p>

<p>HTML se compone de etiquetas que se escriben entre los simbolos menor que y mayor que</p>

<h2><b>Historia de HTML</b></h2>
<p>Los inicios del lenguaje HTML se remontan al año 1990,cuando <i>Tim Berners-Lee</i> creo la primera pagina web.</p>

<h2><b>Versiones de HTML</b></h2>
<p>Tim Berners-Lee defini'o la primera version de <b>HTML</b> en el año 1991.</p>

 <p>En la actualidad la ultima version de <b>HTML</b> es HTML5</p>

    
</body>
</html>





<br><br><br>

## Ejercicio 2

A partir del texto que se te proporciona, debes crear una página web que tenga el mismo aspecto que la siguiente imagen:

![](res/b5.e2.png)

Además, tienes que tener en cuenta los siguientes requisitos:

* El título de la página debe ser Tim Berners-Lee.
* El texto "Tim Berners-Lee" como encabezado de nivel 1.
* El texto "Biografía" como encabezado de nivel 2.
* Todas las siglas, como HTTP, W3C o MIT deben aparecer como texto destacado.
* Los nombres de las instituciones o empresas, como Consorcio de la World Wide Web o Universidad de Oxford, deben aparecer como texto enfatizado.


Código base:

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tim Berners-Lee</title>
</head>
<body>
<h1> <b>Tim Berners-Lee </b></h1>
<p>Sir Timothy "Tim" John Berners-Lee (Londres, Reino Unido, 8 de junio de 1955) es un científico de la computación británico, conocido por ser el padre de la Web. Estableció la primera comunicación entre un cliente y un servidor usando el protocolo <b>HTTP</b> en noviembre de 1989. En octubre de 1994 fundó el <i>Consorcio de la World Wide Web</i> <b>(W3C)</b> con sede en el <b>MIT</b>, para supervisar y estandarizar el desarrollo de las tecnologías sobre las que se fundamenta la Web y que permiten el funcionamiento de Internet.</p>

<h2><b> Biografia </b></h2>
<p>Nació en el sudoeste de Londres en 1955. Sus padres eran matemáticos y formaron parte del equipo que construyó el Manchester Mark I (una de las primeras computadoras). Durante el tiempo que estuvo en la universidad, construyó una computadora con una soldadora, circuitos <b>TTL</b>, un procesador Motorola 68000 y un televisor viejo. Se graduó en física en 1976 en el <i>Queen's College de la Universidad de Oxford</i>. Conoció a su primera esposa en este periodo. En 1978, trabajó en <i>D.G. Nash Limited </i>(también en <i>Poole</i>) escribió un sistema operativo.</p>

<h2><b>Desarrollo de su carrera</b></h2>
<p>Berners-Lee trabajó en el <b>CERN</b> desde junio hasta diciembre de 1980. Durante ese tiempo, propuso un proyecto basado en el hipertexto para facilitar la forma de compartir y la puesta al día de la información entre investigadores. En este periodo también construyó un programa llamado Enquire que no llegó a ver la luz.</p>

<p>Después de dejar el <b>CERN</b>, en 1980, se fue a trabajar a la empresa de *John Poole Image Computer Systems Ltd*., pero regresó al <b>CERN</b>otra vez en 1984.</p>

<p>En 1989, el <b>CERN</b> era el nodo de Internet más grande de Europa y Berners-Lee vio la oportunidad de unir Internet y el hipertexto (<b>HTTP</b> y <b>HTML</b>), de lo que surgiría la World Wide Web. Desarrolló su primera propuesta de la Web en marzo de 1989, pero no tuvo mucho eco, por lo que en 1990 y con la ayuda de Robert Cailliau, hicieron una revisión que fue aceptada por su gerente, Mike Sendall. Usó ideas similares a las que había usado en el sistema Enquire para crear la World Wide Web, para esto diseñó y construyó el primer navegador (llamado WorldWideWeb y desarrollado con NextStep) y el primer servidor web al que llamó httpd (HyperText Transfer Protocol daemon).</p>

<p>Fuente: <i>Wikipedia</i></p>
    
</body>
</html>

<br><br>

## Ejercicio 3

Corrige los errores que presenta el código base que se te proporciona.


<html lang=es>
<head>
<title>World Wide Web</title>
</head>
<body>

<h1>World Wide Web</h1>

<p>
En informática, la <strong><em>World Wide Web</strong></em> (WWW) o Red informática mundial comúnmente conocida como la web, es un sistema de distribución de documentos de hipertexto o hipermedios interconectados y accesibles vía Internet. Con un navegador web, un usuario visualiza sitios web compuestos de páginas web que pueden contener texto, imágenes, vídeos u otros contenidos multimedia, y navega a través de esas páginas usando hiperenlaces.
</p>
<h2>Historia</h2>

<p>
La web se desarrolló entre marzo de 1989 y diciembre de 1990 por el inglés Tim Berners-Lee con la ayuda del belga Robert Cailliau mientras trabajaban en el CERN en Ginebra, Suiza, y publicado en 1992.
</p>

<p>
Desde entonces, Berners-Lee ha jugado un papel activo guiando el desarrollo de estándares web (como los lenguajes de marcado con los que se crean las páginas web), y en los últimos años ha abogado por su visión de una web semántica.
</p>

<p>Fuente: <em>Wikipedia</em></p>
</body>
</html>
```
<br><br><br>


## Ejercicio 4

A partir del texto que se te proporciona, debes crear una página web que tenga el mismo aspecto que la siguiente imagen:

![](res/b5.e4.png)

Además, tienes que tener en cuenta los siguientes requisitos:

* El título de la página debe ser Curriculum Vitae de Bruce Wayne.
* El resto de la estructura de la página debes deducirlo a partir de la imagen proporcionada

<br><br>
Código base:
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Curriculum Vitae de Bruce Wayne</title>
</head>
<body>
<h1><b>Curriculum Vitae de Bruce Wayne</b></h1>
    <h2><b>Datos personales</b></h2>
        <ul><li>Nombre completo: <b>Bruce Wayne</b> </li>
        <li>Fecha de nacimiento: <b>1/5/1939</b> </li>
        <li>Lugar de nacimiento: <b>Gotham City</b> </li></ul>
    <h2><b>Formazión académica</b></h2>
        <ul><li>1956-1961: <b>Universidad del Espantapájaros</b></li>
        <li>1952-1956: <b>Instituto de Dos Caras</b></li>
        <li>1944-1952: <b>Escuela Primaria del Joker</b></li></ul>
    <h2><b>Experiencia laboral</b></h2>
      <ul><li>1975-1985: <b>En el paro</b> </li>
      <li>1965-1975: <b>Cazavillanos y demás chusma</b></li>
      <li>1962-1965: <b>Aprendiz de superhéroe </b></li></ul>
</body>
</html>

<br><br><br>

## Ejercicio 5

A partir del texto que se te proporciona, debes crear una página web que tenga el mismo aspecto que la siguiente imagen:

![](res/b5.e5.png)

Además, tienes que tener en cuenta los siguientes requisitos:

* El título de la página debe ser Los tres pilares de la Web.
* Los enlaces que aparecen en la página deben tener los siguientes destinos:
  * Tim Berners-Lee → http://es.wikipedia.org/wiki/Tim_Berners-Lee
  * Web → http://es.wikipedia.org/wiki/World_Wide_Web
  * HTML → enlace intradocumental al epígrafe HTML
  * HTTP → enlace intradocumental al epígrafe HTTP
  * URL → enlace intradocumental al epígrafe URL
  * Fuente: HTML → http://es.wikipedia.org/wiki/HTML
  * Fuente: HTTP → http://es.wikipedia.org/wiki/Hypertext_Transfer_Protocol
  * Fuente: URL → http://es.wikipedia.org/wiki/Localizador_de_recursos_uniforme


Código base:

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Los tres pilares de la Web</title>
</head>
<body>
<h1><b>Los tres pilares de la Web</h1></b>
<p><a href="http://es.wikipedia.org/wiki/Tim_Berners-Lee">Tim Berners-Lee</a> es considerado el padre de la Web porque desarrolló los tres elementos básicos para el funcionamiento de la <a href="http://es.wikipedia.org/wiki/World_Wide_Web">Web</a>:</p>

<ul><li><a href="#HTML">HTML</a></li>
  <li><a href="#HTTP">HTTP</a></li>
  <li><a href="#URL">URL</a></li></ul>
  <h2 id="HTML"><b> HTML </b></h2>

<p>HTML, siglas de <b>HyperText Markup Language</b>, hace referencia al lenguaje de marcado para la elaboración de páginas web. Es un estándar que sirve de referencia para la elaboración de páginas web en sus diferentes versiones, define una estructura básica y un código (denominado código HTML) para la definición de contenido de una página web, como texto, imágenes, entre otros. Es un estándar a cargo de la W3C, organización dedicada a la estandarización de casi todas las tecnologías ligadas a la web, sobre todo en lo referente a su escritura e interpretación. Es el lenguaje con el que se definen las páginas web.</p>

<p>Fuente: <a href="http://es.wikipedia.org/wiki/HTML">HTML</a> , Wikipedia</p>

<h2 id="HTTP"><b> HTTP </b></h2>

<p><b>Hypertext Transfer Protocol</b> o HTTP (en español protocolo de transferencia de hipertexto) es el protocolo usado en cada transacción de la World Wide Web. HTTP fue desarrollado por el World Wide Web Consortium y la Internet Engineering Task Force, colaboración que culminó en 1999 con la publicación de una serie de RFC, el más importante de ellos es el RFC 2616 que especifica la versión 1.1.</p>

<p>Fuente: <a href="http://es.wikipedia.org/wiki/Hypertext_Transfer_Protocol">HTTP</a> , Wikipedia</p>

<h2 id="URL"><b>URL</b></h2>

<p>Un <b>localizador de recursos uniforme</b> o URL —siglas en inglés de Uniform Resource Locator— es un identificador de recursos uniforme (URI) cuyos recursos referidos pueden cambiar, esto es, la dirección puede apuntar a recursos variables en el tiempo. Están formados por una secuencia de caracteres, de acuerdo a un formato modélico y estándar, que designa recursos en una red, como Internet.</p>

<p>Fuente: <a href="http://es.wikipedia.org/wiki/Localizador_de_recursos_uniforme"
>URL</a>, Wikipedia</p>

</body>
</html>

<br><br><br>


## Ejercicio 6

Crear una lista de definiciones a partir del texto que se entrega:

![](res/b5.e6.png)

Código base:

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Lista de definiciones</title>
</head>
<body>
  <b>HTTP</b>
    <p><ul>El Protocolo de transferencia de hipertexto (en inglés: Hypertext Transfer Protocol o HTTP) es el protocolo de comunicación que permite las transferencias de información en la World Wide Web.</ul></p>
  <b>HTML</b>
    <p><ul>HTML, sigla en inglés de HyperText Markup Language, hace referencia al lenguaje de marcado para la elaboración de páginas web.</ul></p>
  <b>URL</b>
    <p><ul>URL es una sigla del idioma inglés correspondiente a Uniform Resource Locator (Localizador Uniforme de Recursos). Se trata de la secuencia de caracteres que sigue un estándar y que permite denominar recursos dentro del entorno de Internet para que puedan ser localizados.</ul></p>
  <b>TCP/IP</b>
    <p><ul>TCP/IP son las siglas de Protocolo de Control de Transmisión/Protocolo de Internet (en inglés Transmission Control Protocol/Internet Protocol), un sistema de protocolos que hacen posibles servicios Telnet, FTP, E-mail, y otros entre ordenadores que no pertenecen a la misma red.</ul></p>
  <b>Internet</b>
    <p><ul>Internet (el internet o, también, la internet)​ es un conjunto descentralizado de redes de comunicación interconectadas que utilizan la familia de protocolos TCP/IP, lo cual garantiza que las redes físicas heterogéneas que la componen, formen una red lógica única de alcance mundial.</ul></p>
  <b>W3C</b>
    <p><ul>El Consorcio WWW, en inglés: World Wide Web Consortium, es un consorcio internacional que genera recomendaciones y estándares que aseguran el crecimiento de la World Wide Web a largo plazo.​</ul></p>
  <b>Mozilla Foundation</b>
    <p><ul>Fundación Mozilla es una organización sin ánimo de lucro dedicada a la creación de software libre. Tiene como misión «mantener la elección y la innovación en Internet». La fundación es conocida por crear el navegador Mozilla Firefox o, simplemente Firefox en la actualidad.</ul></p>

</body>
</html>

<br><br>

## Ejercicio 7

A partir del texto que se te proporciona, debes crear una página web que tenga el mismo aspecto que la siguiente imagen:

![](res/b5.e7.png)

Selecciona para cada lista el mejor tipo de lista.

Código base:

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Ejercicio 7</title>
</head>
<body>
  <h1><b>Internet</b></h1>
  <h2><b>Contenido</b></h2>
    <p><ol><li>Principales protocolos</li></p>
    <p><li>Formas de conectarse</li></ol></p>
  <h2><b>1. Principales protocolos</b></h2>
    <p><ul><li>Transmisión de ficheros:</p></ul></li>
      <p><ul><ul><li>FTP</p></ul></ul></li>
    <p><ul><li>Correo electrónico:</p></ul></li>
      <p><ul><ul><li>IMAP</p></ul></ul></li>
      <p><ul><ul><li>POP</p></ul></ul></li>
      <p><ul><ul><li>SMTP</p></ul></ul></li>
  <h2><b>2. Formas de conectarse</b></h2>
    <p>Red Telefónica Conmutada (RTC)</p>
      <p><ul>La línea telefónica de toda la vida.  Para acceder a Internet es necesario un módem.</ul></p>
    <p>Red Digital de Servicios Integrados (RDSI)</p>
      <p><ul>Una línea telefónica especial. Para acceder a Internet es necesario un módem RDSI.</ul></p>
    <p>Línea de Abonado Digital Asimétrica (ADSL)</p>
      <p><ul>Se basa en la conversión de una línea RTC en una línea de alta velocidad. Para acceder a Internet es necesario un módem ADSL.</ul></p>
    <p>Fibra Óptica</p>
      <p><ul>Una línea de fibra óptica. Normalmente la fibra óptica no llega hasta el usuario final, por lo que el término más apropiado es Fibra híbrida coaxial.</ul></p>

</body>
</html>

<br><br><br>


## Ejercicio 8

A partir del texto que se te proporciona, debes crear una página web que tenga el mismo aspecto que la siguiente imagen:

![](res/b5.e8.png)

> **Nota**: en el código base que se te proporciona vas a encontrar una etiqueta nueva, la etiqueta "style". Esta etiqueta permite introducir instrucciones de CSS (Cascading Style Sheets) en una página web. CSS se emplea para definir la presentación visual de una página web y se explica en la segunda parte de este curso. Las instrucciones que se han incluido tienen como objetivo que la tabla y las celdas de la tabla se muestren con un borde. Esto también se podría haber logrado con el atributo border de HTML, pero es mejor utilizar siempre CSS para todo lo relacionado con la presentación de una página web.

Código base:

<!DOCTYPE html>
<html>
<head>
<title>Desempleo</title>
<style>
table, tr, th, td {
  border: 1px solid black;
}
</style>
</head>
<body>
<h1><b>El desempleo en España</b></h1>
<p>
La siguiente tabla muestra la evolución del desempleo en España, comparado con la media de los 27 países de la Unión Europea, Grecia, que compite con España en ser el primero en esta vergonzosa competición y Estados Unidos y Japón, dos de las primeras economías mundiales.</p>

<table>
   <tr>
      <td><b>País</b></td>
      <td><b>2000</b></td>
      <td><b>2001</b></td>
      <td><b>2002</b></td>
      <td><b>2003</b></td>
      <td><b>2004</b></td>
      <td><b>2005</b></td>
      <td><b>2006</b></td>
      <td><b>2007</b></td>
      <td><b>2008</b></td>
      <td><b>2009</b></td>
      <td><b>2010</b></td>
      <td><b>2011</b></td>
      <td><b>2012</b></td>
      <td><b>2013</b></td>
    </tr>
    <tr>
      <td>UE (27 países)</td>
      <td>8.9</td>
      <td>8.7</td>
      <td>9</td>
      <td>9.1</td>
      <td>9.3</td>
      <td>9</td>
      <td>8.2</td>
      <td>7.2</td>
      <td>7</td>
      <td>9</td>
      <td>9.6</td>
      <td>9.6</td>
      <td>10.4</td>
      <td>10.8</td>
  </tr>
  <tr>
      <td><b>España</b></td>
      <td><b>10.6</b></td>
      <td><b>10.6</b></td>
      <td><b>11.5</b></td>
      <td><b>11.5</b></td>
      <td><b>11</b></td>
      <td><b>9.2</b></td>
      <td><b>8.5</b></td>
      <td><b>8.2</b></td>
      <td><b>11.3</b></td>
      <td><b>17.9</b></td>
      <td><b>19.9</b></td>
      <td><b>21.4</b></td>
      <td><b>24.8</b></td>
      <td><b>26.1</b></td>
  </tr>
  <tr>
      <td>Grecia</td>
      <td>11.2</td>
      <td>10.7</td>
      <td>10.3</td>
      <td>9.7</td>
      <td>10.6</td>
      <td>10</td>
      <td>9</td>
      <td>8.4</td>
      <td>7.8</td>
      <td>9.6</td>
      <td>12.7</td>
      <td>17.9</td>
      <td>24.5</td>
      <td>27.5</td>
  </tr>
  <tr>
      <td>Estados Unidos</td>
      <td>4</td>
      <td>4.8</td>
      <td>5.8</td>
      <td>6</td>
      <td>5.5</td>
      <td>5.1</td>
      <td>4.6</td>
      <td>4.6</td>
      <td>5.8</td>
      <td>9.3</td>
      <td>9.6</td>
      <td>8.9</td>
      <td>8.1</td>
      <td>7.4</td>
  </tr>
  <tr>
      <td>Japón</td>
      <td>4.7</td>
      <td>5</td>
      <td>5.4</td>
      <td>5.3</td>
      <td>4.7</td>
      <td>4.4</td>
      <td>4.1</td>
      <td>3.9</td>
      <td>4</td>
      <td>5.1</td>
      <td>5.1</td>
      <td>4.6</td>
      <td>4.3</td>
      <td>4</td>
  </tr>
</table>
<br>
Fuente: <a href="https://datosmacro.expansion.com/paro">Índice de desempleo anual</a>, Eurostat

</body>

</html>
<br><br><br>

## Ejercicio 9

A partir del texto que se te proporciona, debes crear una página web que tenga el mismo aspecto que la siguiente imagen:

![](res/b5.e9.png)

> **Nota**: en el código base que se te proporciona vas a encontrar una etiqueta nueva, la etiqueta "style". Esta etiqueta permite introducir instrucciones de CSS (Cascading Style Sheets) en una página web. CSS se emplea para definir la presentación visual de una página web y se explica en la segunda parte de este curso. Las instrucciones que se han incluido tienen como objetivo que la tabla y las celdas de la tabla se muestren con un borde. Esto también se podría haber logrado con el atributo border de HTML, pero es mejor utilizar siempre CSS para todo lo relacionado con la presentación de una página web.

codigo base:

<!DOCTYPE html>
<html>
<head>
<title>Título de la página</title>
<meta charset="UTF-8">


</head>
<body>
  
<table border='1'>
    <tr>
    <td><strong>Categoría</strong></td><td><strong>Etiquetas</strong></td>
    </tr>
    <tr>
        <td rowspan="5">Formulario</td><td>form</td>
    </tr>
    <tr>
    <td>button</td>
    </tr>
    <tr>
    <td>input</td>
    </tr>
    <tr>
    <td>select</td>
    </tr>
    <tr>
    <td>textarea</td>
    </tr>
    <tr>
        <td rowspan="5">Tabla</td><td>Table</td>
    </tr>
    <tr>
    <td>tr</td>
    </tr>
    <tr>
    <td>th</td>
    </tr>
    <tr>
    <td>td</td>
    </tr>
    <tr>
    <td>Caption</td>
    </tr>
    <tr>
        <td rowspan="6">Texto</td><td>b</td>
    </tr>
    <tr>
    <td>em</td>
    </tr>
    <tr>
    <td>i</td>
    </tr>
    <tr>
    <td>strong</td>
    </tr>
    <tr>
    <td>sub</td>
    </tr>
    <tr>
    <td>sup</td>
    </tr>


  </table>

</body>

</html>
```
<br><br><br>

## Ejercicio 10

Crea una página web que contenga un formulario con los siguientes campos de información:

* El nombre, con un control de tipo texto.
* Los apellidos, con un control de tipo texto.
* El sexo, con dos opciones excluyentes hombre o mujer.
* El correo electrónico, con un control de tipo texto.
* Una casilla de verificación con el texto "Deseo recibir información sobre novedades y ofertas".
* Una casilla de verificación con el texto "Declaro haber leido y aceptar las condiciones generales del programa y la normativa sobre protección de datos".
* Un botón de envío.

Además, tienes que tener en cuenta los siguientes requisitos:

* El título de la página debe ser Formulario de registro - Mi web.
* El método de envío del formulario debe ser GET.
* El destino del envío del formulario debe ser "".
* La longitud máxima de entrada de datos de los controles para el nombre y los apellidos debe ser 50 caracteres.
* La casilla de verificación con el texto "Deseo recibir información sobre novedades y ofertas" debe estar activada por defecto.
* Debes crear una página web que tenga el mismo aspecto que la siguiente imagen:

![](res/b5.e10.png)


<!DOCTYPE html>
<html>
<head>
<title>Formulario de registro - Mi web</title>
</head>
<body>

<h1>Formulario de registro</h1>

<form action="" method="get">

<p>Nombre: <input type="text" name="nombre" maxlength="50" /></p>

<p>Apellidos: <input type="text" name="apellidos" maxlength="50" /></p>

<p>Sexo: <input type="radio" name="sexo" value="h" /> hombre <input type="radio" name="sexo" value="m" /> mujer</p>

<p>Correo: <input type="text" name="correo" maxlength="100" /></p>

<p><input type="checkbox" name="info" checked="checked" /> Deseo recibir información sobre novedades y ofertas</p>

<p><input type="checkbox" name="condiciones" /> Declaro haber leido y aceptar las condiciones generales del programa y la normativa sobre protección de datos</p>

<p><input type="submit" value="Enviar" /></p>
</form>
</body>
</html>