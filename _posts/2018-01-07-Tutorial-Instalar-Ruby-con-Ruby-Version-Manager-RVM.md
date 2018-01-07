---
layout: post 
title: "Tutorial | Instalar Ruby con Ruby Version Manager (RVM)"
date: 2018-01-07
description: 'Como instalar Ruby con Ruby Version Manager (RVM) en Linux Mint.'
main-class: 'post'
color: '#EB7728'
tags: Ruby, Jekyll
categories: articulo
permalink: /Ruby con RVM/
introduction: 'Como instalar Ruby con Ruby Version Manager (RVM) en Linux Mint.'
comment: true
---


Recientemente cambié de sistema operativo. Tenía **Manjaro** y decidí instalar **Linux Mint 18.3 XFCE**.  

Para poder deguir usando Jekyll en Local debía de volver a instalarlo. Comprobé que Ruby ya venía instalado así que me dispuse a instalar Jekyll con el comando gem.  

Para mi sorpresa no fue posible. Me daba errores de acceso a la carpeta de las gemas. Probé varias soluciones que encontré por internet y ninguna me solucionó el problema.  

Entonces me dijeron que lo mejor era instalar Ruby a través de **RVM**, Ruby Version Manager, que nos permite poder utilizar varias versiones de ruby  o de gemas en el mismo sistema con distintos proyectos.  

Esta fue la solución que me funcionó y ya tengo Jekyll instalado.  

Veamos como lo tenemos que instalar:  

Lo mejor es instalar RVM utilizando el script de instalación que hay en su [web](http://rvm.io/)  

````
$ gpg --keyserver hkp://keys.gnupg.net --recv-keys 409B6B1796C275462A1703113804BB82D39DC0E3 7D2BAF1CF37B13E2069D6956105BD0E739499BDB
````
Con el comando gpg verificamos la legitimidad de la versión de RVM que descargamos.  

Lo siguiente es instalar **curl**. Ya que lo vamos a necesitar para descargar el script de instalación de **RVM**.  

```
$ sudo apt-get install curl

```
Ahora con el comando *curl* descargamos el script.  

```
$ \curl -sSL https://get.rvm.io -o rvm.sh
```

Ya tenemos el script y procedemos a instalar la última versión estable de RVM.  

```
$ cat rvm.sh | bash -s stable

```

Se nos creará un nuevo directorio llamado *.rvm*  

El proceso de instalación modifica el archivo *.bashrc*  agregando la carpeta *.rvm/bin* a su *PATH*, para que se pueda ejecutar el comando *rvm* fácilmente.  

Como en la sesión actual no está accesible este comando hay que ejecutar lo siguiente:  

```
source ~/.rvm/scripts/rvm
```

Ahora ya podemos instalar **Ruby**:  

```
rvm install ruby --default
```
Junto con Ruby se instalan algunas herramientas relacionadas:  

- irb: la consola interactiva Ruby.
- rake: un programa que puede ejecutar scripts de automatización.
- gem:  para poder instalar las distintas gemas de Ruby. 


comprobamos que Ruby se ha instalado:  

```
ruby -v 
```

Ahora vamos a realizar una última modificación. Para que RVM utilice automáticamente la versión de Ruby que hemos instalado cada vez que abra una nueva Terminal, esta debe abrir un shell de inicio de sesión. RVM modifica el archivo *.bash_profile* , que sólo se invoca en los shells de inicio de sesión.  

El Terminal predeterminado lo que abre es un shell interactivo y no llama a este archivo. Por tanto en las preferencias de la terminal debemos indicar *Ejecutar comando como shell de inicio de sesión*.  

Ya solo nos queda instalar **Jekyll**:

```
gem install jekyll
```

Y con esto tenemos nuestro sistema preparado para usar Jekyll en local.  

Espero que te haya sido de utilidad este tutorial.

