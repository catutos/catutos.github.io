---
layout: post
title: Declaración de Variables
---

Las variables son construcciones de los lenguajes de programación que nos permiten almacenar valores en memoria para utilizarlos luego en operaciones más complejas, y operar sobre ellos.

## Declaración

En Swift, es necesario declarar las variables antes de utilizarlas. Esto es necesario aclararlo, por si venís de un lenguaje de tipado dinámico como puede ser Python. Si tenés experiencia, o conocés Java, C# o C++, esto no debería sorprenderte.

Una variable se puede declarar así

```swift
var nombre: String = "Morita"
```

Podemos separar esta declaración un poco para comprenderla mejor

`var` es la palabra clave del lenguaje que nos permite declarar variables

`nombre` es el nombre de esta variable. A partir de este momento, cada vez que escribamos `nombre`, nos referiremos a esta variable.

`String` es un tipo de datos que nos permite almacenar textos.

`=` es el operador de asignación. Como acabamos de declarar la variable `nombre` que es un `String`, lo que se encuentre a la derecha del `=` va a ser asignado a `nombre` si es un `String`, o generará un error de compilación, en caso de que sea cualquier otro tipo de dato, como `Int` o `Bool`.

`"Morita"`, así es como escribimos valores de tipo `String` en Swift. Las comillas siempre tienen que ser dobles. Las comillas simples no son válidas cuando queremos escribir valores de tipo `String`.

Pero hemos dicho anteriormente que Swift es simple, legible y moderno. Y lo que acabamos de escribir no es precisamente lo que yo llamaría simple, legible y moderno. Veamos como podemos simplificarlo.

Swift implementa una característica de la mayoría de los lenguajes de programación modernos, que es la inferencia de tipos. La anterior sentencia podría ser también escrita del siguiente modo:

```swift
var nombre = "Morita"
```

Es importante notar cómo no es necesario escribir el tipo `String`.

Luego de declarar `nombre`, podemos asignarle otros valores libremente:

```swift
nombre = "Simona" // Ahora nombre tendrá el valor "Simona" en vez de "Morita"
nombre = "" // Ahora nombre será un String vacío
nombre = 12 // ERROR! Estamos intentando asignar un entero a una variable que almacena una cadena de caracteres.
```

## Constantes

Las variables en Swift se declaran de un tipo en particular, y luego pueden cambiar su valor cuantas veces sean necesarias, siempre que estos valores sean del tipo declarado.

Pero esto no es verdad si hablamos de constantes. Veamos:

```swift
let nombre: String = "Morita"
```

O lo que es equivalente:

```swift
let nombre = "Morita"
```

Con esta declaración, hemos creado una constante de tipo `String` que almacena el valor `"Morita"`. La característica que diferencia a las constantes de las variables, es que las variables pueden cambiar de valor cuantas veces sean necesarias, como dijimos anteriormente, pero no así las constantes, que mantendrán su valor hasta que salgan de memoria.

```swift
let nombre = "Morita"
nombre = "Simona" // ERROR! Una constante no puede cambiar su valor luego de que se le fue asignado otro valor previamente.
```

Por lo general, la buena práctica aquí es utilizar constantes por defecto, y variables solo en caso de ser necesario. Esto hará que a la larga el código sea más correcto, y optimizará la velocidad de compilación, entre otras ventajas.