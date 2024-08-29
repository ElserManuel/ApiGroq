# Documentación del API de Inteligencia Artificial de GorqCloud
## Introducción
Esta documentación describe cómo utilizar y probar el API de Inteligencia Artificial de GorqCloud mediante Postman. GorqCloud es una potente plataforma de inteligencia artificial que ofrece una amplia gama de servicios, incluyendo procesamiento de lenguaje natural, análisis de datos y aprendizaje automático. Este API proporciona una interfaz para interactuar con los algoritmos de IA de GorqCloud, facilitando la integración de funcionalidades avanzadas en tus aplicaciones.

El propósito de este documento es guiarte a través del proceso de configuración y uso del API en Postman, una herramienta popular para realizar pruebas de API. Aquí aprenderás a realizar solicitudes HTTP, gestionar los endpoints disponibles y entender las respuestas que devuelve la API.

## Configuración Previa
Antes de comenzar a realizar pruebas con el API de GorqCloud, asegúrate de cumplir con los siguientes requisitos:
### Requisitos
- Postman: Instala Postman desde [aqui](https://www.postman.com/downloads/).
- Clave de API de GorqCloud: Obtén tu clave de API desde la consola de GorqCloud. [Aqui](https://console.groq.com/keys)
## Inicio 
 * Para empezar, primero debes ingresar a la página de GorqCloud y crear una cuenta. Puedes hacerlo desde [Aqui](https://console.groq.com/login)
   
![image](https://github.com/user-attachments/assets/3ac24ece-1734-46c8-b0ec-a545ff356714)
Una vez que hayas creado tu cuenta, dirígete a la sección de Documentación de GorqCloud, donde podrás encontrar toda la información referente al uso del API que nos interesa.

![image](https://github.com/user-attachments/assets/e8f80be5-7b2c-465a-b31b-912452330d17)
GorqCloud ofrece diferentes opciones, como Chat, Audio y Models. En este caso, nos enfocaremos en la funcionalidad de Chat.

![image](https://github.com/user-attachments/assets/395b9ae9-8c5b-4b16-a746-e25072fde58a)

Para poder usar el API, necesitarás una clave de uso personal. Esta se puede generar en la parte inferior de la documentación, donde GorqCloud te ofrece la opción de crear una nueva clave.

![image](https://github.com/user-attachments/assets/dc4879d6-6ca2-42e5-8aa8-31efc9fc60b7)

Al crear una clave, podrás darle un nombre para identificarla fácilmente.

![image](https://github.com/user-attachments/assets/e8c6dc0d-ffae-4cc9-8ce4-d6de1cfdd779)

Una vez creada, se te proporcionará una clave única. Guarda esta clave ya que la necesitarás para configurarla en Postman.

![image](https://github.com/user-attachments/assets/881edf51-29ab-4895-839c-ec01d0ca432d)

## Prueba con Postman
En este apartado, aprenderás cómo configurar Postman para interactuar con el API de GorqCloud usando la clave que generaste. Asegúrate de haber seguido todos los pasos anteriores antes de proceder.

### Crear Colección en Postman

* Crear una Colección: Primero, necesitas crear una colección en Postman para organizar las pruebas de la API. Una colección es un contenedor que te permite agrupar múltiples solicitudes relacionadas. Para ello, abre Postman y haz clic en "New Collection". Nombra la colección como "GorqCloud API".
![image](https://github.com/user-attachments/assets/9793a456-a05b-495a-ada4-b663fcee99c6)

* Crear una Solicitud POST: Dentro de la colección que acabas de crear, añade una nueva solicitud de tipo POST. Esta será utilizada para interactuar con el servicio de chat del API de GorqCloud. En el campo URL, ingresa el endpoint proporcionado para el servicio de chat.

![image](https://github.com/user-attachments/assets/9793a456-a05b-495a-ada4-b663fcee99c6)

### Configurar Encabezados (Headers)
Añadir Encabezados: Es importante configurar los encabezados de la solicitud para autenticarte correctamente y enviar los datos en el formato adecuado. Dirígete a la pestaña Headers en tu solicitud de Postman.
Completar Datos de los Headers: Añade los siguientes encabezados:
 - Authorization: Aquí debes ingresar tu clave de API personal de GorqCloud en el formato Bearer <tu_clave_api>.
 Content-Type: Especifica application/json para indicar que los datos que se enviarán están en formato JSON.

![image](https://github.com/user-attachments/assets/eb6ff385-a633-4e76-b6e7-fa104bb8473d)

### Configurar el Cuerpo (Body)
* Configurar el Cuerpo de la Solicitud: Ahora, ve a la pestaña Body y selecciona la opción raw. Asegúrate de que el formato esté configurado en JSON. Aquí es donde vas a introducir los datos necesarios para la interacción con el servicio de chat.
* Ejecutar la Solicitud: Una vez que hayas completado los campos de Headers y Body, haz clic en Send para ejecutar la solicitud. Postman se encargará de enviar la solicitud al API de GorqCloud y te devolverá una respuesta que podrás revisar en la parte inferior de la pantalla.

![image](https://github.com/user-attachments/assets/97687af0-3216-44ad-aef8-b000624b23fa)

## Resultado en Postman

- Una vez que ejecutaste la solicitud en Postman, recibiste una respuesta con un código de estado 200 OK. Esto indica que la solicitud fue exitosa y que el servidor procesó la petición correctamente.
- ![image](https://github.com/user-attachments/assets/1e1430b8-01cf-4790-b68e-a35f4ccd30f3)

Esta informacion Breve, espero que sea de su agrado ... y profe no se olvide de mi 20 🦫
