Paradigma de ingenieria de software a la serie de pasos que abarcan los metodos, herramientas y los procedimientos utilizadas en el proceso de software

- Enfoque CASCADA
  
  - Ciclo de vida

- Desarrollo evolutivo
  
  - Prototipos, desarrollo en espiral

- Programaci[on exploratoria

# Ciclo de vida

Prpuesto por roycen en 1970 popularizado por bohem en 1981

Finalidada: establecer orden en el desarrollo de grandes productos de software

Diferentes etapas, las cuales son procesadas de un modo lineal

Base de muchos otros modelos, levemente mejorada y retocada a lo largo del tiempo

Aun en nuestros dias siguie siendo muy utilizado.

Etapas (Todas requieres documentacion)

- Definicion de requirimientos
  
  Estudio de la cituacion actua;

- Analisis y diseño
  
  Decomposicion modular de toda la aplicacion, descripcion detallada de cada uno de los modulos y sus interrelaciones, todo ello para poder facilitar al maximo la fase de codigicacion

- Implementacion
  
  Cada modulo como resulta de la fase anterior es traducido  a la herramienta o lenguaje apropiado.

- Integracion y pruebas
  
  Verificacion del correcto funcionamiento de cada modullo y todo el sistema una vez ha sido integrado, detectar erroes en la codificacion, definiciones de requisitos y de diseño

- Manteimiento
  
  Garantizar el mantenimiento del sistema, corrección de errores detectados en esta fase, adaptacion del sistema a nuevos entornos.



### Desventajas

El establecimiento explicito de todos los requisitos del sistema al principio del desarrollo

poca flexibilidad para cambios en el sistema

Nada hecho hasta el final. La validacion de los requisistos iniciales se realiza hasta el final.



# Desarrollo por prototipos (desarrollo evolutivo)

Utilizados principalmente en el desarrollo de sistemas donde existe un pobre conocimiento de los requerimientos de un sistema o la rapida evolucion de los mismo a traves del tiempo.

Captura de requirimientos -> diseño rápido

El diseño rápido se centra en una representación de aquellos aspectos de software que serán visibles al usuarios. El prototipo es evaluado por el cliente y el usuario y utilizado para refinar los requqerimientos del software a ser desarrolado.

**Etapas:**

1. Analisis preliminar y especificacion de los requerimientos

2. Diseño e implementacion de un prototipo
   
   Enfasis en la interface de usuarios, equipo pequeño para minimizar los costos de comunicacion. utilizacion de herramientas de ayuda al desarrollo

3. Evaluzación del cliente y-o usuario

4. Refinamiento del prototipo y'o requerimientos

5. Diseño e implementación de un sistema
   
    A partir de la fase 5 se sigue con el estándar del ciclo de vida.
   
   ### Desventajas
   
   La manera tan rapida va a obligar a utilizar fragmentos de codigo ya existentes descuidando así la calidad de software.



# Modelo espiral (Desarrollo evolutivo)

Descrito por barty bohem en 1986, presenta mejores caracteristicas que los dos modelos anteriormente expuestos.

INcorpora el factor riego al modelo de ciclo de vida

Se produce una cadea continua de productos, los cuales estan disponibles para la examinacion y evaluacion por parte del cliente

PRiovee mecanismos para la aseguracion de calidad del software

La reevaluacion despues de cada fase permite cambios en las percepciones de los usuarios, avances tecnoloficos o perspectivas financieras.



**Cuadrantes:**

- Planificacion

    Determinacion de objetos, alternativas, restricciones y elaboracion de plan de desarrollo para el ciclo actual

- Analisis de riegos
  
     Evaluacion de las alternativas, identificacion y resolucion de riegos. Se decide si se sigue o no con el proyecto.

- INgenieria
  
  Desarrollo del producto siguiendo un modelo, del ciclo de vida o cascad, prototipo, etc.

- Evaluacion por el cliente

- Valoracion de los recursos    
