# Clase 02

## Estado de los archivos 

* Uncracked

* Unmodified

* modified 

* staged

## GIT LOG
me muestra las fotos que les fui sacando al proyecto que estan dentro del repo 

``` sh
git log
```
> GIT LOG version corta
``` sh
git log --oneline
```

## GIT DIIF
Me permite visualizar los cambios que hay entre el WD (working directory) y la ultima foto (Commit) dentro de la 
caja de commits (local Repo)

``` sh
git diff 
```

## GIT AMEND 
Me permite agregar cambios al ultimo commit. Sean lineas de codigo o archivos completos

Coloco en el area temporal (Stage area) los cambios que quiero sumar en el ulimo commit. Sean lineas que me faltaron, archivos que faltaron. Y luego hago el amend  
``` sh
git add .
git commit --amend 
```
El GIT commit suele abrir un editor de texto
* Ctrl + O: Guardar 
* Ctrl + X: Salir