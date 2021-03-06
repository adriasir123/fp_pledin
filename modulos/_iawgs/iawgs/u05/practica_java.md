---
title: Despliegue de CMS java
permalink: /iawgs/u05/practica_java.html
---

En esta práctica vamos a desplegar un CMS escrito en java. Puedes escoger la aplicación que vas a desplegar de [CMS escritos en Java](http://java-source.net/open-source/content-managment-systems) o de [Aplicaciones Java en Bitnami](https://bitnami.com/tag/java).

{% capture notice-text %}
Indica la aplicación que vas a instalar. Indica las características principales de la aplicación. Recuerda que tienes que hacer un despliegue en el servidor Tomcat que tienes instalado (no puedes hacer una instalación desde un fichero ejecutable.

* Se evaluará la complejidad de la instalación (por ejemplo, necesidad de tener que instalar un conector de base de datos, ...)(máximo 3 puntos).
{% endcapture %}<div class="notice--info">{{ notice-text | markdownify }}</div>

## Tarea 1: Despliegue de la aplicacion en el servidor de aplicaciones Tomcat

Realiza el despliegue de la aplicación (fichero WAR) en tu servidor Tomcat. 

{% capture notice-text %}
* Escribe una guía de los pasas fundamentales para realizar la instalación.
* ¿Has necesitado instalar alguna librería?¿Has necesitado instalar un conector de una base de datos?
* Entrega una captura de pantalla donde se vea la aplicación funcionando.

3 puntos
{% endcapture %}<div class="notice--info">{{ notice-text | markdownify }}</div>

## Tarea 2: Integración de apache2

Realiza la configuración necesaria en apache2 y tomcat (utilizando el protocolo AJP) para que la aplicación sea servida por el servidor web.

{% capture notice-text %}
* Escribe una guía de los pasas fundamentales para realizar la integración.
* Entrega una captura de pantalla donde se vea la aplicación funcionando.

2 puntos
{% endcapture %}<div class="notice--info">{{ notice-text | markdownify }}</div>
