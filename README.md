# REPOSITORIO CAMPUSCIFF
#2.1 Crear un repositorio en vuestro GitHub llamado campusciff
![picture alt] /images/foto crear repositorio
#2.2 Clonar el repositorio en local
   * git clone git@github.com:ffsolana/campusciff.git

#2.3 Crear (si no lo habéis creado ya) en vuestro repositorio local un documento README.md
   * Fichero README.md creado con la opción disponible al iniciar el repositorio
#2.4 Añadir al README.md los comandos utilizados hasta ahora y hacer un commit inicial con el mensaje "commit inicial"
   *git add .
   *git commit -m "Commit inicial"
#2.5 Subir los cambios al repositorio remoto
   *git push origin master
#2.6 Ignorar archivos (I)  
   1. Crear en el repositorio local un fichero llamado privado.txt
      *touch privado.txt
   2. Crear en el repositorio local una carpeta llamada privada
      *mk dir privado
#2.7 Ignorar archivos (II)
      *echo -e "privado.txt \nprivada/" > .gitignore
      *git add .
      *git commit -m "Crear fichero .gitignore y volcar los ficheros a ignorar
#2.8 Añadir fichero 1.txt al repositorio local
      *touch 1.txt
      *git add .
      *git commit -m "Crear fichero 1.txt"
#2.9 Crear Tag
      *git tag V0.1
      *git add .
      *git commit -m "Crear etiqueta V0.1"
#2.10 Subir los cambios al repositorio
      *git push --tag origin master
#2.11 Crear la rama V0.2
  1. Crear la rama
      *git branch V0.2
  2. Posicionar la carpeta de trabajo en la rama creada
      *git checkout V0.2
#2.12 Añadir fichero en la rama V0.2
      *touch 2.txt
      *git add .
      *git commit -m "Crear fichero 2.txt en rama V0.2
#2.13 Subir cambios al repositorio
      *git push origin V0.2
#2.14 Merge Directo
    1. Situarse en la rama master
      *git checkout master
    2. Hacer un merge
      *git merge V0.2
#2.15 Merge con conflicto
    1. En la rama master poner Hola en el fichero 1.txt y hacer commit
      *echo Hola > 1.txt
      *git add .
      *git commit -m "añadir tecto al fichero 1.txt"
#2.16 Merge con conflicto (II)
    1. Posicionarse en la rama v0.2 y poner Adios en el fichero "1.txt" y hacer commit
      *git checkout V0.2
      *echo Adios > 1.txt
      *git add .
      *git commit -m "Añadir adios al fichero 1.txt en la rama V0.2
#2.17 Merge con conflcto (III)
    1. Posicionarse de nuevo en la rama master y hacer un merge con la rama v0.2
      *git checkout master
      *git merge V0.2
#2.18 Listar las ramas con merge y las ramas sin merge
      *git branch --merged
      *git branch --no-merged
#2.19 Arreglar el conflicto anterior y hacer un commit
      *El conflicto que ha dado es Already up-to-date



