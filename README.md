# Laboratorio-11-PW
¿Cuál es la finalidad del archivo vercel.json?
R// Es utilizado para configurar y personalizar el comportamiento de un proyecto desplegado en la plataforma Vercel. Específicamente, permite definir cómo se manejarán las rutas, las funciones del backend (en caso de una API), los ajustes de redirección, y otros aspectos importantes relacionados con el despliegue y funcionamiento de la aplicación.

¿Qué ventajas tiene desplegar en Vercel frente a un servidor
tradicional?
R//     
1. Configuración Sencilla: Vercel simplifica el proceso de despliegue con una interfaz fácil de usar y soporte integrado para frameworks populares como React, Next.js, entre otros.

2. Despliegue Automático: Integración directa con repositorios de GitHub, GitLab o Bitbucket permite despliegues automáticos cada vez que se realiza un commit en el repositorio.

3. Escalabilidad Automática: Las aplicaciones se escalan automáticamente según la demanda, sin necesidad de configuración adicional.

4. Distribución Global: Vercel usa una red de distribución de contenido (CDN), lo que asegura que tu aplicación se sirva rápidamente desde ubicaciones cercanas al usuario.

5. Manejo de Funciones Serverless: Ofrece soporte para funciones serverless, lo que facilita la ejecución de código del backend sin preocuparte por la administración del servidor.

6. Certificados SSL Gratuitos: Todas las aplicaciones en Vercel reciben automáticamente un certificado SSL, mejorando la seguridad de la aplicación.

7. Optimización Integrada: Herramientas como optimización de imágenes y compresión automática vienen habilitadas por defecto.

¿Qué propiedades del archivo vercel.json son necesarias para que una
aplicación Express funcione correctamente en Vercel?
R//
1. routes: Configura las rutas de entrada para la aplicación. Esto es útil si necesitas redirigir ciertas solicitudes a funciones específicas del backend o manejar rutas personalizadas.

2. builds: Define cómo construir las funciones o el backend de tu aplicación. En el caso de Express, especificas el archivo principal de tu API.

3. functions (opcional): Si necesitas configurar funciones serverless específicas, como un límite de tiempo o memoria, puedes hacerlo aquí.

4. rewrites (opcional): Se utiliza para reescribir URL y manejar rutas amigables.

5. outputDirectory: Especifica la carpeta donde están los archivos estáticos de tu aplicación si estás sirviendo un frontend.