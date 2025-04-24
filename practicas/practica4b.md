# Cambios en el historial

Haz un fork del (repositorio de practicas)[https://github.com/oscarnovillo/practicasCursoGit.git]
Hazlo de todas las ramas


1. ### Practicar `git commit --amend`

    Trabajo con el contenido de la rama de ultimo-commit
    con esta instrucción cambios los cambios del último commit

    1.  Realiza un cambio en cualquier archivo (por ejemplo, este mismo `README.md`).
    2.  Añade otro archivo al repositorio (por ejemplo, `archivo.md`):
    3.  Añade el archivo al área de preparación: `git add <nombre_archivo>`
    4.  Modifica el mensaje del último commit: `git commit --amend -m "Nuevo mensaje del commit"`
    5.  Verifica que en el historial de commits el mensaje y los archivos han cambiado
 
2. ### git rebase 

    Trabaja con el contenido de la rama llamada rebase.
    Con esta instrucción cambios todo el historial de la rama.
    1. haz un rebase del primer commit, y realiza las acciones que se indican en el mensaje de los commit.


3. ### git reset, revert
    Trabaja con el contenido de la rama llamada revert
    Git revert es para hacer un commit que revierta los cambios a como estaban antes
    Git reset, borra los commits. Los cambios puedes dejarlos o no.
    1. Haz un revert del commit inicial. Comprueba el historial
    2. Haz un reset soft del commit inicial y un commit de los cambios con el mensaje de commit "reset hecho"
    

