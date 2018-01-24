---
id: 502
title: '#132 &#8211; Jekill o WordPress'
date: 2017-05-06T23:23:54+00:00
author: bateria2x100
layout: post
guid: http://www.bateria2x100.com/?p=502
permalink: /132-jekill-wordpress/
enclosure:
  - |
    https://www.bateria2x100.com/podcast/Bat2x100_132.mp3
    63791990
    audio/mpeg
    a:1:{s:8:"duration";s:8:"01:31:43";}
categories:
  - crossover
  - Mac OSX
---
<div class="powerpress_player" id="powerpress_player_5981">
  <audio class="wp-audio-shortcode" id="audio-502-134" preload="none" style="width: 100%;" controls="controls"><source type="audio/mpeg" src="https://www.bateria2x100.com/podcast/Bat2x100_132.mp3?_=134" /><a href="https://www.bateria2x100.com/podcast/Bat2x100_132.mp3">https://www.bateria2x100.com/podcast/Bat2x100_132.mp3</a></audio>
</div>

<p class="powerpress_links powerpress_links_mp3">
  Podcast: <a href="https://www.bateria2x100.com/podcast/Bat2x100_132.mp3" class="powerpress_link_pinw" target="_blank" title="Play in new window" onclick="return powerpress_pinw('https://www.bateria2x100.com/?powerpress_pinw=502-podcast');" rel="nofollow">Play in new window</a> | <a href="https://www.bateria2x100.com/podcast/Bat2x100_132.mp3" class="powerpress_link_d" title="Download" rel="nofollow" download="Bat2x100_132.mp3">Download</a>
</p>

<p class="powerpress_links powerpress_subscribe_links">
  Subscribe: <a href="https://subscribeonandroid.com/www.bateria2x100.com/feed/podcast/" class="powerpress_link_subscribe powerpress_link_subscribe_android" title="Subscribe on Android" rel="nofollow">Android</a> | <a href="https://www.bateria2x100.com/feed/podcast/" class="powerpress_link_subscribe powerpress_link_subscribe_rss" title="Subscribe via RSS" rel="nofollow">RSS</a>
</p>

Jekyll i WordPress

Herramientas para crear Websites, con pros y contras para ambos. WordPress

WordPress https://wordpress.org/ (No WordPress.com claro…) Filosofía

La filosofía de WordPress apuesta decididamente por la elegancia, la sencillez y las recomendaciones del W3C pero depende siempre de la plantilla a usar. TwentyTen, por ejemplo, es una plantilla predeterminada y que es válida como (X)HTML Tradicional y CSS.

— Wikipedia https://es.wikipedia.org/wiki/WordPress

Concepto

WordPress es un sistema de gestión de contenidos o CMS (por sus siglas en inglés, Content Management System) enfocado a la creación de cualquier tipo de sitio web. Originalmente alcanzó una gran relevancia usado para la creación de blogs, para convertirse con el tiempo en una de las principales herramientas para la creación de páginas web comerciales.

Eligió el nombre WordPress por sugerencia de su amiga Christine Selleck.

— Wikipedia https://es.wikipedia.org/wiki/WordPress

Licencia

Es software libre GPL https://es.wikipedia.org/wiki/GNU\_General\_Public_License Creador

Su fundador es Matt Mullenweg, (Houston, Texas, 11 de enero de 1984). WordPress fue creado a partir del desaparecido b2/cafelog y se ha convertido en el CMS más popular de la blogosfera y en el más popular con respecto a cualquier otro CMS de uso general.2 3

Las causas de su enorme crecimiento son, entre otras, su licencia, su facilidad de uso y sus características como gestor de contenidos.

— Wikipedia https://es.wikipedia.org/wiki/WordPress

Desarrollo

Ha sido desarrollado en el lenguaje PHP para entornos que ejecuten MySQL y Apache. Estructura



Jekyll Licencia

Es software libre MIT License https://en.wikipedia.org/wiki/MIT_License Filosofía

Hace lo que le pides que haga, ni más ni menos. No trata de burlar a los usuarios haciendo suposiciones audaces, ni les carga con complejidad y configuración innecesarias. En pocas palabras, Jekyll se sale de su camino y te permite concentrarte en lo que realmente importa: su contenido.

Es el blog hacker por excelencia por su flexibilidad.

Creador

Creado por Tom Preston-Wener cofundador y Ceo de GitHub en 2008. Nacido el 28 de octubre de 1979) es un software developer, inventor y emprendedor. Activo contribuidor de open-source development community, en San Francisco Bay Area, donde vive. Artículo de Tom Preston-Wener presentando Jekyll Características

Texto plano, sin Bases de Datos MarkDown y Textitle principalmente y html Simple la edición en texto plano, se puede editar con Vim, Emacs, Gedit, TextEdit, Notepad, etc. Aproximado 1,5 Mb de RAM Pinta el código mediante rouge antes lo pintaba con pygments, de esta forma al marcar el código reconoce la sintaxis de Python, Ruby, Bash, etc. Flujo de trabajo

Muy fácil instalación, pero requiere un mínimo de conocimientos sobre la terminal, sistema de instalación de Ruby y sus gemas. Posibilidad de realizar tags, colecciones. Se escribe en Markdown pero posibilidad de incrustar html. Colaboración fácil, mediante GitHub, necesidad de conocer Git mínimamente. Ultra-Rápido ya que renderiza desde texto plano, una vez renderizado es texto en .html Webs Estáticas (google analytics, añadir comentarios, …) Van apareciendo plugins pero siendo una web mas estatica, dentro de porder modificar todo Aprendizaje

Curva de aprendizaje relativamente rápida, dependiendo de conocimientos previos En menos de 1 minuto construyes el blog básico Hosting

GitHub Pages (Crear tu web gratis y sin publicidad) No está tan expuesto pues es texto plano Posibilidad de trabajar en https y en ssh Local

Servidor local para previsualizar y probar código, antes de subir. jekyll serve Ventajas de Git, versionado Lenguaje

Toda la potencia de Ruby Utiliza un lenguaje interno de templates: Liquid Componentes

jekyll new myblog Esto creará un directorio llamado myblog/ donde se encuentran todos los archivos necesarios para crear nuestro blog.

&#95;includes/ &#95;layouts/ &#95;posts/ &#95;sass/ css/ &#95;config.yml about.md feed.xml index.html &#95;config.yml: Archivo de configuración.

_includes/: Directorio, contiene fragmentos de código reutilizables para incluir en nuestros templates y posts (footer.html o header.html).

_layouts/: Directorio contiene los templates necesarios para mostrar nuestras páginas y posts.

_posts/: Directorio donde se guardan los posts, organizados por fechas con formato inverso y escritos markdown.

_draft/: Directorio de borradores.

Estructura de un post

* * *

layout: post title: Título del post date: dc 03 mai 2017 19:30:33 CEST description: Archivar keywords: archive coments: true

* * *

A partir de aquí empieza en post en Markdown Conclusiones

WordPress

Posibilidad de autenticación en dos pasos Muy fácil de levantar Host gratuito Extramadamente fácil de cambiar los themes Comunidad enorme, mucha documentación Expuesto, se conoce la estructura Curva de aprendizaje rápida Jekyll

Más seguro, no hay nada que hackear, si a caso el host, pues todo es texto plano que el navegador interpreta Posibilidad de activar la autenticación en dos pasos en GitHub Más rápido, posibilidad de plugins, como está generado los plugins no influyen en el rendimiento Flexibilidad y personalización extrema Curva de aprendizaje más lenta, para cambiar cosas hay que aprender la lógica de Liquid primero