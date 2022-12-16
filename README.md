<img align="right" alt="img" src="https://user-images.githubusercontent.com/75348924/202714183-134a8600-6541-4a1f-a569-ad01e5195400.png" width="" height="auto" />


# EVALUACIÓN PRÁCTICA

## EJERCICIO 2

- 1	<b>¿Qué es un servidor HTTP? </b>

Un servidor HTTP es una pieza de software capaz de comprender URLs (direcciones web) y HTTP (el protocolo que tu navegador usa para obtener las páginas web). Un servidor HTTP puede ser accedido a través de los nombres de dominio de los sitios web que aloja, y entrega el contenido de esos sitios web alojados al dispositivo del usuario final.

- 2	<b>¿Qué son los verbos HTTP? Mencionar los más conocidos?</b>

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
 
 Por ejemplo:
 
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

- <b>1	Realizar un request GET</b>

<img align="" alt="img" src="https://user-images.githubusercontent.com/75348924/202811121-37e3c9cc-c277-44bf-aa70-ce46d7f31820.PNG" width="" height="auto" />

- <b>2	Realizar un request POST </b>

<img align="" alt="img" src="https://user-images.githubusercontent.com/75348924/202811819-31f0119c-d600-45b8-ae52-82625f4a793a.PNG" width="" height="auto" />

- <b>3	Realizar nuevamente un request GET </b>

<img align="" alt="img" src="https://user-images.githubusercontent.com/75348924/202812392-b06aacc1-76c6-40f1-8d9a-57b0e3d45e13.PNG" width="" height="auto" />

<b>¿Qué diferencias se observan entre las llamadas el punto 1 y 3?</b>

La única diferencia es el nuevo dato agregado a causa de la request POST del punto 2, al realizar nuevamente la request GET obtuve el objeto actualizado con el impacto del POST ya incluido.


## EJERCICIO 4

<img align="" alt="img" src="https://user-images.githubusercontent.com/75348924/208189879-4c382b68-b41e-4dd3-b300-c2b827426aaf.PNG" width="" height="auto" />

[Cuenta de Trailhead](https://trailblazer.me/id/gwilliam)

## EJERCICIO 5

Explicar qué son conceptualmente, qué datos almacenan en forma estándar y cómo se relacionan al resto cada uno de los siguientes objetos de Salesforce.

1. Lead: Representa un prospecto o cliente potencial. 

<details><summary>Campos</summary>

    - Address
    - Annual Revenue
    - Campaign
    - Clean Status
    - Company
    - Company D-U-N-S Number
    - Created By
    - Current Generator(s)
    - D&B Company
    - Data.com Key
    - Description
    - Do Not Call
    - Email & Email Opt Out
    - Fax & Fax Opt Out
    - Individual
    - Industry
    - Last Modified By
    - Last Transfer Date
    - Lead Owner
    - Lead Source
    - Lead Status
    - Mobile
    - Name
    - No. of Employees
    - Number of Locations
    - Phone
    - Primary
    - Product Interest
    - Rating
    - SIC Code
    - Title
    - Website
 
</details>
 
2. Account: Representan compañías con las que se hace negocio o relacionadas con el mismo (clientes, socios, competencia).

<details><summary>Campos</summary>

    - Account Name, Number, Owner, Site Source
    - Active
    - Annual Revenue
    - Billing Address
    - Clean Status
    - Created By
    - Customer Priority
    - D&B Company
    - Data.com Key
    - Description
    - D-U-N-S Number
    - Einstein Account Tier
    - Employees
    - Fax
    - Industry
    - Last Modified By
    - NAICS Code & Description
    - Number of Locations
    - Ownership
    - Parent Account
    - Phone
    - Rating 
    - Shipping Address
    - SIC Code & Description
    - SLA, Expiration Date, Serial Number
    - Ticker Symbol
    - Tradestyle
    - Type
    - Upsell Opportunity
    - Website
    - Year Started
 
</details>

3. Contact: Son personas asociadas con una cuenta, con las que se requiere comunicación y relaciones de negocio. Provienen de Leads u otras fuentes y tienen especial utilidad en permitir darle seguimiento a la información que provoca relaciones efectivas. 

<details><summary>Campos</summary>
 
    - Account Name
    - Assistant & Asst. Phone
    - Birthdate
    - Clean Status
    - Contact Owner
    - Created By
    - Data.com Key
    - Department
    - Description
    - Do Not Call
    - Email & Email Opt out
    - Fax & Fax Opt Out
    - Home Phone
    - Individual
    - Languages
    - Lasy Modified By
    - Last Stay-in-Touch Request Date & Last Stay-in-Touch Save Date
    - Lead Source
    - Level
    - Mailing Address
    - Mobile
    - Name
    - Reports To
    - Stage
    - Title
 
</details>

4. Opportunity: Son tratos cualificados con los que el equipo de ventas está trabajando. Ayudan a monitorear la etapa en la que se encuentra el proceso de venta. Una oportunidad se suele crear cuando un Lead es convertido.

<details><summary>Campos</summary>

    - Account Name
    - Amount
    - Close Date
    - Contract
    - Created By
    - Current Generator(s)
    - Delivery/Installation Status
    - Description
    - Expected Revenue
    - Forecast Category
    - Lasy Modified By
    - Lead Source
    - Main Competitor(s)
    - Next Step
    - Opportunity Name, Owner, Score
    - Order Number
    - Price Book
    - Primary Campaign Source
    - Private
    - Probability (%)
    - Quantity
    - Stage
    - Tracking Number
    - Type
 
</details>

5. Product: Son artículos o servicios que se ofrecen a los clientes. Cada producto puede existir en múltiples Price Books con diferentes precios.
 
 <details><summary>Campos</summary>
 
    - Active
    - Created By
    - Display URL
    - External Data Source
    - External ID
    - Last Modified By
    - Product Code, Description, Family, Name, SKU
    - Quantity Unit of Measure
 
</details>

6. Price Book: Se trata de una lista de productos y precios.

<details><summary>Campos</summary>

    - Active
    - Created By
    - Description
    - Is Standard Price Book
    - Last Modified By
    - Price Book Name
 
</details>

7. Quote: Representa una cotización, que es un registro que muestra los precios propuestos para productos y servicios.

<details><summary>Campos</summary>

    - Account Name
    - Additional To & Additional To Name
    - Bill To & Bill To Name
    - Contact Name
    - Contract
    - Created By
    - Description
    - Discount
    - Email 
    - Expiration Date
    - Fax 
    - Grand Total
    - Last Modified By
    - Line Items
    - Opportunity Name
    - Owner Name
    - Phone
    - Quote Name, Number, PDF, To, To Name
    - Shipping and Handling
    - Shipping, To, To Name
    - Status
    - Subtotal
    - Syncing
    - Tax
    - Total Price
 
</details>

8. Asset: Mientras que el objeto de Product representa los productos que la compañía vende, los assets representan los productos específicos que los clientes han comprado. Es decir, los Assets se utilizan para guardar información de las adquisiciones de los clientes.

<details><summary>Campos</summary>

    - Account
    - Address
    - Asset Level, Name, Owner
    - Asset Provided By, Serviced By
    - Competitor Asset
    - Consequence of Failure
    - Contact
    - Created By & Last Modified By
    - Current Amount, Lifecycle End Date, Monthly Recurring Revenue, Quantity
    - Description
    - Digital Asset Status
    - External Id
    - Has Lifecycle Management
    - Install Date
    - Internal Asset
    - Lifecycle End Date
 
</details>

9. Case: Un case se refiere a alguna pregunta, retroalimentación o inconveniente que proviene de un cliente. Tiene especialidad utilidad para identificar acciones que se pueden tomar para tener una mejor atención y conformidad del cliente. 

<details><summary>Campos</summary>
 
    - Account Name
    - Asset
    - Business Hours
    - Case Number, Origin, Owner, Reason
    - Closed When Created
    - Contact Email, Fax, Mobile, Name, Phone
    - Created By
    - Date/Time Closed & Opened
    - Description
    - Engineering Req Num
    - Entitlement Name, Process End Time, Process Start Time
    - Escalated
    - Internal Comments
    - Milestone Status & Status Icon
    - Parent Case
    - Potential Liability
    - Priority
    - Product
    - Service Contract
    - SLA Violation
    - Status
    - Stopped & Stopped Since
    - Subject 
    - Type
    - Web Company, Email, Name, Phone
 
</details>

10. Article: Los artículos capturan información acerca de los productos y servicios que se desean hacer disponible en la base de conocimiento. Pueden ser clasificados en categorías para facilitar el proceso de búsqueda y añadir funcionalidades de control de acceso. 

<details><summary>Campos</summary>

    - Archived By & Date                                                   
    - Article Number & Type ID
    - Case Association Account
    - Created By & Date
    - Custom Fields
    - First Published Date
    - Knowledge Article Version
    - Last Modified By, Date, Published Date
    - Primary Language
    - Article Type
    - Is Latest Version
    - Summary
    - Title
    - Validation Status
    - Total Views
    - Owner
 
</details>
    
**Diagrama de relaciones**

<img align="" alt="img" src="https://raw.githubusercontent.com/william97-su/ProContact-TP/main/Diagrama.png" width="" height="auto" />

## EJERCICIO 6

<b>Soluciones de Salesforce</b>

-	¿Qué es Salesforce?

Es una plataforma que permite gestionar la información de los clientes de una compañia (CRM),
Entrega software a medida del cliente(gestiona ventas, procesos de creacion y realizacion de pedidos, servicio de atencion al cliente, gestion de clientes existentes y potenciales, conectar con empleados y optimizar procesos).

-	¿Qué es Sales Cloud?

Sales Cloud es un módulo de Salesforce que permite gestionar de forma eficiente las relaciones con tus clientes y la colaboración entre equipos comerciales. Ofrece automatización y productividad para la fuerza de ventas optimizando los procesos comerciales y alineándolos con el marketing de tu empresa y servicio de atención al cliente.

-	¿Qué es Service Cloud?

Service Cloud es una solución completa de atención al cliente creada especialmente para dar soporte a los clientes a cualquier hora y en cualquier lugar, por teléfono, correo electrónico, redes sociales, chats y páginas o comunidades de auto ayuda.

-	¿Qué es Health Cloud?

Health Cloud es una plataforma especialmente diseñada para la gestión clínica de pacientes , la cual ofrece: una comunicación más personalizado entre pacientes, miembros, proveedores y prestadores de servicios de salud, y un mejor ajuste a los procesos, servicios y datos médicos.

-	¿Qué es Marketing Cloud?

Es un módulo de Salesforce que contiene múltiples herramientas para mejorar la interacción de las marcas con sus clientes y potenciales a través de todo tipo de canales. Está, obviamente, enfocada en el área de negocio de Marketing.

<b>Funcionalidades de Salesforce</b>

- ¿Qué es un RecordType?

Nos permiten definir diferentes Business Process, Pages Layouts y Picklist Values en un determinado objeto. Así mismo, los Record Types nos ayudan a mostrar distintos tipos de información según el perfil del usuario.

- ¿Qué es un ReportType?

Indica el tipo de informe al que pertenece la plantilla seleccionada previamente por el creador de la misma.

- ¿Qué es un Page Layout?

Los diseños de página controlan el diseño y la organización de botones, campos, s-controls, Visualforce, enlaces personalizados y listas relacionadas en páginas de registros de objetos.

- ¿Qué es un Compact Layout?

Un diseño compacto muestra los campos clave de un registro de un vistazo en la aplicación móvil Salesforce, Lightning Experience y en las integraciones de Outlook y Gmail.

- ¿Qué es un Perfil?

Los perfiles definen cómo acceden los usuarios a objetos y datos y qué pueden hacer en la aplicación.

- ¿Qué es un Rol?

Es aquella función que determina los niveles de acceso que tienen los usuarios.

- ¿Qué es un Validation Rule?

Las reglas de validación verifican que los datos que un usuario ingresa en un registro cumplen con los estándares que usted especifica antes de que el usuario pueda guardar el registro.

- ¿Qué diferencia hay entre una relación Master Detail y Lookup?

En lookup, ambos objetos no comparten propiedades entre ellos, lo que significa que están débilmente acoplados.

En Master-detail, ambos objetos comparten propiedades entre sí, lo que significa que están estrechamente acoplados.

- ¿Qué es un Sandbox? 
 
Un Sandbox es una copia de su organización en un entorno aislado que puede usar para distintos fines, como pruebas y capacitación.

- ¿Qué es un ChangeSet?

Un conjunto de cambios entrantes es un conjunto de cambios que se ha enviado desde otra organización de Salesforce a la organización en la que ha iniciado sesión. Un conjunto de cambios se debe implementar para que los cambios surtan efecto.

- ¿Para qué sirve el import Wizard de Salesforce?

Se puede utilizar para importar un máximo de 50,000 registros.

- ¿Para qué sirve la funcionalidad Web to Lead?

Sirve para definir una campaña o fuente de clientes potenciales colocando valores dentro de los campos ocultos.

- ¿Para qué sirve la funcionalidad Web to Case?

Para ver cómo afectan al proceso de ventas., responder a casos satisface a sus clientes y mejora su marca.

- ¿Para qué sirve la funcionalidad Omnichannel?

Omni- canal es una función personalizable y flexible que se puede configurar de forma declarativa en Salesforce, es decir, sin necesidad de escribir código. OmniCanal ayuda al enrutamiento automático de diferentes tipos de elementos de trabajo (como casos y clientes potenciales) a los agentes.

- ¿Para qué sirve la funcionalidad Chatter?

Chatter facilita la conexión con las personas y la información que les es más relevante.

<b>Conceptos generales</b>

- ¿Qué significa SaaS?

El software como servicio (SaaS) es un modelo de entrega de software basado en la nube en el que el proveedor de la nube desarrolla y mantiene el software de las aplicaciones en la nube.

- ¿Salesforce es Saas?

Salesforce es una compañía de PaaS (Plataforma como Servicio), un concepto que nace como resultado de la aplicación al desarrollo de Software del modelo SaaS (Software como Servicio). Este modelo abarca el ciclo completo para desarrollar e implantar aplicaciones desde Internet.

- ¿Qué significa que una solución sea Cloud?

La computación en la nube (cloud computing) es una tecnología que permite acceso remoto a softwares, almacenamiento de archivos y procesamiento de datos por medio de Internet

- ¿Qué significa que una solución sea On-Premise?

on-premise se refiere a que la instalación del programa se ha realizado de manera local, en las instalaciones de la empresa y obligando a esta a crear una infraestructura informática compleja con servidores que requieren mantenimiento.

- ¿Qué es un pipeline de ventas?

El pipeline de ventas es, precisamente, el proceso de actividades y estrategias que necesita un vendedor para acelerar el ciclo de ventas, transformando clientes potenciales (aquellos que acaban de conocer tu marca o servicio) en clientes.

- ¿Qué es un funnel de ventas?

El concepto de embudo de ventas representa todo el proceso de cierre de un negocio, desde el momento de la captación hasta la conversión final.

- ¿Qué significa Customer Experience?

El Customer Experience, también llamada experiencia del cliente o CX, es la experiencia que formará tu consumidor en función de sus interacciones con tu marca, que pueden ser positivas o negativas.

- ¿Qué significa omnicanalidad?

Es una estrategia de comunicación utilizada para estar en contacto con los prospectos o clientes a través de diferentes canales (email, redes sociales, sitio web, etc.).

- ¿Qué significa que un negocio sea B2B?

El término B2B nace de la expresión en inglés “business to business” (empresa a empresa). Es decir, son las ventas de una empresa a otra.

- ¿Qué significa que un negocio sea B2C?

B2C es el acrónimo en inglés de “business to consumer” (empresa a consumidor). Es decir, es un modelo de negocio en el que una empresa le vende de forma directa al consumidor final.

- ¿Qué es un KPI?

Un KPI, conocido también como indicador clave o medidor de desempeño o indicador clave de rendimiento, es una medida del nivel del rendimiento de un proceso. El valor del indicador está directamente relacionado con un objetivo fijado previa y normalmente se expresa en valores porcentuales.

- ¿Qué es una API y en qué se diferencia de una Rest API?

Por lo general, la API sigue el formato de aplicación a aplicación, mientras que REST sigue una estructura diferente: Cliente-Servidor. El cliente y el servidor están evolucionando de forma independiente, proporcionando más flexibilidad en el trabajo.

- ¿Qué es un Proceso Batch?

Los sistemas Batch se basan en la producción por lotes, que no es más que la producción de una cantidad limitada de un tipo de producto cada vez. Cada lote recibe una identificación, como número o código. Además, cada lote exige un plan de producción específico.

- ¿Qué es Kanban?

La metodología Kanban es un sistema de producción tan eficiente como efectivo. Forma parte de las metodologías ágiles y su objetivo es gestionar la realización de las tareas hasta su finalización.

- ¿Qué es un ERP?

Enterprise Resource Planning (ERP) es un tipo de software que las organizaciones utilizan para gestionar las actividades empresariales diarias, como la contabilidad, el aprovisionamiento, la gestión de proyectos, la gestión de riesgos, el cumplimiento y las operaciones de la cadena de suministro.

- ¿Salesforce es un ERP? 

Salesforce Billing complementa las plataformas de planificación de recursos de negocio (ERP) mediante la conversión de los datos de la gestión de procesos desde el prospecto hasta el pedido de Salesforce CPQ en datos de transacciones.

## EJERCICIO 7

- <b>A.	Consultar tu ID haciendo un GET con POSTMAN a este WS: https://procontacto-reclutamiento-default-rtdb.firebaseio.com/contacts.json</b>

<img align="" alt="img" src="https://user-images.githubusercontent.com/75348924/208191384-daffd013-8eaa-4ec9-9797-77977a3b423b.PNG" width="" height="auto" />

- <b>B.	Agregar un campo al objeto Contact llamado idprocontacto de tipo texto de 255 caracteres.</b>

<img align="" alt="img" src="https://user-images.githubusercontent.com/75348924/208192314-9caf4f85-305a-474e-90f6-231fdc37aaa3.PNG" width="" height="auto" />

- <b>C.	Desarrollar un trigger para que cuando un usuario Modifica o Crea un contacto de Salesforce completando el campo generado el punto B con TU id obtenido en el punto A, se invoque al Web Service con el idprocontacto obtenga los datos de email de la respuesta y actualice el campo email del contacto.
- El Codigo de este ejercicio se encuentra en el repositorio. </b>
