---
layout: post
title: Introducción a Swift
---

Bienvenido al mundo del desarrollo iOS! Como verás en muy poco tiempo, este es un mundo inmenso. Hay muchísimas cosas por aprender antes de crear el nuevo Instagram, el nuevo Uber o el nuevo Facebook.

El primer tema que debemos dominar antes de incursionarnos en tareas más complejas es el lenguaje de programación con el que desarrollamos aplicaciones en iOS, y es el lenguaje **Swift**.

## Algunas características

Swift es un lenguaje de programación moderno, a comparación del anterior lenguaje de programación dominante en el desarrollo iOS, Objective-C, Swift es mucho más parecido a los lenguajes que hoy en día están dominando la industria.

Algunas características de Swift:

### Tiene tipado estático

Esto quiere decir que las variables en Swift son declaradas de un tipo, y no cambian su tipo de dato en el resto de la ejecución de un programa.

Por ejemplo:

```swift
var a: Int = 5 // a es una variable entera con valor 5
a = 10 // Esto está permitido, porque le asignamos un valor entero a una variable entera
a = false // ERROR! No podemos asignarle un valor booleano a una variable entera
```

Esta característica brinda mayor seguridad a la hora de programar, asegurándonos de que las variables son del tipo que nosotros estamos esperando.

### Fácil de aprender, difícil de perfeccionar

El diseñador del lenguaje Swift, el genial [Chris Lattner](https://en.wikipedia.org/wiki/Chris_Lattner), diseñó el lenguaje alrededor de una premisa fundamental: Tiene que ser fácil de comenzar a utilizarlo, pero no por ese debe limitar sus capacidades (progressive disclosure).
Swift es un lenguaje realmente placentero de utilizar, uno puede comenzar a usar Swift luego de algunas breves lecciones, y pasarse años perfeccionando luego su uso.
Es un gran primer lenguaje de programación en mi opinión, y es realmente bello y expresivo cuando se usa en escenarios complejos.

### Es multiparadigma

No me quiero meter demasiado en este punto todavía, pero ninguna introducción a Swift estaría completa sin mencionar su capacidad de ser utilizado en paradigmas de programación diversos. Esto quiere decir que uno podría utilizar Swift para programación orientada a objetos (de nuevo, luego lo veremos más en profundidad), en programación funcional (aunque no de modo estricto), en programación orientada a protocolos (una característica avanzada del lenguaje), o simplemente en programación procedural clásica.

### Es moderno

Swift tiene todo lo que uno buscaría en un lenguaje de programación hoy en día, por ejemplo:

- Inferencia de tipos
- Funciones como tipo de dato
- Genéricos
- Tipos de datos de valor (Value types)
- Pattern matching

### Pone el foco en la legibilidad

Swift es extraordinariamente expresivo. Y este es el punto más importante por el que es mi lenguaje de programación favorito. Uno puede realizar tareas muy complejas, y puede seguir leyendo el código con facilidad si es que fue cuidadoso y prolijo. Swift permite realizar abstracciones realmente poderosas.
Swift tiene la ventaja, además, de que es muy rápido. Su foco en la legibilidad no significa que se comprometa su performance.

### Es de código abierto

A partir del año 2015, Swift es desarrollado activamente por la comunidad. Esto quiere decir que si te interesa el lenguaje, y tenés tiempo y ganas, podés darles una mano a quienes desarrollan Swift, para ayudar a mejorar el lenguaje.