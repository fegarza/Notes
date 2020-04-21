# Dispositivos de red

Este capítulo se abarcan los dispositivos ya vistos en los anteriores capítilos, dando así una información detallada para que nosotros podamos entender su comportamiento y características.

Estos dispositivos son llamados dispositrivos de conectividad puesto que nos permiten conectar entidades de nuestra red.

- [x] NIC
- [x] HUB
- [x] Bridge
- [x] Switch
- [x] Router
- [x] Firewall
- [x] IDS/IPS/HIDS
- [x] Access Point
- [x] Wireles Range Extender
- [x] Contention Methods
- [x] DHCP Server
- [ ] DHC Relay
- [ ] IPAM
- [ ] Load balancer
- [ ] DNS Server
- [ ] Proxy server
- [ ] Encription devices
- [ ] Analog modem
- [ ] Packet shader
- [ ] VPN concentrator
- [ ] Media converter
- [ ] VoIP PBX
- [ ] VoIP Endpoint
- [ ] VoIP Gateway
- [ ] SOHO
- [ ] Connection methods













## IDS/IPS

Por sus siglas Intrusion detection system / Intrusion prevention system, en un sistema de seguridad que monitorea los paqutes de una red para evitar actividad maliciosa.



## HIDS

Host-based IDS consiste en un software que monitorea todo el trafico de red.

Existen distintos tipos de IDS:

- PID

  Monitorean un puerto en específico.

- APIDS

  Monitorean una aplicación en específico.



## Access point

Es un dispositivo de otorgar acceso al medio por medio de señales analogas.

Los clientes modulan las s   eñales digitales a analogas para poder ser recibidas por el AP para poder ser demoduladas a señales digitales.



## Wireless Range Extender

Son antenas que operan en la misma frecuencia o canal de tu red para transmitir señales recibidas a la dirección que se quiera.

Deben colocarse 15% del punto limite de la cobertura del AP.

## CSMA/CA

Utilizado en los medios inalambricos, verifica el medio para el "phyisical carrier sense", si el medio no esta libre la estación implementara un algoritmo aleatorio  que inicializara un contador para volver a mandar los datos en el medio.

## CSMA/CD

Carrier Sense Multiple Access with Collision Detection, es un método de control de acceso a los medios que ayudan a los dispositivos a compartir el ancho de banda.

Fue creado para superar el problema de las colisiones que ocurren cuando los paquetes son transmitidos simultáneamente de diferentes hosts.

**Cuando un host quiere transmitir en la red:**

1. Checa si hay una presencia de señal en el cable.
2. Si todo esta libre prosigue con la transmisión.
3. Constantemente checa que no haya una presencia de señal en el cable.
4. Si detecta una señal envia una señal de jam que causa a todos los host en un segmento a parar el envio de datos. Los hosts responden a esa señal esperando un momento antes de transmitir de nuevo.
5. Por medio de los algoritmos de backoff se determina cuando las estaciones congeladas pueden retransmitir.
6. Si la colision sigue ocurriendo despues de 15 intentos, los hosts  se agotan.

**Cuando una colisión ocurre en un Ethernet LAN, pasa lo siguiente:**

- Una señal de jam informa a todos los dispositivos que una colisión ocurrió.
- La colisión invoca un algoritmo de backoff  aleatorio.
- Cada dispositivo en un segmento ethernet para de transmitir por un corto tiempo hasta que el tiempo expire.
- Todos los hots tienen la misma prioridad para transmitir después de que los timers expiren.

**Efectos de tener un CSMA/CD**

- Retraso
- Bajo rendimiento
- Congestión

El backoff en una red 802.3 es un retraso de retransmisión.



## DHCP Server

P0r sus siglas Dynamic Host Configuration Protocol Server provee de un IP que se encuentre dentro de un rango establecido a los host de una red, facilitando así el manejo de las IP.

Las direcciones de IP dadas por un DHCP son llamadas IP dinamicas.

Un servidor DHCP puede trabajar con una lista de reservación que permitira establecer una direccion IP fija a un host. 

Un servidor de DHCP nos puede proveer de un ip, mascar, gateway, el valor por defecto TCP TTL  para pquetes TCP, servidor DNS y un servidor TFTP.

Los mensajes DHCP utilizan el puerto UDP 67  para el servidor y 68 para el cliente.

