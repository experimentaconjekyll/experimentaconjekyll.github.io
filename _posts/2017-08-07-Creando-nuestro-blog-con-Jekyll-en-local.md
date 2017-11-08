---
layout: post 
title: "#02-Creando nuestro blog con Jekyll en local" 
date: 2017-08-07
main-class: 'podcast'
color: '#8D68CD'
categories: podcast
tags: [Jekyll, Local]
introduction: 'En este episodio veremos los 4 pasos para crear nuestro blog en local'
permalink: /2/
image: images/Logo2.jpg
podcast_link: https://archive.org/download/02CreandoNuestroBlogConJekyllEnLocal/02-Creando%20nuestro%20blog%20con%20Jekyll%20en%20local.mp3
comment: true
---

<br>
<center>
<audio controls>
  <source src="{{ page.podcast_link }}" type="audio/mp3">

</audio>
</center>

<center><p><a href="https://archive.org/download/02CreandoNuestroBlogConJekyllEnLocal/02-Creando%20nuestro%20blog%20con%20Jekyll%20en%20local.mp3">Descarga</a></p></center>

<br>

Para crear nuestro primer blog y trabajar de forma local seguiremos los pasos indicados en la web principal de [Jekyll](http://jekyllrb.com/).  En el mismo home te da las 4 lineas de comandos que necesitas para tener tu blog disponible en apenas unos minutos


Veamos entonces que comandos hay que ejecutar.:

**Paso 1**  
 Abrimos la terminal y realizamos primero la comprobación de ruby escribiendo: 

`$ ruby -v`

Si está instalado te dará la versión de Ruby que tengas.  En caso de no tenerlo lo instalas desde los repositorios. En el caso de Manjaro:

`$ sudo pacman -S ruby`
<br/>

**Paso 2**  
Instalamos las gemas jekyll y bundler. Las gemas de ruby se instalan con `gem install`.


así que escribimos:

`$ gem install jekyll bundler`


**Paso 3**  
Creamos el nuevo blog con el comando `jekyll new` seguido del nombre del blog. En mi caso sería:

`$ jekyll new experimenta-con-jekyll`

No se pueden dejar espacios entre las palabras del nombre sino guiones.


**Paso 4**  
Nos trasladamos a la carpeta nueva creada con el comando `cd`

`$ cd experimenta-con-jekyll`

Y ahora ejecutamos el blog haciendo uso del servidor que trae Jekyll de la siguiente manera:

`$ bundle exec jekyll serve`

con este comando construira el blog y nos dara la url de localhost.

`http://localhost:4000`

colocas  esta dirección en el navegador y podras ver tu blog con la plantilla mínima que vienen por defecto. 


## Posibles errores  
- En Archlinux y derivadas como Manjaro, para poder ejecutar las gemas es necesario añadir la siguiente línea en el archivo ~/.bashrc del sistema . 

`PATH="$(ruby -e 'print Gem.user_dir')/bin:$PATH"`

Todo esto te lo indica la [Wiki de Archlinux](https://wiki.archlinux.org/index.php/Ruby)


- Para ver las gemas instaladas por si nos falta alguna ejecutamos 

`gem list`

y te dará el listado completo.



Para cualquier duda o comentario que quieras hacerme, puedes contactar conmigo en **twitter** y **telegram** como **@lormez16** y también en el correo **experimentaconjekyll@gmail.com**. 

Puedes escuchar el podcast en itunes, ivoox y en la web del podcast que es:

 https://lormez16.github.io/experimenta-con-jekyll




<br>


Credito de Sintonia:
**"Spring Whistle Ukulele Summer" de GIUSEPPE LORENZONI ** (https://www.jamendo.com)
License Creative Commons

Si te ha gustado compártelo en tus redes favoritas.



[mp3]: https://archive.org/download/02CreandoNuestroBlogConJekyllEnLocal/02-Creando%20nuestro%20blog%20con%20Jekyll%20en%20local.mp3
