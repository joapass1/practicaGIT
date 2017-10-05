# PracticaGit - Respuestas

--
**1. ¿Qué comando utilizaste en el paso 11? ¿Por qué?**
`git reset --hard HEAD~1`

Porque de este modo volvemos atrás perdiendo los cambios realizados. 

--

**2. ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?**

`git reflog` + `git reset --hard 569dff2`

Primero usamos el git reflog para que nos muestre el historial por el que nos hemos movido y cuando localizamos el paso al que queremos volver, o en este caso recuperar, copiamos su número de referencia y lo pegamos a continuación del comando git reset --hard, de esta manera volvemos al paso antes de borrar el commit.

--

**3. El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?**

Realmente no ha causado ningún conflicto, lo único que nos ha dicho que la información ya estaba fusionada realmente.

--

**4. El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?**

Ha causado conflicto ya que hemos creado dos commits iguales en ramas distintas con lo cuál los ha fusionado de alguna manera. De manera que abrimos el archivo y lo modificamos quedandonos con el contenido de styled. 

--

**5. El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?**

No ha causado ningún conflicto porque eran dos ramas distintas que se han fusionado, todo estaba en orden y no había varios commits creados en cada una de ellas. 

--

**6. El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?**

No ha causado ningún conflicto ya que ya habíamos solucionado anteriormente el problema de los commits fusionados, ha realizado un merge fast-forward. 

--

**7. ¿Qué comando o comandos utilizaste en el paso 25?**

`git graph`

--

**8. El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?**

Sí, porque las ramas estaban en la misma línea y no separadas, de manera que el merge no podía ser no fast-forward. 

--

**9. ¿Qué comando o comandos utilizaste en el paso 27?**

`git reset HEAD~1`

--
**10. ¿Qué comando o comandos utilizaste en el paso 28?**

`git diff HEAD` + `git checkout -- don-quijote.md`

Con el primer comando compararmos lo que tenemos en el staging con el repositorio y con el segundo descartamos los cambios si queremos quedarnos con lo que tenemos en el repositorio, que en este caso es el archivo sin el título.

--

**11. ¿Qué comando o comandos utilizaste en el paso 29?**

`git branch -d title` + `git branch -D title`

Al utilizar el primero nos preguntará si estamos seguros de eliminar la rama, y en caso de que sea así debemos usar el mismo comando pero cambiando la D minúscula por mayúscula. 

--

**12. ¿Qué comando o comandos utilizaste en el paso 30?**

`git reflog` + `git reset --hard 20228ca`

--

**13. ¿Qué comando o comandos usaste en el paso 32?**

`git reflog` + `git reset --hard 513dfc0`

--

**14. ¿Qué comando o comandos usaste en el punto 33?**

`git reflog` + `git reset --hard 20228ca`

--

