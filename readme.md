# PRIMERA PRÁCTICA DEL BOOTCAMP MOBILE EN *KEEPCODING*

## Git y GitHub

### Preguntas de la práctica:

¿Qué comando utilizaste en el paso 11? ¿Por qué?
- git reset --hard HEAD~1 para vovler al commit anterior y con "--hard" 
modificar mi working copy

¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?
- git log para localizar el HASH del commit deshecho y copiarlo
- git reset id-commit para volver al commit con los cambios

El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?
- Sí. Una rama que tiene más cambios guardados no puede unirse a otra que 
es más antigua (menos cambios guardados)

El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?
- Sí. Ambas ramas tenian un archivo con modificaciones en las mismas 
líneas. Después de elegir con qué cambios me quedaba he finalizado el 
merge siendo éste un no fast forward 

El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?
- No. En la rama main no se realizó ningún cambio, simplemente ésta 
absorvió los cambios nuevos de la rama styled

¿Qué comando o comandos utilizaste en el paso 25?
- git log --graph

El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?
- Sí, con el comando git merge --no-ff title
- Si no se usa éste comando, git hace por defecto un fast forward ya que 
no es necesario crear un commit nuevo, solo moviendo la rama main al 
commit de title tiene todos los cambios nuevos

¿Qué comando o comandos utilizaste en el paso 27?
- git reset HEAD~1

¿Qué comando o comandos utilizaste en el paso 28?
- git restore --staged nombre-archivo

¿Qué comando o comandos utilizaste en el paso 29?
- git branch -D title

¿Qué comando o comandos utilizaste en el paso 30?
- git reflog para copiar el HASH del commit donde estaba title
- git branch title id-commit
- git merge title

¿Qué comando o comandos usaste en el paso 32?
- git log para copiar el HASH del commit inicial
- git reset id-commit-inicial

¿Qué comando o comandos usaste en el punto 33?
- git reflog para localizar el commit donde puse el título y copiar su 
HASH
- git reset id-commit para volver al estado final

Así quedaría el graph:

![Git 
graph](https://github.com/Marcnava/Practica-Git-y-GitHub/blob/main/Captura%20de%20pantalla%202023-07-03%20a%20las%200.49.21.png?raw=true)

