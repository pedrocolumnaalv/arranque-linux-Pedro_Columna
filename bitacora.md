# Bitácora de arranque - Pedro Columna

**Fecha:** 19/03/2026
**Duración estimada:** 2 horas


# Pasos ejecutados

1- Primero cree la carpeta cidium_security, donde llevaré a cabo todas las prácticas relacionadas con esta bonita comunidad, para ello usé el comando mkdir de la siguiente forma

mkdir cidium_security

2- Luego con el comando cd entre a esa carpeta

cd cidium_security

3- Después cloné el repositorio del laboratorio2 arranque-linux-Pedro_Columna
con:

git clone https://github.com/pedrocolumnaalv/arranque-linux-Pedro_Columna

4- Luego con el comando ls corroboré que se haya clonado la carpeta arranque-linux-Pedro_Columna

ls

5- Tal como lo indica el ejercicio del laboratorio 2 intenté crear una rama con el siguiente comando.

git checkout -b semana2-arranque

## Problemas encontrados 

Pero me salió un mensaje de error:

fatal: no es un repositorio git (ni ningún padre en el punto de montaje /)
Parando a la frontera del sistema de archivos (GIT_DISCOVERY_ACROSS_FILESYSTEM no establecido).

## Como lo resolví

Esta falla sucedió porque no había entrado a la carpeta del repositorio, para corregirlo solo ingresé a la carpeta:

cd arranque-linux-Pedro_Columna


6- Volví a intentar crear mi rama 

git checkout -b semana2-arranque

Y me saltó el mensaje “Cambiado a nueva rama ‘semana2-arranque’”

#----------------------------------------------------------------#

7- Como no tenía archivo README.md lo creé con nano.

nano README.md

8- Entonces sobre el archivo coloqué mi nombre de usuario de GitHub y mi color favorito.

Nota: Para guardar el contenido apreté Ctrl + O y para salir de nano Ctrl + X

## Comandos destacados





