# Proceso y aplicación

#### Capa 1 protocolos



## Telnet 

##### TCP 23

Es un protocolo para el acceso entre dos dispositivos por medio de una emulación de una terminal y tiene como fin otorgar recursos a otro dispositivo extenro a la LAN.

Consiste en un cliente (Client Telnet) y un servidor (Server Telnet).

Telnet no ofrece ningún tipo de seguridad a la hora de lograr la conexión entre dos dispositivos, por lo que es remplazado por SSH (Secure Shell).



## FTP (File Transfer Protocol)

##### TCP 20, 21

Nos permite en transferir archivos sobre una red IP, sin embargo, no solo es un protocolo tambien se le puede considerar un programa operando como protocolo, ya que es usado en aplicaciones.

Perimte en intercambio bidireccional de archivos entre dos dispositivos por medio de un login para lograr una autenticación adecuada y lograr seguridad en el acceso de los archivos.

El problema con este protocolo es que no se pueden ejecutar archivos remotos con programas y tambien el texto se manda sin algun tipo de encriptamiento sino que el texto viaja sobre el medio de manera clara y esto es visto como una grave vulnerabilidad. Es por ello que si se necesita algún tipo de seguridad se debe implementar SFTP



## SFTP (Secure Transfer Protocol)

##### TCP 22

Básicamente hace la función del protocolo FTP pero con la diferencia de que ya se esta manejando un encriptamiento de los datos a la hora de viajar por elo medio, esto es posible gracias a una sesion SSH.



## TFTP (Trivial File Transfer Protocol)

##### UDP 69

Facíl de utilizar, rápido y poco seguro son sus principales caracteristicas.

No hay autenticación ni busqueda de directorios.



## SMTP

##### TCP 25

Utilizado para el envio de emails.



## Post Office Protocol

##### TCP 110

Utilizado para recibir emails.

Siendo POP3 su última versión y remplazada por IMAP.



## Internet Message Access Protocol V4 

##### TCP 143

Remplaza a POP3 ya que te permite el eligir cómo es que quieres descargar tu correo.

Implementa distintas características de autenticación, entre ellas el esquema Kerberos que MIT ha desarrollado.



## Remote Desktop Protocol

##### RCP 3389

Desarrollado por Microsoft, permite conectarnos a otra computadora y correr programas.

Básicamente hace las funciones de TELNET pero con una interfáz gráfica.



## Transport Layer Security/Secure Sockets Layer

##### TCP 995/465

TLS y SSL son protocolos criptograficos que permiten una seguridad en el transporte de datos.

Ambos utilizan el certificado X.509 y cirptografía asimetrica para autenticarse.

Si bien es cierto que utiliza los puerto 995 y 465 para servicios como gmail, no hay puertos definidos para estos protocolos.



## SIP (VoIP)

##### TCP - UDP 5060 o TCP 5061

Session Initiation Protocol es un protocolo utilizado para contruir y destruir sesiones de comunicacion multimedia como los son video llamadas y llamadas.



## RTP (VoIP)

##### UDPC 5004 TCP 5005

Real time Transport Protocol Define el formateo un paquete como estandar para entregar audio y video sobre internet.

Comunmente empleado para el streaming de media.



## MGCP (Multimedia)

##### TCP 2427-2727

Media Gateway Control Protocol.

Estandar para el manejo de señales y sesiones durante una conferencia multimedia.

Puede ser usado para configurar, mantener y terminar llamadas entre multiples puntos.

## H.232 (Video)

##### TCP 1720

Estandar de video sobre una red IP.

Define como en tiempo real el audio y video se debe de transmitir.

Usa el esrtandar RTP para la comunicación.



## Simple Network Managment Protocol

##### UDP 161

Colecta y manipula información valiosa de una red.

Cuando todo esta bien SNMP recibe algo llamado baseline (Informe que delimita el funcionamiento de la red).

Este protocolo tambien actua como un vigilante(agents) notificando cualquier evento(trap) a la estación de mantenimiento. 

Támbien actua como configurador de la red y la administración de la misma internetwork.



## SSH

##### TCP22

Utilizado para la autenticación , correr programas en sistemas remotos y mover archivos de un sistema a otro, todo esto manejado desde un procedimiento de encriptado.



## Hypertext Transfer Protocol

##### TCP 80

HTTP Mantiene la comunicación entre buscadores web y servidores web.

  

## Hypertext Transfer Protocol Secure

##### TCP 443

HTTPS es una versión segura de HTTP.



## Network Time Protocol 

##### UDP 123

NTP  es usado para sincronizar los relojes de computadoras con un estandar de tiempo.



## Lightweight Directory Access Protocol

##### TCP 389

Estandariza el como accedes a los directorios.



## Internet Group Management Protocol

Usado para manejar las sesiones multicast.



## NetBIOS

##### TCP y UDP 137 , 139

Utilizado en capas altas  y es usado para comunicar host con servidores Microsoft y Novell.



## Server Message Block

##### TCP 445

Usado para compartir acceso a archivos e impresoras entre HOSTS.



## Domain Name Service

##### TCP y UDP 53

Resuelve los nombres de host especialmente nombres de intenet.



## DHCP/BP

##### UDP 67 68

Dynamic Host Configuration Protocol asigna una direccion IP a un host on informacion dada por el servidor.

DHCP difiere de Boostrap Protocol (BootP) a diferencia del DHCP el BoostP asigna direcciones IP en base a una configuración realizada manualmente e n una tabla de BootP.



