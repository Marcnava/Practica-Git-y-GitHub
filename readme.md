# PRIMERA PRÁCTICA DEL BOOTCAMP MOBILE EN *KEEPCODING*
## Git y GitHub

<details>
  <summary>Contenidos</summary>
  <ol>
    <li><a href="#tecnologías-utilizadas">Stack - Tecnologías utilizadas</a></li>
    <li><a href="#qué-he-aprendido">Qué he aprendido</a></li>
    <li><a href="#objetivo">Objetivo práctica></li>
    <li><a href="#ejercicio-de-la-práctica">Ejercicio práctica</a></li>
    <li><a href="#graph">Graph</a></li>
    <li><a href="#agradecimientos">Agradecimientos</a></li>
  </ol>
</details>

---
### Tecnologías utilizadas
![Static Badge](https://img.shields.io/badge/git-orange?style=for-the-badge&logo=git&logoColor=white) ![Static Badge](https://img.shields.io/badge/github-black?style=for-the-badge&logo=github&logoColor=white) ![Static Badge](https://img.shields.io/badge/visual_studio_code-0078d7?style=for-the-badge&logo=visualstudiocode&logoColor=white)

---
### Qué he aprendido

- Crear repositorios locales y remotos
- Comandos para moverme entre los commits, ramas, mergear...

    `init` `log` `reflog` `status` `add` `commit` `show` `diff` `stash` `clone` `remote` `push` `pull` `fetch` `branch` `checkout` `tag` `merge` `rebase` `restore` `reset`
  
- Funcionamiento de Git: qué hacen los comandos por detrás. Gracias a esto puedo usar Git con o sin interfaz gráfica y solucionar los problemas que me surjan

---
### Objetivo

Para esta práctica debía:
- Crear un repositorio local
- Generar varios commits
- Crear varias ramas y etiquetas
- Deshacer cambios y recuperar datos perdidos
- Mergear diferentes ramas
- Crear un repositorio remoto y vincularlo con mi repositorio local
- Manejar el repositorio remoto creando commits, ramas, deshaciendo cambios...

---
### Ejercicio de la práctica

> Este apartado va dirigido al profesor

La práctica incluye responder a ciertas preguntas teóricas relacionadas con el repositorio creado.

#### Preguntas del ejercicio

1. ¿Qué comando utilizaste en el paso 11? ¿Por qué?
    - git reset --hard HEAD~1 para vovler al commit anterior y con "--hard" 
    modificar mi working copy

2. ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?
    - git log para localizar el HASH del commit deshecho y copiarlo
    - git reset id-commit para volver al commit con los cambios

3. El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?
    - Sí. Una rama que tiene más cambios guardados no puede unirse a otra que 
    es más antigua (menos cambios guardados)

4. El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?
    - Sí. Ambas ramas tenian un archivo con modificaciones en las mismas 
    líneas. Después de elegir con qué cambios me quedaba he finalizado el 
    merge siendo éste un no fast forward

5. El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?
    - No. En la rama main no se realizó ningún cambio, simplemente ésta 
    absorvió los cambios nuevos de la rama styled

6. ¿Qué comando o comandos utilizaste en el paso 25?
    - git log --graph

7. El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?
    - Sí, con el comando git merge --no-ff title
    -  Si no se usa éste comando, git hace por defecto un fast forward ya que
    no es necesario crear un commit nuevo, solo moviendo la rama main al
    commit de title tiene todos los cambios nuevos

8. ¿Qué comando o comandos utilizaste en el paso 27?
    - git reset HEAD~1

9. ¿Qué comando o comandos utilizaste en el paso 28?
    - git restore --staged nombre-archivo

10. ¿Qué comando o comandos utilizaste en el paso 29?
    - git branch -D title

11. ¿Qué comando o comandos utilizaste en el paso 30?
    - git reflog para copiar el HASH del commit donde estaba title
    - git branch title id-commit
    - git merge title

12. ¿Qué comando o comandos usaste en el paso 32?
    - git log para copiar el HASH del commit inicial
    - git reset id-commit-inicial

13. ¿Qué comando o comandos usaste en el punto 33?
    - git reflog para localizar el commit donde puse el título y copiar su 
    HASH
    - git reset id-commit para volver al estado final

---
### Graph

![Git 
graph](./Captura%20de%20pantalla%202023-07-03%20a%20las%200.49.21.png)

---
### Agradecimientos

Agradecer al profesor por sus excelentes clases.

- **Alberto**

<a href="https://github.com/kasappeal" target="_blank"><img alt="Static Badge" src="https://img.shields.io/badge/github-black?style=for-the-badge&logo=github&logoColor=orange"></a>
