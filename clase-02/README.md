# CLASE 02

https://github.com/abhisheknaiidu/awesome-github-profile-readme

## Repaso

## Para Vincular el Repostorio Local con el siguiente Repositorio Remoto
    Copiar URL del repo "git remote add origin https://github.com/Axfroy/git-pescar.git"

## Para verificar eso
    git remote
    Origin => Es el estandar 

    git remote -v 

##  
git push -u origin main
Push es subir, empujar al remoto, 
-u Es  como una banderita que hay que hacer una vez sla, define todo lo que yo tenga en master, se va a subir siempre a origin "esas ramas", a la master(tiene que coincidir con la rama principal que aparece en la ruta de acceso)

## Agregar remoto en repositorio local 
    git remote add origin <URL>

## Verificar que este configura el remoto
    git remote
    git remote -v

## Status de los Archivos
    UNTRACED => Archivos que no se agregaron al index (Staging Area) y por conseucnia no se les hara seguimientos

    STAGED => Archivos que fueron agregados al area temporal o Staging Area

    UNMODIFIED => Archivos que se encuentran en el repositroio y que no fueron modificados

    MODIFIED => Archivso que se encuentran en el repositirio pero difieren con los que se encuentran actualemnete en el directorio de trabajo (Working Directory)

## Git amend
Agregar algo que me olvide en el ultimo commit
Tmb se puede modificar el comentario
    git add . o <archivo>
    git commit --amend

![status_archivos](img/ruta){width='200px'}

