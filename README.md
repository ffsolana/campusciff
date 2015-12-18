# REPOSITORIO CAMPUSCIFF
## 2.1 Crear un repositorio en vuestro GitHub llamado campusciff
![imagen repositorio] (C:\Users\NENITOS\Desktop\Crear repositorio.png)
##2.2 Clonar el repositorio en local
###   git clone git@github.com:ffsolana/campusciff.git
## 2.3 Crear (si no lo habéis creado ya) en vuestro repositorio local un documento README.md
###   Fichero README.md creado con la opción disponible al iniciar el repositorio
## 2.4 Añadir al README.md los comandos utilizados hasta ahora y hacer un commit inicial con el mensaje "commit inicial"
###   git add .
###   git commit -m "Commit inicial"
## 2.5 Subir los cambios al repositorio remoto
###   git push origin master
## 2.6 Ignorar archivos (I)  
###   1. Crear en el repositorio local un fichero llamado privado.txt
####      touch privado.txt
###   2. Crear en el repositorio local una carpeta llamada privada
####      mk dir privado
## 2.7 Ignorar archivos (II)
###  echo -e "privado.txt \nprivada/" > .gitignore
###  git add .
###  git commit -m "Crear fichero .gitignore y volcar los ficheros a ignorar
## 2.8 Añadir fichero 1.txt al repositorio local
###  touch 1.txt
###  git add .
###  git commit -m "Crear fichero 1.txt"
## 2.9 Crear Tag
###  git tag V0.1
###  git add .
###  git commit -m "Crear etiqueta V0.1"
## 2.10 Subir los cambios al repositorio
###  git pull --tag origin master
## 2.11 Crear la rama V0.2
###  1. Crear la rama
###    git branch V0.2
###  2. Posicionar la carpeta de trabajo en la rama creada
###    git checkout V0.2
## 2.12 Añadir fichero en la rama V0.2
###  touch 2.txt
###  git add .
###  git commit -m "Crear fichero 2.txt en rama V0.2
## 2.13 Subir cambios al repositorio
###  git pull origin V0.2
## 2.14 Merge Directo
###  1. Situarse en la rama master
###    git checkout master
###  2. Hacer un merge
###    git merge V0.2
## 2.15 Merge con conflicto
###  1. En la rama master poner Hola en el fichero 1.txt y hacer commit
###    echo Hola > 1.txt
###    git add .
###    git commit -m "añadir tecto al fichero 1.txt"
## 2.16 Merge con conflicto (II)
###  1. Posicionarse en la rama v0.2 y poner Adios en el fichero "1.txt" y hacer commit
###    git checkout V0.2
###    echo Adios > 1.txt
###    git add .
###    git commit -m "Añadir adios al fichero 1.txt en la rama V0.2
## 2.17 Merge con conflcto (III)
###  1. Posicionarse de nuevo en la rama master y hacer un merge con la rama v0.2
###    git checkout master
###    git merge V0.2
## 2.18 Listar las ramas con merge y las ramas sin merge
###  git branch --merged
###  git branch --no-merged
## 2.19 Arreglar el conflicto anterior y hacer un commit
#### El conflicto que ha dado es Already up-to-date
## 2.20 Borrar rama
###   1. Crear un tag V0.2
####    git tag -a V0.2 -m "Crear tag v0.2"
###   2. Borrar rama Vo.2
####    git branch -d V0.2
## 2.22 Cuenta de GITHUB
###   1. Poner una foto en el perfil de GITHUB
####    Hecho
###   2. Poner el doble factor de autentificación en la cuenta de GITHUB
####    Hecho
###   3. Añadir (si no lo habéis hecho ya) la clave pública que se corresponde a tu ordenador
####    Hecho durante la sesión de clase
## 2.23 Uso social de GITHUB
###   1. Preguntar los nombres de usuario de GitHub de tus compañeros de clase, búscalos, y sigueles
####    Hecho
###   2. Seguir los repositorios campusciff del resto de tus compañeros
####    Hecho
###   3. Añadir una estrella a los repositorios campusciff del resto de tus compañeros
####    Hecho
## 2.24 Crear una tabla
|        *NOMBRE*        |             CUENTA GITHUB            |
| ---------------------- | ------------------------------------ |
| Carlos Paz             | http://github.com/cpazsantos         |
| Pablo Suarez           | https://github.com/pablosuarezmanjon |
| Julián Gómez           | http://github.com/CIFFjuliangomez    |
## 2.25 COLABORADORES
###   1. Poner a github.com/asanzdiego como colaborador del repositorio campusciff
####    Hecho
## 2.26 Crear Organización
###   1. Crear una organización llamada campusciff-tunombredeusuariodegithub
####    Hecho
## 2.27 Crear equipos
###   1. Crear 2 equipos en la organización campusciff-tunombredeusuariodegithub, uno llamado administradores con más permisos y otro colaboradores con menos permisos
####    Hecho
###   2. Meter a github.com/asanzdiego y a 2 de vuestros compañeros de clase en el equipo administradores
####    Hecho
###   3. Meter a github.com/asanzdiego y a otros 2 de vuestros compañeros de clase en el equipo colaboradores
####    Hecho
