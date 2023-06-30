# ejercicio-1-git

1. Git reset —hard HEAD~1, porque para deshacer el último commit perdiendo los cambios realizados en el working copy hay que usar ese comando o también se puede usar “git reset HEAD~1 + git restore <file>”
2. En el paso 12 he usado “git reflog” para obtener el ID del commit al que deseo volver. Después he usado el comando git reset <ID del commit> para restaurar el commit que he elegido con el ID. Y por último he usado git restore <nombre del archivo>  para restaurar el estado del archivo “git-nuestro.md”.
3. No ha causado ningún conflicto, cuando usé el comando “git merge main” me dio el mensaje “Already up to date”.
4. En el paso 19 si me ha creado conflicto porque me pedía con que contenido de las dos ramas me quería quedar, elegí el contenido de la rama styles para resolver el conflicto.
5. En el paso 21, no me causó ningún conflicto. Realizó correctamente el merge.
6. En el paso 25 he utilizado el comando “git log —graph”
7. No porque crearía conflicto y podríamos perder todos los cambios
8. En el paso 27 usé un “git log” para obtener el identificador del commit al que quería volver. Luego he usado el comando “git reset —hard <identificador del commit>” para volver al commit deseado.
9. En el Paso 28 he usado el comando “git reset —hard HEAD”
10. En el paso 29 he usado el comando “git branch -D title”
11. En el paso 30 he usado el comando “git reflog” para obtener el identificador del commit en el que he hecho el merge con la rama main y la rama title y después he utilizado el comando “git reset <identificador del commit>” para volver al commit anteriormente mencionado.
12. En el paso 32 he usado el comando “git log —oneline” para obtener el identificador del primer commit de todos y después use este en el comando “git checkout <identificador>” para volver al primer commit
13. En el paso 33 volví a usar “git log” para obtener el id del commit en el que le puse el titulo al archivo y use de nuevo el comando “git checkout <id>” para volver a dicho commit
