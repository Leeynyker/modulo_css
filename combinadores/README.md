# Combinadores
Nos permiten combinar múltiples selectores de manera que proporcionan una relación útil entre ellos. Tenemos cuatro combinadores.


### Hermano cercano 
Se aplica a los elementos cercanos al que se designa como principal. Se establece con un signo mas `+` entre los elementos.

```
div + p{

}
```

### Hermano general
Se aplica a los elementos cercanos de manera general con el mismo contenedor. se establece con una virgulilla `~` entre los elementos.

```
div ~ p{

}
```

### Hijo
Se aplica a el hijo directo del elemento designado como principal, se denota con un signo de maryor que `>` entre los elementos.

```
div > p{

}
```

### Descendiente
Se aplica a todos los elementos internos del mismo tipo dfentro de un contenedor.

```
div p{

}
```
***

| Anterior                   | Siguiente                     |
|----------------------------|-------------------------------|
| [Selectores](/selectores/) | [Pseudoclases](/pseudos/)|
