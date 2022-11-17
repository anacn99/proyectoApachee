### Añade un DNS al docker-compose (puedes usar el que ya tienes)


 # Con nuestro docker anterior Para ello, en el docker-compose le poemos poner un contenedor para el asir_cliente, ademas le añadimos a asir_apache la IP fija.
La añadimos el dns para que nos permita hacer el ping a dichas direcciones ip.
Una vez comprobamos el funcionamiento correcto de esta parte de la instalacion apache+VirtualHost
Como ya hemos dicho,configuramos las ip de los contenedor,


Utiliza docker-compose para configurar las IP fijas a los dos contenedores

Escribimos asir_ para nombrar cada contenedor.

El DNS tiene que resolver dos dominios a la ip del apache, por ejemplo:

    www.fabulasoscuras.com
    www.fabulasmaravillosas.com


Configura dos virtual-host separados para cada dominio en el mismo puerto (80)
