# nodejs-mysql-restapi-test

Esta es la documentación y guía de instalación para la aplicación de servidor REST API desarrollada en Node.js, Express y MySQL para gestionar la información de empleados.

Instalación

Siga estos pasos para instalar y configurar el proyecto en su entorno local:

1.Clonar el Repositorio:

git clone https://github.com/Mathr91/nodejs-mysql-restapi-test.git

2.Instalar Dependencias:
npm install

3.Configurar Variables de Entorno:
Cree un archivo `.env` en el directorio raíz del proyecto y defina las variables de entorno necesarias según se describe en la sección de configuración.

4.Ejecutar la Aplicación:

Modo de Desarrollo con Nodemon:
npm run dev

Modo de Producción con Node.js:
npm start  

Documentación de la API
La documentación detallada de la API se encuentra en la https://matiashrdevs-organization.gitbook.io/api-rest/
      
Estructura del Proyecto

-src/: Contiene el código fuente de la aplicación.

-src/controllers/: Controladores de la API.

-src/routes/: Definición de rutas de la API.

-src/app.js: Configuración de la aplicación Express.

-src/config.js: Configuración de variables de entorno.

-src/db.js: Configuración de la base de datos.

-src/index.js: Punto de entrada de la aplicación.


actualmente la API esta desplegada en railway, se puede testear , leer la documentacion de la API para mas informacion

nodejs-mysql-restapi-test-production-a908.up.railway.app/api/employees
