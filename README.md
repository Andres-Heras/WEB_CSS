

1.-cd /c/users/q92he/"Google drive"/Proyectos/Github # __Localizamos nuestro directorio de trabajo__

2.-mkdir Web_CSS # __Creamos la carpeta del directorio de trabajo__

3.-cd /c/users/q92he/"Google drive"/Proyectos/Github/Web_CSS # __Entramos en la carpeta de directorio de trabajo__


4.-__Creamos o copiamos los archivos en el directorio de trabajo__


5.- git init # __Creamos el repositorio__


6.- git status # A__rchivos sin seguimiento__


7.- git add . # __Ponemos los archivos en seguimiento__


8.- git status # __Archivos en seguimiento__


9.- git commit -m "Archivos al HEAD" # __Subimos al HEAD__


10.- git rm "Facebook.html" # __Borro el arhcivo Facebook.html del HEAD__


11.- git commit -m "FB borrado"


12.- git mv css-3-logo.png log-CSS3.png # __Cambiamos el nombre del archivo__


13.- git commit -m "Cambio nombre LOGO"


14.- git reset --soft HEAD~1 #Borro el commit anterior


15.- git mv log-CSS3.png Favicon.png


16.- git commit -m "cambios al HEAD"


17.- git remote add origin https://github.com/Andres-Heras/WEB_CSS.git


18.- git push origin master #Subimos al repositorio remoto creado al principio del video (GITHUB)


19.- ## Subido el archivo borro el repositorio LOCAL


20.- cd /c/users/q92he/"Google drive"/Proyectos/Github


21.- git clone https://github.com/Andres-Heras/WEB_CSS.git


22.- cd /c/users/q92he/"Google drive"/Proyectos/Github/WEB_CSS


23.- git init # __Iniciamos el repositorio__


24.- git add . # __Ponemos los archivos en seguimiento__


25.- git commit -m "Repositorio clonado"


26.- git pull  https://github.com/Andres-Heras/WEB_CSS.git


27.- git show # __Para ver toda la información del repositorio añadida.__


28.- git branch CSS # __Creamos la rama CSS__


29.- git checkout -b "HTML" # __Creamos la rama HTML y empezamos a trabajar sobre ella_


30.- ## Introduzco los Metadatos y el Formulario


31.- git add .


32.- git commit -m"Cambios HTML"


33.- git checkout CSS # __Cambio de rama__


34.- ## Pasamos el CSS a un archivo externo (estilo)


35.- git status


36.- git add .


37.- git commit -m "CSS Archivo externo"


38.- ## Colaboración en Github añadiendo LAYOUT a la web


39.- git pull  https://github.com/Andres-Heras/WEB_CSS.git


40.- git  commit -m "Conflicto resueltos"


41.- git log --oneline --graph --color --all --decorate # Modo gráfico para ver información


42.- git checkout master #__Cambio de rama__


43.- git diff HTML master #__Diferencias de ramas


44.- git merge HTML # __Uno la rama HTML__


45.- git merge css #__Uno la rama CSS__


46.- git fetch origin # __Actualizamos con el repositorio remoto__


47.- git push origin


