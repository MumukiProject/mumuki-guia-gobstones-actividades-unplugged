Ya aprendimos que un **algoritmo** es una secuencia de pasos _ordenada_. Pero... ¿Qué pasa si cambiamos el orden de los pasos?

A continuación tenemos tres programas muy similares entre sí. Probalos uno a la vez para ver si el resultado es el mismo.

``` gobstones
program {
Mover(Norte)
Mover(Este)
Poner(Azul)
}

program {
Mover(Este)
Mover(Norte)
Poner(Azul)
}

program {
Mover(Norte)
Poner(Azul)
Mover(Este)
}
```
