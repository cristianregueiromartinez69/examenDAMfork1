# examenDAM
**Explicación del fork:**
1. nos fuimos al repositorio el cual queremos hacer un fork y le damos donde pone fork
2. le damos el nombre que queramos y se nos crea un repositorio con la información del fork
3. en el repositorio ya nos indica que es un fork lo que tenemos
4. nos vamos al terminal y nos ponemos en el directorio en el que queremos trabajar
5. git init por si no lo tenemos iniciado
6. git clone -o (nombre que quieras) url del repositorio clonado
7. se nos crea una carpeta con el nombre del repositorio clonado
8. cd al directorio clonado
9. modificaciones y añadimos programas o lo que queramos.
10. git add (archivos que queramos añadir)
11. git commit -m (comentario de lo que hicimos)
12. git remote add origin (url de tu repositorio con fork)
13. git push -u origin (main/master)

***Explicación del gitignore:***

1. en nuestro terminal, vemos que hay archivos que, a lo mejor por error, podríamos llegar a subir
2. para eso está el gitignore, para añadir archivos que son confidenciales o que no aportan nada si se suben por error
3. vemos que archivos son y click derecho en ellos
4. vemos que hay una opción llamada git y que tiene una barra
5. le damos y arriba aparece la opcíon add y luego add to gitignore.
6. le damos y ese archivo ya está en el gitignore
7. luego, si quieres, puedes subirlo como haré yo ahora por lo del examen, pero lo recomendable es ~~NO HACERLO~~