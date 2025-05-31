# Acción de Docker "Hola mundo". 

Esta acción imprime en el registro "Hola mundo" o "Hola" + el nombre de la persona a saludar. 

## Entradas 

## `who-to-greet` 

**Obligatorio** El nombre de la persona a saludar. Predeterminado: `"Mundo"`. 

## Salidas 

## `time` 

La hora a la que te saludamos. 

## Ejemplo 

de uso: actions/hello-world-docker-action@v2 
with: 
  who-to-greet: 'Mona the Octocat'
