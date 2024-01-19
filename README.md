# ProyectoLagartija
Heaven Sinners - Action Tower Defense

# IMPORTANTE
Siempre que se quieran descartar cambios no "commiteados" se deberá ``` cerrar el Unreal Engine  ANTES de descartar los cambios ```.

Recomiendo cerrar Unreal siempre que se quiera ejecutar alguna orden relacionada con Github, como son los push, pull, merge, commit, etc.
esto evitará problemas de sincronización y generación de conflictos.

``` En cualquier caso, ante la duda conservad los cambios en local ```

# Organización Archivos Content
El contenido de la carpeta Content está dividido en 2 carpetas "Dynamic" y "Static".

-Dynamic  ->  Se guardarán todos los archivos que serán modificados con frecuencia. Como son los BP o Levels por ejemplo

-Static   ->  Se guardarán archivos que no serán modificados con frecuencia y que pueden llegar a ocupar mucho espacio.
              Como por ejemplo, archivos de sonido, texturas, meshes/modelos...

En el commit de Configuración Inicial (LFS) se puede apreciar sutilmente cual será la estructura de los archivos del proyecto junto a
algún ejemplo (Material de ladrillo)

# Trabajar con ramas

## Gestión Rama
En principio, cada vez que se quiera trabajar en una tarea, se creará una rama desde 'main' con el nombre de la tarea por la cual se realiza la rama. 
Indicando algo como lo siguiente:
- (CodigoNombreTablaTrello) Nombre Tarea
- Ejemplo
    - (P) Islas Inferiores
    - 
Los commit de la rama se estructurarán de la siguiente forma

- Summary
  - Nombre Rama
  - Ejemplo
    - (P) Islas Inferiores

- Description
  - Especificación de lo que se ha hecho en ese commit. Lo que vendria siendo a ser una subtarea dentro de la tarea, alguna modificación o corrección, si se ha finalizado la tarea o si se está mejorando describiendo que es lo que se ha realizado.
  - Ejemplo
    - Blockout de una de las islas
    - Adición de edificios en el blockout
    - Finalización de blockout (La diferencia de alturas entre islas no se tienen en cuenta de momento)

## Subir cambios de Rama a Main
Una vez finalizada la tarea y realizado su último commit en la rama. Se deberán seguir los siguientes pasos
1. Actualizar rama con posibles cambios subidos en 'main' (Pull o Merge)
2. Asegurarse de que no hay conflictos y todo funciona como corresponde una vez hecho el Pull/Merge
3. Subir los cambios a 'main' (Push)

