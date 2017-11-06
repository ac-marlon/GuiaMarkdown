<p>La mejor manera de hacerse una idea de la sintaxis de Markdown es simplemente echar un vistazo a un <strong>escrito formateado</strong> como tal.</p><pre><code>

## Título
### Subtítulo

Este es un ejemplo de texto que da entrada a una lista genérica de elementos:

- Elemento 1
- Elemento 2
- Elemento 3

Este es un ejemplo de texto que da entrada a una lista numerada:

1. Elemento 1
2. Elemento 2
3. Elemento 3

Al texto en Markdown puedes añadirle formato como **negrita** o *cursiva* de una manera muy sencilla.
</code></pre><p>Como ves, se cumple perfectamente uno de los <strong>objetivos</strong> para los que Markdown fue diseñado, y es hacer las publicaciones <strong>lo más legibles posible</strong>.</p><p>Otro de los objetivos de Markdown, es que puedas <strong>publicar</strong> los documentos <em>“como están”</em>. No importa si el resultado final que necesitas es <strong>HTML</strong>, un <strong>PDF</strong> o texto en <strong>formato enriquecido</strong> (RTF); ya que siempre podrás obtener estos formatos a través de un conversor, o a través de aplicaciones compatibles con Markdown.</p><h2>

<h2 id="bloque">Elementos de bloque</h2><h3 id="parrafos">Párrafos y saltos de línea</h3><p>Para generar un nuevo párrafo en Markdown simplemente separa el texto mediante  una línea en blanco <strong>(pulsando dos veces intro)</strong></p><p>Al igual que sucede con HTML, <strong>Markdown no soporta dobles líneas en blanco</strong>, así que si intentas generarlas estas se convertirán en una sola al procesarse.</p><p>Para realizar un salto de línea y empezar <strong>una frase en una línea siguiente dentro del mismo párrafo</strong>, tendrás que pulsar <strong>dos veces la barra espaciadora antes de pulsar una vez intro</strong>.</p><p>Por ejemplo si quisieses escribir un poema Haiku quedaría tal que así:</p><p><em>&#8220;Andando con sus patitas mojadas,<br/> el gorrión<br/> por la terraza de madera&#8221;</em></p><p>Donde cada verso tiene <strong>dos espacios en blanco al final</strong>.</p><hr/><h3 id="encabezados">Encabezados</h3><p>Las <code>#</code> <strong>almohadillas</strong> son uno de los métodos utilizados en Markdown para crear encabezados. Debes usarlos añadiendo <strong>uno por cada nivel</strong>.</p><p>Es decir,</p><pre><code>

# Encabezado 1
## Encabezado 2
### Encabezado 3
#### Encabezado 4
##### Encabezado 5
###### Encabezado 6

</code></pre><p>Se corresponde con</p><h1>Encabezado 1</h1><h2>Encabezado 2</h2><h3>Encabezado 3</h3><h4>Encabezado 4</h4><h5>Encabezado 5</h5><h6>Encabezado 6</h6><p>También puedes cerrar los encabezados con el mismo número de almohadillas, por ejemplo escribiendo <code>### Encabezado 3 ###</code>. Pero la única finalidad de esto es un <strong>motivo estético</strong>.</p><p>Existe otra manera de generar encabezados, aunque este método está <strong>limitado a dos niveles</strong>.</p><p>Consiste en <em>subrayar</em> los encabezados con el símbolo <code>=</code> (para el encabezado 1), o con guiones <code>-</code> para el encabezado 2.</p><p>Es decir,</p><pre><code>Esto sería un encabezado 1
===
Esto sería un encabezado 2
—-
</code></pre><p>No existe un número concreto <code>=</code> o <code>-</code> que necesites escribir para que esto funcione, ¡incluso bastaría con uno!</p><hr/><h3 id="citas">Citas</h3><p>Las citas se generar utilizando el carácter <em>mayor que</em> <code>&gt;</code> al comienzo del bloque de texto.</p><pre><code>&gt; Un país, una civilización se puede juzgar por la forma en que trata a sus animales.  — Mahatma Gandhi
</code></pre><blockquote><p> Un país, una civilización se puede juzgar por la forma en que trata a sus animales.  — Mahatma Gandhi</p></blockquote><p>Si la cita en cuestión se compone de <strong>varios párrafos</strong>, deberás añadir el mismo símbolo <code>&gt;</code> al comienzo de cada uno de ellos.</p><pre><code>&gt; Creo que los animales ven en el hombre un ser igual a ellos que ha perdido de forma extraordinariamente peligrosa el sano intelecto animal.

&gt; Es decir, que ven en él al animal irracional, al animal que ríe, al animal que llora, al animal infeliz. — Friedrich Nietzsche
</code></pre><blockquote><p> Creo que los animales ven en el hombre un ser igual a ellos que ha perdido de forma extraordinariamente peligrosa el sano intelecto animal.</p><p> Es decir, que ven en él al animal irracional, al animal que ríe, al animal que llora, al animal infeliz. — Friedrich Nietzsche</p></blockquote><p>Incluso puedes concatenar varios <code>&gt;&gt;</code> para crear <strong>citas anidadas</strong>.</p><pre><code>&gt; Esto sería una cita como la que acabas de ver.
&gt; 
&gt; &gt; Dentro de ella puedes anidar otra cita.
&gt; 
&gt; La cita principal llegaría hasta aquí. 
</code></pre><blockquote><p> Esto sería una cita como la que acabas de ver.</p><blockquote><p> Dentro de ella puedes anidar otra cita.</p></blockquote><p> La cita principal llegaría hasta aquí.</p></blockquote><p>Recuerda separar los saltos de línea con <code>&gt;</code>, o <code>&gt;&gt;</code> si te encuentras dentro de la cita anidada; para crear párrafos dentro del mismo bloque de cita.</p><hr/><h3 id="listas">Listas</h3><p>A diferencia de lo que ocurre en HTML, generar listas en Markdown es tremendamente sencillo. Puedes encontrarte con dos tipos.</p><h4>Listas desordenadas</h4><p>Para crear <strong>listas desordenadas</strong> utiliza <strong><code>*</code> asteriscos, <code>-</code> guiones, o <code>+</code> símbolo de suma</strong>.</p><pre><code>- Elemento de lista 1
- Elemento de lista 2
* Elemento de lista 3
* Elemento de lista 4
+ Elemento de lista 5
+ Elemento de lista 6
</code></pre><p>Da igual qué elemento escojas, incluso puedes intercambiarlos. Todos se verán igual al procesarse.</p><ul><li>Elemento de lista 1</li><li>Elemento de lista 2</li><li>Elemento de lista 3</li><li>Elemento de lista 4</li><li>Elemento de lista 5</li><li>Elemento de lista 6</li></ul><p>Para generar <strong>listas anidadas</strong> dentro de otras, simplemente tendrás que añadir **cuatro espacios en blanco antes del siguiente <code>*</code>, <code>-</code> o <code>+</code>.</p><pre><code>- Elemento de lista 1
- Elemento de lista 2
    - Elemento de lista 3
    - Elemento de lista 4
        - Elemento de lista 5
        - Elemento de lista 6
</code></pre><ul><li>Elemento de lista 1</li><li>Elemento de lista 2<ul><li>Elemento de lista 3</li><li>Elemento de lista 4<ul><li>Elemento de lista 5</li><li>Elemento de lista 6</li></ul></li></ul></li></ul><h4>Listas ordenadas</h4><p>Para crear listas ordenadas debes utilizar la sintaxis de tipo: <em>&#8220;número.&#8221;</em> <code>1.</code>. Al igual que ocurre con las listas desordenadas, también podrás <strong>anidarlas o combinarlas</strong>.</p><pre><code>1. Elemento de lista 1
2.  Elemento de lista 2
    - Elemento de lista 3
    - Elemento de lista 4
        1. Elemento de lista 5
        2. Elemento de lista 6
</code></pre><ol><li>Elemento de lista 1</li><li>Elemento de lista 2<ul><li>Elemento de lista 3</li><li>Elemento de lista 4<ol><li>Elemento de lista 5</li><li>Elemento de lista 6</li></ol></li></ul></li></ol><hr/><h3 id="codigosbloque">Códigos de bloque</h3><p>Si quieres crear un bloque entero que contenga código. Lo único que tienes que hacer es <strong>encerrar dicho párrafo entre dos líneas formadas por tres <code>~</code> virgulillas</strong>.</p><p>Tal que así:<br/> <script async src="//pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><br/> <br/> <ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-1602196224032955" data-ad-slot="8270314841" data-ad-format="auto"></ins></p><p><script>(adsbygoogle=window.adsbygoogle||[]).push({});</script></p><pre><code>~~~
Creando códigos de bloque.
Puedes añadir tantas líneas y párrafos como quieras.  
~~~</code></pre><p>De esta forma, obtendrás el siguiente resultado:</p><pre><code>Creando códigos de bloque.
Puedes añadir tantas líneas y párrafos como quieras.
</code></pre><hr/><h3 id="reglas">Reglas horizontales</h3><p>Las reglas horizontales se utilizan para separar secciones de una manera visual. Las estás viendo constantemente en este artículo ya que las estoy utilizando para separar los diferentes elementos de sintaxis de Markdown.</p><p>Para crearlas, en una línea en blanco deberás incluir <strong>tres de los siguientes elementos</strong>: asteriscos, guiones, o guiones bajos.</p><p>Es decir</p><pre><code>***
---
___
</code></pre><p>También puedes separarlos mediante un espacio en blanco por pura estética.</p><pre><code>* * *
- - -
_ _ _
</code></pre><hr/><h2 id="linea">Elementos de línea</h2><h3 id="enfasis">Énfasis (negritas y cursivas)</h3><p>Markdown utiliza <strong>asteriscos</strong> o <strong>guiones bajos</strong> para enfatizar.</p><p>Simplemente tendrás que envolver palabras o textos en éstos símbolos para conseguir <em>cursivas</em> o <strong>negritas</strong>.</p><table><thead><tr><th>Markdown</th><th>Resultado</th></tr></thead><tbody><tr><td>&#42;cursiva*</td><td><em>cursiva</em></td></tr><tr><td>&#95;cursiva_</td><td><em>cursiva</em></td></tr><tr><td>&#42;*negrita**</td><td><strong>negrita</strong></td></tr><tr><td>&#95;_negrita__</td><td><strong>negrita</strong></td></tr></tbody></table><p>Por supuesto si quieres utilizar los dos tipos de énfasis no tienes más que <strong><em>combinar la sintaxis</em></strong>, envolviendo la palabra entre tres asteriscos o tres guiones bajos.</p><table><thead><tr><th>Markdown</th><th>Resultado</th></tr></thead><tbody><tr><td>&#42;**cursiva y negrita***</td><td><strong><em>cursiva y negrita</em></strong></td></tr><tr><td>&#95;__cursiva y negrita___</td><td><strong><em>cursiva y negrita</em></strong></td></tr></tbody></table><hr/><h3 id="links">Links o enlaces</h3><p>Añadir enlaces a una publicación, más que común, hoy en día es algo <strong>casi obligatorio</strong>. Con Markdown tendrás varias formas de hacerlo.</p><h4>Links o enlaces en línea</h4><p>Son los enlaces de toda la vida. Como su nombre indica, se encuentran en línea con el texto.</p><p>Se crean escribiendo la palabra o texto enlazada entre <code>[]</code> <strong>corchetes</strong>, y el link en cuestión entre <code>()</code> <strong>paréntesis</strong>.</p><table><thead><tr><th>Markdown</th><th>Resultado</th></tr></thead><tbody><tr><td>&#091;enlace en línea](http://www.limni.net)</td><td><a href="http://www.limni.net">enlace en línea</a></td></tr></tbody></table><h4>Links o enlaces como referencia</h4><p>La desventaja del método anterior, es que si utilizas links demasiado complejos o largos pueden dificultarte la lectura de tu texto.</p><p>Para solucionarlo y crear tu contenido de una manera más ordenada puedes generar enlaces de referencia.</p><p>Esto quiere decir que en tu texto enlazarás <strong><em>palabras o códigos concretos</em></strong> (formados por letras y/o números), que en otro lugar más apartado de tu documento tendrás definidos como determinadas URL.</p><pre><code>[nombre que quieres darle a tu enlace][nombre de tu referencia]

[nombre de tu referencia]: http:www.tuenlace.com
</code></pre><p>Esto se ve más claro con un ejemplo.</p><pre><code>Me llamo Javier Cristóbal y tengo un blog sobre [productividad mac][blog].

En dicha [web][blog] recopilo artículos sobre todo lo relacionado con automatización, gestión y eficiencia.

[blog]: http://limni.net/blog/
</code></pre><p>La referencia <code>[blog]</code> puede estar incluida en cualquier parte del documento, así puedes organizarte mejor y de una manera más <em>limpia</em>, recopilando todas tus referencias en un mismo lugar.</p><p>Además como ves a continuación, esta referencia <strong>no se incluye en el resultado final</strong>, sino que desaparece.</p><p><em>&#8220;Me llamo Javier Cristóbal y tengo un blog sobre <a href="http://limni.net/blog/">productividad mac</a>.</em></p><p><em>En dicha <a href="http://limni.net/blog/">web</a> recopilo artículos sobre todo lo relacionado con automatización, gestión y eficiencia.&#8221;</em></p><h4>Links automáticos</h4><p>Verás esta forma <strong>dentro de elementos varios</strong>: <a href="#linkauto">links automáticos</a></p><hr/><h3 id="codigo">Código</h3><p>En según que tipo de publicaciones (sobre todo las de carácter técnico), necesitarás añadir pequeñas secciones donde mostrar código de otro lenguaje, atajos de teclado, o demás contenido que no debería ser tratado como tal.</p><p>Para ello tienes disponible dos alternativas.</p><h4>Código puro <code>&lt;code&gt;</code></h4><p>La forma más sencilla de escribir código en Markdown es envolver el texto entre dos comillas sencillas <code>`</code>. Esto se corresponde con la etiqueta HTML <code>&lt;code&gt;</code></p><pre><code>`Esto es una línea de código`
</code></pre><p>Se verá como <code>Esto es una línea de código</code>.</p><p>Como ves, es muy útil para introducir código dentro de la misma línea o párrafo, algo que no permite el método siguiente.</p><h4>Texto preformateado <code>&lt;pre&gt;</code></h4><p>La otra manera de añadir código en Markdown es <strong>comenzar el párrafo con cuatro espacios en blanco</strong>. Esto se corresponde con la etiqueta HTML <code>&lt;pre&gt;</code></p><pre><code><br/>    Esto es una línea de código

</code></pre><p>Se convierte en</p><pre><code>Esto es una línea de código
</code></pre><p>Ojo, ¡estos espacios deberás incluirlos <strong>en cada línea que escribas</strong>! Para añadir código en bloque es mejor utilizar la sintaxis que viste anteriormente: <a href="#codigosbloque">códigos de bloque</a>.</p><h3 id="imagenes">Imágenes</h3><p>Insertar una imagen con Markdown se realiza de una manera prácticamente idéntica a insertar <a href="#links">links</a>.</p><p>Solo que en este caso, deberás añadir un símbolo de <strong><code>!</code> exclamación</strong> al principio y el <strong>enlace</strong> no será otro que <strong>la ubicación de la imagen</strong>.<br/> <script async src="//pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><br/> <br/> <ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-1602196224032955" data-ad-slot="8270314841" data-ad-format="auto"></ins></p><p><script>(adsbygoogle=window.adsbygoogle||[]).push({});</script></p><pre><code><br/>![Texto alternativo](/ruta/a/la/imagen.jpg)

</code></pre><p>El <em>texto alternativo</em> es lo que se mostraría si la carga de la imagen fallase.</p><p>También podrás añadir un <strong>título alternativo</strong> entrecomillándolo al final de la ruta. Esto sería el título mostrado al dejar el cursor del ratón sobre la imagen.</p><pre><code>![Texto alternativo](/ruta/a/la/imagen.jpg "Título alternativo")
</code></pre><p>Ya que al añadir imágenes también estás tratando con URLs, puedes utilizar el método que viste anteriormente para <strong>incluir links mediante referencias</strong>, solo que en este caso <strong>los enlaces de referencia serán aquellos donde se encuentre tu imagen</strong>.</p><pre><code>De esta forma podrías insertar una imagen
![nombre de la imagen][img1]

O dos, sin ensuciar tu espacio de escritura.
![nombre de la imagen2][img2] 

[img1]: /ruta/a/la/imagen.jpg "Título alternativo"
[img2]: /ruta/a/la/imagen2.jpg "Título alternativo"
</code></pre><hr/><h2 id="varios">Elementos varios</h2><h3 id="linkauto">Links automáticos</h3><p>Cuando viste los <a href="#links">tipos de links</a> te comenté que había un tipo más: los automáticos.</p><p>Estos son necesarios cuando lo que quieres es <strong>mostrar una URL completa</strong>, y no un enlace enmascarado bajo una palabra o frase como ocurre con los links en línea.</p><p>Para generar links automáticos tan solo tendrás que rodearlos con los símbolos <code>&lt; &gt;</code></p><pre><code>&lt;http://www.limni.net&gt;
</code></pre><p><a href="http://www.limni.net">http://www.limni.net</a></p><hr/><h3 id="omitir">Omitir Markdown</h3><p>Si has llegado hasta aquí es probable que te estés preguntando <strong>cómo he conseguido escribir ciertos símbolos</strong> como &#42; asteriscos o &#95; guiones bajos, sin que Markdown los interprete para convertirlos en negritas, cursivas&#8230;</p><p>Esto es muy sencillo, ya que en este lenguaje existe un elemento estrella para especificar que todo lo que escribas a continuación, no se interprete como Markdown.</p><p>Se trata de la barra invertida <code>\</code>.</p><p><strong>Escribiéndola justo delante</strong> de cualquiera de los elementos  que verás a continuación, los mismos <strong>no tendrán efecto</strong> a la hora de convertirse en negritas, cursivas, links&#8230;</p><pre><code>\  barra invertida
`  acento invertido
*  asterisco
_  guión bajo
{} llaves
[] corchetes
() paréntesis
#  almohadilla
+  símbolo de suma
-  guión
.  punto
!  exclamación
