# Ejercicio 3: Git. Trabajando con ramas y uniones
`por Alvaro San Juan - ASIR2 (2024/2025)`

En esta actividad vamos a trabajar con ramas y aprender como funcionan, ademas de como se traducen a GitHub en un repositorio remoto.

## Preparación

> Antes de comenzar con la creación de ramas y demas pasos tenemos que asegurarnos de que tenemos el entorno adecuado para empezar. Para ello vamos a crear un fichero con el nombre del ejercicio, en este fichero haremos un **git init**.
>
> Tras el git init crearemos un archivo (en este caso el markdown) para que contenga algo dentro, ahora haremos un **git add .** para añadirlo y un **git commit -m**. Con esto nos hemos asegurado de tener algo dentro y al hacer **git branch** para ver que estamos en master.

![Imagen](https://github.com/AlvaroSanJuan20/prueba3_Alvaro/blob/master/GitHubImages/1.png)

## Creación de la rama

> Para crear la rama vamos a hacer el **git branch primera** que nos creará la rama pero no nos pondrá en ella, para ver que se ha creado la rama con **git branch**.

![Imagen](https://github.com/AlvaroSanJuan20/prueba3_Alvaro/blob/master/GitHubImages/2.png)

## Fusionar ramas

> Tenemos que crear un fichero primero antes de fusionar ramas así que vamos a hacer un **git checkout primera** para cambiamos a la rama de primera, cuando estemos en primera hacemos un **touch fichero.txt**.

> Ahora vamos a fusionarlos usando el comando **git checkout**, hacemos un **git add .**, **git commit -m** y luego **git merge** para fusionar las ramas, el resultado es el siguiente y no da ningún conflicto porque crear y borrar usualmente no dan.

![Imagen](https://github.com/AlvaroSanJuan20/prueba3_Alvaro/blob/master/GitHubImages/3.png)

> Ahora borraremos la rama primera con el comando **git branch -d primera**

![Imagen](https://github.com/AlvaroSanJuan20/prueba3_Alvaro/blob/master/GitHubImages/4.png)

## Creación de la segunda rama

> Crearemos la nueva rama segunda de la misma forma que creamos la rama primera.

![Imagen](https://github.com/AlvaroSanJuan20/prueba3_Alvaro/blob/master/GitHubImages/5.png)

> Ahora modificaremos el fichero dentro de la rama segunda, y hacemos otra modificación en la rama master para que al fusionar las ramas nos suelte un conflicto.

![Imagen](https://github.com/AlvaroSanJuan20/prueba3_Alvaro/blob/master/GitHubImages/6.png)

## Solucione el conflicto

> Simplemente vamos a ir al fichero de master y quitamos la modificación que hicimos, al hacer merge si nos dejará.

![Imagen](https://github.com/AlvaroSanJuan20/prueba3_Alvaro/blob/master/GitHubImages/7.png)
