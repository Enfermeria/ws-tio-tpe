secuencias de comandos usados:

problemas 1,2,3:
clona el repo:
git clone https://github.com/nombre.usuario/nombreDelRepositorio.git

Cambia al directorio del repositorio clonado:
cd ws-tio-tpe

Contribuir al proyecto y trabajar en ramas separadas, ceracion de mi rama especifica:

 Verificar las ramas existentes(buena practica) git branch
crear una rama que refle mi función en el proyecto: git checkout -b project-management

 Verificar que la rama se ha creado y se está trabajando en ella: git branch: La rama actual tiene  un asterisco * junto a su nombre.


problemas 4: trabaje en mi  respectiva rama. Simule cambios relevantes en la relacionados con mi rol en el proyecto (lider). 

Cree archivos dentro de mi carpeta projetc-managemnet-lider :
licenciasYPrecios.txt
NuevaFormaPago.txt
revisionDoc.txt

por cada uno de los archivos  modificados use comandos como : git status, git add nombre del archivo, git  commit-m "mensaje descriptivo del cambio hecho" siemre asegurandome de estar en la rama correcta con git checkout project-management
 complete tres confirmaciones con cambios simulados relacionados con las tareas del Líder de Proyecto



 problema 5: mostrar las diferencias entre la primera confirmación (commit) y la última
primero obtuve los identificadores (hash) de los commits usando el  comando: git log --oneline, 
git diff 904405 HEAD

git diff hash-primer-commit hash-último-commit

se deja una captura de pantalla archivo : diferenciasEntrePrimerCommitYactual para mostrar la evidencia de dicho paso . 


Problema 6:Fusionar los cambios que hicieron a la rama principal de proyecto. NO eliminar
la rama local.
para saber cual es la rama princiapl git brnach me doy cuenta q es  main y no master

me Cambie a la rama principal :git checkout main

Actualice la rama principal con los cambios más recientes :
Antes de hacer la fusión, es recomendable actualizar la rama principal con los últimos cambios remotos (si otros colaboradores han trabajado en la rama principal) se supone que no porque esta etapa del TPE era trabajar todo en local

Fusione los cambios de la rama de trabajo a la rama principal
Después de fusionar,  verifique  que todo esté en orden git status:




