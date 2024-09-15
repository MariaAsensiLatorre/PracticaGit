# **Practica** del curso **Git-GitHub-Sourcetree** de *Keepcoding* impartido por *Alberto Casero*. 

## CUESTIONARIO EJERCICIO 1

- ¿Qué comando utilizaste en el paso 11? ¿Por qué?
	$ git reset --hard HEAD~1 --> deshago un commit de donde estoy con el HEAD 
	virgulilla 1 (un commit abajo) y con --hard deshago tanto stage area como 	working copy

- ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?
	** $ git reflog** porque al ser un GPS de GIT si he deshecho un paso me dirá 	también donde estaba antes de deshacerlo solo con mirar el segundo paso desde 	arriba que indica HEAD{1} y el identificador del commit es mas corto y,

	** $ git reset --hard id_del_commit** --> para volver a rehacer todo en el 	staging area y en el workingcopy y quedarme allí posicionada con HEAD

- El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?
	No hay conflicto porque lo único que se ha modificado es el estilo de 	escritura 

- El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?
	si que causa conflicto porque las líneas del archivo están modificadas en el 	mismo archivo de las dos ramas.

- El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?
  	No, porque la rama main ya estaba mergeada y al quedarme con el git-nuestro.md 	de esta rama se hizo un fast-forward donde se implementa el registro de los 	
- ¿Qué comando o comandos utilizaste en el paso 25?
	**git map** que es un comando que tengo configurado para hacer git log --	graph --pretty=oneline.

- El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?
	si porque la rama title sale de la rama main.

- ¿Qué comando o comandos utilizaste en el paso 27?
	**$ git reset HEAD~1**

- ¿Qué comando o comandos utilizaste en el paso 28?
	**$ git restore git-nuestro.md**

- ¿Qué comando o comandos utilizaste en el paso 29?
	desde la rama main **$ git branch -d title**

- ¿Qué comando o comandos utilizaste en el paso 30?
	**git reflog** y después **$ git reset --hard d6c8646**

- ¿Qué comando o comandos usaste en el paso 32?
	
	**git log** y después **$ git switch --detach  	e763179309e69514962bee322fa73f0c597e213f**

- ¿Qué comando o comandos usaste en el punto 33?

	*git reflog* y después **$ git switch --detach 7797631**
	HEAD is now at 7797631 Añado complemento aclaratorio al título del 	rezo a Git


