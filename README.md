# ProContacto-Evaluacion-Practica
Evaluacion practica realizada para una entrevista realizada por la empresa ProContacto.

## EJERCICIO 2
1-	Que es un servidor Http
Es un servidor el cual tiene como objetivo intercambiar información entre un servidor y un cliente/usuario, mantiene esta estructura cliente-servidor utilizando el protocolo HTTP el cual permite realizar una petición de datos y recursos. Se realiza mediante conexiones que son bidireccionales o unidireccionales. Este protocolo permite

2-	Que son los verbos HTTP
Los verbos HTTP son distintas palabras que son utilizadas para realizar peticiones al servidor, los más utilizados son:
- GET: Recupera información de un recurso
- PUT: Reemplaza la información de un recurso. Utilizado para actualizar información. Puede devolver informacion.
- POST: Crea un recurso. Devuelve el código 201 que significa la correcta creación del nuevo recurso/instancia.
- DELETE: Utilizado para suprimir un recurso identificado.

3- ¿Qué es un request y un response en una comunicación HTTP? ¿Qué son los headers? 
Un request es la peticion que realiza el cliente al servidor,esta es realizada junto con un metedo (como lo puede ser Get) y una URL.Un response es la respuesta que el servidor realiza al tener una peticion, devuelve un codigo de status junto con la informacion requerida en la peticion. En ambos casos se especifica el tipo de lenguaje, que púede ser XML, Jason, etc.
Los Headers contienen informacion de los metadatos

4- ¿Qué es un queryString? (En el contexto de una url)
Forma parte de la URL, contiene los datos que deben pasar a las API. Estas cadenas de consultas permiten acceder a paginas web dinamicas. Al final de la url se pone el caracter "?" y luego se puede incluir uno o mas parametros representados como clave-valor (Clave=Valor). Esta Query lo que realiza es devolver una informacion especifica, la cual se obtiene buscando sobre los valores mensionados luego del caracter.

5- ¿Qué es el responseCode? ¿Qué significado tiene los posibles valores devueltos?
Es un codigo que se devuelve en un response por parte del servidor, el cual indica el estado de la peticien realizada por el navegador web del cliente ( la requiest ). Este indica como se realizo la request, puede tener un valor negativo como positivo (404 0 200 por ejemplo).
Hay distintos tipos de codigo, por lo general los 1xx informan respuestas informativas,
2xx informa que la request realizada se resolvio con exito, una peticion correcta.
3xx se utiliza para redirecciones,
4xx es utilizada para informar errores por parte del CLIENTE 
5xx informa un error por parte del servidor,base de datos.

6- ¿Cómo se envía la data en un Get y cómo en un POST?

7- ¿Qué verbo http utiliza el navegador cuando accedemos a una página?
Este realiza un metodo GET, ya que pide todos los recursos necesarios para obtener los datos/archivos de la pagina. Por ejemplo trae los archivos css,js,html,etc.

8- Explicar brevemente qué son las estructuras de datos JSON y XML dando ejemplo de estructuras posibles.
Ambos son un formato de intercambio de datos, estandares utilizados para intercambiar informacion.
Formato XML : basado en texto y en el uso de etiquetas. permite una adecuada representacion estructurada de la informacion,ya sean datos o documentos.
Las etiquetas empiezan con <> y siempre deben cerrarse con </>. Dentro de cada etiqueta puede estar vacia o tener contenido y distintos elementos. Este estandar tambien permite agregar atributos, añade propiedades a un elemento.
Caracteristicas: es un formato complicado de trabajar por las personas y mantiene un formato estricto.
Ejemplo: 

Formato JSON (JavaScript Object Notation): presenta la informacion mas legible para las personas. Este formato se basa en un subconjunto concreto del lenguaje de programacion JavaScript. Este protocolo utiliza una serie de pares de Nombre y valor en orden. 
Caracteristicas: Es un formato simple y trabaja con una velocidad de procesamiento alta
Ejemplo: 

9- Explicar brevemente el estándar SOAP
Simple Object Access Protocol conocido por su abreviatura SOAP, es un protocolo de red basado en XML que define como diseñar infercaces de programacion de aplicaciones (API). Es ideal para las empresas, ya que esta bien definida por una serie de reglas integradas que aumentan la complejidad y la sobrecarga.
Es independiente del transporte, aunque habitualmente se utiliza con el protocolo http. Se definen tres partes en todo el mensaje:
- Sobre: Define una infrasestructura para describir que hay en un mensaje y como procesarlo
- Reglas de codificacion: Instancia de tipos de datos definidos por la aplicacion. Normas de codificacion que definen un mecanismo de serializacion.
- Estilos de comunicacion: Puede seguir el formato RPC ( llamada de procedimiento remoto ) o estilo de documento.
Caracteristicas: Seguridad,atomicidad,aislamiento,uniformidad,durabilidad.Grantiza operaciones confiables en la base de datos.

10- Explicar brevemente el estándar REST Full

Es un servicio doble via, consulta y respuesta, que dos sistemas computados utilizan para intercambiar informacion de manera segura a traves de internet.
Una consulta debe especificar parametros de consulta para que el servicio sepa lo que se quiere consultar. Por lo general el cuerpo de la respuesta de una API con este estandar es una estructura con el formato JSON. Este estandar trabaja sobre el protocolo HTTP.

11- ¿Qué son los headers en un request? ¿Para qué se utiliza el key Content-type en un header?

Los headers transmiten 


## EJERCICIO 3
1- ![Ejercicio 1](Captura.PNG)

2- ![ejercicio 2](Captura2.PNG)

3- En el punto 1 vimos como al realizar un metodo GET el servidor nos devuelve un recurso en formato JSON el cual contiene una cantidad X de informacion sobre usuarios con sus respectivos mails y nombres, los cuales se pueden identificar por un TOKEN. En cambio, en el punto 2 vimos como al realizar un metodo POST mandamos un recurso al servidor con informacion del cliente, la cual el servidor GUARDA en la base de datos y nos devuelve como respuesta el codigo TOKEN de nuestra informacion.

## EJERCICIO 4 

Cuenta TrailHead: https://trailblazer.me/id/lrodriguez353


## EJERCICIO 5

Conceptualmente se los conoce como objetos estandar, son objetos que estan incluidos en Salesforce, conocidos como objetos de negocio. Estos objetos alamacenan campos estandar, que son campos basicos que estan incluidos en todos los objetos:

  - Identidad: Codigo unico para cada registro que consta de 15 caracteres, se direncian mayusculas y miniculas. Se crea automaticamente.
  - Sistema: Fecha creacion registro o fecha ultima modificacion.
  - Nombre: Nombre del registro.

Los registros mencionados son:

  1.	Lead: 
  2.	Account
  3.	Contact
  4.	Opportunity
  5.	Product
  6.	PriceBook
  7.	Quote
  8.	Asset
  9.	Case
  10.	Article

Diagrama resuelto con la vinculacion pedida: 

![ejercicio 5](ejercicio_diagrama.png)


## EJERCICIO 6 

### Soluciones Salesforce

a) ¿Qué es salesforce?

Es una compañia en la nube con sistema de CRM, que alamacena sus datos de clientes, le da procesos para cuidar a clientes potenciales y proporciona maneras para colaborar con personas que trabajan con empresas. Da la posibilidad de personalizar funciones para potenciar la aplicacion de manera unica para cada empresa,clientes,empleados y socios, esto se logra con salesforce platform.

Existen algunos términos aquí cuya comprensión es de capital importancia: confianza, capacidad multiusuario, metadatos y la API.

Algunas ejemplos de las tareas que puede realizar salesForce: Gestiona  y mejora la eficiencia de ventas, simplifica procesos de creacion y realizacion de pedidos, conecta a sus empleados.

b) ¿Qué es sales cloud?

Es un modulo de SalesForce que permite gestionar de forma eficiente las relaciones con tus clientes y colaboracion entre equipos comerciales. Automatiza y ofrece productividad para la fuerza de ventas optimizando los procesos comerciales y alineandolos con el marketing de la empresa o servicio de atencion al cliente.

c) ¿Que es Service Cloud?

Es un componente de la plataforma Salesforce customer 360, que ofrece un servicio de asistencia para proporcionar a la empresa y agentes los sistemas adecuados para resolver casos de manera rapida y sencilla, para así lograr una atención mas inteligente,rápida y personalizada.

d) ¿Qué es Health Cloud?

Es una plataforma para gestionar la interaccion medico-paciente y el mantenimiento de registros. Mantiene una comunicación personalizada entre el paciente y las entidades de salud vinculadas en una nube de salud que reúne una amplia gama de datos de varias fuentes en un solo lugar.

e) ¿Qué es Marketing Cloud?

Es un modulo dirigido al area de equipos de marketing, utilizado para mejorar la experiencia de sus clientes y aumentar las ventas. Contiene multiples herramientas diseñadas para gestionar de manera eficienta la interacción de la marca con sus clientes a través de diferentes canales.

### Funcionalidades de SalesForce

a) ¿Qué es un RecordType?

Permite controlar como se muestra la informacion de ciertos objetos y como son mostrados a los usuarios. Define diferentes Business Process, pages layouts y picklist values en un determinado objeto. Es utilizado cuando un objeto de salesforce es usado para multiples propósitos y debe mostrar diferente información en su respectivo Page layout.

b) ¿Qué es un ReportType?

Es una plantilla que facilita la generacion de reportes. Determina que campos y registros están disponibles para el uso al crear un reporte. Basa la relación entre un objeto principal y los objetos relacionados.

c) ¿Qué es un Page layout?

Se ocupa de controlar el diseño y la organizacion de botones,campos,controles de visualforce,enlaces personalizados y listas relacionadas en paginas de registros de objetos. Determina que campos son visibles, de solo lectura y obligatorios. Son utilizados para personalizar el contenido de las paginas de registro para sus usuarios.

d) ¿Qué es un compact layout?

Muestra los campos clave de un registro en la app movil de salesforce, lightning experience y en las integraciones de outlook y gmail.

e) ¿Qué es un perfil?

Un perfil define como acceden los usuarios a objetos y datos, asi como tambien lo que pueden realizar en la aplicacion. Cuando se crean usuarios se asigna un perfil a cada uno.

f) ¿Qué es un Rol?

Un rol es capaz de controlar el nivel de visibilidad que un usuario tiene sobre los datos de su organizacion.

g) ¿Qué es un Validation Rule?

Verifican datos que un usuario introduce en un registro, si estos cumplen con las normas que especifica antes de que el usuario guarde el registro.
Contiene una formula o expresión que evalúa los datos en uno o mas campos y ofrece un valor booleano.

h) ¿Qué diferencia hay entre una relación Master Detail y Lookup?

  -> Relacion Lookup: Permite hasta 25 por objeto y no tiene impacto en la eliminación.No es obligatorio el campo de relacion con el padre. El campo de busqueda no es obligatorio. No se puede crear un campo de resumen acumulativo.
  
  -> Relacion Master Detail: Relacion obligatoria padre-hijo. Si se elimina la clase padre entonces la clase hijo es eliminada tambien. El campo de busqueda es obligatorio en el diseño de la pagina. Se puede crear un campo de resumen acumulativo.

i) ¿Qué es un sandbox?

Es una copia de la organizacion, aislada. Una instancia completamente independiente con el proposito de ser utilizado para pruebas. Cualquier cambio realizado en ellas no afecta a la organizacion real en la cual se esta trabajando.

j) ¿Qué es un ChangeSet?

Son un conjunto de cambios utilizados para enviar personalizaciones de una organizacion de salesforce a otra.

k) ¿Para qué sirve el import Wizard de Salesforce?

Es una herramienta que permite importar datos de muchos de los objetos estandares de salesforce, como prospectos,cuentas o contactos, así como objetos personalizados.

l) ¿Para qué sirve la funcionalidad Web to Lead?

Es utilizada para generar información de clientes potenciales de los visitantes del sitio web.

m) ¿Para qué sirve la funcionalidad Web to Case?

Es utilizada para recopilar las solicitudes de servicio de atención al cliente directamente del sitio web de la compañia. Esta herramienta es capaz de generar automáticamente casos nuevos con Web to case.

n) ¿Para qué sirve la funcionalidad Omnichannel?

Es una función de salesforce que ofrece canales de servicio y aumenta la eficiencia de de un centro de contacto. Mantiene el seguimiento de la información y solicitud de asistencia entrantes de distintos canales en la empresa. Facilita a los agentes a seguir con sus practicas de negocio y ayudar a los clientes independientemente de como hacen el contacto.

o) ¿Para qué sirve la funcionalidad Chatter?

Es una red social interna de salesforce que permite comunicar diferentes compañeros de trabajo para estar mas coordinados y evitar usar mail. Permite seguir objetos de negocio.

### Conceptos generales


## EJERCICIO 7 


