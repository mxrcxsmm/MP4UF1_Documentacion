# MP4UF1_Documentacion
## Índice
1. Github
   
   1.1. Instalación de git
   
   1.2. Darse de alta en Github
   
   1.3. Instalación de Visual Studio Code
   
   1.4. Como crear los repositorios en Github
   
   1.5. Como clonar los repositorios para editar en local
2. Markdown
   
   2.1. Sintaxis Markdown
3. HTML
4. CSS
--------------------------------------------------------
1. GITHUB
   
   1.1 Instalación de git
      * Descargar el instalador de GIT para Windows
      * Una vez que hayas descargado el instalador, haz doble clic sobre el ejecutable para que           comience el proceso de instalación y sigue las instrucciones que te aparecerán en pantalla.       Al igual que cualquier otro programa, tendrás que dar “Next” (siguiente) en varias               ocasiones hasta que aparezca la opción “Finish” (terminar) para completar la instalación.
      * Ahora tienes que abrir el cmd y escribir los siguientes comandos en la terminal de tu SO:
    ``` 
    git config --global user.name "nombre de usuario"
    git config --global user.mail "ejemplo@gmail.com"
    ```
   1.2. Darse de alta en Github
      1. Ir a [Github.com](https://github.com/join)
      2. Escriba un nombre de usuario, una dirección de correo electrónico y una contraseña
      3. Ir a __Sign up for Github__ y seguir las instrucciones.
   
   1.3. Instalación de Visual Studio Code
      1. Ir a la página Microsoft [Visual Studio Code](https://code.visualstudio.com/) y haz clic          en el botón de descargar.
      2. Abrir el archivo de instalación en nuestra carpeta de descargas para iniciar la                  instalación
      3. Cuando nos aparece la primera pantalla del instalador, tenemos que aceptar el acuerdo de licencia y le damos todo a __Next__ hasta que nos aparezca la última            pantalla que nos saldrá __Finish__ y ya podremos utilizar nuestro programa.

   1.4. Como crear los repositorios en Github
   ![image](https://user-images.githubusercontent.com/90915730/193757398-0ca53db6-2763-405f-b097-bcd2658c9ef5.png)
   
   
   Para crear un nuevo repositorio en Github, tienes que irte a mis repositorios y clicar en la zona marcada que pone New.
   
   
   
   ![image](https://user-images.githubusercontent.com/90915730/193758482-beaf0afc-0754-4438-83ad-d085aa362631.png)
   
   Una vez le das a New, te sale esta ventana donde en las zonas remarcadas son las zonas "más importantes" por así decirlo. La primera es como se va a llamar tu          repositorio y como lo van a ver las personas que lo visitarán. El siguiente punto es decidir si va a ser privado o público, es decir, si quieres todo el mundo o si    es privado, solo la gente que tu decidas que lo pueda ver. El siguiente punto es decidir si va a tener un fichero README.md, eso quiere decir que es un documento      como si fuese de texto pero tiene diferentes funciones que en el siguiente punto os explico. Por último, es el botón para crear el repositorio.

   1.5. Como clonar los repositorios en local
   
   ![image](https://user-images.githubusercontent.com/90915730/193762405-d4ac4112-1057-4b5a-9249-4b1f664a3480.png)
   
   Para que Github nos de el código, tenemos que seguir los pasos como indica la imagen. 
   
   Una vez tenemos el código copiado en el portapapeles, tenemos que irnos a Visual Studio Code para ejecutar el comando que nos lo clona en local. Pero antes de          clonarlo, tenemos que seleccionar en donde queremos guardar el trabajo en local, es decir, en que carpeta queremos que se guarde. Para ello, tenemos que irnos a la    barra de arriba y seleccionar Archivo --> Abrir carpeta y seleccionas la carpeta donde quieres que se guarde. Por último, abrimos un terminal en el propio Visual y    ejecutamos lo siguiente:
   
   ```git clone con el enlace que hemos copiado anteriormente en el Github```
   
2. Markdown
     
     2.1. Sintaxis Markdown
      - Las ```#``` son uno de los métodos utilizados en Markdown para crear encabezados. El más grande es poniendo una almohadilla y el más pequeño es                         poniendo 6 almohadillas.
      - Las citas se generan utilizando el carácter ```>``` la comienzo del bloque o texto.
      - Para crear las listas desordenadas se utilizan tres tipos de símbolos: 
          * Asteriscos 
          * Guiones
          * Símbolo de suma
      - Para crear las listas ordenadas, debemos utilizar la sintaxis de tipo: <<número.>> ```1.```. Al igual que con las desordenadas, podremos combinarlas.
      - Para crear un bloque entero que contenga código, lo único que tenemos que hacer es encerrar dicho párrafo entre dos líneas formadas por tres ```~```                   virgulillas.
      - Para poder hacer la palabra o la frase que quieras en cursiva, hay dos formas de hacerlo:
          * Con asterisco simple tanto a principio como a final de palabra o frase
          * *cursiva*
          * Con guión bajo tanto a principio como a final de palabra o frase
          * _cursiva_
      - Para poder hacer la palabra o el texto en negrita puedes hacerlo de dos formas:
          * Con doble astérisco tanto a principio como a final de palabra o el texto
          * **negrita**
          * Con doble guión bajo tanto a principio como a final de palabra o texto
          * __negrita__
      - Para enlazar a una página web tienes que escribir la palabra o texto enlazado entre ```[]``` corchetes y el link entre ```()``` paréntesis.
      - Para insertar una imagen con Markdown, tienes que añadir una exclamación al principio y el enlace de la propia imagen, tanto si es en local como si has copiado         la URL de Google.
          * ```![Texto alternativo](rutaalaimagen)```

3. HTML

   ![image](https://user-images.githubusercontent.com/90915730/196371080-4b196740-b0cd-43b2-aca5-ce771d12d1c5.png)

   1.1. En el head, se tiene que poner el título que quieras para que salga tu página web. A parte, puedes enlazar con un documento css para aplicarle estilos a tu página y hacerla más dinámica.
   
   ![image](https://user-images.githubusercontent.com/90915730/208617025-2ef0c06f-7d43-4884-935e-b70ccfc2e401.png)
   
   1.2. En el body es donde va a ir toda la parte importante, es decir, todo el código de la página web.
   
   ![image](https://user-images.githubusercontent.com/90915730/208617082-8c07db47-0875-44b9-bee9-59d493598021.png)
   
   1.3. <meta>. Define los metadatos que no pueden ser definidos usando otro elemento HTML. 
   
   ![image](https://user-images.githubusercontent.com/90915730/208616946-69cfdecc-0281-4d28-a6f8-b529df10a553.png)
   
   1.4. <title>. Representa el título del documento. Se muestra en la barra superior del navegador o en las pestañas de página.
   
   ![image](https://user-images.githubusercontent.com/90915730/208619625-ee146b8d-67cc-4f70-878e-af6b99ab0e21.png)

   1.5. <link>. Utilizada para enlazar documentos externos, por ejemplo CSS. Se debe incluir dentro del <head>.
   
   ![image](https://user-images.githubusercontent.com/90915730/208619539-0516ae5d-2fdb-4a3e-b662-fcfbbd604886.png)   
   
   1.6. <style>. Usada para escribir CSS interno.
   
   ![image](https://user-images.githubusercontent.com/90915730/208618912-5cf0e0b2-8520-4cd3-b3c6-5a9d5a982e32.png)

   1.7. header. Determina la cabecera de una web o de un elemento.
   
   ![image](https://user-images.githubusercontent.com/90915730/208619041-45b5b364-aaa8-4455-bb0e-b99ecde58516.png)

   1.8. Encabezados. Describe el tema de la sección. Disponemos de seis niveles: de h1 a h6, siendo h1 la cabecera de mayor importancia. Sólo puede existir una etiqueta h1 en el documento.
   
   ![image](https://user-images.githubusercontent.com/90915730/208618333-090f3933-aa93-4d21-9eea-58b86ea0b34f.png)

   ![image](https://user-images.githubusercontent.com/90915730/208618479-e5326930-d99d-4819-9588-584bf93e1a2d.png)

   1.9. Párrafo. Se utilizan para encerrar párrafos de texto, entendiendo como párrafo un conjunto de frases relacionadas entre sí. Son elementos de bloque.
   
   ![image](https://user-images.githubusercontent.com/90915730/208621835-3f1f6793-f3c6-43c6-8a7d-1daf8ff11547.png)

   1.10. Listas:
      
      1.10.1. Desordenadas. Son aquellas en las que el orden de los ítems no es relevante, como en una lista de compras. Estas son encerradas en un elemento ul.
      
      1.10.2. Ordenadas. son aquellas en las que el orden sí es relevante, como en una receta. Estas son encerradas en un elemento ol.
   
      IMPORTANTE. CADA ELEMENTO DE LA LISTA SE COLOCA DENTRO DE UN ELEMENTO li.
   
   1.11. Enlaces. Sirve para convertir algún texto dentro de un párrafo en un vínculo.
   
   1.12. Salto de línea. (br) Inserta un intro en un párrafo.
   
   1.13. Comentarios. En un documento HTML podemos poner anotaciones que no se visualizarán cuando la página web se vea en el navegador pero que son útiles para desarrollar la web. La sintaxis es <!-- comentario -->
   
4. CSS
   
   ![image](https://user-images.githubusercontent.com/90915730/208623346-a9cfee6a-d5e1-424c-b7c0-f737f1ad104a.png)

   4.1. Selector de elementos. Corresponde con todos los elementos de este nombre en la página. El siguiente ejemplo afectaría a TODOS los elementos a del documento HTML
   
   ![image](https://user-images.githubusercontent.com/90915730/208624497-25a379cb-3e1e-41fa-8a41-eb3c88d00289.png)

   4.2. Selector de clase. Corresponde con todos los elementos que tengan el atributo class con el valor especificado. Por ejemplo el selector
   
   ![image](https://user-images.githubusercontent.com/90915730/208624456-4598bb2f-b2db-485f-b0c2-431f8a0df4af.png)

   4.3. Selector de id. Corresponde a todos los elementos HTML que tienen un atributo id con el valor especificado.
   
   ![image](https://user-images.githubusercontent.com/90915730/208624389-4eb0b113-b555-401d-97e2-8ff3f6238ddb.png)

   4.4. Selectores universales. Sirven para seleccionar todos los elementos de la página. En el  ejemplo, todos los elementos han de tener un borde solido negro de un pixel.
   
   ![image](https://user-images.githubusercontent.com/90915730/208624336-1408e4c6-5fff-450c-87ab-99db6e215a92.png)

   4.5. Selectores de atributos. Permiten seleccionar elementos en función de los atributos que contienen. En el ejemplo quedan afectados todos los elementos img con un atributo “alt”.
   
   ![image](https://user-images.githubusercontent.com/90915730/208624303-67fd7763-fe02-4ac3-b5d5-ca518ac99c71.png)

   4.6. Selectores de hijos. Para seleccionar elementos concretos que son hijos DIRECTOS de otros elementos concretos. Por ejemplo, esta regla pone de color azul el texto de los elementos strong que son hijos de h3 pero no el resto de elementos strong.
   
   ![image](https://user-images.githubusercontent.com/90915730/208624240-bf14ad1d-a3d8-42b4-af57-62d1fed892de.png)

   4.7. Selectores de descendientes. Similar al selector de hijos pero, a diferencia de ellos, que solo seleccionan elementos descendientes DIRECTOS, los selectores de descendientes seleccionan los elementos pertinentes EN CUALQUIER PUNTO de la jerarquía del elemento.
   
   ![image](https://user-images.githubusercontent.com/90915730/208624176-22caa9f5-f3e9-4324-ba6a-4a007c3bd2b1.png)

   4.8. Selectores de hermanos adyacentes. Permiten seleccionar un elemento concreto que aparece DIRECTAMENTE DESPUÉS de otro elemento concreto al mismo nivel de la jerarquía del elemento.
   
   ![image](https://user-images.githubusercontent.com/90915730/208624646-49c2722c-eb78-4eed-a669-80edb0d8592a.png)

   4.9. Márgenes (margin). Representan el área transparente que rodea la caja. Es decir, el espacio que la separará de los elementos contiguos. La propiedad margen se puede desplegar a su vez en cuatro propiedades además del valor “margin” como propiedad global.
      - margin-top (margen superior)
      - margin-bottom (margen inferior)
      - margin-right (margen derecho)
      - margin-left (margen izquierdo)
   
   4.10. Bordes (border). Representan el estilo que tendrán los bordes del elemento.
   
   4.11. Relleno (padding). Espacio entre el borde del elemento y su contenido.
   
