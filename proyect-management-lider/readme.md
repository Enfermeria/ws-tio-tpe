# Secuencias de Comandos Usados

## Problemas 1 y 2

1. **Clona el repositorio**:
git clone https://github.com/nombre.usuario/nombreDelRepositorio.git


Cambia al directorio del repositorio clonado:
cd ws-tio-tpe

Contribuir al proyecto y trabajar en ramas separadas:

Verificar las ramas existentes (buena práctica):git branch

Contribuir al proyecto y trabajar en ramas separadas:

Verificar las ramas existentes (buena práctica): git checkout -b proyect-management

 Verificar que la rama se ha creado y se está trabajando en ella: git branch: LLa rama actual tiene un asterisco * junto a su nombre.


## Problemas 3 y 4


Trabajé en mi respectiva rama. Simulé cambios relevantes relacionados con mi rol en el proyecto (líder).

Creé archivos dentro de mi carpeta project-management-lider:

licenciasYPrecios.txt
NuevaFormaPago.txt
revisionDoc.txt
Por cada uno de los archivos modificados, usé los siguientes comandos:

git status
git add nombre_del_archivo
git commit -m "mensaje descriptivo del cambio hecho"


Siempre asegurándome de estar en la rama correcta con: git checkout proyect-management-  Completé tres confirmaciones con cambios simulados relacionados con las tareas del Líder de Proyecto.


## Problemas 5:Para mostrar las diferencias entre la primera confirmación (commit) y la última:

Obtuve los identificadores (hash) de los commits usando el comando: V

Mostré las diferencias entre el primer y el último commit: git diff 904405 HEAD o git diff hash-primer-commit hash-último-commit
Se deja una captura de pantalla del archivo: diferenciasEntrePrimerCommitYactual para mostrar la evidencia de dicho paso.


## Problemas 6:Para fusionar los cambios que hice a la rama principal del proyecto, NO eliminar la rama local:


Para saber cuál es la rama principal: git branch. Me doy cuenta que es main y no master.

Me cambié a la rama principal: git checkout main

Actualicé la rama principal con los cambios más recientes: Antes de hacer la fusión, es recomendable actualizar la rama principal con los últimos cambios remotos (si otros colaboradores han trabajado en la rama principal). Se supone que no, porque esta etapa del TPE era trabajar todo en local.
Fusioné los cambios de la rama de trabajo a la rama principal:

git merge project-manayement

Después de fusionar, verifiqué que todo esté en orden:git status


## Problema 8: Para crear un commit que deshaga los cambios introducidos:

Elegí revertir el segundo commit: 0ffc195 "nueva forma de pago averiguaciones".

Deshacer dicho commit usando:git revert 0ffc195 Se deja captura gitRrevert.png, se guarda un commit de ese revert.













para saber cual es la rama princiapl git brnach me doy cuenta q es  main y no master

me Cambie a la rama principal :git checkout main

Actualice la rama principal con los cambios más recientes :
Antes de hacer la fusión, es recomendable actualizar la rama principal con los últimos cambios remotos (si otros colaboradores han trabajado en la rama principal) se supone que no porque esta etapa del TPE era trabajar todo en local

Fusione los cambios de la rama de trabajo a la rama principal
Después de fusionar,  verifique  que todo esté en orden git status:


Problema 8:Crear un commit que deshaga los cambios introducidos: se eligio que se va a revertir el segndo commit 0ffc195 "nueva forma de pago averiguaciones"

Deshacer dicho commit usando git revert. se deja captura gitRrevert.png, se guarda un comit de ese revert

