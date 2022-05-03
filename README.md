# Algunos conceptos de Lenguaje de Programación 

## _¿Qué es un servidor HTTP?_

   Un servidor web es un software y un hardware que utiliza el protocolo HTTP (Hypertext Transfer Protocol) y otros protocolos para responder a las peticiones de los clientes realizadas a través de la World Wide Web. Almacena y entrega el contenido de un sitio web, como texto, imágenes, videos y datos de aplicaciones a las personas que lo solicitan. 

   El hardware del servidor web está conectado a Internet y permite intercambiar datos con otros dispositivos conectados, mientras que el software del servidor web controla cómo un usuario accede a los archivos alojados.

## _¿Qué son los verbos HTTP?_

Los verbos Http involucrados en un sistema REST son:

- GET
- POST
- PUT
- PATCH 
- DELETE

## _¿Qué es un request y un response en una comunicación HTTP?_

HTTP se basa en un modelo solicitud / respuesta, de modo que hay dos tipos de mensajes HTTP: la solicitud (request) y la respuesta (response). El navegador abre una conexión a un servidor y realiza una solicitud. El servidor procesa la solicitud del cliente y devuelve una respuesta.

## _¿Qué son los headers?_

Header o encabezado es un término que en lenguaje de programación designa la parte superior de un sitio web. En otras palabras, el heather es lo primero que ves cuando visitas una página.

## _¿Qué es un queryString?_

   Las Query String o cadenas de consultas es un término que se utiliza para hacer referencia a una interacción con una base de datos. Además, es la parte de una URL que contiene los datos que deben pasar a las aplicaciones web.

   En resumen, las Query String permiten acceder a páginas web dinámicas con distintas variables consiguiendo así que las páginas web no estén compuestas de decenas de directorios y permitiendo que su estructura esté basada en URLs amigables para el posicionamiento web SEO.


## _¿Qué es el responseCode? ¿Qué significado tiene los posibles valores devueltos?_

   El elemento ResponseCode proporciona información de estado sobre la solicitud.

   Los posibles valores devueltos: 

- Respuestas informativas (100–199)
- Respuestas satisfactorias (200–299)
- Redirecciones (300–399)
- Errores de los clientes (400–499)
- Errores de los servidores (500–599)

## _¿Cómo se envía la data en un Get y cómo en un POST?_

GET lleva los datos de forma "visible" al cliente (navegador web). El medio de envío es la URL. Los datos los puede ver cualquiera.
- El método GET envía la información en la propia URL, estando limitada a 2000 caracteres.
- La información es visible por lo que con este método nunca se envía información sensible.
- No se pueden enviar datos binarios (archivos, imágenes...).

POST consiste en datos "ocultos" (porque el cliente no los ve) enviados por un formulario cuyo método de envío es post. Es adecuado para formularios. Los datos no son visibles.
- El método POST no tiene límite de cantidad de información a enviar.
- La información proporcionada no es visible, por lo que se puede enviar información sensible.
- Se puede usar para enviar texto normal así como datos binarios (archivos, imágenes...).

## _¿Qué verbo http utiliza el navegador cuando accedemos a una página?_
El método/verbo GET para regresar la página que solicite el cliente o en definitiva un error.

## _Explicar brevemente qué son las estructuras de datos JSON y XML dando ejemplo de estructuras posibles_

   JSON, JavaScript Object Notation, Notación de Objetos de JavaScript es un formato ligero de intercambio de datos. Leerlo y escribirlo es simple para humanos, mientras que para las máquinas es simple interpretarlo y generarlo. JSON es un formato de texto que es completamente independiente del lenguaje pero utiliza convenciones que son ampliamente conocidos por los programadores de la familia de lenguajes C, incluyendo C, C++, C#, Java, JavaScript, Perl, Python, y muchos otros. Estas propiedades hacen que JSON sea un lenguaje ideal para el intercambio de datos.

JSON está constituído por dos estructuras:

- Una colección de pares de nombre/valor. En varios lenguajes esto es conocido como un objeto, registro, estructura, diccionario, tabla hash, lista de claves o un arreglo asociativo.
- Una lista ordenada de valores. En la mayoría de los lenguajes, esto se implementa como arreglos, vectores, listas o sequencias.

## _Explicar brevemente el estándar SOAP_
    
   SOAP es el protocolo de comunicación para los servicios web. Define el formato de los mensajes de solicitud, respuesta y fallo de un servicio web. 
    
   Un mensaje SOAP contiene las siguiente secciones
  
   **Envoltorio SOAP!**
        El envoltorio define el marco de trabajo del mensaje, el contenido del mensaje y aquello que debe manejar el mensaje.
        
   **Encabezado SOAP**
        El encabezado identifica la entidad que envía el mensaje SOAP. Incluye información de autenticación. También incluye información sobre cómo procesar el mensaje SOAP.
        
   **Cuerpo SOAP**
        El cuerpo es el contenedor de los datos que el cliente y el proveedor del servicio web intercambian entre sí.
        Los mensajes SOAP son XML. Cuando un mensaje SOAP contiene elementos de ocurrencia múltiple, los grupos de elementos constituyen niveles en la jerarquía XML. Los grupos están relacionados cuando un nivel está anidado dentro de otro.
        Un mensaje SOAP puede contener datos jerárquicos. Por ejemplo, el cliente envía una solicitud para añadir pedidos de clientes a una base de datos de ventas. El cliente pasa dos grupos de datos en un mensaje de solicitud SOAP. Un grupo contiene un ID y nombre de cliente y el otro grupo contiene información de los pedidos. La información de los pedidos puede ocurrir varias veces.
        Un mensaje de respuesta SOAP puede contener datos jerárquicos. Por ejemplo, un cliente de servicio web genera una solicitud SOAP para pedidos de clientes. El servicio web devuelve un encabezado de pedido y elementos de detalle de pedido de ocurrencia múltiple en la respuesta SOAP.


## _Explicar brevemente el estándar REST Full_
Los dos conceptos clave son necesarios ya que un servicio Web RESTful es aquél servicio web que está basado en la arquitectura REST. Los servicios Web RESTful se basan en recursos. Un recurso es una entidad, la cual se almacena principalmente en un servidor y el cliente solicita el recurso utilizando servicios Web RESTful.

Características principales de un servicio Web RESTful
- Tiene cinco operaciones típicas: listar, crear, leer, actualizar y borrar
- Cada operación requiere de dos cosas: El método URI y HTTP
- El URI es un sustantivo que contiene el nombre del recurso
- El método HTTP es un verbo

## _¿Qué son los headers en un request? ¿Para qué se utiliza el key Content-type en un header?_
Cuando visitas cualquier sitio web, tu navegador envía una solicitud al servidor web para obtener datos o información del mismo, por ejemplo, un archivo HTML (es decir, una página web). Tanto en la solicitud, la HTTP-Request, como en la respuesta del servidor, se intercambian, además de datos reales, "información meta". Esta información se resume en la cabecera HTTP

¿Para qué se utiliza el key Content-type en un header?
```sh
Content-Type: text/tml; charset=utf-8
```

Campo de cabecera: Content-Type	
Significado: Tipo MIME del archivo solicitado
```sh
Content-Type: text/tml; charset=utf-8
```


# SALESFORCE

# Trailhead realizado

Se realizó el trailhead:

```sh
https://trailhead.salesforce.com/es-MX/users/norozco3/trailmixes/introduccion
```

Con el usuario:

```sh
https://trailblazer.me/id/mlopez409
```

# Algunos conceptos de Salesforce
## _Lead_
El lead es un potencial cliente que demostró interés en un producto o servicio ofrecido por la marca a través de la interacción con contenidos y otros materiales. Además de ser una oportunidad de negocio, el lead es un recurso valioso en cualquier estratégia de marketing, pudiendo tornarse tanto un cliente como un abogado de la marca.
los prospectos son clientes potenciales que expresaron interés en su producto pero que no han cualificado aún para comprar. En Salesforce, su objetivo con prospectos es impulsar la conversión, el momento en que un prospecto califique para comprar. La conversión de un prospecto crea un contacto, junto con una cuenta y una oportunidad. Pero primero debe cualificar ese prospecto.

## _Account_
Una cuenta es una entidad comercial, es una empresa. Necesitamos información sobre nuestro negocio y nuestros datos, y eso comienza con las personas con las que hacemos negocios. Podemos almacenar información sobre nuestros clientes utilizando cuentas y contactos. Las cuentas son empresas con las que hacemos negocios.

## _Contact_
Es una persona física cuyos datos de contacto se encuentren en su base de datos y hayan sido cualificados. Por lo general, serán parte de una empresa u organización a la que intentas vender, pero también podrían ser un socio de referencia o incluso alguien que conoces personalmente.

## _Opportunity_
Las oportunidades son acuerdos en curso. En Salesforce, puede crear oportunidades para cuentas existentes o convertir un prospecto calificado.

Las oportunidades son ventas pasadas o pendientes de una cuenta que desea trabajar y/o rastrear. Las oportunidades juegan un papel importante en una organización porque representan ventas y ventas potenciales. Usando Oportunidades podemos pronosticar las ventas en una organización, realizar un seguimiento de sus negocios, comprender mejor a quién le está vendiendo y enfocar los esfuerzos de su equipo.

## _Product_
Los productos en Salesforce son un servicio o artículo que la empresa vende a los clientes. Después de definir los productos, puedes asociarlos a los precios que hayas establecido en el libro de precios.

## _PriceBook_
Un libro de precios es una lista de productos y sus precios asociados. Cada producto y su precio se denomina entrada del libro de precios. El libro de precios proporcionará una lista de los productos y los diferentes precios de los productos. Salesforce proporcionará libros de precios estándar y personalizados, lo que facilita tener múltiples precios para un producto.

En otras palabras, podemos decir que a veces los precios de los productos difieren según el cliente; puede depender de quién compra, cuándo compra o en qué cantidad. Para dar cabida a esta flexibilidad, un Producto puede existir en Salesforce con muchos precios asociados diferentes, utilizando una función llamada Libros de precios y Entradas de libros de precios.

## _Quote_

Las cotizaciones en Salesforce representan los precios propuestos de los productos y servicios de su empresa. Usted crea una cotización a partir de una oportunidad y sus productos. Cada oportunidad puede tener varias cotizaciones asociadas y cualquiera de ellas se puede sincronizar con la oportunidad. Cuando se sincronizan un presupuesto y una oportunidad, cualquier cambio en los elementos de línea del presupuesto se sincroniza con los productos de la oportunidad y viceversa.

## _Asset_

Representa un artículo de valor comercial, como un producto vendido por su empresa o un competidor, que ha comprado un cliente.
Un activo en Salesforce representa un producto específico comprado o instalado. Por ejemplo, si vende robots, puede crear un producto Robot en Salesforce y luego crear múltiples activos que representen los robots que ha vendido. El robot de cada cliente se rastrearía en su propio registro de activos que está vinculado al producto Robot.

## _Case_
Un caso es una pregunta, comentario o problema de un cliente. Los agentes de soporte pueden revisar los casos para ver cómo pueden brindar un mejor servicio. Los representantes de ventas pueden usar casos para ver cómo afectan el proceso de ventas. Responder a los casos mantiene contentos a sus clientes y mejora su marca.

## _Article_
Los artículos capturan información sobre los productos y servicios de su empresa que desea que estén disponibles en su base de conocimiento. Los artículos de la base de conocimientos se pueden clasificar mediante una o más categorías de datos para facilitar a los usuarios la búsqueda de los artículos que necesitan. Los administradores pueden usar categorías de datos para controlar el acceso a los artículos.

Los artículos se basan en tipos de artículos, que se basan en:
- Diseños tipo artículo para organizar el contenido en secciones.
- Plantillas de tipo artículo para renderizar artículos.

## _Relaciones entre los ojetos de salesforce mencionados antes_

![alt text](https://github.com/meilinglopez/Salesforce/blob/main/modelo%20entidad%20relacion.png)

# Soluciones de Salesforce
## _¿Qué es Salesforce?_
Salesforce es una solución de gestión de relaciones con clientes que une empresas y clientes. Es una plataforma de gestión de relaciones con los clientes CRM integrada que brinda a todos tus departamentos, incluidos marketing, ventas, comercio y servicios, una vista única y compartida de cada cliente.

## _¿Qué es Sales Cloud?_
Sales Cloud es un módulo de Salesforce que permite gestionar de forma eficiente las relaciones con tus clientes y la colaboración entre equipos comerciales. Ofrece automatización y productividad para la fuerza de ventas optimizando los procesos comerciales y alineándolos con el marketing de tu empresa y servicio de atención al cliente.

## _¿Qué es Service Cloud?_
Service Cloud es una solución completa de atención al cliente creada especialmente para dar soporte a los clientes a cualquier hora y en cualquier lugar, por teléfono, correo electrónico, redes sociales, chats y páginas o comunidades de auto ayuda.

Con esta solución de Salesforce es posible que la atención al cliente sea más inteligente, rápida y personalizada. La herramienta también monitoriza métricas de atendimiento y rastrea los indicadores clave de desempeño.

## _¿Qué es Health Cloud?_
Health Cloud es una plataforma especialmente diseñada para la gestión clínica de pacientes por medio de tecnologías on-cloud, la cual ofrece: una comunicación más personalizado entre pacientes, miembros, proveedores y prestadores de servicios de salud, y un mejor ajuste a los procesos, servicios y datos médicos según el perfil de cuidado de cada paciente.

## _¿Qué es Marketing Cloud?_
Marketing Cloud es una plataforma de marketing digital de Salesforce que incluye herramientas para el marketing por correo electrónico, el marketing a través de redes sociales, el marketing para dispositivos móviles, la publicidad online y la automatización del marketing.

# Funcionalidades de Salesforce
## _¿Qué es un RecordType?_

Los Record Types en Salesforce nos permiten definir diferentes Business Process, Pages Layouts y Picklist Values en un determinado objeto. Así mismo, los Record Types nos ayudan a mostrar distintos tipos de información según el perfil del usuario.

## _¿Qué es un ReportType?_

los informes se crean seleccionando primero un tipo de informe. Un tipo de informe es una plantilla que define los objetos y campos que estarán disponibles para usar en el informe que cree . De fábrica, Salesforce proporciona muchos tipos de informes estándar útiles. Hay dos tipos de tipos de informes: tipos de informes estándar y tipos de informes personalizados.

## _¿Qué es un Page Layout?_

se utilizan para controlar el diseño de las páginas de Salesforce. Puede controlar las ubicaciones de botones, campos, enlaces personalizados, Visualforce, s-controls y listas relacionadas en cualquier página de registro de objetos.

Los diseños de página también se utilizan para determinar qué campos se marcan como visibles, de solo lectura o obligatorios en las páginas de registros de objetos. Determinan qué datos se mostrarán a qué usuarios. Casi todos los elementos de una página de objetos de Salesforce se pueden personalizar mediante las funciones de diseño de página estándar o mediante el código personalizado de Visualforce.

## _¿Qué es un Compact Layout?_
Muestra los campos clave de un registro de un vistazo en la aplicación móvil Salesforce, Lightning Experience y en las integraciones de Outlook y Gmail.

## _¿Qué es un Perfil?_
Definen cómo acceden los usuarios a objetos y datos y qué pueden hacer en la aplicación. Cuando cree usuarios, asigne un perfil a cada uno.

## _¿Qué es un Rol?_
Controlan el nivel de visibilidad que un usuario tiene sobre los datos de su organización. Usuarios en cualquier función dada pueden ver, editar, e informar sobre todos los datos para funciones por debajo de ellos en la jerarquía de roles.

## _¿Qué es un Validation Rule?_
Verifican que los datos que un usuario ingresa en un registro cumplen con los estándares que usted especifica antes de que el usuario pueda guardar el registro . Una regla de validación puede contener una fórmula o expresión que evalúa los datos en uno o más campos y devuelve un valor de "Verdadero" o "Falso".
 
## _¿Qué diferencia hay entre una relación Master Detail y Lookup?_

Relación Master Detail:
- Es un registro estrechamente acoplado que tiene una dependencia directa entre los dos objetos. 
- También se puede describir como una relación padre-hijo.
- El registro de detalle no se puede crear sin un maestro.
- Las reglas de colaboración se heredan del maestro al registro de detalles.
- No podemos actualizar la relación con el maestro en una relación maestro-detalle.
- El número de relaciones maestro-detalle que se pueden usar está limitado a 2.
- Las relaciones maestro-detalle se incluyen automáticamente en los tipos de registros de informes.
- Tampoco podemos establecer los permisos del objeto de perfil para el registro de detalles.
- Si se elimina un registro maestro, el registro de su detalle también se elimina junto con él, es decir, implementa la eliminación en cascada.
- El resumen acumulado se puede crear en un detalle maestro.

Lookup
- Este tipo de relación se puede usar cuando solo necesitamos tener la relación entre dos objetos pero no una dependencia directa entre sí.
- Esta es una relación débilmente acoplada.
- Estos se utilizan para hacer referencia a datos compartidos comúnmente, como datos de referencia.
- El número máximo de relaciones de búsqueda en un campo puede ser 40.
- Se utilizan para vincular dos objetos cuando no queremos tener el comportamiento del maestro-detalle, como reglas de uso compartido, permisos de perfil y eliminación en cascada.
- Las búsquedas se utilizan cuando necesitamos relacionar varios "principales" con el registro de detalles.
- La eliminación del padre solo elimina el campo relacionado en el hijo, pero no todo el registro.
- Este tipo de relación también es como una relación de uno a muchos.

## _¿Qué es un Sandbox?_
Un sandbox es simplemente una copia de su base de datos que puede usar para probar nuevas ideas . A menudo, cuando trabaja con un consultor en una nueva funcionalidad para su base de datos, la crearán y la demostrarán en un espacio aislado antes de que se convierta en parte de su base de datos real.

## _¿Qué es un ChangeSet?_
Utilice ChangeSet para enviar personalizaciones de una organización de Salesforce a otra. Por ejemplo, puede crear y probar un nuevo objeto en una organización sandbox y luego enviarlo a su organización de producción mediante un ChangeSet. Los ChangeSet solo pueden contener modificaciones que puede realizar a través del menú Configuración. Por ejemplo, no puede usar un ChangeSet para cargar una lista de registros de contactos. LosChangeSet contienen información sobre la organización. No contienen datos, como registros.

## _¿Para qué sirve el import Wizard de Salesforce?_
Facilita la importación de datos para muchos objetos estándar de Salesforce, incluidas cuentas, contactos, clientes potenciales, soluciones, miembros de campaña y cuentas personales . También puede importar datos para objetos personalizados. Puede importar hasta 50.000 registros a la vez.

## _¿Para qué sirve la funcionalidad Web to Lead??_
Web to lead es una función estándar de Salesforce que permite al usuario generar registros de leads, permite recopilar hasta 500 clientes potenciales por día con los datos de prospección de los visitantes del sitio web de su empresa. También puede redirigir a los clientes potenciales a otras páginas web que son fundamentales para el éxito de la campaña.

## _¿Para qué sirve la funcionalidad Web to Case?_
Salesforce Web-to-Case permite a las organizaciones generar un formulario web que pueden agregar en el sitio web de su empresa mediante el cual sus clientes de Soporte y servicio pueden crear fácilmente un caso dentro de Salesforce.com.

## _¿Para qué sirve la funcionalidad Omnichannel?_
Es una característica flexible y personalizable, y puede configurarla de forma declarativa, es decir, sin escribir código. Utilice Omni-Channel para administrar la prioridad de los elementos de trabajo, lo que facilita enrutar elementos de trabajo importantes a los agentes rápidamente. Administre la capacidad de sus agentes para asumir elementos de trabajo para que solo se les asigne la cantidad de tareas que pueden manejar. También puede definir qué agentes pueden trabajar en diferentes tipos de asignaciones. Por ejemplo, puede crear un grupo de agentes para responder a clientes potenciales y consultas de ventas, y otro grupo que ayude a los clientes con preguntas de soporte.

## _¿Para qué sirve la funcionalidad Chatter?_
Es una herramienta de comunicación dentro de Salesforce.com diseñada especialmente para la interacción y retroalimentación instantánea, el intercambio de archivos y la utilización de encuestas entre los miembros de tu departamento comercial


# Conceptos generales
## _¿Qué significa SaaS?_
Software como un Servicio o SaaS es un modelo de distribución de software donde el soporte lógico y los respectivos datos que maneja se alojan en los servidores de un proveedor, cuyo acceso es a través de Internet. El proveedor no solo proporciona el hardware, sino también el software correspondiente.

## _¿Salesforce es Saas?_
Si, es un modelo de licencia y distribución que ofrece software a través de Internet. Las aplicaciones de software como servicio suelen estar alojadas y gestionadas por un proveedor externo mediante suscripción.

## _¿Qué significa que una solución sea Cloud?_##
Es una tecnología que permite el acceso remoto a softwares, procesamiento de datos y almacenamiento de archivos a través de Internet. No demanda la instalación de aplicaciones a nivel local, sino que ofrece los servicios a gran escala gracias a la conectividad.
 
## _¿Qué significa que una solución sea On-Premise?_

A diferencia del software basado en la nube, el software on-premise está instalado en los servidores y dispositivos locales de la empresa. Esto permite tener acceso físico a la información y control directo de la configuración, manejo y seguridad de esos datos.

## _¿Qué es un pipeline de ventas?_
Es el proceso de actividades y estrategias que necesita un vendedor para acelerar el ciclo de ventas, transformando clientes potenciales (aquellos que acaban de conocer tu marca o servicio) en clientes. También conocido como embudo de ventas, es una herramienta de gestión que se usa para observar las etapas de ventas con ciclos medios o largos.

## _¿Qué es un funnel de ventas?_
Es un sistema diseñado para atraer a desconocidos, convertirlos en leads y transformarlos en clientes. Así de fácil, así de simple. En pocas palabras, el objetivo del funnel es: Conseguir clientes potenciales.

## _¿Qué significa Customer Experience?_
El Customer Experience o Experiencia de Cliente es “el recuerdo que se genera en la mente del consumidor como consecuencia de su relación con la marca”.

## _¿Qué significa omnicanalidad?_
Es una estrategia de comunicación utilizada para estar en contacto con los prospectos o clientes a través de diferentes canales (email, redes sociales, sitio web, etc.). El uso de los diferentes canales debe hacerse bajo una misma estrategia para llegar al consumidor en el momento indicado.

## _¿Qué significa que un negocio sea B2B?¿Qué significa que un negocio sea B2C?_
El término B2B nace de la expresión en inglés “business to business” (empresa a empresa). Es decir, son las ventas de una empresa a otra.
B2C es el acrónimo en inglés de “business to consumer” (empresa a consumidor). Es decir, es un modelo de negocio en el que una empresa le vende de forma directa al consumidor final.

## _¿Qué es un KPI?_
Conocido también como indicador clave o medidor de desempeño o indicador clave de rendimiento, es una medida del nivel del rendimiento de un proceso. El valor del indicador está directamente relacionado con un objetivo fijado previamente y normalmente se expresa en valores porcentuales.

## _¿Qué es una API y en qué se diferencia de una Rest API?_
Una API o interfaz de programación de aplicaciones es un conjunto de definiciones y protocolos que se usa para diseñar e integrar el software de las aplicaciones. Una API de REST, o API de RESTful, es una interfaz de programación de aplicaciones (API o API web) que se ajusta a los límites de la arquitectura REST y permite la interacción con los servicios web de RESTful. El informático Roy Fielding es el creador de la transferencia de estado representacional (REST).

## _¿Qué es un Proceso Batch?_
Se conoce como sistema por lotes, o modo batch, a la ejecución de un programa sin el control o supervisión directa del usuario que se denomina. Este tipo de programas se caracterizan porque su ejecución no precisa ningún tipo de interacción con el usuario.

## _¿Qué es Kanban?_
Es un sistema de información que controla de modo armónico la fabricación de los productos necesarios en la cantidad y tiempo necesarios en cada uno de los procesos que tienen lugar tanto en el interior de la fábrica, como entre distintas empresas.

## _¿Qué es un ERP?_
La planificación de recursos empresariales, también conocida como ERP, es un sistema que ayuda a automatizar y administrar los procesos empresariales de distintas áreas: finanzas, fabricación, venta al por menor, cadena de suministro, recursos humanos y operaciones.

## _¿Salesforce es un ERP?_
si

