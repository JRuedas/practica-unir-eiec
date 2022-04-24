# Repo para EIEC - DevOps - UNIR


Este repositorio nos servirá para demostrar el uso de Git en la asignatura de EIEC y muchas cosas más.

# Integrantes:
# Jonatan Ruedas Mora
# Ignacio Ferrer Sanz
# Fernando Ares Chicote
# Pedro Angel Moreno Romero

# Práctica 1 de la actividad
# Se realizarán pull requests en GitHub como manejo de repositorios remotos

Este repositorio nos servirá para demostrar el uso de Git en la asignatura de EIEC y muchas cosas mas.

---

Los comandos del Makefile funcionarán en Linux y MacOS. En caso de usar Windows, necesitarás adaptarlos o ejecutarlos en una máquina virtual Linux.

En caso de usar Linux, se debera verificar la versión instalada con el comando:

~~~
python3 --version
~~~

Si posee una versión menor a la 3, es recomendable que a través de su gestor de paquetes actualice la versión.

## Uso

`python3 main.py <filename> <dup> <order>`
  - filename: **ruta** al fichero que contiene la lista de palabras separadas por líneas.
  - dup: **yes|no**
    - `yes` -> elimina duplicadas.
    - `no` -> mantiene la lista.
  - order: **asc|desc** -- Por defecto `asc`
    - `asc` para ordenar ascendentemente.
    - `desc` para ordenar descendentemente.