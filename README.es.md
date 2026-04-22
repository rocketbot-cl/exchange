



# Exchange

Conecta con servidores Microsoft Exchange para enviar, leer y gestionar correos y carpetas mediante servicios web.

*Read this in other languages: [English](README.md), [Português](README.pr.md), [Español](README.es.md)*

## Como instalar este módulo

Para instalar el módulo en Rocketbot Studio, se puede hacer de dos formas:
1. Manual: __Descargar__ el archivo .zip y descomprimirlo en la carpeta modules. El nombre de la carpeta debe ser el mismo al del módulo y dentro debe tener los siguientes archivos y carpetas: \__init__.py, package.json, docs, example y libs. Si tiene abierta la aplicación, refresca el navegador para poder utilizar el nuevo modulo.
2. Automática: Al ingresar a Rocketbot Studio sobre el margen derecho encontrara la sección de **Addons**, seleccionar **Install Mods**, buscar el modulo deseado y presionar install.


## Overview


1. Configurar Correo
Ingrese las credenciales para poder enviar y listar correos 

2. Enviar Email
Envia un email, previamente debe configurar el servidor

3. Listar todos los email
Obtiene los Id's de todos los mail, por filtro

4. Listar email nuevos
Obtiene los Id's de los email no leidos, por filtro

5. Leer email por ID
Lee el contenido del mail pasandole el ID

6. Mover email a carpeta
Mueve el email pasandole su ID a una carpeta especificada

7. Responder email por ID
Responder email por ID

8. Reenviar email por ID
Reenviar email por ID




----
### OS

- windows
- mac
- linux
- docker

### Dependencies
- [**exchangelib**](https://pypi.org/project/exchangelib/)
### License

![MIT](https://img.shields.io/github/license/instaloader/instaloader.svg)
[MIT](https://opensource.org/license/mit)