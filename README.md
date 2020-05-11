# Registro temporal de los datos de una película

Este es un proyecto estudiantil, creado netamente en el lenguaje c# que consiste sobre un registro de películas en el que se almacenan temporalmente todos sus datos como lo serian el nombre de la película, su género, la duración en minutos, su director, el idioma en que se encuentra y si esta se encuentra subtitulada o no. Al momento de almacenar estos datos pertinentes se creará una tabla y una grafica al mismo tiempo(La cual esta implementada por un Dll graficador, que mas adelante en el documento se hablara de él).<br><br> 
La tabla almacenara cada uno de los nombres de las diferentes películas ingresadas, así como si esta se encuentra activa o no, en diferentes listas. Además de eso en cada una de las listas, abra un botón, en donde si lo accionamos, nos desplegará todos los datos que hayan sido introducidos y sean referentes a esa película, y nos permitirá modificarlos a nuestro antojo, para seguido guardarlos y actualizar la lista en cuestión.<br><br>
En cuanto a la grafica que se creara, esta nos mostrara un diagrama grafico entre la relación del nombre de cada una de las diferentes películas que se encuentran en las listas y sus respectivas duraciones. En caso tal de que se modifique el nombre o la duración de la película, también lo hará en la gráfica. Todo esto lo realizara en un mismo graficador automático. Así mismo esta grafica contara con un botón de etiqueta en donde si se oprime se ocultarán o se visualizaran todos los datos de las duraciones que se encuentren actualmente en la gráfica. 




## Tabla de Contenido.

<ul>
  <li><a href="#install">Como instalar el proyecto </a></li>
  <li><a href="#proyectofun">Funcionalidades del proyecto</a></li>
  <li><a href="#dlls">Sobre los Dlls</a>
          <ul>
            <li><a href="#dllraiz">Dll Raiz de un numero</a></li>
            <li><a href="#dllgraficador">Dll Graficador</a></li>
          </ul>
  </li>
  <li><a href="#autores">Autores</a></li>
</ul>

<h2 id="install"> Como instalar el proyecto </h2>
<ul>
<li>Para instalar el proyecto primero tienes que ir al github en el que se encuentra este y descargarlo como zip, para mas informacion ir al <a href="#recurso1">Recurso 1</a></li>
<br>
  <div id="recurso1">
<img src="http://g.recordit.co/x1h0WN73N0.gif" alt="Instalar Software" id="recurso1" width="550px"></img>
 </div> 

###### Recurso 1. Ejemplo de como descargar el proyecto.

<li>Después descomprimir los archivos en una carpeta y tendrás el proyecto en cuestión, en caso de no quedar claro ver <a href="#recurso2"> Recurso 2</a></li><br>
<div id="recurso2">
<img src="http://g.recordit.co/QzXpqnByV7.gif" alt="Descomprimir Software" id="recurso2" width="550px"></img>
</div>

###### Recurso 2. Ejemplo de como descomprimir el proyecto.
<br>
<li>Por ultimo, ejecutar el programa. Para esto solo tienes que abrir al archivo llamado <b> "Trabajo1Corte.exe" </b> que se encuentra en la carpeta descomprimida anteriormente, ver <a href="#recurso3">Recurso 3 </a></li><br>
<div id="recurso3">
<img src="http://g.recordit.co/9C1RQpxNeo.gif" alt="Abrir el Software" id="recurso2" width="450px"></img>
</div>

###### Recurso 3. Ejemplo de abrir el proyecto.

<h2 id="proyectofun"> Funcionalidades del proyecto </h2>
<ul>
  <li><a href="#aggpel"> Agregar y listar películas </a></li>
  <li><a href="#editpel"> Editar películas listadas </a></li>
  <li><a href="#graficapel"> Graficador nombre de la película contra la duración de la misma </a></li>
  <li><a href="#idiomapel"> Cambiar el idioma del Software </a></li>
  <li><a href="#configpel"> Cambiar la configuración del Software </a></li>
  <li><a href="#raiznum"> Calcular la raíz de un numero </a> </li>
</ul>

<h3 id="aggpel"> Agregar y listar películas </h3>

El usuario podrá agregar tantas películas como desee, para esto tendrá que ingresar el nombre de la película, su género, la duración en minutos de esta, su director, el idioma en que se encuentra (Teniendo algunos de base o si el usuario desea ingresar el suyo) y si la película esta subtitulada o no.

Aquí un ejemplo de como se ingresaran los datos:

<img src="http://g.recordit.co/pzKkKEthDc.gif" alt="Agregar una pelicula"></img>
###### Recurso 4. Ejemplo de como se deben agregar las peliculas

<h3 id="editpel"> Editar películas listadas </h3>

Del mismo modo que el usuario puede agregar películas, también las puede editar, para esto solo es necesario darle al botón mostrar en una de las listas, este nos mostrará los datos ingresados anteriormente con respecto a esa lista, y así mismo el usuario podrá editarlos. Al darle al botón de actualizar, los nuevos datos o los que no hayan sufrido cambio alguno se volverán a guardar temporalmente en esa lista, en caso de que se quieran volver a modificar.

Aquí un ejemplo de como editar los datos de una pelicula:

<img src="http://g.recordit.co/tz3Xi3Hq18.gif" alt="Editar datos de una pelicula"></img>
###### Recurso 4. Ejemplo de como se deben editar los datos de una pelicula

<h3 id="graficapel"> Graficador nombre de la película contra la duración de la misma </h3>

A la hora de ingresar una película también se creará una gráfica. Esta grafica nos mostrara dos datos, el nombre de la película y su duración en minutos. Cada película agregada se ubicará en la gráfica una junto a otra para así poder comparar los tiempos de duración de cada una. Por otro lado en la grafica habrá un botón de nombre “etiqueta”, el cual sirve para esconder o visualizar la duración de las películas de una forma mas precisa.

Aquí un ejemplo de la grafica y el botón etiqueta:

<img src="http://g.recordit.co/KILIHK9SEo.gif" alt="Botón etiqueta de la grafica"></img>
###### Recurso 5. Ejemplo de la grafica y el botón etiqueta.

<h3 id="idiomapel"> Cambiar el idioma del Software </h3>

Otra de las funcionalidades que posee este software, es que puedes alternar entre varios idiomas. Para cambiar el idioma tan solo basta con ir a la parte inferior derecha donde dice "Cambiar Idioma", en este se desplegará una lista con unos idiomas ya establecidos en el software y que al momento de elegir uno, todo el programa se cambiará automáticamente a ese idioma. 

Idiomas incluidos en el software:
<ul> <li>Español</li>
  <li> Ingles </li>
  <li> Ruso </li>
  <li> Chino Simplificado </li>
  <li> Frances </li>
  <li> Italiano </li> 
  <li> Aleman </li>
</ul>


Aquí un ejemplo de como cambiar el idioma:

<img src="http://g.recordit.co/x6rbG6I606.gif" alt="Cambiar idioma"></img>
###### Recurso 6. Ejemplo de como cambiar el idioma.


<h3 id="configpel"> Cambiar la configuración del Software </h3>

Así mismo otra funcionalidad del software, es el poder configurarlo al gusto del usuario. Por el momento solo está habilitada la opción del cambio de color, es decir, cambiara el color de todo el programa dependiendo del escogido por el usuario. Próximamente se implementarán más opciones de configuración.

Aquí un ejemplo de como cambiar la configuración del software:

<img src="http://g.recordit.co/jx7Qaa9DBA.gif" alt="Cambiar Color"></img>
###### Recurso 7. Ejemplo de como cambiar las configuraciones.

<h3 id="raiznum"> Calcular la raíz de un numero</h3>

Además de agregar películas, este software también permite calcular la raíz de un numero por medio de un DLL implementado.<br><br> 
Pero antes de continuar….¿Qué es la raíz de un numero? Es la suma de sus dígitos hasta que el resultado sea solo un digito, por ejemplo, supongamos que tenemos el número 123, la raíz de este seria 6, esto es porque 1 + 2 + 3 = 6, otro ejemplo seria 999, el resultado de este es 9, esto es porque 9 + 9 + 9 = 27 y 2 + 7 = 9, ósea que si el primer resultado da un número que sea mayor o igual a dos dígitos este tendrá que volver a hacer la suma con el resultado obtenido hasta llegar a un numero de un solo digito.


Aquí un ejemplo de como sacar la raiz de un numero:

<img src="http://g.recordit.co/4aIqLrpj6P.gif" alt="Raiz de un numero"></img>
###### Recurso 8. Ejemplo de como sacar la raiz de un numero.

<br>Por otro lado, el software también cuenta con un apartado de créditos en los cuales se le hace alusión a los creadores del software, y también cuenta con un apartado de Ayuda, esto para que los usuarios que tengan algún problema o alguna duda sobre el proyecto, puedan enviar su petición de ayuda a los creados del mismo.

<h2 id="dlls"> Sobre los Dlls</h2>

Nuestro software cuenta con dos Dlls. Cada uno de estos con diferentes funciones que podemos usar. Cabe destacar que para nuestro proyecto solo implementamos algunas de estas, y de esa forma lograr un programa optimo y de buen funcionamiento según los requisitos establecidos.  

<h3 id="dllraiz"> Dll Raiz de un Numero </h3>

Anteriormente se mencionó el Dll de la raíz de un número, ahora hablaremos del proceso que conlleva hacer esto mismo. Para lograrlo tenemos que sumar todos sus dígitos, por tanto, hay que hacer un proceso en el cual se verifica cuantos números existen en este, descomponiéndolo, y que de esa forma se sumen los dígitos por partes. En caso que el resultado de esta suma vuelva a dar 2 o más dígitos, se volverá a repetir el proceso anterior y seguirá hasta que de como resultado 1 solo digito en la suma, en ese momento se mostrara en pantalla cuál es ese resultante.

Aquí un ejemplo de la logica que implementa este DLL:

<img src="http://g.recordit.co/aG7Y1AxqNw.gif" alt="Logica Raiz de un Numero"></img>
###### Recurso 9. Ejemplo de la logica que se implementa el DLL.

<h3 id="dllgraficador"> Dll Graficador </h3>

El siguiente Dll implementado es un graficador, el cual posee un montón de funcionalidades en cuanto a realizar graficas. En nuestro software, este es el encargado de crearnos gráficamente las barras correspondientes al nombre de las películas con su duración, y compararlas con las demás que hayan sido ingresadas. En cuanto a la lógica que utiliza, es que, al momento de ingresar una nueva película, el Dll se encargara de tomar los datos del nombre de esta y su duración, los ubicara en posiciones "X" y "Y", donde el Eje X hace referencia al nombre de la película y el Y a la duración de la misma. Realizara este proceso con todas las listas que tengamos actualmente en nuestro programa.

Aquí un ejemplo de como se Agregan diversas barras a la grafica cuando se ingresa una pelicula:

<img src="http://g.recordit.co/ce4cIrbniA.gif" alt="Barras de la grafica"></img>
###### Recurso 10. Ejemplo de como se Agregan diversas barras a la grafica cuando se ingresa una pelicula.

<h2 id="autores">Autores</h2>

<strong>Carlos Mauricio Chinchilla Rosales</strong> - <a href="https://github.com/Cchinchilla3">Cchinchilla3</a> <br>
<strong>Diego Andrés Gualdrón Angarita </strong> - <a href="https://github.com/dgualdron04">dgualdron04</a> <br>
