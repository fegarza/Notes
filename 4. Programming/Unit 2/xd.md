# Programación funcional

 Es un paradigma de programación declarativa basado en la utilizacion de funciones aritmeticas que no manejan datos mutables o de estado.

Enfatiza la aplicacion de funciones, en contraste con el paradigma de programación imperativa que enfatiza los cambios de estado.

La característica principal de la programación funcional es que los cálculos se ven como una función matemática que hacen corresponder entradas y salidas.

Tiene sus raíces en el cálculo lamba, un sistema formal desarrollado en los años 1930s para investigar la definición de función, la aplicación de las funciones y recursión.

Muchos lenguajes de programación funcionales pueden ser vistos como elaboraciones del cálculo lambda.



Caracteristicas:

- No hay noción de posición de memoria y por tanto, necesidad de una instrucción de asignación.
- Los bucles se modelan a través de la recursividad ya que no hay manera de incrementar o diminuir el valor de una variable.
- Como aspecto práctico casi todos los lenguajes funcionales soportan el concepto de variable, asignación y bucle. Estos elementos no forman parte del modelo funcional puro.

 Cualquiera que haya programado una hoja de calculo conoce la experiencia de la programacion funcional

- En la hoja de calculo se especifica cada celda en terminos de los valores de otras celdas. El objetivo es que debe ser calculado y no como debe calcularse
- No especificamos el orden en el que las celdas seran calculadas, en cambio obtenemos el orden que garantiza que la hoja de calculo puede calcular las celdas respetando las dependencias.
- No indicamos a la hoja de calculo como manejar la memopria, en cambio esperamos que nos presente un plano de ceeldas, aparantemente in finito, pero que solo utiliza la memoria de las celdas que estan actualmente en uso
- Lo mas importante especificamos el valor de una celda por una expresion cuyas partes pueden ser evaluadas en cualquier orde, en vez de una secuencia de comando que calculan los valores.



LISP es uno de los principales lenguajes de progrmacion del paradigma funcional

Fue desarrollado por John McCarthy, en 1958 LISP es un lenguaje maduro, aplicable a diversos escenarios tales como:

- Robótica.
- Inteligencia Artificiales.
- Procesamiento de lenguaje natural.
- Demostración auomática de teoremas.

- El nombre de LISP es un acronimo del LIST Processing .

- La caracteristica principal de LISP es que todo programa consiste en una función.

- No psee asignaciones.

- Su principal estructura de control es una recursion.

- Los programa sy los datos son equivalentes.

- Su principal estructura de datos es la lista.

- La memoria es asignada por demanda.