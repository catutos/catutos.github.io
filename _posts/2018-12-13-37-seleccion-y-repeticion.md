---
layout: post
title: Estructuras de selección y repetición
---

Llamamos **estructuras de selección** a las construcciones del lenguaje que nos permiten ejecutar un determinado código u otro según una serie de condiciones.
Llamamos **estructuras de repetición** a las construcciones del lenguaje que nos permiten ejecutar un determinado código mientras una serie de condiciones resulten verdaderas.

Lo que acabo de decir es totalmente cierto y es una definición concisa, pero no ayuda demasiado a simple vista, no nos dice demasiado. Pasemos a ejemplos más prácticos.

## Estructuras de selección

¿Por qué usaríamos estructuras de selección? Creo que es más facil con un ejemplo.

Supongamos que mi gata, Morita, se enferma. Al llevarla al veterinario, el mismo consulta en un programa informático cuál es la dosis de medicación que debe administrársele a la minina según su peso.
La fórmula es la siguiente. Si el gato pesa más de 2 kilogramos, una pastilla cada 12 horas. Si el gato pesa 2 kilogramos o menos, media pastilla cada 12 horas.

### if / else

Este es el escenario perfecto para utilizar la primera estructura de selección que veremos: **if/else**. Comencemos con el ejemplo:

```swift
let weight = 1.5

if weight > 2 { // Si el peso es mayor a 2 kilogramos. NO INCLUYE el valor 2
    print("Una pastilla cada 12 horas")
} else { // En cualquier otro caso (2 kilogramos o menos)
    print("Media pastilla cada 12 horas")
}
```

Lo primero que vas a notar, si es que venís de otro lenguaje de programación como Java, C# o C++, es que la condición no se encuentra encerrada entre paréntesis. Esto es así porque los paréntesis, al igual que el punto y coma, **son opcionales**.

Es decir, es lo mismo escribir esto en Swift:

```swift
if weight > 2 {
    // ...
}
```

que escribir esto:

```swift
if (weight > 2) {
    // ...
}
```

Además, la parte del `else` es opcional también. Puede o no haber un bloque de código que se ejecute al no cumplirse la condición del `if`.

### Secuencia de if/else

### Guard

### Switch

## Estructuras de repetición

### for-in

### while

### do/while

### Cláusula where