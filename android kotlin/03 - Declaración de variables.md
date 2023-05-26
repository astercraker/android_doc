
Kotlin utiliza dos palabras clave diferentes para declarar variables: `val` y `var`.

- Usa `val` para una variable cuyo valor no cambia nunca. No puedes volver a asignar un valor a una variable que se declaró mediante `val`.
- Utiliza `var` para una variable cuyo valor puede cambiar.

En el siguiente ejemplo, `count` es una variable de tipo `Int` asignada a un valor inicial de `0`:

``` kotlin
var count: Int = 0
```

`Int` es un tipo que representa un número entero, uno de los muchos tipos numéricos que se pueden representar en Kotlin. Del mismo modo que con otros lenguajes, también puedes utilizar `Byte`, `Short`, `Long`, `Float` y `Double` según tus datos numéricos.

La palabra clave `var` quiere decir que puedes volver a asignar valores a `count` según sea necesario. Por ejemplo, puedes cambiar el valor de `count` de `10` a `15`:

``` kotlin
var count: Int = 10
count = 15
```
Sin embargo a veces queremos variables que no puedan cambiar, para esos usamos *val*

``` kotlin
val languajeName: String = "Kotlin"
```

[Tipos de Datos kotlin]([¿Cuáles son los tipos básicos en Kotlin? (keepcoding.io)](https://keepcoding.io/blog/cuales-son-los-tipos-basicos-en-kotlin/#:~:text=En%20general%2C%20podemos%20decir%20que%20existen%205%20tipos,2%20Numbers.%203%20Boolean.%204%20Strings.%205%20Array.))


