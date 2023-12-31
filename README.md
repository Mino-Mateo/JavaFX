# JavaFX
Trabajo realizado por
* Mateo Miño
* Erick Villarroel
* Danny Yanacallo
-----------------------------------
Elementos utilizados:

* Video Converter
  <img src="Readme-Imagenes/videoconverter.png" width="170">

* JavaFX
  <img src="Readme-Imagenes/JavaFX2.png" width="170">

* Java JDBC Driver
  <img src="Readme-Imagenes/jdbc.png" width="170">

* Scene Builder
  <img src="Readme-Imagenes/Scene.png" width="170">

* Intellij
  <img src="Readme-Imagenes/IDEA.png" width="170">

* SQL connector
  <img src="Readme-Imagenes/SQLC.png" width="170">

* Youtube
  <img src="Readme-Imagenes/Youtube.png" width="170">

-----------------------------------
DESARROLLO:

1. Descargar de la página oficial de JavaFX la librería con su controlador (https://openjfx.io/)

   <img src="Readme-Imagenes/paso1.png" width="560">


2. Descargar el Controlador Visual “Scene Builder”, que contendrá la interfaz grafica para desarrollar las aplicaciones.

   <img src="Readme-Imagenes/paso2.png" width="560">


3. Descargar el controlador SQL para Java (https://learn.microsoft.com/en-us/sql/connect/jdbc/download-microsoft-jdbc-driver-for-sql-server?view=sql-server-ver16#download)

   <img src="Readme-Imagenes/paso3.png" width="560">


4. En nuestro sistema SQL (en este caso MySQL), crear la base de datos a utilizarse

   <img src="Readme-Imagenes/paso4.png" width="560">


5. Dentro de Intellij Crear un nuevo Proyecto con JavaFX

   <img src="Readme-Imagenes/paso5.png" width="560">


6. Opcional añadimos librerías extra para nuestro proyecto

   <img src="Readme-Imagenes/paso6.png" width="560">


7. Una vez creado el proyecto visualizamos todas las librerías

   <img src="Readme-Imagenes/paso7.png" width="400">


8. Ahora añadimos la librería de SQL a nuestro proyecto

   <img src="Readme-Imagenes/paso8.png" width="560">


9. Instalamos en nuestro PC el “Scene Builder” y lo guardamos en un sitio accesible

   <img src="Readme-Imagenes/paso9.png" width="560">


10. En nuestro archivo en Intellij damos click derecho sobre nuestro archivo “.fxml” y abrimos nuestro proyecto en nuestro “Scene Builder”

    <img src="Readme-Imagenes/paso10.png" width="500">


11. Una vez dentro del “Scene Builder” veremos el sistema que tenemos

    <img src="Readme-Imagenes/paso11.png" width="560">


12. Ahora le vamos a dar el formato con sus respectivos id a los elementos para empezar a trabajar.

    <img src="Readme-Imagenes/paso12.png" width="560">


13.	Una vez creada la interfaz grafica copiamos la estructura del controlador y la copiamos en nuestro “Controller” o el archivo que se tenga para controlar.

    <img src="Readme-Imagenes/paso13.png" width="560">


14.	Una vez copiado el código vamos a importar la librería SQL a nuestro proyecto

    <img src="Readme-Imagenes/paso14.png" width="560">


15.	Ahora vamos a insertar las variables que vamos a utilizar mas adelante, estas cuentan con:

       • Conexión a nuestra base de datos (DB_URL)

       • Usuario de SQL (USER)

       • Contraseña de SQL (PASS)

       • Querys de trabajo (Crear, Borrar, Actualizar, Mostrar)

    <img src="Readme-Imagenes/paso15.png" width="560">


16.	Opcional crear funciones para trabajar más limpio


* Función Crear

            • Establecer la conexión con la base de datos y pasarle el Query con el que vamos a trabajar

<p align="center">
    <img src="Readme-Imagenes/paso16.png" width="560">
</p>


            • Texto para señalar el funcionamiento del programa

<p align="center">
    <img src="Readme-Imagenes/paso16_2.png" width="560">
</p>


            • Query de trabajo con las instrucciones a ejecutar

<p align="center">
    <img src="Readme-Imagenes/paso16_3.png" width="560">
</p>


* Funcion Actualizar

            • Establecer la conexión con la base de datos y pasarle el Query con el que vamos a trabajar

<p align="center">
    <img src="Readme-Imagenes/paso16_4.png" width="560">
</p>


            • Texto para señalar el funcionamiento del programa

<p align="center">
    <img src="Readme-Imagenes/paso16_5.png" width="560">
</p>


            • Query de trabajo con las instrucciones a ejecutar

<p align="center">
    <img src="Readme-Imagenes/paso16_6.png" width="560">
</p>


* Función Borrar

            • Establecer la conexión con la base de datos y pasarle el Query con el que vamos a trabajar

<p align="center">
    <img src="Readme-Imagenes/paso16_7.png" width="560">
</p>


            • Texto para señalar el funcionamiento del programa

<p align="center">
    <img src="Readme-Imagenes/paso16_8.png" width="560">
</p>


            • Query de trabajo con las instrucciones a ejecutar

<p align="center">
    <img src="Readme-Imagenes/paso16_9.png" width="560">
</p>


* Función Mostrar

            • Establecer la conexión con la base de datos y pasarle el Query con el que vamos a trabajar

<p align="center">
    <img src="Readme-Imagenes/paso16_10.png" width="560">
</p>


            • Texto para señalar el funcionamiento del programa, aquí tendremos que detalla con el “rs.getInt o rs.getString” el tipo de datos de nuestra base de datos y con esto detallaremos el nombre de la columna de la base de datos.

<p align="center">
    <img src="Readme-Imagenes/paso16_11.png" width="560">
</p>


            • Query de trabajo con las instrucciones a ejecutar

<p align="center">
    <img src="Readme-Imagenes/paso16_12.png" width="560">
</p>



17.	Una vez desarrollado el código vamos a ejecutar el programa y visualizar los resultados

        * Botón Mostrar

<p align="center">
    <img src="Readme-Imagenes/paso17.png" width="560">
</p>


        * Botón Actualizar y Mostrar

<p align="center">
    <img src="Readme-Imagenes/paso17_2.png" width="560">
</p>


        * Botón Borrar (Debido a que se borró el dato no se mostrara el dato de SQL)

<p align="center">
    <img src="Readme-Imagenes/paso17_3.png" width="560">
</p>


        * Botón Crear y Mostrar 

<p align="center">
    <img src="Readme-Imagenes/paso17_4.png" width="560">
</p>


