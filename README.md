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

### Añadir los cambios a la zona de intercambio temporal.

```code
git add .
```

### Hacer un commit de los cambios con el mensaje Añadido capítulo 1.

```code
git commit -m "Añadido capítulo 1."
[main (commit-raíz) 5ad0e90] Añadido capítulo 1.
 2 files changed, 42 insertions(+)
 create mode 100644 README.md
 create mode 100644 capitulos/capitulo1.txt
```

### Volver a mostrar el historial de cambios del repositorio

```code
git log
commit 5ad0e9060ed3d2d96fb9e4d28d4df8a1d2e2f1f5 (HEAD -> main)
Author: aday-ctr <adaybolt@gmail.com>
Date:   Mon Oct 14 16:03:35 2024 +0100

    Añadido capítulo 1.
```

## Ejercicio 2

### Creamos el fichero .txt

```code
cat > capitulos/capitulo2.txt 
El flujo de trabajo básico con Git consiste en:
 1- Hacer cambios en el repositorio.
 2- Añadir los cambios a la zona de intercambio temporal.
 3- Hacer un commit de los cambios.
```

### Añadir los cambios a la zona de intercambio temporal.

```code
git add .
```