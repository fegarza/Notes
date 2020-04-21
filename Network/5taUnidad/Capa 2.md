# Dispositivos de la capa de enlace de datos

Proporcionan un direccionamieno físico todos los dispositivos que se encuentran en esta sección



## Switch

Al igual que el hub sirve para conectar varios segmentos de una red pero con la diferencia de que ahora estamos hablando de un dispositivo inteligente que  trabaja en la capa de red y entiende de direcciones MAC, tiene la habilidad de limitar el broadcast dejando como cada puerto o interfaz una colision de dominio excluida o a parte.

Este dispositivo sí toma en cuenta los frames de datos , el origen y el destino de los datos.

El switch posee de puertos que trabajan de manera separada a los demas puertos a diferencia del switch que actua como repetidor.

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





## Bridge

Es un dispositivo de la capa de enlace de datos (usa la MAC address para tomar desiciones) basado en software que permite conectar dos segmentos de red parecidos pero con la función especial de separar el tráfico de ambos segmentos de red (rompe la colision de dominio). 

Los switchs utilizan la misma tecnología de puente y por esta misma razon es que no se suelen ver dispositivos de este tipo en una LAN, puesto que fueron remplazados por los switchs.



## NIC 

#### Primero que nada,  ¿Qué es una NIC?

Por sus siglas Network Interface Card se refiere a un dispositivo de interfaz que es agregado a una computadora por un bus de comunicación permitiendonos así un acceso al medio de red a velocidades de 10, 100, 1000 Mbps.

Es la encargada de otorgar a nuestros equipos la dirección MAC.

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

