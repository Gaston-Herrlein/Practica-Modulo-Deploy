# Practica modulo despliegue en servidor

## Ejercicios

1.  Cada alumno deberá desplegar en un servidor su desarrollo para la práctica del curso de Programación Backend con Node

        • Utilizar node como servidor de aplicación utilizando PM2 o supervisor como gestor de procesos node para que siempre esté en ejecución. La aplicación node deberá reiniciarse automáticamente al arrancar el servidor (en el startup).
        • Utilizar nginx como proxy inverso que se encargue de recibir las peticiones HTTP y derivárselas a node.
        • Los archivos estáticos de la aplicación (imágenes, css, etc.) deberán ser servidos por nginx (no por node). Para poder diferenciar quién sirve estos estáticos, se deberá añadir una cabecera HTTP cuando se sirvan estáticos cuyo valor sea: X-Owner (la X- indica que es una cabecera personalizada) y el valor de la cabecera deberá ser el nombre de la cuenta de usuario en github del alumno.

2.  Si se accede al servidor web indicando la dirección IP del servidor en lugar del nombre de dominio, se deberá carga la práctica realizada en el módulo de React o React Avanzado (a elección del almuno).

## Resolucion

Ip Publica: 54.196.69.32

DNS Ip publica: ec2-54-196-69-32.compute-1.amazonaws.com
