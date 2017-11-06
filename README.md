# GuiaMarkdown
Guías de sintaxis y ejemplos de aplicación de Markdown

<!DOCTYPE html>
<html class="no-js" lang="en">
<head>
	<meta charset="utf-8">
	<meta http-equiv="X-UA-Compatible" content="IE=edge">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<meta name="twitter:site" content="@spinesme">
	<meta property="og:title" content="Sintaxis de Markdown"/>
	<meta name="google" content="notranslate" />

	<title>Sintaxis de Markdown</title>
	
	<meta name="description" content="Markdown es un lenguaje de marcado de texto plano que te permite añadir estilo, imágenes y enlaces a un simple documento de texto. Puedes usar Markdown para ...">
	<meta property="og:description"	content="Markdown es un lenguaje de marcado de texto plano que te permite añadir estilo, imágenes y enlaces a un simple documento de texto. Puedes usar Markdown para ..."/>
	
	
	<meta name="keywords" content="markdown, formato, estilos, imagenes, imágenes, negrita, cursiva, italica, itálica, enlaces, links">
	

	

	

	


	
	<link rel="alternate" hreflang="en" href="/help/markdown/syntax/" />
	

	<link type="text/css" rel="stylesheet" href="/resources/vendor/foundation.min-eb2af196376a03048fd28939f51272b43a1f2347885c355cb1982e53b1ed05d7.css">
	<link type="text/css" rel="stylesheet" href="/resources/site-f98a4da41a71b85addb0886601659f26b1af012440fc2de80f80de8419ca02bc.css">
	<link type="text/css" rel="stylesheet" href="/resources/animations-8c8d29812b9e9abaf0c8eb2752929db7c108e9e62bdccc931ad3884ede5605de.css">
	<link type="text/css" rel="stylesheet" href="/resources/vendor/cookieslaw-11b324f457504e5a4d7dc1ebbfc9e588021658085f24877bc533c50154128b7c.css">

	<link rel="icon" type="image/png" href="/img/favicon-master.png"/>

	
	
<meta property="og:image" content="https://spines.me/img/es-share-help.png"/>
<meta name="twitter:card" content="summary_large_image">
<meta name="twitter:title" content="Spines">
<meta name="twitter:description" content="Aprende más. Consigue tus objetivos. Lleva siempre tus ideas contigo.">
<meta name="twitter:image:src" content="https://spines.me/img/es-share-help.png">




	<script src="//code.jquery.com/jquery-1.11.3.min.js"></script>

<!-- Flex support for IE 10 and bellow -->
	<script type="text/javascript" src="/resources/vendor/flexibility-42ba66fff871b98aee932d41c50ecacb885efd8ca22b164cd3c4e77f1b37c672.js"></script>
	<script type='text/javascript'>
	window.onload=function(){
		flexibility(document.body);
	}
	</script>
	<!-- end -->

	

	<script type="text/javascript" src="/resources/ga-3a80c9d0b0604e763e126e6ae323349c6829d85e39aa9b191b57920137a16a21.js"></script>

</head>

<body>
	<!-- Google Tag Manager (noscript) -->
	<noscript><iframe src="https://www.googletagmanager.com/ns.html?id=GTM-T9BX87H"
	height="0" width="0" style="display:none;visibility:hidden"></iframe></noscript>
	<!-- End Google Tag Manager (noscript) -->
<script type="application/ld+json">
{
  "@context": "http://schema.org",
  "@type": "techArticle",
  "mainEntityOfPage": {
    "@type": "WebPage",
    "@id": "https://spines.me/es/help/markdown/syntax/"
  },
  "headline": "Sintaxis de Markdown",
  "image": {
    "@type": "ImageObject",
    "url": "https://spines.me/img/logos/spines_icon_small.png",
    "height": 400,
    "width": 300
  },
  "datePublished": "2016-05-06 00:00:00 +0000",
  "dateModified": "2017-10-27 15:07:48 +0000",
  "articleBody": "Markdown es un lenguaje de marcado de texto plano que te permite añadir estilo, imágenes y enlaces a un simple documento de texto. Puedes usar Markdown para dar formato al texto de tus ideas en Spines.

Markdown es muy fácil de aprender y usar. Vamos a repasar algunas carácterísticas básicas pero muy útiles.

Titulares

Hay seis tamaños de titulares (llamados titular 1 a 6) disponibles en Markdown. Indicas que una frase es un titular con el prefijo #, de la siguiente manera:

# Esto es un titular de tamaño 1

El ejemplo anterior se visualiza así:


  Esto es un titular de tamaño 1


El número de caracteres # que escribes se corresponde con el tamaño de titular mostrado:

## Esto es un titular de tamaño 2
Este titular es de tamaño 3
Un titular más pequeño, de tamaño 4
Este solo es de tamaño 5
El de tamaño 6 es el más pequeño
&lt;/code&gt;

translates to:


  Esto es un titular de tamaño 2
  Este titular es de tamaño 3
  Un titular más pequeño, de tamaño 4
  Este solo es de tamaño 5
  El de tamaño 6 es el más pequeño


Párrafos

Normalmente, el texto escrito en Markdown automáticamente se inserta en párrafos. Para crear un nuevo párrafo, deja una línea en blanco antes de escribir de nuevo.

Esta frase automáticamente crea un párrafo en Markdown.
Esta frase pertenece al mismo párrafo aunque está en una nueva línea.

Esta frase ha creado un nuevo párrafo.


Negrita

Para señalar una palabra como negrita, usa asteriscos. Escribir:

La última palabra es **negrita**.

da como resultado:


  La última palabra es negrita.


Cursiva

Dos guiones bajos delimitando una palabra indican cursiva:

Escribe en _cursiva_ para dar énfasis.

Esto genera:


  Escribe en cursiva para dar énfasis.


Puedes combinar diferentes marcadores en la misma frase o palabra:

Usando **negrita** y _cursiva_ para _**énfasis extremo**_.

crea el siguiente pero no particularmente recomendable ejemplo:


  Usando negrita y cursiva para énfasis extremo.


Tachado

Para resaltar una corrección, puedes añadir dos tildes antes y después de la palabra o frase:

Ella ~~nació~~ creció en Alemania.

será mostrado como:


  Ella nació creció en Alemania.


Enlaces

Una dirección web (URL) se convierte automáticamente en un enlace interactivo:

http://spines.me

aparecerá como:


  http://spines.me


Puedes crear enlaces HTML más complejos con la siguiente sintaxis:

[The New York Times](http://www.nytimes.com) es un periódico.

devuelve:


  
    The New York Times es un periódico.
  


También puedes escribir enlaces en dos estilos con formato de referencia:

[The New York Times][1] es un periódico.
[1]: http://www.nytimes.com

[The New York Times] es un periódico.
[The New York Times]: http://www.nytimes.com


y los dos ejemplos producirán el mismo resultado:


  The New York Times es un periódico.


Imágenes

De la misma manera, puedes incorporar imágenes de otras páginas web. Por ejemplo, usa:

![La Gioconda (Wikipedia)](http://spines.me/img/help/Mona_Lisa.jpg)


para obtener:


  
  La Gioconda (Wikipedia)



Texto citado

Un simple prefijo denota texto citado:

&gt; Habían puesto la mesa debajo de un árbol, delante de la casa, y la Liebre de Marzo y el Sombrerero estaban tomando el té. Sentado entre ellos había un Lirón, que dormía profundamente, y los otros dos lo hacían servir de almohada, apoyando los codos sobre él, y hablando por encima de su cabeza.


que resultará en:

Habían puesto la mesa debajo de un árbol, delante de la casa, y la Liebre de Marzo y el Sombrerero estaban tomando el té. Sentado entre ellos había un Lirón, que dormía profundamente, y los otros dos lo hacían servir de almohada, apoyando los codos sobre él, y hablando por encima de su cabeza.


Líneas de código

Las líneas de código se delimitan con acentos abiertos. Si tecleas  Esta es una línea de código.  el resultado aparecerá así:


  Esta es una línea de código.


Bloques de código

Markdown convierte el texto marcado con tres acentos abiertos (```) al principio y al final en un bloque de código. Por ejemplo:


  $(function(){
    $('div').html('Hola, mundo');
  });


Si añades al ejemplo anterior la palabra clave javascript justo después de los acentos de apertura, el bloque de código será automáticamente coloreado de esta manera:


  $(function(){
    $('div').html('Hola, mundo')
  });


Esta funcionalidad soporta docenas de lenguajes de programación comunes. Consulta un listado completo de los lenguajes soportados.

Tablas

Si te animas, puedes incluso crear tablas en Markdown:
| Modelo | Color   | Precio |
| ------ |---------| ------:|
| Globe  | Negro   | 99€    |
| Scala  | Azul    | 199€   |
| Palais | Granate | 399€   |


será convertido en:


  
    
      
        Modelo
        Color
        Precio
      
    
    
      
        Globe
        Negro
        99€
      
      
        Scala
        Azul
        199€
      
      
        Palais
        Granate
        399€
      
    
  



"
}
</script>

	<div class="row help-header-page">
		<div class="help-header small-12 columns">
      <a href="https://spines.me">
        <img src="/img/spines-bluegrey.svg" alt="Spines">
      </a>
		</div>
	</div>
	<section class="row help-page inner-page">
		<div class="small-12 medium-12 large-10 medium-centered columns">
			<aside class="small-12 medium-12 large-3 left help-aside">
			<div class="help-menu">
			<h3>Ayuda</h3>
				<ul class="show-for-medium-up">
  
  
    
    
    <li>
      
        <p class="">Sintaxis de Markdown</p>
      
    </li>
  
</ul>




			</div>
			</aside>
			<div class="small-12 medium-12 large-9 left" id="top">
				<div class="help-wrapper">
					<article>
					


<div class="help-breadcrumb--wrapper">
  <div class="help-breadcrumb"><a href="/es/learn/">Aprende con Spines</a> &rarr;
    
    <a href="/es/help/">Ayuda</a> &rarr;
    
    
    <a href="/es/help/markdown/">Markdown</a> &rarr;
    
    Sintaxis de Markdown
  </div>
  <form action="get" id="site_search" class="help-search">
    <input type="text" placeholder="Buscar..." id="search_box" class="help-input">
  </form>
</div>

					<small class="help--date">Actualizado el 06.05.16</small>
					<h2>Sintaxis de Markdown</h2>
						
						<p>Markdown es un lenguaje de marcado de texto plano que te permite añadir estilo, imágenes y enlaces a un simple documento de texto. Puedes usar Markdown para dar formato al texto de tus ideas en Spines.</p>

<p>Markdown es muy fácil de aprender y usar. Vamos a repasar algunas carácterísticas básicas pero muy útiles.</p>

<h3 id="titulares">Titulares</h3>

<p>Hay seis tamaños de titulares (llamados titular 1 a 6) disponibles en Markdown. Indicas que una frase es un titular con el prefijo <strong>#</strong>, de la siguiente manera:</p>

<p><code># Esto es un titular de tamaño 1</code></p>

<p>El ejemplo anterior se visualiza así:</p>

<blockquote>
  <h1 class="md-example">Esto es un titular de tamaño 1</h1>
</blockquote>

<p>El número de caracteres <strong>#</strong> que escribes se corresponde con el tamaño de titular mostrado:</p>

<p><code>## Esto es un titular de tamaño 2</code></p>
<h3 id="este-titular-es-de-tamaño-3">Este titular es de tamaño 3</h3>
<h4 id="un-titular-más-pequeño-de-tamaño-4">Un titular más pequeño, de tamaño 4</h4>
<h5 id="este-solo-es-de-tamaño-5">Este solo es de tamaño 5</h5>
<h6 id="el-de-tamaño-6-es-el-más-pequeño">El de tamaño 6 es el más pequeño</h6>
<p>&lt;/code&gt;</p>

<p>translates to:</p>

<blockquote>
  <h2 class="md-example">Esto es un titular de tamaño 2</h2>
  <h3 class="md-example">Este titular es de tamaño 3</h3>
  <h4 class="md-example">Un titular más pequeño, de tamaño 4</h4>
  <h5 class="md-example">Este solo es de tamaño 5</h5>
  <h6 class="md-example">El de tamaño 6 es el más pequeño</h6>
</blockquote>

<h3 id="párrafos">Párrafos</h3>

<p>Normalmente, el texto escrito en Markdown automáticamente se inserta en párrafos. Para crear un nuevo párrafo, deja una línea en blanco antes de escribir de nuevo.</p>

<p><code>Esta frase automáticamente crea un párrafo en Markdown.
Esta frase pertenece al mismo párrafo aunque está en una nueva línea.
<br />
Esta frase ha creado un nuevo párrafo.
</code></p>

<h3 id="negrita">Negrita</h3>

<p>Para señalar una palabra como negrita, usa asteriscos. Escribir:</p>

<p><code>La última palabra es **negrita**.</code></p>

<p>da como resultado:</p>

<blockquote>
  <p>La última palabra es <strong>negrita</strong>.</p>
</blockquote>

<h3 id="cursiva">Cursiva</h3>

<p>Dos guiones bajos delimitando una palabra indican cursiva:</p>

<p><code>Escribe en _cursiva_ para dar énfasis.</code></p>

<p>Esto genera:</p>

<blockquote>
  <p>Escribe en <em>cursiva</em> para dar énfasis.</p>
</blockquote>

<p>Puedes combinar diferentes marcadores en la misma frase o palabra:</p>

<p><code>Usando **negrita** y _cursiva_ para _**énfasis extremo**_.</code></p>

<p>crea el siguiente pero no <em>particularmente</em> recomendable ejemplo:</p>

<blockquote>
  <p>Usando <strong>negrita</strong> y <em>cursiva</em> para <em><strong>énfasis extremo</strong></em>.</p>
</blockquote>

<h3 id="tachado">Tachado</h3>

<p>Para resaltar una corrección, puedes añadir dos tildes antes y después de la palabra o frase:</p>

<p><code>Ella ~~nació~~ creció en Alemania.</code></p>

<p>será mostrado como:</p>

<blockquote>
  <p>Ella <del>nació</del> creció en Alemania.</p>
</blockquote>

<h3 id="enlaces">Enlaces</h3>

<p>Una dirección web (URL) se convierte automáticamente en un enlace interactivo:</p>

<p><code>http://spines.me</code></p>

<p>aparecerá como:</p>

<blockquote>
  <p><a href="http://spines.me">http://spines.me</a></p>
</blockquote>

<p>Puedes crear enlaces HTML más complejos con la siguiente sintaxis:</p>

<p><code>[The New York Times](http://www.nytimes.com) es un periódico.</code></p>

<p>devuelve:</p>

<blockquote>
  <p>
    <a href="http://www.nytimes.com">The New York Times</a> es un periódico.
  </p>
</blockquote>

<p>También puedes escribir enlaces en dos estilos con <em>formato de referencia</em>:</p>

<p><code>[The New York Times][1] es un periódico.
[1]: http://www.nytimes.com
<br />
[The New York Times] es un periódico.
[The New York Times]: http://www.nytimes.com
</code></p>

<p>y los dos ejemplos producirán el mismo resultado:</p>

<blockquote>
  <a href="http://www.nytimes.com">The New York Times</a> es un periódico.
</blockquote>

<h3 id="imágenes">Imágenes</h3>

<p>De la misma manera, puedes incorporar imágenes de otras páginas web. Por ejemplo, usa:</p>

<p><code>![La Gioconda (Wikipedia)](http://spines.me/img/help/Mona_Lisa.jpg)
</code></p>

<p>para obtener:</p>

<blockquote><figure>
  <img src="/img/help/Mona_Lisa.jpg" alt="La Gioconda (Wikipedia)" />
  <figcaption>La Gioconda (Wikipedia)</figcaption>
</figure>
</blockquote>

<h3 id="texto-citado">Texto citado</h3>

<p>Un simple prefijo denota texto citado:</p>

<p><code>&gt; Habían puesto la mesa debajo de un árbol, delante de la casa, y la Liebre de Marzo y el Sombrerero estaban tomando el té. Sentado entre ellos había un Lirón, que dormía profundamente, y los otros dos lo hacían servir de almohada, apoyando los codos sobre él, y hablando por encima de su cabeza.
</code></p>

<p>que resultará en:</p>

<blockquote><p class="blockquote-example">Habían puesto la mesa debajo de un árbol, delante de la casa, y la Liebre de Marzo y el Sombrerero estaban tomando el té. Sentado entre ellos había un Lirón, que dormía profundamente, y los otros dos lo hacían servir de almohada, apoyando los codos sobre él, y hablando por encima de su cabeza.</p>
</blockquote>

<h3 id="líneas-de-código">Líneas de código</h3>

<p>Las líneas de código se delimitan con acentos abiertos. Si tecleas <strong><code class="highlighter-rouge"> Esta es una línea de código. </code></strong> el resultado aparecerá así:</p>

<blockquote>
  <code>Esta es una línea de código.</code>
</blockquote>

<h3 id="bloques-de-código">Bloques de código</h3>

<p>Markdown convierte el texto marcado con tres acentos abiertos (```) al principio y al final en un bloque de código. Por ejemplo:</p>

<blockquote>
  <code>$(function(){
    $('div').html('Hola, mundo');
  });</code>
</blockquote>

<p>Si añades al ejemplo anterior la palabra clave <em>javascript</em> justo después de los acentos de apertura, el bloque de código será automáticamente coloreado de esta manera:</p>

<blockquote class="code-color">
  <code><span class="nx">$</span><span class="p">(</span><span class="kd">function</span><span class="p">(){</span>
    <span class="nx">$</span><span class="p">(</span><span class="s1">'div'</span><span class="p">).</span><span class="nx">html</span><span class="p">(</span><span class="s1">'Hola, mundo'</span><span class="p">)</span>
  <span class="p">});</span></code>
</blockquote>

<p>Esta funcionalidad soporta docenas de lenguajes de programación comunes. Consulta <a href="http://pygments.org/languages/" target="_blank">un listado completo de los lenguajes soportados</a>.</p>

<h3 id="tablas">Tablas</h3>

<p>Si te animas, puedes incluso crear tablas en Markdown:
<code>| Modelo | Color   | Precio |
| ------ |---------| ------:|
| Globe  | Negro   | 99€    |
| Scala  | Azul    | 199€   |
| Palais | Granate | 399€   |
</code></p>

<p>será convertido en:</p>

<blockquote>
  <table>
    <thead>
      <tr>
        <th>Modelo</th>
        <th>Color</th>
        <th>Precio</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Globe</td>
        <td>Negro</td>
        <td align="right">99€</td>
      </tr>
      <tr>
        <td>Scala</td>
        <td>Azul</td>
        <td align="right">199€</td>
      </tr>
      <tr>
        <td>Palais</td>
        <td>Granate</td>
        <td align="right">399€</td>
      </tr>
    </tbody>
  </table>
</blockquote>

<hr />

					</article>
				</div>
			</div>
		</div>
		<a href="#top" class="up" data-track-link="site.help.back_to_top"><span class="icon-arrow-up"></span></a>
	</section>
	
<footer class="full-row left">
  <nav class="row">
    <ul class="small-block-grid-1 medium-block-grid-4 large-block-grid-4 columns small-10 end">
    </ul>
  </nav>
  <div class="row">
    <div class="full-row topnav--wrapper topnav--">
  <div class="topnav">
    <div class="topnav-logo--wrapper">
      <h1 title="Spines - Learn More" class="spines-logo">
        <a href="/es/" data-track-link="site.menu.home"><img src="/img/spines-bluewhite.svg" alt="Spines. Learn More" title="Spines. Learn more"/></a>
      </h1>
    </div>
    <ul class="topnav-menu">
      <li><a href="/es/features/" class="" data-track-link="site.menu.features">Características</a></li>
      <li><a href="/es/education/" class="" data-track-link="site.menu.education">Educación</a></li>
      <li><a href="/es/companies/" class="" data-track-link="site.menu.companies">Empresa</a></li>
      <li><a href="/es/training/" class="" data-track-link="site.menu.training">Formación</a></li>
      <li><a href="/es/learners/" class="" data-track-link="site.menu.learners">Estudiantes</a></li>
    </ul>
   <div class="topnav-action--wrapper">
    <a href="https://api.spines.me/api/v1/users/sign_in" class="button tiny positive radius right" data-track-link="site.menu.signin">Entrar</a>
    
    <a href="/help/markdown/syntax/" data-track-link="site.menu.lang_en" class="button tiny action">
      ENGLISH
    </a>
    
  </div>
</div>
</div>

    <ul class="links columns small-12">
      <li><a href="/" class="logo-wrapper" data-track-link="site.footer.home"></a></li>
      <li>
        <p>Sobre Spines</p>
        <ul>
          <li><a href="/es/pricing/" data-track-link="site.footer.price">Precios</a></li>
          <li><a href="/blog/" data-track-link="site.footer.blog">Blog</a></li>
          <li><a href="/es/contact/" data-track-link="site.footer.help_contact">Contacto</a></li>
          <li><a href="/es/press-kit/" data-track-link="site.footer.presskit">Kit de prensa</a></li>
        </ul>
      </li>
      <li>
        <p>Herramientas</p>
        <ul>
          <li><a href="/es/app/#android" data-track-link="site.footer.android">App para Android</a></li>
          <li><a href="/es/app/#iphone" data-track-link="site.footer.ios">App para iPhone</a></li>
          <li><a href="/es/app/#browser" data-track-link="site.footer.extensiones">Extensión del navegador</a></li>
        </ul>
      </li>
      <li>
        <p>Ayuda</p>
        <ul>
          <li><a href="/es/learn/" data-track-link="site.footer.help_center">Aprende con Spines</a></li>
          <li><a href="/es/help/" data-track-link="site.footer.help_help">Ayuda de Spines</a></li>
          <li><a href="https://api.spines.me/coupons" data-track-link="site.footer.help_coupon">Canjea un cupón</a></li>
        </ul>
      </li>
      <li>
        <p>Síguenos</p>
        <ul>
          <li><a href="http://eepurl.com/TR-MT" target="_blank" data-track-link="site.footer.newsletter">Newsletter</a></li>
          <li><a href="https://twitter.com/spinesme" target="_blank" data-track-link="site.footer.social_twitter">Twitter</a></li>
          <li><a href="https://www.facebook.com/spinesme" target="_blank" data-track-link="site.footer.social_facebook">Facebook</a></li>
          <li><a href="https://plus.google.com/+SpinesMe/posts" target="_blank" data-track-link="site.footer.social_googleplus">Google+</a></li>
        </ul>
      </li>
    </ul>
    <p>
      &copy; <time datetime="2017-10-31T11:36:24+00:00">2014 – 2017</time> Spines de Lihuen Hub S.L. Todos los derechos reservados<br>
      <a href="/es/privacy-policy/" data-track-link="site.footer.privacy_policy">Política de privacidad</a>
      &nbsp;–&nbsp; <a href="/es/terms-of-service/" data-track-link="site.footer.tos">Términos del servicio</a>
      &nbsp;–&nbsp; <a href="/es/cookies-policy/" data-track-link="site.footer.cookies">Política de cookies</a>
      &nbsp;–&nbsp; <a href="http://ec.europa.eu/consumers/odr/" data-track-link="site.footer.odr">Resolución de litigios en línea</a></p>
  </div>
  <div class="footer-sticker"><a href="https://mixpanel.com/f/partner"><img src="//cdn.mxpnl.com/site_media/images/partner/badge_blue@2x.png" alt="Mobile Analytics" /></a></div>
</footer>


<script type="text/javascript" src="/resources/vendor/modernizr.min-be155fd9260445954c8f505cfb9e76c79abbcd3cef57e01a6d67c3fa159c2dfb.js"></script>
<script type="text/javascript" src="/resources/vendor/modernizr.min-be155fd9260445954c8f505cfb9e76c79abbcd3cef57e01a6d67c3fa159c2dfb.js"></script>
<script type="text/javascript" src="/resources/vendor/foundation/foundation.min-53239d9f292d27ebc0ecb3aeac360511bb6ff62baa8b1b76d2e219185ed75a52.js"></script>
<script type="text/javascript" src="/resources/vendor/foundation/foundation.offcanvas-2f34a4b91e1e958aefbde46004d6186ee82e018fe95634214749799141339810.js"></script>
<script type="text/javascript" src="/resources/vendor/jquery.cookie-1.4.1.min-ba278b0c026e1407b8d41d8dbc309504051c65e49da93c3b7068aa1580c0c007.js"></script>
<script type="text/javascript" src="/resources/vendor/smoothscroll-4d87c6536d61f9e3260d4e107a779e69f343c04e6184adfafe0f4fc4c3bf8d26.js"></script>
<script type="text/javascript" src="/resources/vendor/cookieslaw-b886afc38b192d042e2de49b8a43fc31e538c421111c3088d5c8146f4be2635d.js"></script>
<script type="text/javascript" src="/resources/vendor/lunr.min-918ed2b4e8292b1e4879cf58ca1d5e80338e9719206f70bf899c3c2763d9392c.js"></script>

<script type="text/javascript" src="/resources/common-66ffa21bf2e1ccf2bd292c44f77af7fedb74ccb792954ab0b20268ea64fa6c8c.js"></script>
<script type="text/javascript" src="/resources/cookies-ae634a8f76fb4e569353dc0715a6c3a450ad7e64d9a11f9a77a5b6dfbefbc562.js"></script>

<!--  -->
<script>
	$(document).foundation();
</script>


	<script type="text/javascript" src="/resources/search_help-065ab1975f456be1cec372750c0a188dffa7b5227050d01bb29fb35ab1cb2e3b.js"></script>
	<script type="text/javascript" src="/resources/vendor/typeahead-83fb8a1eb4a5d0db7cea04423e9b0925cfd76067911ee10a62634d89ce8c55cc.js"></script>
	<script>
		$( document ).ready(function() {
			$('.up').hide();
			$(document).scroll(function() {
				var y = $(this).scrollTop();
				if (y > 400 && y < 4900) {
					$('.up').fadeIn();
					$(".up").click(function(){
						window.scroll(0,0);
					});
				} else {
					$('.up').fadeOut();
				}
			});
		});
	</script>
</body>
</html>
