---
layout: post
title: Comentarios
---

Los comentarios son textos incluidos en el código de un programa que el compilador simplemente ignora, y que se utilizan con propósitos explicativos.

En Swift, los comentarios son muy similares a los comentarios de C++ o Java.

## Comentarios de una línea

Los comentarios de una única línea se escriben luego de una doble barra `//`. El compilador simplemente ignora todo lo que vaya después de estas dos barras, permitiendo agregar documentación.

```swift
print("Hola Mundo!") // Esto es un comentario
// En Swift, los comentarios de una única línea
// se escriben con dos barras al comienzo del comentario.
```

## Comentarios de varias líneas

Los comentarios de varias líneas, o multilínea se encierran entre /* y */

```swift
print("Hola Mundo!")
/*
En Swift, los comentarios multilínea se encierran entre estos caracteres
Aquí dentro podemos escribir cuantas
líneas queramos
*/
```

## Pro-Tip

Para comentar/descomentar rápidamente un fragmento de código, podemos usar el atajo de teclado `Cmd + /`, de esta manera, todo lo seleccionado bajo el cursor será comentado, o descomentado en caso de que ya estuviera comentado previamente.