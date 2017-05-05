
# Instituto Tecnológico de Tepic
Ingeniería en Sistemas Computacionales
Desarrollo de Aplicaciones Multiplataforma

# Práctica 1 - Camara App

# Alumnos:
Armando Antonio Navarro Flores  12400297
Ernesto Pacheco Morelos  12400306
# Maestro:
Israel Arjona Vizcaino

Grupo: 5A
Tepic, Nayarit a 04 de mayo de 2017

# Descripción
La práctica consiste en una aplicación capaz de tomar una foto; o bien tomar una foto de la galería del dispositivo y mostrarla en la pantalla principal así como la URI donde se encuentra almacenada y la codificación base64.

El flujo de funcionamiento de la aplicación es:
* Acceder al plugin de Cordova de la cámara, para lanzar la aplicación de cámara del dispositivo y obtener la imagen en formato Base64 o URI
* Insertar la información en un objeto DOM <code><img></code>
* Mostrar la URI si está en ese formato.
* Capturar el evento de un switch para mostrar la URI.

Cabe destacar que esta aplicación necesita un dispositivo físico debido a el uso del recurso nativo de la cámara, que en el navegador por ejemplo no está disponible en la versión de Ionic 2.
