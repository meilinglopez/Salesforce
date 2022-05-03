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

![alt text](https://github.com/[meilinglopez]/[reponame]/blob/[branch]/modelo entidad relacion.png?raw=true)

# Algunos conceptos de Salesforce
## __
## __
