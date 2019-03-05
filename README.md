# GUION " 18 COMANDOS GIT"

cd /c/users/q92he/"Google drive"/Proyectos/Github # __Localizamos nuestro directorio de trabajo__

mkdir Web_CSS # __Creamos la carpeta del directorio de trabajo__

cd /c/users/q92he/"Google drive"/Proyectos/Github/Web_CSS # __Entramos en la carpeta de directorio de trabajo__

__Creamos o copiamos los archivos en el directorio de trabajo__

git init # __Creamos el repositorio__


git status # A__rchivos sin seguimiento__


git add . # __Ponemos los archivos en seguimiento__


git status # __Archivos en seguimiento__ 


git commit -m "Archivos al HEAD" # __Subimos al HEAD__


git rm "Facebook.html" # __Borro el arhcivo Facebook.html del HEAD__


git commit -m "FB borrado"


git mv css-3-logo.png log-CSS3.png # __Cambiamos el nombre del archivo__


git commit -m "Cambio nombre LOGO"


git reset --soft HEAD~1 #Borro el commit anterior


git mv log-CSS3.png Favicon.png


git commit -m "cambios al HEAD"


git remote add origin https://github.com/Andres-Heras/WEB_CSS.git 


git push origin master #Subimos al repositorio remoto creado al principio del video (GITHUB)



## Subido el archivo borro el repositorio LOCAL


cd /c/users/q92he/"Google drive"/Proyectos/Github 


git clone https://github.com/Andres-Heras/WEB_CSS.git


cd /c/users/q92he/"Google drive"/Proyectos/Github/WEB_CSS


git init # __Iniciamos el repositorio__


git add . # __Ponemos los archivos en seguimiento__


git commit -m "Repositorio clonado" 


git pull  https://github.com/Andres-Heras/WEB_CSS.git


git show # __Para ver toda la información del repositorio añadida.__


git branch CSS # __Creamos la rama CSS__

git checkout -b "HTML" # __Creamos la rama HTML y empezamos a trabajar sobre ella__

## Introduzco los Metadatos y el Formulario


git add .


git commit -m"Cambios HTML"


git checkout CSS # __Cambio de rama__


## Pasamos el CSS a un archivo externo (estilo)


git status


git add .


git commit -m "CSS Archivo externo"


## Colaboración en Github añadiendo LAYOUT a la web


git pull  https://github.com/Andres-Heras/WEB_CSS.git


git  commit -m "Conflicto resueltos"


git log --oneline --graph --color --all --decorate # Modo gráfico para ver información


git checkout master #__Cambio de rama__


git diff HTML master #__Diferencias de ramas


git merge HTML # __Uno la rama HTML__


git merge css #__Uno la rama CSS__


git fetch origin # __Actualizamos con el repositorio remoto__


git push origin


