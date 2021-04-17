# Trabajo Práctico N° 1: Sistemas de control de versiones

## Pasolli Lucas

### 1) Instalar GIT

```sh
$ sudo apt install git
    git ya está en su versión más reciente (1:2.17.1-1ubuntu0.7).
```

### 2) Crear un repositorio local y agregar archivos

```sh
$ git init
    Inicializado repositorio Git vacío en /home/lucas/Colegio/7°C/ANT/Trabajo Práctico N° 1:             Sistemas de control de versiones/.git/
    
$ touch README.md
$ touch CV.md

$ git commit -m "Creacion README.md y CV.md"
    [master (commit-raíz) 445299d] Creacion README.md y CV.md
     2 files changed, 28 insertions(+)
     create mode 100644 CV.md
     create mode 100644 README.md

``` 

### 3) Crear un repositorio remoto

```sh
$ git remote add origin https://github.com/LucasPasolli/
TPN1-Sistemas-de-control-de-versiones.git
$ git branch -M main
$ git push -u origin main

```
### 4)
```sh
$ git checkout -b branchLocal
$ touch pullrequest.md
$ git add .
$ git commit -m "Adicion de archivo pullrequest.md"
```
![](<Imagenes/TPN1/1.png>)
![](<Imagenes/TPN1/2.png>)

### 5)
```sh
$ git clone https://github.com/LucasPasolli/TPN1-Sistemas-de-control-de-versiones.git

$ git add .
$ git commit -m "Cambios en readme"
$ git push

*Se resuelve el problema en la pagina de github*

$ git add .
$ git commit -m "Clon CV modificado"
$ git push


$ git add .
$ git commit -m "Cambios CV clon"
$ git push
```
![](<Imagenes/TPN1/3.png>)
```
$ git add .
$ git commit -m "Cambios CV clon"
$ git push
```


* LOCAL: el archivo de la rama en la que se fusiona

* REMOTE: el archivo en la rama desde donde se está fusionando

* BASE: El ancestro común de $ LOCAL y $ REMOTE, es decir. el punto donde las dos ramas comenzaron a desviar el archivo considerado

### 6) Algunos ejercicios online
![](<Imagenes/TPN1/5.jpeg>)
![](<Imagenes/TPN1/6.jpeg>)
![](<Imagenes/TPN1/7.jpeg>)
![](<Imagenes/TPN1/8.jpeg>)
![](<Imagenes/TPN1/9.jpeg>)

### 7) Crear Repositorio de la materia

https://github.com/LucasPasolli/ANT
