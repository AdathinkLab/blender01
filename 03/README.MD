# NODE JS

[NODEJS](https://nodejs.org/es/)

# GITHUB

GitHub es una plataforma de desarrollo colaborativo que reúne a la comunidad de 
desarrolladores más grande del mundo para descubrir, compartir y construir un mejor 
software. Desde proyectos de código abierto hasta equipo privado y alojar proyectos 
utilizando el sistema de control de versiones Git.

[GITHUB](https://github.com/)

# GIT 

Git es un sistema de control de versiones distribuido gratuito y 
de código abierto diseñado para manejar todo, desde proyectos pequeños 
hasta muy grandes, con rapidez y eficiencia.

[GIT](https://git-scm.com/docs)

## COMANDOS GIT

* GIT HELP: Muestra una lista con los comandos más utilizados en GIT. <git help>

* GIT INIT: Podemos ejecutar ese comando para crear localmente un repositorio con GIT y así                   utilizar todo el funcionamiento que GIT ofrece.  Basta con estar ubicados dentro de               la carpeta donde tenemos nuestro proyecto y ejecutar el comando.  Cuando agreguemos               archivos y un commit, se va a crear el branch master por defecto. <git init>

* GIT ADD: Agrega al repositorio los archivos que indiquemos. <git add src/index.js>

* GIT ADD: Agrega al repositorio TODOS los archivos y carpetas que estén en nuestro proyecto, los            cuales GIT no está siguiendo. <git add .>

* GIT COMMIT: Hace commit a los archivos que indiquemos, de esta manera quedan guardados nuestras               modificaciones. <git commit -m "" index.html>

* GIT COMMIT: Hace commit de los archivos que han sido modificados y GIT los está siguiendo.
              <git commit -m "mensaje">

#### GIT FLOW
* GIT CHECKOUT: Crea un nuevo branch y automaticamente GIT se cambia al branch creado, clonando                   el branch desde donde ejecutamos el comando. <git checkout -b develop>

* GIT BRANCH: Nos muestra una lista de los branches que existen en nuestro repositorio.
              <git branch>

* GIT CHECKOUT: Sirve para moverse entre branches, en este caso vamos al branch que indicamos en                  el comando. <git checkout master>

* GIT MERGE: Hace un merge entre dos branches, en este caso la dirección del merge sería entre el              branch que indiquemos en el comando, y el branch donde estémos ubicados. 
             <git merch develop>

* GIT STATUS: Nos indica el estado del repositorio, por ejemplo cuales están modificados, cuales                no están siendo seguidos por GIT, entre otras características. <git status>

* GIT CLONE: Clona un proyecto de git en la carpeta NombreProyecto. <git clone http://frontend>

* GIT PUSH: Luego de que hicimos un git commit, si estamos trabajando remotamente, este comando               va a subir los archivos al repositorio remoto, específicamente al branch que                      indiquemos. <git push origin master>

* GIT PULL: Hace una actualización en nuestro branch local, desde un branch remoto que indicamos              en el comando. <git pull origin develop>

### OTROS RECURSOS

[1](https://gist.github.com/dasdo/9ff71c5c0efa037441b6)
[2](https://rogerdudler.github.io/git-guide/index.es.html)