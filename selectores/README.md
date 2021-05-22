# Selectores

Los selectores definen a que elemento se le aplicará un conjunto de reglas CSS (El estilo). Existen cinco tipos de selectores.

### Selector Universal

Se denota con un asterisco `*` y se aplica a todos los elementos del documento.


_Ejemplo_

```
* {
  color: green;
  backgroun-color: black;
}
```

Este bloque de código hará que todos los textos que se encuentren en el documento se muestren de color verde y que cada elemento tenga fondo negro.

### Selector de tipo

Se aplica a todos los elementos en los que su etiqueta HTML coincida con el valor del selector.


_Ejemplo:_

```
p{
  color: red;
}
```

En este caso la regla se aplica a todos los elementos `<p>...</p>` dentro del documento.

### Selector de clase

Se aplica a todos los elementos que tengan el atributo `class` especificado, y se denota con un punto `.classname`.


_Ejemplo:_
Código en HTML

```
<h2 class="titulo-2">
    Este es un tutulo 2
</h2>
```
Código CSS
```
.titulo-2{
  color: yellow;
  background: black;
}
```

### Selector de ID

Se aplica a un elemento basándose en el valor su atributo `id`, se denota con una almohadilla o numeral `#idvalor`.
(El `id` para cada elemento debe ser único)


_Ejemplo:_
Código en HTML

```
<p id="parrafo">
    Esto es un parrafo 
</p>
```
Código CSS
```
#parrafo{
  color: blue;
  font-size: 20px;
}
```

### Selector de atributo

Se aplica a los elementos en los que un determinado atributo y su valor coincidan con el selector, se denota entre corchetes cuadrados `[atributo = valor]`.


_Ejemplo:_
Código en HTML

```
<a href="#"> Esto es un ancla </a>
```
Código CSS
```
[href='#']{
  background-color: violet;
}
```
***

| Anterior                   | Siguiente                     |
|----------------------------|-------------------------------|
| [¿Cómo agregar CSS a un proyecto?](/como_agregar_css/) | [Combinadores](/combinadores/)|