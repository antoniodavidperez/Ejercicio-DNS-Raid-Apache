# Ejercicio-DNS-Raid-Apache
Lo primero que tenemos que hacer es declarar las formas directas para los diferentes sitios y una inversa para todas.

![named.conf.local.PNG](https://github.com/antoniodavidperez/Ejercicio-DNS-Raid-Apache/blob/master/named.conf.local.PNG)

Ahora configuramos los servidores DNS a los que nuestro servidor va a preguntar por nombre que no conoce.

![named.conf.local.PNG](https://github.com/antoniodavidperez/Ejercicio-DNS-Raid-Apache/blob/master/named.conf.options.PNG)

Después de preparar el servidor vamos a crear los archivos donde se guardaran las relaciones entre nombre e ip.

![named.conf.local.PNG](https://github.com/antoniodavidperez/Ejercicio-DNS-Raid-Apache/blob/master/rd.gato.com.PNG)
![named.conf.local.PNG](https://github.com/antoniodavidperez/Ejercicio-DNS-Raid-Apache/blob/master/rd.mosquito.com.PNG)
![named.conf.local.PNG](https://github.com/antoniodavidperez/Ejercicio-DNS-Raid-Apache/blob/master/rd.escherichiacoli.es.PNG)
![named.conf.local.PNG](https://github.com/antoniodavidperez/Ejercicio-DNS-Raid-Apache/blob/master/rd.chip555.org.PNG)
