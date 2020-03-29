

# Flexbox

Es dar al contenedor la habilidad de alterar su tamaño, orden y llenar eficientemente el espacio dentro del contenedor. Acomodar el contenido de una caja de manera unidimensional.

![Flexbox](https://rejkowicz.pl/wp-content/uploads/2018/01/koko.jpg)



Implementación de flexbox en un contenedor.

```css
.contenedor {
    display: flex;
}
```



## Propiedades del contenedor



### Propiedad: flex-direction

Define la dirección de los elementos que se encuentran dentro del contenedor y permite el cómo van a estar posicionados, ya sea en columnas o en filas.

```css
.contenedor {
    display: flex;
    flex-direction: column | column-reverse | row | row-reverse;
}
```



### Propiedad: flex-wrap

Por defecto los elementos van a intentar encajar en una línea, esto se puede cambiar con esta propiedad.

```css
.contenedor {
	display: flex;
  	flex-wrap: nowrap | wrap | wrap-reverse;
}
```



### Propiedad: flex-flow

Es un shorthand de flex-wrap y flex-direciton.

```css
.contenedor {
	display: flex;
	flex-flow: <‘flex-direction’> || <‘flex-wrap’>
}

```



### Propiedad: Justify-content

Es la manera que nosotros le especificamos al contenedor para que acomode los elementos que se encuentran dentro de el.

```css
  
.contenedor {
  display: flex;
  justify-content: flex-start | flex-end | center | space-between | space-around | space-evenly | start | end | left | right;
  }

```



### Propiedad: align-items

Es la manera que nosotros le especificamos al contenedor para que acomode los elementos que se encuentran dentro de el.

```css
.contenedor {
	display: flex;
  	align-items: stretch | flex-start | flex-end | center | baseline | first baseline | last baseline | start | end | self-start | self-end;
}
```



### Propiedad: align-content

Alinea las líneas del contenedor cuando hay un espacio adicional en el eje transversal.

Esta propiedad no tiene efecto cuando solo hay una sola línea con elementos.

```css
.contenedor {
  align-content: flex-start | flex-end | center | space-between | space-around | space-evenly | stretch | start | end | baseline | first baseline | last baseline;
}
```



## Propiedades de los hijos



### Propiedad: order

Por defecto los elementos se acomodan respecto a su padre y tiene un valor de 0.

Order  controla el orden en cual se debe aparecer el elemento en el contenedor

```
.elemento {
  order: <numero>;  
}
```



### Propiedad: flex-grow

Define la habilidad de hacer crecer un elemento si es necesario, por defecto los elementos tienen un valor de 0.

En el caso de que todos los elementos tengan un valor igual, el espacio del contenedor será repartido de manera equitativa.

```css
.elemento {
  flex-grow: <numero>;  
}
```



### Propiedad: flex-shrink

Le da la habilidad al elemento de encogerse si es necesario.

Su valor por defecto es de 1.

```css
.elemento {
  flex-shrink: <numero>; 
}
```



### Propiedad: flex-basis

Define el tamaño por defecto de un elemento antes de que el espacio disponible sea distribuido.

```css
.elemento {
  flex-basis: <cantidad> | auto; 
}
```



### Propiedad: flex

Es simplemente un shorthand para flex-grow, flex-shink y flex-basis.

```css
.elemento {
  flex: none | [ <'flex-grow'> <'flex-shrink'>? || <'flex-basis'> ]
}
```



### Propiedad: align-self

Esto permite la sobre escritura de el valor por defecto o el valor establecido por el contenedor con la propiedad align-items para ser cambiada por otra distinta.

```css
.elemento {
  align-self: auto | flex-start | flex-end | center | baseline | stretch;
}
```

