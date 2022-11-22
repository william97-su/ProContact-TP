<img align="right" alt="img" src="https://user-images.githubusercontent.com/75348924/202714183-134a8600-6541-4a1f-a569-ad01e5195400.png" width="" height="auto" />


# EVALUACIÓN PRÁCTICA

## EJERCICIO 2

- 1	<b>¿Qué es un servidor HTTP? </b>

Un servidor HTTP es una pieza de software capaz de comprender URLs (direcciones web) y HTTP (el protocolo que tu navegador usa para obtener las páginas web). Un servidor HTTP puede ser accedido a través de los nombres de dominio de los sitios web que aloja, y entrega el contenido de esos sitios web alojados al dispositivo del usuario final.

- 2	<b>¿Qué son los verbos HTTP? Mencionar los más conocidos</b>

Son un conjunto de métodos de petición para indicar la acción que se desea realizar para un recurso determinado, los más conocidos son: GET utilizado para consultar un recurso, su característica es que no deben producir nuevos registros, ni modificar los ya existentes. POST son sólo para crear recursos nuevos. Cada llamada con POST debería producir un nuevo recurso. PUT/PATCH son muy similares ya que ambos se usan para modificar un recurso existente. PUT se utiliza para remplazar por completo un recurso mientras que PATCH es utilizado para aplicar modificaciones parciales a un recurso. DELETE borra un recurso en específico.

- 3	 <b>¿Qué es un request y un response en una comunicación HTTP? ¿Qué son los headers? </b>

HTTP se basa en un modelo solicitud / respuesta, de modo que hay dos tipos de mensajes HTTP: la solicitud y la respuesta. El navegador abre una conexión a un servidor y realiza una solicitud. El servidor procesa la solicitud del cliente y devuelve una respuesta.
Los HTTP headers son la parte central de los HTTP requests y responses, y transmiten información acerca del navegador del cliente, de la página solicitada, del servidor.

- 4	 <b>¿Qué es un queryString? (En el contexto de una url)</b>

Siempre que nosotros ingresamos a un sitio web utilizando nuestro navegador la petición al servidor se hará a través del método GET.
Con este método podemos enviar información al servidor de tal forma que seamos más precisos en el recurso que deseamos obtener. La información la enviaremos a través de la URL, en una sección denominada Query String.

- 5 <b>¿Qué es el responseCode? ¿Qué significado tiene los posibles valores devueltos?</b>

Los códigos de estado de respuesta HTTP indican si se ha completado satisfactoriamente una solicitud HTTP específica. Las respuestas se agrupan en cinco clases:

> - Respuestas informativas (100–199)
> - Respuestas satisfactorias (200–299)
> - Redirecciones (300–399)
> - Errores de los clientes (400–499)
> - Errores de los servidores (500–599)


- 6	<b>¿Cómo se envía la data en un Get y cómo en un POST?</b>

Con el método GET, los datos que se envían al servidor se escriben en la misma dirección URL.
Toda la información introducida por el usuario (los llamados “parámetros URL”) se transmiten tan abiertamente como el URL en sí mismo.
El método POST introduce los parámetros en la solicitud HTTP para el servidor. Por ello, no quedan visibles para el usuario.

- 7	<b>¿Qué verbo http utiliza el navegador cuando accedemos a una página?</b>

El navegador envía una petición de documento HTML al servidor (GET). Entonces procesa este documento, y envía más peticiones para solicitar scripts, hojas de estilo, etc.

- 8	<b>Explicar brevemente qué son las estructuras de datos JSON y XML dando ejemplo de estructuras posibles.</b>

Se utilizan para la transferencia de datos estructurados entre un servidor de Web y una aplicación Web.

El XML se basa en el uso de etiquetas. Estas pueden ser vacíos o tener contenido y otros elementos. Siempre se encuentran entre <> y se cierran con </>.
Hoy en día, es uno de los más usados por aquellos que se dedican a la gestión de proyectos empresariales.

El formato JSON (JavaScript Object Notation) es un formato abierto utilizado como alternativa al XML. El formato ganó popularidad en servicios de la Web, dado que consigue transmitir una gran cantidad de información entre el cliente y el servidor utilizando una menor cantidad de caracteres.

<b>Estrucutra JSON</b>

```JSON
{
 "Usuario 1": {
  "Id": "1",
  "Nombre": "William",
  "ImgPerfil": "Url"
 },
 "Usuario 2": {
  "Id": "2",
  "Nombre": "Hideo",
  "ImgPerfil": "Url"
 },
 "Usuario 3": {
  "Id": "3",
  "Nombre": "Kojima",
  "ImgPerfil": "Url"
 }
}
```

<b>Estructura XML</b>

```XML
<libreria>
    <libro categoría="COOKING">
        <título lang="en">Everyday Italian</título>
        <autor>Giada De Laurentiis</autor>
        <año>2005</año>
        <precio>3000</precio>
    </libro>
    <libro categoría="INFANTIL">
        <título lang="en">Harry Potter</título>
        <autor>J K. Rowling</autor>
        <año>2005</año>
        <precio>299</precio>
    </libro>
    <libro categoría="WEB">
        <título lang="en">Learning XML</título>
        <autor>Erik T. Ray</autor>
        <año>2003</año>
        <precio>100</precio>
    </libro>
</libreria>
```

- 9	  <b>Explicar brevemente el estándar SOAP</b>

SOAP es un protocolo estándar que se creó originalmente para posibilitar la comunicación entre las aplicaciones que se diseñaban con diferentes lenguajes y en distintas plataformas.
Los servicios web de SOAP ofrecen seguridad y cumplimiento de las operaciones integrados que coinciden con muchas de las necesidades empresariales, pero que también los hacen más pesados. Los mensajes SOAP de retorno deben ser documentos XML.

- 10	<b>Explicar brevemente el estándar REST Full</b>

REST es un conjunto de principios arquitectónicos que se ajusta a las necesidades de las aplicaciones móviles y los servicios web ligeros. Dado que se trata de un conjunto de pautas, la implementación de las recomendaciones depende de los desarrolladores. Cuando se envía una solicitud de datos a una API de REST, se suele hacer a través de un protocolo de transferencia de hipertexto.
RESTful hace referencia a un servicio web que implementa la arquitectura REST.

- 11	<b>¿Qué son los headers en un request? ¿Para qué se utiliza el key Content-type en un header?</b>

 Los headers HTTP permiten al cliente y al servidor enviar información adicional junto a una petición o respuesta.
 
 Content-Type dice al cliente que tipo de contenido será retornado.
 
 Por ejemplo
 
 ```
application/pdf
application/xml
audio/ogg
audio/mpeg
image/apng
image/jpeg (.jpg, .jpeg, .jfif, .pjpeg, .pjp)
text/css
text/html
text/php
text/xml
video/mp4
```

## EJERCICIO 3
## EJERCICIO 4

[Cuenta de Trailhead](https://trailblazer.me/id/gwilliam)

