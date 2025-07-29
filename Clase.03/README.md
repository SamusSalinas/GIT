# Clase 03

## Crear repositorio en Github

![crear-repo](imgs/creo-repo.png)

## Si el repositorio no esta creado

…or create a new repository on the command line

``` sh
echo "# nombre-repo" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/SamusSalinas/nombre-repo.git
git push -u origin main
```
## Si el repo esta creado

…or push an existing repository from the command line

``` sh
git remote add origin https://github.com/SamusSalinas/nombre-repo.git
git branch -M main
git push -u origin main
```

## GIT REMOTE 

``` sh
git remote
```

>Mas detalle sobre los remotos 

``` sh
git remote -v
```

> Para agregar un remoto 

``` sh
git remote add <alias> <url-del-remoto>
```

## Si quiero subir al repositorio remoto el local 

>La primera vez

``` sh
git push -u <alias-del-remoto> <rama-local-que-quiero-subir>
git push -u origin main
```

> Las sigiuentes veces que quiera subir

``` sh
git push 
```