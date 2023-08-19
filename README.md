#   TP GIT

![screen](JAC_Icono.png)

***
*Titulo:* "MARKDOWN & GIT-GITHUB"
*Autor:* Gabriel A. Vasquez H.
*Creado:* 18/08/2023
*Versión:* 1.00
*Publicado:* no
***

## Objetivo

El objetivo de este trabajo practico es familiarizacer con con el uso de git, github y markdown.

* Objetivos:
  1. Usuario de Github.
  1. Creacion de repositorio.
  1. Clonar repositorio.
  1. Realizar nuestro primer commit desde nuestra PC.
  1. Configurar Github-Desktop, Visual Studio Code.
  1. Crea Documento Markdown.
  
***

## Pasos Git

* Crea un nuevo repositorio haciendo clic en el botón de "Nuevo repositorio" en la página web de GitHub.
* Elije un nombre para tu primer repositorio, agrega una pequeña descripción, marca la opción "Inicializar este repositorio con un README", y haz clic en el botón "Crear Repositorio".
* Tu primera misión es obtener una copia del repositorio en tu computadora. Para hacer eso, necesitas "clonar" el repositorio en tu computadora.
  * Descargar git
  * Verifica que Git se instaló correctamente
  >git --version

  * Configuramos git
  >git config --global user.name "Gabriel - VH"
git config --global user.email "example@mail.com"
  * cd [NAME OF REPOSITORY]
  git clone [DIRECCION HTTPS]


## Markdown

* Crear un archivo Maarkdown(debe terminar .md)
* Agrege un parrafo al documento. 
* Agrege tres encabezados de diferentes tamanos.
* Esscribimnos un parrafo largo(esto es texto continuo sin enter. Cada enter es un nuevo parrafo)
* Editamos negrita y cursiva, para esto se puede usar * o _, Agrege el siguiente renglon:
  Hola _Alumnos_ __como__ se ___ve?___
  * Que pasa si:
    Hola \_Alumnos\_ \_\_como\_\_ se \_\_\_ve?\_\_\_
  
* Agregamos enlaces 
[Texto del link](https://youtube.com/)
[Enlance interno](#tp-git)
[A la imagen](ruta de la imagen)  
si se la antecede un ! entonces nos meustra al imagen en el documento.
* Agregar divisiones al documento
  para esto se usa: --- (equivalente a las etiquetas hr de HTML)
* Crear una lista ordenada.
* Crear una lista sin orde (La vinietase puede usar, -;+;* recordar dejar un espacio).
* Crear una sublista.
* Citas, 
  * Modifique el texto siguiente para que apaparescan como un solo blque pero con un renglon en blanco de separacion.
  * Modifique el texto siguiente para que apaparescan como tres bloques separados.

> Más valen dos que uno,
porque obtienen más fruto de su esfuerzo.  Eclesiastés 4:9

* Cree una tabla, de Nombre, Eded,emial.
+ Agrege un bloque de codigo:
  + Agregar un codigo en linea.
    En javascript utilizamos la palabra clave `let` que se utiliza para declarar una variable con alcance de bloque.
  + agregar un codigo en un bloque.
    ```js
    function suma(a,b)
    {
      return a + b;
    }
    ```
+ Que pasa si insertamos html:
  <from>
  <label for="q">Buscar:<\label>   
  <input type="search" name="q" id="q">
  </from>
+ Comentario e Markdown, es como en html.
<!-- Esto eno genera vsta -->
+ Ignorar el uno normal en mardown