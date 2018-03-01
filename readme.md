- ¿Qué comando utilizaste en el paso 11? ¿Por qué? 
 git reset --hard HEAD~1, ya que nos permite eliminar el ultimo commit, incluyendo el working copy.

- ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?
git reflog para poder visualizar todas las acciones realizadas y copiar el código del commit anteriormente eliminado, utilizando git reset --hard "hash".

- El merge del paso 13, ¿Causó algún conﬂicto? ¿Por qué?    
No, debido a que no hay ningún nodo que pueda causar error
- El merge del paso 19, ¿Causó algún conﬂicto? ¿Por qué?    
 Hay dos archivos con el mismo nombre, por lo tanto debemos   elegir cual debe perdurar.
- El merge del paso 21, ¿Causó algún conﬂicto? ¿Por qué?
No hay conflicto
- ¿Qué comando o comandos utilizaste en el paso 25? 
git log --graph en windows
- El merge del paso 26, ¿Podría ser fast forward? ¿Por qué? 
Si se podría efectuar, pero en este caso se realiza de esta manera para mantener las ramas sin mezclar.

- ¿Qué comando o comandos utilizaste en el paso 27? 
git reset HEAD~1

- ¿Qué comando o comandos utilizaste en el paso 28? 
git reset HEAD~1, además de utilzar git reflog para volver a cargar el commit sin su working copy.

- ¿Qué comando o comandos utilizaste en el paso 29? 
git branch -d(-D) title

- ¿Qué comando o comandos utilizaste en el paso 30?
git reflog para coger el codificador, y el posteior git reset --hard "hash"

- ¿Qué comando o comandos usaste en el paso 32?
mismo procedimiento anterior git reflog más git reset --hard "hash"
- ¿Qué comando o comandos usaste en el punto 33? 
mismo procedimiento anterior git reflog más git reset --hard "hash"