# Ejercicio-DNS-Raid-Apache
## Creación del servidor DNS
Declarar las zonas de los sitios.
![named.conf.local.PNG](https://github.com/antoniodavidperez/Ejercicio-DNS-Raid-Apache/blob/master/named.conf.local.PNG)

Configurar los servidores DNS a los que va a acudir nuestro servidor en el caso de que nos conozca la IP del nombre por el que le están preguntando.
![named.conf.options.PNG](https://github.com/antoniodavidperez/Ejercicio-DNS-Raid-Apache/blob/master/named.conf.options.PNG)

Crear las zonas directas de cada sitio donde se relacionan las IP con los nombres.
![rd.gato.com.PNG](https://github.com/antoniodavidperez/Ejercicio-DNS-Raid-Apache/blob/master/rd.gato.com.PNG)
![rd.mosquito.com.PNG](https://github.com/antoniodavidperez/Ejercicio-DNS-Raid-Apache/blob/master/rd.mosquito.com.PNG)
![rd.escherichiacoli.es.PNG](https://github.com/antoniodavidperez/Ejercicio-DNS-Raid-Apache/blob/master/rd.escherichiacoli.es.PNG)
![rd.chip555.org.PNG](https://github.com/antoniodavidperez/Ejercicio-DNS-Raid-Apache/blob/master/rd.chip555.org.PNG)

Crear la zona inversa donde se relacionan los nombres con las IP.
![ri.10.PNG](https://github.com/antoniodavidperez/Ejercicio-DNS-Raid-Apache/blob/master/ri.10.PNG)

## Creación del servidor Apache
Crear los host virtuales, para ello hay que crear primero la estructura de carpetas y luego configurar los archivos.
![gato.com.conf.PNG](https://github.com/antoniodavidperez/Ejercicio-DNS-Raid-Apache/blob/master/gato.com.conf.PNG)
![mosquito.com.conf.PNG](https://github.com/antoniodavidperez/Ejercicio-DNS-Raid-Apache/blob/master/mosquito.com.conf.PNG)

Los dos sitios que vemos a continuación además de la configuración tienen también la de los usuarios. Para ello primero hay que crear un directorio y un archivo donde añadimos los usuarios del sitio.
![escherichiacoli.es-passwords.PNG](https://github.com/antoniodavidperez/Ejercicio-DNS-Raid-Apache/blob/master/escherichiacoli.es-passwords.PNG)
![escherichiacoli.es.conf.PNG](https://github.com/antoniodavidperez/Ejercicio-DNS-Raid-Apache/blob/master/escherichiacoli.es.conf.PNG)
![chip555.org-passwords.PNG](https://github.com/antoniodavidperez/Ejercicio-DNS-Raid-Apache/blob/master/chip555.org-passwords.PNG)
![chip555.org.conf.PNG](https://github.com/antoniodavidperez/Ejercicio-DNS-Raid-Apache/blob/master/chip555.org.conf.PNG)

## Comprobación desde el lado del cliente
