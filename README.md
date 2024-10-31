# Tarea 1 - Ejemplo Proyecto Git

En esta primer tarea comenzamos a utilizar las funciones de Git y GitHub para trabajar con repositorios locales y remotos, utilizando aplicaciones como Git Bash y en mi caso 
Intelij IDEA para hacer un primer acercamiento a estas funciones indispensables en el mundo tec. 

## Instrucciones de uso 

Primero, debemos crear una carpeta en nuestra computadora donde trabajaremos nuestro repositorio local, en mi caso cree un package dentro de mi darpeta de IDEA (donde trabajo
java en InteliJ) y la nombre ProyectoEjemploGit, conecte esta carpeta a mi repositorio remoto en GitHub y comence a enviar mis archivos en distintos commits somo se solicito en 
el archivo de la tarea:
1. Envie el archivo **HolaMundo.java**
2. Cree el archivo git.ignore y el archivo **debug.log**; escribi en el archivo ignore el comando _/debug.log_ e hice _commit_ de todos los archivos, posteriormente hice
un _push_ del repositorio local al remoto para subir los archivos y no se subio el archivo _debug.log_ previamente creado.
3. Modifique el archivo **HolaMundo.java** cambiando el mensaje que imprimia.
4. Enviar todos estos cambios al repositorio remoto
5. Cree este archivo README

## Comandos utilizados 

```
git config --global user.name "Nombre"
git config --global user.email "Email.email@email.com"
git init
git add
git touch
git status
git commit
git push
```

## ¿Por qué se creo el archivo _git.ignore_? 

Este archivo se utiliza para que GIT detecte que archivos o carpetas deseamos ignorar, esto significa que Git no los incluirá en el control de versiones, es decir, no 
los rastreará ni los enviará al repositorio remoto. Este archivo es útil para evitar que archivos sensibles o temporales (como contraseñas, archivos de configuración 
locales, o archivos de compilación) se suban al repositorio. En este caso lo utilizamos para ignorar el archivo **debug.log**.
El archivo al crearlo puede accederse desde algun IDE y en este podemos utilizar diversos comandos ya sea para evitar enviar archivos especificos o incluso todos los 
que tengan una terminacion en especifico como podria ser archivos ejetucables que terminen en _.exe_ 
