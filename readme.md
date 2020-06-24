Ejercicio 1
Se deberá crear un repositorio y realizar una serie de operaciones desde la consola de
comandos sobre el mismo para posteriormente subir el repositorio a Github.
Se deberá entregar a través del formulario de prácticas indicando la URL del repositorio. En el
repositorio, deberá existir un archivo readme.md con las respuestas a las siguientes preguntas:
- ¿Qué comando utilizaste en el paso 11? ¿Por qué?

- ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?

  git reflog y git reset -hard HEAD@{1}

  git reflog para saber a qué comit tenía que volver y, git reset -hard HEAD@{1}, para mover los punteros HEAD y el de rama styled al estado indicado.

- El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?

  No causó conflictos pero no hizo nada porque ya estaba actualizado y no había nada que fusionar.
  La rama master no se había modificado desde que creó la rama styled.

- El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?

  Sí, porque el archivo git-nuestro.md se había modificado en la rama htmlify y no coincidía con el que tenía styled en la working area.

- El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?

  No causó ningún conflicto porque se trataba de un merge fast forward donde no habían transacciones pendientes de guardar.

- ¿Qué comando o comandos utilizaste en el paso 25?

  git log --graph --decorate --pretty=oneline

- El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?

  Sí, porque las ramas master y title forman una lista.

- ¿Qué comando o comandos utilizaste en el paso 27?

  git reset HEAD~1

- ¿Qué comando o comandos utilizaste en el paso 28?

  git checkout git-nuestro.md

- ¿Qué comando o comandos utilizaste en el paso 29?

  git branch -D title (con -d no lo elimina y da aviso porque el commit se queda detached).

- ¿Qué comando o comandos utilizaste en el paso 30?

  git reset --hard fe1dac3

- ¿Qué comando o comandos usaste en el paso 32?

  git log
  git reset --hard 6258a0d8ee659a90a825f204ff41b8dbaea00b2c

- ¿Qué comando o comandos usaste en el punto 33?
  
  git reflog
  git reset --hard fe1dac3	

Saludos,
Ramón Beltrán Sánchez
