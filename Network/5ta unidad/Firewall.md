# Firewall



## ¿Qué es un firewall?

Es un sistema de protección a la red que trabaja en la capa de red y permite la entrada de paquetes autorizados solamente, bloqueando o denegando aquellas que no se permiten. O bien un filtrado entre nuestra LAN y la WAN.

## Importancia

Es considerado el dispositivo más importante puesto que la seguridad de una red es crucial a la hora de salvaguardar tanto nuestros datos como los de grandes empresas.

## Funcionamiento

Para funcionar necesita un conjunto de normas o reglas establecidas en una lista de acceso por el administrador de red (definiendo que puede entrar y salir de la red).

Las reglas aplican para

- Puertos
- Direcciones IP
- DNS
- Protocolos
- Programas

El proceso por el cual se decide si el paquete puede o no entrar a la red es llamado packet filtering.

El firewall poser de un conjunto de registros por host de lo que han estado enviando o recibiendo, esta es llamada conversation list, gracias a esta el firewall puede identificar si un sitio está enviando paquetes sospechosos y procede a bloquearlo (stateful inspection).

## Tipos

**Host-based** 

Utilizado en un host por medio de un software, un ejemplo seria Windows Firewall.

Utilizado proteger solo el host que lo contenga.

**Netwkork-based**

Es una combinación de software y hardware ubicado entre la LAN y la internet pública.

Utilizado para proteger toda una red. 

## **Proxy firewall**

Opera en la capa de aplicación, consiste en una estrategia de protección para ocultar la verdadera dirección de host que desea hacer la petición por medio de un intermediario.