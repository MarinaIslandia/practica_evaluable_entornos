Comandos usados para la practica
cd - cambio de directorio
mkdir - crear directorio
git init - inicializar directorio como repositorio Git
touch - crear archivo
echo - editar archivo añadiendo texto
git add . - añade todos los archivos al working
git add deocument1.txt - añade el document1.txt al working
git commit - valida los archivos del working
git commit -m - valida los archivos y te deja poner un mensaje sin abrir el editor de texto
git status - te enseña el estado de tu repositorio
git log - te enseña los commits y sus numeros de referencia
git log --oneline - simplifica el log de commits
git reset - Deshacer cambios 
git revert 123 - Deshacer commits (hasta el commit 123)
git revert HEAD - Deshacer ultimo commit 
ll - lista de archivos y directorios con informacion
ls - listar archivos y directorios simple
git remote add URL - conecta el repositorio de la URL al local
git push origin master - Envia los cambios realizados a la rama "master" en el repositorio local 
al repositorio remoto "origin"
git checkout mirama / master - Cambiar entre ramas 
git branch - Enseña una lista de las ramas, en verde y con un asterisco te sale la rama en la que estas
git branch mirama - Crea una rama llamada mirama
git branch -D mirama - Elimina la rama mirama (hay que estar en otra rama para hacerlo)
git branch -v -a - Muestra una lista de las ramas -v te da info de los commits de las ramas y
-a muestra las ramas remotas y las locales
git tag V1 - Crea una etiqueta llamada V1 en el repositorio actual
git ls-remote--tags origin - Muestra informacion de las referencias del repositorio, --tags es para mostrar
solo la info de las etiquetas y origin muestra la info de ese repositorio
git clone URL practica_evaluable_2 - clona el repositorio remoto de la URL en un repositorio local y lo 
nombra practica_evaluable_2
git merge mirama - Fusiona los cambaios de la rama mirama al repositorio actual
git merge origin/master - Fusiona los cambios de la rama remota master en la rama local actual
vim document.txt - Abre el archivo document.txt en el editor de texto, lo usamos para resolver un conflicto
de versiones
