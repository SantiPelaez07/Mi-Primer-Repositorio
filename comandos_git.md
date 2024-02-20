## Comandos de git

## Comando para ver la versión de git
- git -v
- git --version 
# Nos dará la versión de git que tenemos instalada en el ordenador


## Comandos para configuración inicial de git
# Este será el nombre que podrán ver mis compañeros al momento de hacer algún cambio
- git config --global user.name "Your name"
- git config --global user.email "Your email"


## Comando para ver o editar la configuración de git
# Para salir del editar ctrl + 0 y ctrl + x     --> y si es VIM esc:wq 
- git config --global --edit
- git config --global --list

## Comando para ver la configuración de git


## Comando para iniciar git en un directorio
- git init

## Para poder saber el estado de nuestros rchivos, es decir si ya etán dentro de la tash o fuera, rojo fuera y verde dentro
-git status

## Pasos para crear una versión de nuestro código
1. Agregar todos los archivos alcommit
- git add .
Para agregar solo los archivos javascript
- git add *.js
Para agregar un solo archivo
- git add index.js

