# prueba_clases_git
comandos git

WORKING DIRECTORY -> STAGING AREA -> REPOSITORY


git init	Inicializa un nuevo repositorio Git en el directorio actual.
git clone <URL>	Clona un repositorio Git existente desde una URL remota al directorio local.
git status	Muestra el estado actual del repositorio (archivos modificados, por añadir, etc.).
git add <archivo>	Añade cambios de archivos al área de preparación (staging).
git commit -m "mensaje"	Confirma los cambios añadidos al repositorio con un mensaje descriptivo.
git pull	Obtiene y fusiona cambios desde un repositorio remoto al branch local. (Trae cambios q hicieron desarrolladores)

git push	Envía cambios confirmados localmente a un repositorio remoto.
git checkout <rama>	Cambia a otra rama en el repositorio.
git branch	Lista todas las ramas locales y resalta qué rama actual me encuentro.
git merge <rama>	Fusiona los cambios de otra rama a la rama actual.
git log	Muestra el historial de commits del repositorio.

git diff	Muestra las diferencias entre el área de trabajo y el área de preparación (staging).
git reset HEAD <archivo>	Quita archivos del área de preparación (staging), pero conserva los cambios en el directorio de trabajo.
git push origin <rama>	Envía los cambios confirmados localmente en una rama específica al repositorio remoto llamado origin.
git checkout main	Cambia a la rama principal (main o master) del repositorio.
git show <objeto>	Muestra información detallada sobre un commit, tag, o un objeto específico en el repositorio.
