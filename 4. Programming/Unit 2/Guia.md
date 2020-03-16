# LISP

Lenguaje de programación con notación prefija

Programación funcional : utiliza un paradigma programación declarativa.

Incluye una interfaz interactiva llamada top level.

Utilizado en:

- IA

- Robotica

- Demostracion de teoremas

bucles

---

(if condicion

    consecuencia

    alternativa

)

---

## Funciones

Una función en lisp tiene la siguiente syntaxis

```lisp
(nombreDeLaFuncion ParametrosAUtilizar)
```

Ejemplo

```lisp
(+ 2 3)
```

#### Definir funciones

Syntaxis

```
(defun nombreDeLaFuncion( argumento )
    "Documentacion de la funcion"
    (argumento)
)
```

---

## Listas

Una lista vacía es igual a NIL, por lo tanto:

() == NIL

#### Definir una lista

```lisp
(setf miLista '(elemento1 elemento2))
```

## 

### Funciones de una lista

**Acceso a un elemento N**

Se puede utilizar cualquiera de las siguientes funciones predeterminadas:

- First o CAR

- Second

- Third

- nth #

- CDR o REST

**Ordenamiento**

- ()

**Inforación**

- Length

**Manipulacion**

- Reverse
