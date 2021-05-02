# Selectores

Los selectores definen a que elemento se le aplicará un conjunto de reglas CSS (El estilo). Existen cinco tipos de seletores.

### Selector Universal

Se denota con un asterisco `*` y se aplica a todos los elementos del documento.


_Ejemplo_

```
* {
  color: green;
  backgroun-color: black;
}
```

Este bloque de codigo hará que todos los textos que se encoentren en el documento se muestren de color verde y que cada elemento tenga fondo negro.

### Selector de tipo

Se aplica a todos los elementos en los que su etiqueta HTML coinsida con el valor del selctor.


_Ejemplo:_

```
p{
  color: red;
}
```

En este caso la regla se aploca a todos los elementos `<p>...</p>` dentro del documento.

### Selector de clase

Se aplica a todos los elementos que tengan el atrubuto `class` especificado, y se denota con un punto `.classname`.


_Ejemplo:_
Codigo en HTML

```
<h2 class="titulo-2">
    Este es un tutulo 2
</h2>
```
Codigo CSS
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
Codigo en HTML

```
<p id="parrafo">
    Esto es un parrafo 
</p>
```
Codigo CSS
```
#parrafo{
  color: blue;
  font-size: 20px;
}
```

### Selector de atributo

Se aplica a los elementos en los que un determinado atributo y su valor coinsidan con el selector, se denota entre corchetes cuadrados `[atributo = valor]`.


_Ejemplo:_
Codigo en HTML

```
<a href="#">Esto es un ancla</a>
```
Codigo CSS
```
[href='#']{
  background-color: violet;
}
```