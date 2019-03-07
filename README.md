# Ejercicio-DNS-Raid-Apache
## Creación del servidor DNS
Declarar las zonas de los sitios.
![named.conf.local.PNG](https://github.com/antoniodavidperez/Ejercicio-DNS-Raid-Apache/blob/master/named.conf.local.PNG)

Configurar los servidores DNS a los que va a acudir nuestro servidor en el caso de que nos conozca la IP del nombre por el que le están preguntando.
![named.conf.local.PNG](https://github.com/antoniodavidperez/Ejercicio-DNS-Raid-Apache/blob/master/named.conf.options.PNG)

Crear las zonas directas de cada sitio donde se relacionan las IP con los nombres.
![named.conf.local.PNG](https://github.com/antoniodavidperez/Ejercicio-DNS-Raid-Apache/blob/master/rd.gato.com.PNG)
![named.conf.local.PNG](https://github.com/antoniodavidperez/Ejercicio-DNS-Raid-Apache/blob/master/rd.mosquito.com.PNG)
![named.conf.local.PNG](https://github.com/antoniodavidperez/Ejercicio-DNS-Raid-Apache/blob/master/rd.escherichiacoli.es.PNG)
![named.conf.local.PNG](https://github.com/antoniodavidperez/Ejercicio-DNS-Raid-Apache/blob/master/rd.chip555.org.PNG)

Crear la zona inversa donde se relacionan los nombres con las IP.
![named.conf.local.PNG](https://github.com/antoniodavidperez/Ejercicio-DNS-Raid-Apache/blob/master/ri.10.PNG)

## Creación del servidor Apache
Crear los host virtuales
![named.conf.local.PNG](https://github.com/antoniodavidperez/Ejercicio-DNS-Raid-Apache/blob/master/gato.com.conf.PNG)
![named.conf.local.PNG](https://github.com/antoniodavidperez/Ejercicio-DNS-Raid-Apache/blob/master/mosquito.com.conf.PNG)
![named.conf.local.PNG](https://github.com/antoniodavidperez/Ejercicio-DNS-Raid-Apache/blob/master/escherichiacoli.es.conf.PNG)
![named.conf.local.PNG](https://github.com/antoniodavidperez/Ejercicio-DNS-Raid-Apache/blob/master/chip555.org.conf.PNG)
