---
layout: post 
title: "#03-Analizando los archivos del proyecto" 
date: 2017-09-03
categories: podcast
main-class: 'podcast'
color: '#8D68CD'
tags: [Jekyll, Mínima]
introduction: 'En este episodio analizamos los archivos que componen nuestro blog . '
permalink: /3/
image: images/Logo2.jpg
podcast_link: https://ia801507.us.archive.org/11/items/03AnalizandoLosArchivosDelProyecto/03-Analizando%20los%20archivos%20del%20proyecto.mp3
comment: true
---
<br>
<center>
<iframe width="640" height="360" src="https://www.youtube.com/embed/9GrpNVw5UVE?ecver=1" frameborder="0" gesture="media" allowfullscreen></iframe>
</center>
<br>

En el episodio de hoy vamos a analizar el proyecto que hemos creado en local. Veremos que archivos tenemos y haremos unas mínimas modificaciones en el archivo de configuración.

Si ya los has estado mirando espero que este episodio te ayude a comprenderlos mejor. Y si no lo has hecho este es el mejor momento para continuar el proyecto y analizarlos.

Los **archivos** que encontramos en el directorio son los siguientes:

```
$ tree

├── about.md
├── _config.yml
├── Gemfile
├── index.md
└── _posts
    └── 2017-08-25-welcome-to-jekyll.markdown

1 directory, 5 files

```
<br>

### Yaml Front Matter
Lo encontramos en la parte alta de muchos de los ficheros del proyecto, paginas, post y layout. En él se definen las variables que queremos usar en distintas partes de nuestra web.

El siguiente ejemplo es el típico de un post.
```
---
layout: post
title:  "Welcome to Jekyll!"
date:   2017-08-25 21:16:43 +0200
categories: jekyll update
---

```
<br>

### El archivo _config.yml

En este archivo cambiaremos los datos que trae  por los nuestros. Título, descripción, correo y usuario de Twitter.

```
title: Your awesome title

email: your-email@domain.com

description: > 
  Write an awesome description for your new site here. 
  
baseurl: "" # the subpath of your site, e.g. /blog

url: "" # the base hostname & protocol for your site, e.g. http://example.com

twitter_username: jekyllrb
github_username:  jekyll

# Build settings
markdown: kramdown
theme: minima
gems:
  - jekyll-feed
exclude:
  - Gemfile
  - Gemfile.lock

```
<br>

Para cualquier duda o comentario que quieras hacerme, puedes contactar conmigo en **Twitter** y **Telegram** como **@lormez16** y también en el correo **experimentaconjekyll@gmail.com**. 

Si lo prefieres utiliza el widget lateral para enviarme un **audio-comentario**.

Puedes escuchar el podcast en iTunes, ivoox y en la web del podcast que es:

 [https://lormez16.github.io/experimenta-con-jekyll](https://lormez16.github.io/experimenta-con-jekyll)




<br>


- - -
<br>

Credito de Sintonia:
**"Spring Whistle Ukulele Summer" de GIUSEPPE LORENZONI**  
[Jamendo](https://www.jamendo.com)  
License Creative Commons

Si te ha gustado compártelo en tus redes favoritas.

<!-- Begin SpeakPipe code -->
<script type="text/javascript">
(function(d){
var app = d.createElement('script'); app.type = 'text/javascript'; app.async = true;
var pt = ('https:' == document.location.protocol ? 'https://' : 'http://');
app.src = pt + 'www.speakpipe.com/loader/v6nlr21vd2ejbv25jd34rektczhqpr96.js';
var s = d.getElementsByTagName('script')[0]; s.parentNode.insertBefore(app, s);
})(document);
</script>
<!-- End SpeakPipe code -->


[mp3]: https://ia801507.us.archive.org/11/items/03AnalizandoLosArchivosDelProyecto/03-Analizando%20los%20archivos%20del%20proyecto.mp3  

