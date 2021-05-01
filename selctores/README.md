# Selectores

Los selectores definen a que elemento se le aplicará un conjunto de reglas CSS (El estilo). Existen cinco tipos de seletores.

### Selector Universal
Se denota con un asterisco `*` y se aplica a todos los elementos del documento.

```
/* Selects all elements */
* {
  color: green;
}
 ```

### Selector de tipo
Se aplica a todos los elementos en los que su etiqueta HTML coinsida con el valor del selctor.

En este caso la regla se aploca a todos los elementos `<p>...</p>` dentro del documento.

### Selector de clase
Se aplica a todos los elementos que tengan el atrubuto `class` especificado, y se denota con un punto `.classname`.

### Selector de ID
Se aplica a un elemento basándose en el valor su atributo `id`, se denota con una almohadilla o numeral `#idvalor`.
(El `id` para cada elemento debe ser único)

### Selector de atributo
Se aplica a los elementos en los que un determinado atributo y su valor coinsidan con el selector, se denota entre corchetes cuadrados `[atributo = valor]`.
