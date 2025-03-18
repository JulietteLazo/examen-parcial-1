Bitácora del Examen Parcial 1.

Paso 1:
una vez creada mi carpeta en local, accedemos con cd ExamenParcial1, inicializamos con “git init”.
Creamos los 4 archivos con formato “.py”, confirmamos con un “git status” para ver si son visibles.
Una vez hecho esto, nos aparecerá la lista de los 4 archivos en rojo y del lado izquierdo junto con la carpeta, la letra “U”.
Falta prepararlos para que podamos utilizarlos correctamente, así que con el comando “git add *.py” (lo escribimos con el asterisco para que añada todos los archivos que terminen con .py).
Ahora para ver nuestro nuevo avance, vemos el estatus y estos aparecerán en verde con la letra “A”.
Para confirmarlos, utilizaremos un “git commit -m y comentario” para ver que estamos realizando, una vez hecho esto, ya no aparecerá ninguna letra y ya quedaron listos nuestros 4 archivos.

Paso 2:
Ya creado nuestro repositorio en Git Hub, sin seleccionar inicializar con readme, copiamos la url del repositorio.

Paso 3:
Una vez subido el repositorio local al repositorio de git hub.
con el comando 
git remote add origin https://github.com/JulietteLazo/examen-parcial-1.git
git branch -M main
git push -u origin main

Vamos a crear el archivo README de manera manual.

Paso 4:
Vamos a recuperar los cambios realizados en Git Hub a su carpeta local. Para eso utilizamos el comando git pull origin main.
