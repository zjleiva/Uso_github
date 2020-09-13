---- Comandos git de ayuda

Iniciar un repositorio
--> git init

Agregar archivo al repositorio
--> git add archivo.txt

Agregar modificaciones antes del commit
--> git add .
        El . indica agregar todos los archivos modificados

Realizar commit del los archivos agregados anteriormente
--> git commit -m "(descripcion de lo que se ha modificado o lo que se ha agregado)"

Estado del proyecto
--> git status

Leer el log de los commit del proyecto
--> git log --oneline

Conocer cuantas ramas tiene nuestro proyecto
--> git branch

Agregar una rama al proyecto
--> git checkout -b nuevarama ("Nombre de la nueva rama")

Cambiar de rama en la edicion 
--> git checkout nuevarama ("Nombre de la Rama ")
    "master" es la rama principal

Mezclar las ramas del proyecto o sea agregar las nuevas ramas al rama "master"
--> git merge nuevarama

Si es necesario Borrar la rama agregada a la "master"
--> git checkout -d nuevarama

