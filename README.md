Ejercicio 1
- ¿Qué comando utilizaste en el paso 11? ¿Por qué?
  Utilicé git reset --hard HEAD~1 con el objetivo de perder los cambios realizados en el working copy tal y como se expresaba.
- ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?
  He utilizado reflog para buscar el commit al que quería volver y después hice git reset --hard a289bc2 ya que era el código del anterior commit.
- El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?
  No causó ningún conflicto pero me apareció este mensaje "Already up to date". No hay conflicto porque los cambios no son contradictorios, es decir las modificaciones se han realizado en líneas diferentes.
- El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?
  Sí ha causado un conflicto porque he modificado la misma línea en dos ramas diferentes, en este caso me quedo con los cambios hechos en styled tal y como dice el ejercicio.
- El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?
  No ha causado ningun conflicto, ha hecho un merge fast forward, ya que los cambios que hice en ambas ramas no se solapan.
- ¿Qué comando o comandos utilizaste en el paso 25?
  El comando que he realizado es el siguiente $ git log --graph --decorate --pretty=oneline
- El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?
  No podría ser fast forward ya que he realizado en la rama main algunos cambios que no están en title.
- ¿Qué comando o comandos utilizaste en el paso 27?
  Utilicé git reflog para el el codigo del commit la que queria acceder y después git reset --soft a12086f utilicé soft para no perder los cambios del working copy.
- ¿Qué comando o comandos utilizaste en el paso 28?
  Utilicé git reset --hard para descartar los cambios realizado en el working copy y en el staging area.
- ¿Qué comando o comandos utilizaste en el paso 29?
  Usé el comando git branch -d title 
- ¿Qué comando o comandos utilizaste en el paso 30?
  Usé git reset --hard a12086f ya que ese era el código del commit al que quería acceder.
- ¿Qué comando o comandos usaste en el paso 32?
  Utilicé git reset --hard 65187df
- ¿Qué comando o comandos usaste en el punto 33?
  Usé git reset --hard a569102
