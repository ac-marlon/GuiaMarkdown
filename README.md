Los caracteres que serían interpretados por Markdown como comandos de formateado se interpretan literalmente si se precede por una barra invertida; por ejemplo la secuencia '\*' mostraría un asterisco en lugar de empezar una sección de texto enfatizado. Un bloque de HTML crudo no se verá alterado por Markdown, pero los comandos de Markdown insertados dentro de un elemento de bloque de HTML crudo no serán procesados.

Saltos de línea: Los saltos de línea se generan cuando se encuentran dos espacios juntos

"Quien fue a sevilla,  
perdió su silla"

Encabezados: Los encabezados se generan cuando se encuentra una almohadilla antes de texto

# Encabezado h1 
## Encabezado h2
### Encabezado h3
#### Encabezado h4
##### Encabezado h5
###### Encabezado h6

Citas: Para citar solo es necesario escribir una cuña antes del texto

> La vida es muy corta para aprender Alemán. -Tad Marburg

Texto con énfasis: Agregar un asterisco para cursiva y dos para negrita

 *énfasis* (cursiva)
 **énfasis fuerte** (negrita)
 
Código: Se utiliza el acento grave para identificar código, y corchetes para identificar el lenguaje de programación

 `Código`
 ``` [language]
 Código en 
 varias líneas
 ```
 
Listas:

 * Un elemento en una lista no ordenada
 * Otro elemento en una lista
 1. Elemento en una lista enumerada u ordenada.
 2. Otro elemento
 
Enlaces:

 [Texto del enlace aquí](https://github.com/ "Título del enlace")
