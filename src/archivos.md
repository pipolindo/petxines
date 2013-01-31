# Bash Shell Básica - Archivos

## Teoría
### Listar directorios y archivos
- ls -l Lista los archivos y directorios

### Manipulación de archivos
- rm <ruta_absoluta/nombre_del_archivo> Elimina el archivo
- cp <ruta_absoluta_origen/nombre_del_archivo> <ruta_absoluta_destino/nombre_archivo_copia> Copia el archivo
- mv <ruta_absoluta_origen/nombre_del_archivo> <ruta_absoluta_origen/nuevo_nombre> Renombra un archivo
- mv <ruta_absoluta_origen/nombre_del_archivo> <ruta_absoluta_destino/nuevo_nombre> Mueve un archivo

### Creación de archivos
No entraremos en cómo crear archivos desde bash ya que exiten diferentes maneras y diferentes editores
para hacerlo que tienen un punto de complejidad que ahora mismo no es necesaria.

Aún así no está de más conocer el comando *touch* que crea un archivo vacío:
- touch <nombre_del_archivo> Crea un archivo vacío

## Ejercicios
### 1
En tu carpeta de usuario crear el directorio dir1 con 3 archivos vacíos llamados ar1, ar2 y ar3

Quedando de esta forma:
    /dir1
        ar1
        ar2
        ar3

### 2
Crear 3 directorios dentro de dir1 llamados sub1, sub2 y sub3 y mover los archivos ar1 al directorio sub1,
ar2 al directorio sub2 y ar3 al directorio sub3.

Quedando de esta forma:
    /dir1
        /sub1
            ar1
        /sub2
            ar2
        /sub3
            ar3

### 3
Renombrar el archivo dir1/sub1/ar1 a dir1/sub1/archivo1. Mover y renombrar dir1/sub2/ar2 a dir1/sub1/archivo2. Y por último
copiar dir1/sub3 dentro de dir1/sub1 y renombrar dir1/sub1/sub3/ar3 por dir1/sub1/sub3/archivo3.

Quedando de esta forma:
    /dir1
        /sub1
            /sub3
                arhivo3
            archivo1
            archivo2
        /sub2
        /sub3
            ar3

### 4
(Hacerlo con papel y lápiz) ¿Qué estructura de directorios y archivos resulta de la siguiente consecución de comandos:

$ mkdir a
$ mkdir b
$ cd a
$ mkdir bb
$ cd bb
$ touch file1
$ cd
$ cd b
$ mkdir c
$ cd ..
$ cp /home/usuario/b/c /home/usuario/a
$ touch file2
$ mv /home/usuario/file2 /home/usuario/b
$ cd b
$ cd c
$ mkdir d
$ cd d
$ mkdir e
$ cd e
$ cd ..
$ touch file3
$ cd ..
$ touch file4
$ cd