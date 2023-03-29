#
# Markdown #
---
---
#
>## Parrafos y Saltos de linea ##
----
#
El signo "#" nos sirve para hacer saltos de linea en los parrafos de algun texto, por lo tanto, se deben poner dos espacios en blanco.
Ejemplo:  
Lo que estoy escribiendo en esta parte esta separado por esos dos espacios.

#
>## Encabezados ## 
---
#
Los encabezados en markdown se deben hacer poniendo el signo "#" seguido del texto que estemos escribiendo. Dependiendo de la cantidad de "#", el texto que tenganis ira cambiando de tamaño, y asi sabremos que es un título, subtítulo,etc.  

#
>## Mejores Prácticas de encabezado ##
#
Si queremos que un encabezado este colocado correctamente debe ir "#" seguido del texto que se quiera poner en el encabezado, lo que no debemos hacer es colocar el "#" despues del texto ya que no se pondra como encabezado.
Algo que se recomienda en este tipo de escritura con Markdown, es colocar líneas en blanco antes y después del texto, para que asi sea mas presentable la página.
# 
>## Saltos de linea ##
---
#
En los saltos de línea se debe utilizar el elemento <"br"> sin las comillas, lo cual generará un salto de línea en la páginan o el parrafo.
<br>

#
>## Enfasis ##
---
#
Si queremos colocar texto en negritas o cursiva se deben colocar los signos "*".

#
>## Atrevido ##
---
#
Para poner el texto en negritas, se debe agregar dos "*" al inicio y al final de la palabra que queramos remarcar.  
**Administración de python**  
#
>## Prácticas recomendadas ##
---  
#
Una recomendacion cuando utilizamos las negritas es no utilizar los guiones bajos, por lo cual debemos utilizar el "*" cuando se quiera poner texto en negritas.

#
>## Italico ##
---
#
Si queremos poner el texto en cursivas, algo que es similar a las letras en negritas, se debe poner "*" uno al inicio y al final del texto que se quiere modificar.   
*Markdown*

#
>## Prácticas recomendadas en cursiva ##
---
#
En este caso se debe hacer lo mismo que en la cursiva sin utilizar los guiones bajos, solo seguir utilizando el signo "*" para crear palabras en cursiva.

#
>## Negrita y cursiva ##
---
#
Si queremos colocar el texto con ambos estilos, solo se debe poner "*" al inicio y al final del texto que se quiera ver en negritas y cursiva.   
***Este es un ejemplo***

#
>## Mejores Prácticas en negrita y cursiva ##
---
#
Al igual que en las negritas, solo se debe usar "*" para colocar el texto en estilo negritas y cursiva.

#
>## Cotizaciones en bloque ##
---
#
Si queremos crear una cita en bloque solo debemos agregar el simbolo ">" delante del texto.
  
>Texto escrito en cita de bloque

#
>## Blockquotes con múltiples parrafos ##
---
#
Para crearlos debemos utilizar el signo ">" en cada línea que queramos colocar en el texto.  
>Texto    
>escrito con el  
>signo ">".

#
>## Citas en bloques anidadas ##
---
#
En esta parte para generar estas citas debemos colocar doble ">" delante del texto.   

>Practica de Markdown
>>Elaborado con git bash

#
>## Blockquotes con otros elementos ##
---
#
En este apartado solo debemos utilizar lo que se ha aplicado anteriomente en el ejercicio

>### Ejercicio elaborado en git bash con estructura Markdown ###   
>
> - Practica ejemplo
> - Ejercicio hecho en git bash
> 
> Grupo *372*

#
>## Liza ##
---
#
Se utiliza para organizar el texto en lista.  
1.Cargador  
2.Laptop  
3.Pc  
4.Hardware  
5.Software  

#
>## Listas desordenadas ##
---
#
Si queremos crear listas debemos utilizar el signo "-". "*" o tambien el "+", de igual forma sera el mismo resultado aunque utilicemos cualquier de esos signos.  

#
>## Comenzar elementos de lista desordenados con números ##
---
#
Si queremos crear una lista diferente, ahora se utilizara la barra invertida. y el numero este seguido de un punto.    
-11/09/2001\. Desafortunado evento donde cayeron las torres gemelas
![](https://imagenes.elpais.com/resizer/M950pSMf4knrjG-H6ycnnR-W6ko=/1960x1103/cloudfront-eu-central-1.images.arcpublishing.com/prisa/QRPB5SOC5VDQDNMHEA7AGMQCB4.jpg)

#
>## Bloques de código
---
#
Normalmente los bloques de código tienen una sangría de cuatro espacios o una tabulación. En el caso de la lista se debe poner una sangría de ocho espacios o doble tabulación.

#
>## Código ##
---
#
Si queremos remarcar una palabra como código debemos encerrarlo con ().

#
>## Escapar de los acentos graves ##
---
#
Si queremos denotar una palabra como código se debe incluir uno o más acentos graves, puede salir encerrandola entre dobles acentos graves (``).

#
>## Reglas horizontales ##
---
#
Para crear una regla horizontal, use tres o más asteriscos ( ***), guiones ( ---) o guiones bajos ( ___) en una sola línea.

#
>## Enlaces ##
---
#
Para crear un enlace, encierre el texto del enlace entre corchetes (p. ej., [Duck Duck Go]) y luego sígalo inmediatamente con la URL entre paréntesis.   
Ejemplo (https://www.google.com).
![](https://play-lh.googleusercontent.com/1-hPxafOxdYpYZEOKzNIkSP43HXCNftVJVttoo4ucl7rsMASXW3Xr6GlXURCubE1tA=w3840-h2160-rw)


#
>## Agregar títulos ##
---
#
Opcionalmente, puede agregar un título para un enlace. Esto aparecerá como información sobre herramientas cuando el usuario se desplace sobre el enlace.

#
>## URL y direcciones de correo electronico ##
---
#
Para convertir rápidamente una URL o una dirección de correo electrónico en un enlace, enciérrelo entre "<>"

#
>## Formateo de enlaces ##
---
#
Para enfatizar los enlaces, agregue asteriscos antes y después de los corchetes y paréntesis
#

>## Vínculos de estilo de referencia ##
---
#
Los enlaces de estilo de referencia son un tipo especial de enlace que hace que las URL sean más fáciles de mostrar y leer en Markdown. Los enlaces de estilo de referencia se construyen en dos partes: la parte que mantiene en línea con su texto y la parte que almacena en otro lugar del archivo para que el texto sea fácil de leer.  

#
>## Dar formato primera parte del enlace ##
---
#
La primera parte de un vínculo de estilo de referencia se formatea con dos conjuntos de corchetes. El primer conjunto de corchetes rodea el texto que debería aparecer vinculado. El segundo conjunto de corchetes muestra una etiqueta que se usa para apuntar al enlace que está almacenando en otra parte de su documento.  

#
>## Formateo de la segunda parte del enlace ##
---
#
La segunda parte de un vínculo de estilo de referencia se formatea con los siguientes atributos:

1. La etiqueta, entre paréntesis, seguida inmediatamente por dos puntos y al menos un espacio (p. ej., [label]: ).
2. La URL del enlace, que opcionalmente puede encerrar entre paréntesis angulares.
3. El título opcional del vínculo, que puede encerrar entre comillas dobles, comillas simples o paréntesis.  

#
>## Un ejemplo de juntar las partes ##
---
#
Digamos que agrega una URL como un enlace de URL estándar a un párrafo y se ve así en Markdown:

In a hole in the ground there lived a hobbit. Not a nasty, dirty, wet hole, filled with the ends
of worms and an oozy smell, nor yet a dry, bare, sandy hole with nothing in it to sit down on or to
eat: it was a [hobbit-hole](https://en.wikipedia.org/wiki/Hobbit#Lifestyle "Hobbit lifestyles"), and that means comfort.  
Aunque puede apuntar a información adicional interesante, la URL que se muestra en realidad no agrega mucho al texto sin formato existente, aparte de dificultar la lectura. Para arreglar eso, podría formatear la URL de esta manera:

In a hole in the ground there lived a hobbit. Not a nasty, dirty, wet hole, filled with the ends
of worms and an oozy smell, nor yet a dry, bare, sandy hole with nothing in it to sit down on or to
eat: it was a [hobbit-hole][1], and that means comfort.

[1]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> "Hobbit lifestyles"  

#
>## Imagenes ## 
---
 #
 Para agregar una imagen, agregue un signo de exclamación ( !), seguido del texto alternativo entre paréntesis y la ruta o URL del recurso de imagen entre paréntesis. Opcionalmente, puede agregar un título entre comillas después de la ruta o URL  
 ![Python](https://media0.giphy.com/media/KAq5w47R9rmTuvWOWa/giphy.gif)  
 Como podemos ver aqui llamamos una imagen pero usando una URL
 #
 >## Vinculación de Imágenes ##
#
Para agregar un enlace a una imagen, encierre el Markdown de la imagen entre paréntesis y luego agregue el enlace entre paréntesis. 

 ![Intentando buscar la imagen](https://c.tenor.com/gyNDu8UeHA8AAAAd/looking-for-a-job-job.gif "No encontramos lo que estabas buscando") 
 En este caso si pasas el maouse sobre la imagen te mostrara un texto.

 #
 >## Personajes que escapan ##
 ---
#
Para poder mostrar un carácter que de otro modo se usuaría para dar formato al texto, se debe poner una barra invertida delante del caracter.  
Ejemplo:   
\ * sin la barra invertida esto seria una lista desordendad  
Ejemplo sin la barra invertida:  
* Esto es una lista ordenada sin la barra invertida
#  
>## HTML ##
#
Muchas aplicaciones de Markdown le permiten usar etiquetas HTML en texto con formato de Markdown. Esto es útil si prefiere ciertas etiquetas HTML a la sintaxis Markdown. Por ejemplo, a algunas personas les resulta más fácil usar etiquetas HTML para imágenes

#
## Hasta la proxima ##
---
#
![](https://media.tenor.com/RBL0tBqEhC4AAAAM/hast-la-proximaaa-social-distancing.gif)