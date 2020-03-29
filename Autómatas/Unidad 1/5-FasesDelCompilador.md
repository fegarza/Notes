# Fases del compilador

Cada fase del proceso de compilación es de suma importancia pues para que pueda proceder a la siguiente fase hace falta comprobar que todo se haya ejecutado correctamente.

## 

## Fases

1. **Análisis**

    Cada fase separa los distintos elementos que integran el programa fuente para comprobar su correcta realización.

   - Fase 1: Análisis léxico

     La cadenas de caracteres del programa fuente se lee carácter por carácter, para crear un archivo de salida que contiene componentes léxicos(secuencia de caracteres que tienen un significado colectivo).

   - Fase 2: Análisis sintáctico

     Los caracteres o componentes léxicos se agrupan jerárquicamente en colecciones anidadas de acuerdo con el significado colectivo y según las gramáticas definidas en el lenguaje.

   - Fase 3: Análisis semántico

     Garantizan que los componentes se ajusten entre sí de modo significativo.

2. **Síntesis**

   Aquí se construye el programa objeto optimizando las instrucciones recibidas del programa fuente.

   - Fase 4: Generación de código intermedio

     Debe ser fácil de producir y fácil de traducir.

     Funciona como un lenguaje ensamblador en donde cada posición de memoria puede actuar como un registro.

   - Fase 5: Optimización de código

     Mejora la eficiencia del código intermedio.

   - Fase 6: Generación de código.

     Fase final, convierte código intermedio en código máquina o código ensamblador.

![image-20200205170625434](C:\Users\Felipe\AppData\Roaming\Typora\typora-user-images\image-20200205170625434.png)



**Tabla de símbolos o diccionario**

Asocia valores con un nombre.

Los valores son una representación semántica del significado de los nombres.

**Detección de errores**

Para ello hay que saber las fases en las cuales se podrían detectar los errores.

- Análisis léxico
- Análisis sintáctico
- Análisis semántico