---
layout: post 
title: "#04-Publicando el Blog con GitHub" 
date: 2017-09-17
main-class: 'podcast'
color: '#8D68CD'
categories: podcast
tags: [Jekyll, GitHub, Git]
introduction: 'En este episodio veremos como publicar el blog en GitHub utilizando GitHub-Pages'
permalink: /4/
image: images/Logo2.jpg
podcast_link: https://ia801508.us.archive.org/0/items/04PublicandoElBlogConGitHub/04-Publicando%20el%20blog%20con%20GitHub.mp3
comment: true
---

<br>
<center>
 <audio controls>
  <source src="{{ page.podcast_link }}" type="audio/mp3">
</audio>
</center>
<br>


En el episodio de hoy vamos a ver como podemos alojar nuestro blog en **GitHub**. Lo haremos utilizando **GitHub-Pages**, que es una opción que da GitHub para hacer una web de los proyectos.

En el episodio anterior analizamos los archivos de nuestro proyecto e hicimos unas mínimas modificaciones en el archivo de configuración. Ahora solo nos queda publicar nuestra web. 


Veamos entonces que comandos hay que ejecutar el la terminal una vez que ya tenemos nuestro usuario y repositorio en GitHub. 

Para ver como darse de alta y crear el repositorio en **GitHub** leer el siguiente [Post](https://lormez16.github.io/experimenta-con-jekyll/repositorio en github/). 

Desde la carpeta en local abrimos una terminal.

- Paso 1 - Iniciar git:

`$ git init`
<br>

- Paso 2 - Rastrear todos los archivos:

`$ git add .`
<br>


- Paso 3 - Guardar lo que ha encontrado con el primer commit:

`$ git commit -m "primer commit"`
<br>

- Paso 4 - Conectar carpeta local con repositorio: 

`$ git remote add origin https://github.com/lormez16/prueba.git`
<br>

- Paso 5 -Subir los archivos: 

`$ git push`

<br>

Con unas pocas líneas de comando tendrás el Blog publicado. 

A partir de ahora para actualizar cambios o publicar nuevos post solo tendrás que realizar 3 de estos pasos, que son:

`$ git add .`  
`$ git commit -m "lo que actualizo"`  
`$ git push`  


<br>

Para cualquier duda o comentario que quieras hacerme, puedes contactar conmigo en **Twitter** y **Telegram** como **@lormez16** y también en el correo **experimentaconjekyll@gmail.com**. 

Si lo prefieres utiliza el widget lateral para enviarme un **audio-comentario**.

Puedes escuchar el podcast en [iTunes](https://itunes.apple.com/es/podcast/experimenta-con-jekyll/id1234086951?l=en), [ivoox](http://www.ivoox.com/podcast-experimenta-jekyll_sq_f1420014_1.html), canal de [Youtube](https://www.youtube.com/channel/UCstNysoGbtQi3WqUCyQ7eKA) y en la web del podcast que es:

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


[mp3]: https://ia801508.us.archive.org/0/items/04PublicandoElBlogConGitHub/04-Publicando%20el%20blog%20con%20GitHub.mp3  

