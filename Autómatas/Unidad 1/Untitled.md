# Compilar

**Léxico**

Reconocer cada elemento pertenezca a mi lenguaje y los convierte en tokens almacenados en archivos de salida.

Se recorre por la matriz de transición.

Las tablas de símbolos son estructuras de datos donde se guardan los identificadores, se guardan aquí para saber el valor de los tokens.

## Reglas

- La longitud de los tokens (nombres) deben ser iguales

- Los identificadores deben numerarse

## Etapas:

### Análisis:

**Sintaxis** corre un método de recorrido o técnica de análisis recursiva que puede ser ascendente o descendente , devolviendo así un sí o no es correcto, si hay error se crea un token de error y se devuelve.(Usa gramática)

**Analizador semántico**: recibe el archivo que deja el analizador léxico (tokens) y analiza un análisis recursivo ascendente o descendente pero exclusivo para reglas de semántica.(Usa reglas semánticas).

### Transformación:

**Convertir a código intermedio**

Recibe el archivo de tokens para convertirlo a una estructura de datos llamada tripleta o cuádruplo. 

**Optimización**

Se optimiza espacios, recursos y tiempo, de manera que se quita todo lo que no sirva(como comentarios, espacios en blancos, variables sin utilizar).

Reduce tiempo, espacio en memoria y código.

**Conversión a código final**

Convierte las tripletas o cuádruplos al lenguaje ensamblador. 



# 

# Unidades

1. Introducción

2. Maquina de Turing

   Se hace una practica llamada diseño de maquina de turing (veer como funcionan y crear una)

3. Expresiones regulares

4. .Definiciones regulares

5. ~~A. Fin (no)

6. Léxico

7. Sintaxis

3 y 4 unidad 6



Examen unidad 1,,6,7

