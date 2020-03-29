# Dispositivos de red

Este capítulo se abarcan los dispositivos ya vistos en los anteriores capítilos, dando así una información detallada para que nosotros podamos entender su comportamiento y características.

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



## NIC

**Primero que nada,  ¿qué es una NIC?..**

Por sus siglas Network Interface Card se refiere a un dispositivo de interfaz que es agregado a una computadora por un bus de comunicación permitiendonos así un acceso al medio de red.

Es utilizado en la capa de enlace de datos ya que es la encargada de otorgar a nuestro equipo la dirección MAC.

**LEDS**

Estas tarjetas tienen indicadores en forma de LEDs, no hay un estandar para los colores de los leds, por lo que cada fabricante incluye un manual para indicar su significado.

- **Indicador de conectividad o Link Light**

  Utilizado para mostrar que la conexión a ethernet ha sido exitosa, normalmente el color de este LED es verde.

- **Indicador de velocidad**

- **Indicador de activdad**

  Muestra el envio y resepcion de frames en la red.

El parpadeo de un LED puede indicar 2 cosas en general, que recibe un la una señal apropiada de un medio o bien la deteccion de trafico en un segmento.

> Nota:
>
> Algunas tarjetas de red poseen de un slot para agregar un chip, según lo que he investiado se trata de un boot rom y lo que permite hacer es iniciar el sistema a partir de una red en vez de un disco local, esto es usado para centralizar el almacenamiento en una red.
>
> https://en.wikipedia.org/wiki/Option_ROM



## HUB

**¿Qué es?**

Se trata de un dispositivo de la capa física y conecta segmentos de una red en forma de topología de estrella.

 **Tonto e ineficiente** 

- **Expande el broadcast en toda la red.**

  Tiene el comportamiento de la topología de bus.

- **No entiende frames de datos ni estructuras de datos.**

- **Es el dispositivo que puede crear la LAN con más colisiones.**

  Ya que se comporta como una topología de bus, un dispositivo no puede recibir y enviar paquetes al mismo tiempo, por lo que significaría una perdida de ancho de banda.

- **Tiene la función de repetidor.**

La única manera en que un switch valdría la pena es utilizarlo para comunicar solo 2 dispositivos.

> Algunos hubs poseen la habilidad de convertir sus puertos en uno adecuado para conectar dos hubs con un cable directo en vez de uno cruzado.
>
> https://www.youtube.com/watch?v=sFGBzKmDfLw



## Bridge

Es un dispositivo de la capa de enlace de datos (usa la MAC address para tomar desiciones) basado en software que permite conectar dos segmentos de red parecidos pero con la función especial de separar el broadcast de ambos segmentos de red (rompe la colision de dominio). 

Los switchs utilizan la misma tecnología de puente y por esta misma razon es que no se suelen ver dispositivos de este tipo en una LAN, puesto que fueron remplazados por los switchs.



## Switch

Al igual que el hub sirve para conectar varios segmentos de una red pero con la diferencia de que ahora estamos hablando de un dispositivo inteligente que  trabaja en la capa de red y entiende de direcciones MAC, tiene la habilidad de limitar el broadcast dejando como cada puerto o interfaz una colision de dominio excluida o a parte.

Este dispositivo sí toma en cuenta los frames de datos , el origen y el destino de los datos.

Hay dos tipos de switch, aquellos que puedes manejar o configurar como lo son las VLans y agregar dirección IP (maneged switches) y aquellos que a los que no (unmaneged switches).

**Puertos**

- SFP
- RJ45

- GBIC

**¿Puerto combinado de SFP?**

Un puerto combinado consta de un soporte para conexiones de cobre como ópticas permitiendo así conectar dos dispositivos físicos distintos pero compartiendo el mismo número de puerto.

> En tanto a las aplicaciones Gigabit Ethernet se puede usar el puerto RJ45, SFP o el puerto GBIC.
>
> La pregunta sería: ¿Cuál y cuándo utilizar cada una?
>
> **GBIC vs SFP**
>
> En resumidas cuentas, tanto el GBIC y el SFP proporcionan las mismas velocidades, sin embargo, el hecho de que SFP sea mas accesible y ocupe menos espacio que el GBIC lo hace el más utilizado
>
> **SFP vs RJ45**
>
> Aqui entraría en cuenta 2 factores principales: 
>
> 1. Factor de inversión o costos
> 2. Factor de distancia o necesidades
>
> En tanto a funcionalidades el SFP soporta mejores velocidades con distancias mucho más largas por el hecho de su soporte con la fibra óptica.
>
> https://community.fs.com/es/blog/gigabit-switch-sfp-port-vs-rj45-port-vs-gbic-port.html



## Router

Es un dispositivo de red que trabaja en la capa de red y permite conectar varios segmentos de red en algo llamado como internetwork, su misión es enviar los paquetes de red por la mejor ruta.

Tambien se le pueden llamad switch de la capa 3 y switch multicapa.

Al igual que el switch puede romper colisiones de dominio.

El router puede romper la colision de broadcast en una red y provee de conectividad a los servicios de WAN.

Un router espera una dirección IP en cada interfaz, estos no se encuentran habilitados por default.

**Interfaces**

- VoIP

- Puerto auxiliar

  Conecta hacía el modem.

- AUI

- Serial

  Conecta un modem u otro dispositivo serial.

- Ethernet/FEthernet/GEthernet

- Consola

  Puerto de configuracion serial para la linea de comandos.



## Firewall

Básicamente un firewall en una red es un guardia de seguridad y para ser reales es probablemente la cosa más importante a la hora de implementar una red. Esto se debe a que hoy en día las redes están conectadas a internet provocando una situación donde la seguridad es crucial.

Un firewall protege los recursos de nuestra LAN de invasores de internet.

Se puede configurar un firewall para filtrar paquetes basados en reglas que se deseen usar en la red.

Sin los firewalls cualquier red expuesta a la internet es vulnerable a robo de información.



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

