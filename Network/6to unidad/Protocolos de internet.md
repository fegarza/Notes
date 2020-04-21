# TCP/IP

### Transmision control protocol / Internet protocol



Creado por el departamento de defensa DoD para resguardar la integridad de los datos y dar comunicación durante una evento de guerra.



<hr/>

### RFC

Por sus siglas request of content son una serie de especificaciones (protocolos para ser más específicos) por un grupo de trabajo de ingeniería de internet el IETF (Internet
Engineering Task Force).

<hr/>

### Historia

- **1974** 

  TCP es creado.

- **1978**

  TCP es dividido en 2  protocolos TCP e IP.

- **1983**

  TCP remplaza al network control protocol NCP y es considereado como un estandar de transmición de datos en el ARPA.NET que es la antecesor del internet.

<hr/>

## Modelo DoD

A comparación del modelo OSI este consta en 4 capas en total.

1. **Proceso / Capa de aplicación**

   Define protocolos de nodo a nodo para aplicaciones de comunicacion y tambien controla inrfaces de usuario.

   Básicamente es la capa de aplicación, presentación y sesión del modelo OSI.

2. **Capa de host a host**

   Define protocolos para configurar el nivel de servicio de transmicion para aplicaciones.

   Mantiene el seguimiento e integracion de los datos. 

   Básicamente es la capa de transporte del modelo OSI.

3. **Capa de internet**

   Define los protocolos encargados de la transmicion lógica de los paquetes sobre una red y se encarga de dar una dirección IP.

   Básicamente es la capa de red del modelo OSI.

4. **Capa de acceso a la red**

   Monitorea el intercambio de datos entre los host y la red.

   Define los protocolos para la transmición de datos.

   Básicamente es la capa de enlace de datos y física del modelo OSI.

Siendo esta la relación con las capas del modelo OSI

![image-20200418200737092](C:\Users\fegar\Documents\Notes\Network\6to unidad\image-20200418200737092.png)