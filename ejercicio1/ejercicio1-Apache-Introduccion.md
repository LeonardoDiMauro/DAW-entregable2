![N|Solid](apache.png)
_**Autor**_: _Leonardo Di Mauro. 22/10/2021_
# 1.- ¿Qué es Apache?

Apache HTTP Server es un software de servidor web gratuito y de código abierto para plataformas Unix con el cual se ejecutan el 46% de los sitios web de todo el mundo. Es mantenido y desarrollado por la Apache Software Foundation.

Le permite a los propietarios de sitios web servir contenido en la web, de ahí el nombre de «servidor web». Es uno de los servidores web más antiguos y confiables, con la primera versión lanzada hace más de 20 años, en 1995.

Cuando alguien quiere visitar un sitio web, ingresa un nombre de dominio en la barra de direcciones de su navegador. Luego, el servidor web envía los archivos solicitados actuando como un repartidor virtual.

# 2.- Contexto de uso.

Aprender a usar el servidor Apache en un ambiente educacional.

# 3.- Motivación:
    
Apache es un programa de servidor gratuito ampliamente utilizado y probado, se busca conocer sus posibilidades, así como su implementación.

# 4.- Instalación de Apache en Linux Ubuntu.

Podemos **instalar** Apache con el siguiente comando:
```
sudo apt-get install apache2
```
Una vez instalado podemos **iniciarlo** con:
```
/etc/init.d/apache2 start
```
Podemos comprobar el **estado del servidor** con el comando:
```
/etc/init.d/apache2 status
```
Para **detener** el servidor podemos usar el comando:
```
/etc/init.d/apache2 stop
```
Para **reiniciarlo** con el comando:
```
/etc/init.d/apache2 restart
```
---
**Para ver que funciona correctamente**:
- ```/etc/init.d/apache2 start```
- Abrimos el navegador y en la URL ponemos _**localhost**_
- Deberiamos poder ver el index prestablecido por Apache.

![imagen](index.png)


