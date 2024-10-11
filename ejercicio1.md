# Ejercicio 1: Introducción a git y GitHub
`por Alvaro San Juan - ASIR2 (2024/2025)`

En esta actividad aprenderemos a usar los comandos basicos de git para conectarnos a GitHub y Debian, el  apartado que resolveremos es el 14.



## Creación del repositorio local en Windows y añadir 2 archivos de formato txt.

> Usaremos el comando de **git init** para crear un repositorio con el nombre de prueba2_Alvaro (En el futuro esta carpeta sería relocalizada dentro de un directorio llamado "IAW") Usaremos **touch** para crear los archivos txt dentro del repositorio prueba2_Alvaro, luego haremos **git add** y **git commit** para añadir y confirmar cambios.

![image](https://github.com/AlvaroSanJuan20/prueba_Alvaro/blob/master/GitHubImages/1.png)

![image](https://github.com/AlvaroSanJuan20/prueba_Alvaro/blob/master/GitHubImages/2.png)

![image](https://github.com/AlvaroSanJuan20/prueba_Alvaro/blob/master/GitHubImages/3.png)

## Agregar el repositorio local al repositorio remoto en GitHub y subirlo a GitHub.

> Para subirlo a GitHub usaremos el comando de **git remote add origin [url]** que nos añadirá como origen remoto la url de nuesto repositorio en GitHub, luego hacemos un **git push** para que se suban los archivos que tenemos en local.

![image](https://github.com/AlvaroSanJuan20/prueba_Alvaro/blob/master/GitHubImages/4.png)

## Clonación del repositorio remoto en Debian

> Vamos a Debian iniciando sesión en nuestro usuario, luego instalaremos los paquetes necesarios para usar comandos de git en Debian y usaremos **git clone [url de nuestro repositorio remoto]** para clonarlo.

![image](https://github.com/AlvaroSanJuan20/prueba_Alvaro/blob/master/GitHubImages/5.png)


## Modificación/Creación de archivos y subida a GitHub

> Haremos los mismos pasos que antes al principio de la actividad, simplemente modificamos el archivo 1 y usamos un touch para crear el archivo 3, luego pasaremos por todo el proceso de add, commit y push.

![image](https://github.com/AlvaroSanJuan20/prueba_Alvaro/blob/master/GitHubImages/6.png)

![image](https://github.com/AlvaroSanJuan20/prueba_Alvaro/blob/master/GitHubImages/7.png)

## Actualizar el repositorio de Debian

> Usaremos **git pull** para traer los archivos de GitHub hasta Debian y el repositorio se actualizará.

![image](https://github.com/AlvaroSanJuan20/prueba_Alvaro/blob/master/GitHubImages/8.png)
