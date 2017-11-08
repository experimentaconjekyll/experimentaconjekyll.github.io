---
layout: post
title:  "#01-Qué es Jekyll y su estructura de archivos"
date:   2017-05-18 
main-class: 'podcast'
color: '#8D68CD'
categories: podcast
tags: 
- Jekyll
introduction: 'Jekyll es un generador de Blog estáticos. Esto quiere decir que generaremos nuestro blog a partir de una serie de archivos de texto'
permalink: /1/
image: /images/Logo.jpg
podcast_link: https://archive.org/download/01QueEsJekyll/01-Que%20es%20Jekyll.mp3
comment: true
---

<br>
<center>
 <audio controls>
  <source src="{{ page.podcast_link }}" type="audio/mp3">
</audio>
</center>
<br>

Jekyll es un generador de Blog estáticos. Esto quiere decir que generaremos nuestro blog a partir de una serie de archivos de texto. No necesita un gestor de contenidos ni una base de datos. Ni tampoco PHP como las web dinámicas estilo Wordpress.

**La Estructura básica** de un sitio hecho con Jekyll es la siguiente:

```

├── _config.yml
├── _includes
│   ├── footer.html
│   ├── header.html
│   
├── index.md
├── _layouts
│   ├── home.html
│   ├── page.html
│   ├── post.html
── _posts
│   ├── 2017-05-02-experimenta-con-jekyll-Presentación.markdown
│
├── _sass
│   └── minima.scss
├── css
│   └── minima.css

```


___


<br>

[Web del podcast](lormez16.github.io/experimenta-con-jekyll)
Audio recomendado [¿Jekyll o WordPress?](https://ugeek.github.io/052.-Jekyll-o-Wordpress/)


Credito de Sintonia:
**"Spring Whistle Ukulele Summer" de GIUSEPPE LORENZONI ** (https://www.jamendo.com)
License Creative Commons

Si te ha gustado compártelo en tus redes favoritas.



[mp3]: https://archive.org/download/01QueEsJekyll/01-Que%20es%20Jekyll.mp3