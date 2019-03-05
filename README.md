- cd /c/users/q92he/"Google drive"/Proyectos/Github #Localizamos nuestro directorio de trabajo
- mkdir Web_CSS # Creamos la carpeta del directorio de trabajo
[x]cd /c/users/q92he/"Google drive"/Proyectos/Github/Web_CSS # Entramos en la carpeta de directorio de trabajo
#Creamos o copiamos los archivos en el directorio de trabajo
[x]git init #Creamos el repositorio
[x]git status #Archivos sin seguimiento
[x]git add . #Ponemos los archivos en seguimiento
[x]git status #Archivos en seguimiento 
(hago cambios en los archivospara usar el diff)
[x]git commit -m "Archivos al HEAD"
[x]git rm "Facebook.html" #Borro el arhcivo Facebook.html del HEAD
[x]git commit -m "FB borrado"
[x]git mv css-3-logo.png log-CSS3.png # Cambiamos el nombre del archivo
[x]git commit -m "Cambio nombre LOGO"
[x]git reset --soft HEAD~1 #Borro el commit anterior
[x]git mv log-CSS3.png Favicon.png
[x]git commit -m "cambios al HEAD"
- git remote add origin https://github.com/Andres-Heras/WEB_CSS.git 
- git push origin master #Subimos al repositorio remoto creado al principio del video (GITHUB)
Subido el archivo borro el repositorio LOCAL


[x]cd /c/users/q92he/"Google drive"/Proyectos/Github 
[x]git clone https://github.com/Andres-Heras/WEB_CSS.git
[x]cd /c/users/q92he/"Google drive"/Proyectos/Github/WEB_CSS
[x]git init #Iniciamos el repositorio
[x]git add . #Ponemos los archivos en seguimiento
[x]git commit -m "Repositorio clonado" 

[]git pull  https://github.com/Andres-Heras/WEB_CSS.git
[x]git show # Para ver toda la información del repositorio añadida.
[x]git branch CSS #Creamos la rama CSS
[x]git checkout -b "HTML" #Creamos la rama HTML y empezamos a trabajar sobre ella
Metadatos
Formulario en español en contacto
[x]git add .
[x]git commit -m"Cambios HTML"
[]git checkout CSS
Cambio de colores
TITULOS
Archivo CSS externo
git status
git add .
git commit -m "CSS Archivo externo"
Layout (ALTEREGO)

[x]git pull  https://github.com/Andres-Heras/WEB_CSS.git
[x]git commit -m "Conflicto resueltos"
[x]git log --oneline --graph --color --all --decorate # Modo gráfico para ver información
[x]git checkout master
[x]git diff HTML master
[x]git merge HTML
[x]git merge css
[x]git fetch origin
[]git push origin
[]Insertamos un formulario en contacto
[]<meta name="viewport" content="width=device-width, initial-scale=1.0">
[]

	* 
git fetch is the command that says "bring my local copy of the remote repository up to date."
	* 
git pull says "bring the changes in the remote repository to where I keep my own code."






