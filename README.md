# Laboratorio-11-PW
Repo para despliegue en Versel

Preguntas:
¿Cuál es la finalidad del archivo vercel.json?
El archivo vercel.json es un archivo de configuración que permite personalizar el comportamiento de Vercel al desplegar una aplicación. cuenta con:
-Configuración de rutas: Permite establecer reglas para redirecciones, reescrituras de URL y encabezados personalizados.
-Especificación de funciones serverless: Define la ubicación de las funciones backend y cómo manejarlas.
-Entornos específicos: Predefine configuraciones específicas para producción, desarrollo o pruebas.

¿Qué ventajas tiene desplegar en Vercel frente a un servidor tradicional?
-Simplicidad de despliegue:	Vercel automatiza el proceso de despliegue con GitHub/GitLab/Bitbucket. Solo requiere un git push para actualizar la aplicación.
-Funciones serverless:	Soporta funciones serverless nativamente, eliminando el requerimiento de gestionar servidores backend.
-Escalabilidad automática:	Vercel escala automáticamente las aplicaciones según la demanda, reduciendo costos y evitando configuraciones complejas.

¿Qué propiedades del archivo vercel.json son necesarias para que una aplicación Express funcione correctamente en Vercel?
builds:	Define las rutas y el tipo de construcción. 
routes:	Configura las rutas para mapear las peticiones a las funciones serverless.
rewrites:	Si es necesario, reescribe las URL para redirigir peticiones específicas hacia el backend.
outputDirectory:	Indica la salida del proyecto (aplicaciones con Express).
