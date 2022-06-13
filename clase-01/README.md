# Comandos de consola

## Crear directorios

    mkdir directorio 1 directorio 2 directorio 3

## Saber donde estoy parado 

    pwd

## Listar directorios

    ls

## Creo archivos vacios 

    touch archivo 1 archivo 2

## Limpio consola

    clear

## Cambio de directorio 

    cd <directorio>

## Salir de un directorio

    cd ..

## Inicializar proyecto git

    git init

## Configurar GIT
Queda siempre configurada para todos los proyectos
git config --global user.name "Ivan Rodriguez"
git config --global user.email "ivane.rodriguez02@gmail.com"

Crees un repo de git, vas a configurar local para ese repo.
git config --local user.name "Ivan Rodriguez"
git config --local user.email "ivane.rodriguez02@gmail.com"


## Comando ejemplo


## Incializar proyecto en git (Crea un repositorio de git)
Entonces, es un repositorio de git por proyecto. Una carpeta o directorio 

    git init

## Veo el estado de los archivos
Pero git no versiona carpetas vacias, no les da pelota

    git status

## GIT: No versioan carpetas
En el caso de querer versionarlas tengo que colocar un archivo. Y estandar por la comunidad es .gitkeep

## Estados de GIT 

### Woring Directory:
Es el area de trabajo. El area sucia, donde interactuo con mis archivos y voy creando el código

### Staging Area / Area intermedia
Cuando uno quiere preservar el estado del archivo en el momento, que se siente a gusto --> GIT add
Preserva y le dice a git que lo prepare para sacarle una foto.  

### Local Repo

    git commit -m "Agrego README.md en la carpeta clase-01"

    git log

    Cunado se bloquea el comando podemos salir con "Q"

## Para ver la informacion de configuracion

    git config --global -l # Salgo con q del comando (quit)
    git config --global --get-regexp user


## Ver la diferencia entre lo que tengo WD y el Repo Local
    git diff clase-01/README.md 
    Me muestra las diferencias con el anterior archivo

## Para ignorar un archivo en particular
Creo el archivo .gitignore. Puede estar en la raiz o no.

Un commit por funcionalidad

## Para 
git log --oneline

## Para ignorar el archivo
.gitignore
