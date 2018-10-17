# Principales comandos GIT
## 1. git config

git config list (listar todos los comandos configurables)

git config --global user.name "Nombre" (configura el nombre del usuario de git)

git config --global user.email email@email.com (configura el correo electrónico del usuario de git)

git config core.editor "nano" (configura el editor por defecto)

## 2. git init
git init (inicializa un nuevo repositorio en el directorio actual)

## 3) git clone
git clone https://github.com/TatyPerson/PruebasConGit.git (clona el repositorio indicado en el directorio actual)

## 4) git add
git add . (agrega todos los archivos nuevos al index)

git add NombreFichero.ext (agrega el archivo indicado al index)

## 5) git status
git status (muestra el estado del repositorio incluyendo la lista de los archivos modificados, los archivos que faltan por añadir, los archivos eliminados, etc..)

## 6) git commit 
git commit -m "Mensaje que describe los cambios realizados" (sube los cambios realizados al repositorio local)

git commit --amend (cambiar mensaje del commit)

## 7) git stash
git stash (guarda los cambios de ficheros que no se quieren enviar a commit temporalmente)

## 8) git rm
git rm NombreFichero.ext (elimina el fichero del directorio local y del remoto)

git rm --cached NombreFichero.ext (elimina el fichero del index)

## 9) git push
git push origin master (sube los cambios realizados al repositorio remoto)

## 10) git pull
git pull (actualiza el directorio de trabajo actual con la versión del repositorio remoto)

## 11) git fetch
git fetch (descarga los ficheros remotos que no están en el directorio de trabajo local)

## 12) git checkout
git checkout -b nombreRama (crea nueva rama)

git checkout nombreRama (cambia a la rama indicada)

## 13) git remote 
git remote -v (listar los repositorios remotos)

## 14) git branch
git branch (listar todas las ramas existentes en el repositorio)

git branch -d nombreRama (borrar la rama indicada)

## 15) git merge
git merge nombreRama (fusiona la rama indicada con la rama activa)

## 16) git diff
git diff --base NombreFichero.ext (lista de conflictos del fichero indicado)

git diff sourceBranch targetBranch (conflictos entre las ramas indicadas que están por fusionar)

git diff (lista de todos los conflictos presentes en el repositorio)

## 17) git tag
git tag 1.1.0 etiquetaCommit (poner etiqueta al commit indicado)

## 18) git log
git log (visualizar el histórico completo de commits)

git log -3 (visualizar los 3 commits más recientes)

## 19) git reset
git reset --hard HEAD (resetea todos los cambios locales del directorio de trabajo)

git reset HEAD NombreArchivo.ext (resetear todos los cambios en el archivo indicado)

