# GUION

1.- cd /c/users/q92he/"Google drive"/Proyectos/Github # _Localizamos nuestro directorio de trabajo_

2.- mkdir Web_CSS # _Creamos la carpeta del directorio de trabajo_

3.- cd /c/users/q92he/"Google drive"/Proyectos/Github/Web_CSS # _Entramos en la carpeta de directorio de trabajo_

## Creamos o copiamos los archivos en el directorio de trabajo

git init #Creamos el repositorio


git status #Archivos sin seguimiento


git add . #Ponemos los archivos en seguimiento


git status #Archivos en seguimiento 


git commit -m "Archivos al HEAD"


git rm "Facebook.html" #Borro el arhcivo Facebook.html del HEAD


git commit -m "FB borrado"


git mv css-3-logo.png log-CSS3.png # Cambiamos el nombre del archivo


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


git init #Iniciamos el repositorio


git add . #Ponemos los archivos en seguimiento


git commit -m "Repositorio clonado" 


git pull  https://github.com/Andres-Heras/WEB_CSS.git


git show # Para ver toda la información del repositorio añadida.


git branch CSS #Creamos la rama CSS

git checkout -b "HTML" #Creamos la rama HTML y empezamos a trabajar sobre ella

## Introduzco los Metadatos y el Formulario


git add .


git commit -m"Cambios HTML"


git checkout CSS


## Pasamos el CSS a un archivo externo (estilo)


git status


git add .


git commit -m "CSS Archivo externo"


## Colaboración en Github añadiendo LAYOUT a la web


git pull  https://github.com/Andres-Heras/WEB_CSS.git


git  commit -m "Conflicto resueltos"


git log --oneline --graph --color --all --decorate # Modo gráfico para ver información


git checkout master


git diff HTML master


git merge HTML


git merge css


git fetch origin 


git push origin


git merge css


git fetch origin


git push origin







