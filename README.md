## Libreria

## Clonamos el repositorio previamente creado

```code
git clone https://github.com/aday-ctr/ejercicio-git-libro.git

Clonando en 'ejercicio-git-libro'...
Username for 'https://github.com': aday-ctr
Password for 'https://aday-ctr@github.com': 
warning: Pareces haber clonado un repositorio sin contenido.

ls -la
total 16
drwxrwxr-x 3 pro pro 4096 oct 14 15:40 .
drwxrwxr-x 3 pro pro 4096 oct 14 15:39 ..
drwxrwxr-x 7 pro pro 4096 oct 14 15:41 .git
-rw-rw-r-- 1 pro pro  322 oct 14 15:45 README.md
```

## Ejercicio 1

### Mostramos el historial de cambios del repositorio.

```code
git log   
fatal: tu rama actual 'main' no tiene ningún commit todavía
```

### Creamos la carpeta capitulos.

```code
mkdir capitulos
```

### Creamos el fichero .txt

```code
cat > capitulos/capitulo1.txt
Git es un sistema de control de versiones ideado por Linus Torv
```
