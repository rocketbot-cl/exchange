



# Exchange

Conecta con servidores Microsoft Exchange para enviar, leer y gestionar correos y carpetas mediante servicios web.

*Read this in other languages: [English](Manual_exchange.md), [Português](Manual_exchange.pr.md), [Español](Manual_exchange.es.md)*

![banner](imgs/Banner_exchange.png)
## Como instalar este módulo

Para instalar el módulo en Rocketbot Studio, se puede hacer de dos formas:
1. Manual: __Descargar__ el archivo .zip y descomprimirlo en la carpeta modules. El nombre de la carpeta debe ser el mismo al del módulo y dentro debe tener los siguientes archivos y carpetas: \__init__.py, package.json, docs, example y libs. Si tiene abierta la aplicación, refresca el navegador para poder utilizar el nuevo modulo.
2. Automática: Al ingresar a Rocketbot Studio sobre el margen derecho encontrara la sección de **Addons**, seleccionar **Install Mods**, buscar el modulo deseado y presionar install.


## Descripción de los comandos

### Configurar Correo

Ingrese las credenciales para poder enviar y listar correos 
|Parámetros|Descripción|ejemplo|
| --- | --- | --- |
|Usuario||Usuario|
|Contraseña||Contraseña|
|Servidor||Servidor|
|Dirección correo||Dirección correo|
|Variable donde almacenar resultado|En este campo debemos poner el nombre de la variable donde almacenaremos el resultado de la conexión.|Variable|

![exchange](example\exchange.png)
### Enviar Email

Envia un email, previamente debe configurar el servidor
|Parámetros|Descripción|ejemplo|
| --- | --- | --- |
|Para||to@mail.com, to2@mail.com|
|Copia||cc@mail.com, cc2@mail.com|
|Asunto||Nuevo mail|
|Mensaje||Esto es una prueba|
|HTML|||
|Archivo Adjunto||C:\User\Desktop\test.txt|
|Carpeta (Varios archivos)||C:\User\Desktop\Files|

### Listar todos los email

Obtiene los Id's de todos los mail, por filtro
|Parámetros|Descripción|ejemplo|
| --- | --- | --- |
|Tipo de Filtro||Variable sin {}|
|Filtro||ej: test|
|Asignar a Variable||Variable|

### Listar email nuevos

Obtiene los Id's de los email no leidos, por filtro
|Parámetros|Descripción|ejemplo|
| --- | --- | --- |
|Tipo de Filtro||Variable sin {}|
|Filtro||ej: test|
|Asignar a Variable||Variable|

### Leer email por ID

Lee el contenido del mail pasandole el ID
|Parámetros|Descripción|ejemplo|
| --- | --- | --- |
|ID Mail||ID|
|Asignar a Variable||Variable|
|Ruta donde se descargan archivos adjuntos|||

### Mover email a carpeta

Mueve el email pasandole su ID a una carpeta especificada
|Parámetros|Descripción|ejemplo|
| --- | --- | --- |
|ID Mail||ID|
|Carpeta de destino||Nombre carpeta|

### Responder email por ID

Responder email por ID
|Parámetros|Descripción|ejemplo|
| --- | --- | --- |
|ID Email||355|
|Responder a todos||355|
|Mensaje||Esto es una prueba|
|Archivo Adjunto||C:\User\Desktop\test.txt|

### Reenviar email por ID

Reenviar email por ID
|Parámetros|Descripción|ejemplo|
| --- | --- | --- |
|ID Email||355|
|Email||test@email.com|
