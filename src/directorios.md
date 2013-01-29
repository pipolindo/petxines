# Bash Shell Básica - Directorios

## Teoría
### Moverse entre directorios
- cd <nombre_de_directorio> : Te sitúa en el directorio
- cd .. : Te sitúa en el directorio superior
- cd : Te sitúa en tu directorio de usuario

### Listar directorios y archivos
- ls : Lista los archivos y directorios

### Manipulación de directorios
- mkdir <nombre_de_directorio> : Crea un directorio
- rm -r <nombre_de_directorio> : Elimina el directorio
- cp <nombre_de_directorio> <nombre_copia> : Copia el directorio
- mv <nombre_de_directorio> <nuevo_nombre> : Renombra un directorio
- mv <nombre_de_directorio> <nueva_ruta_y_nombre> : Mueve un directorio


## Ejercicios
### 1
Desde tu carpeta de usuario crea un directorio llamado dir1, uno llamado dir2 y otro llamado dir3. Dentro de dir1 crea un directorio llamado subdir11 y otro llamado subdir12.
Dentro de dir2 crea un directorio llamado subdir21 y dentro de dir3 crea un directorio llamado subdir31.

Debe quedar la siguiente estructura:

    dir1
            subdir11
			subdir12
    dir2
			subdir21
    dir3
		    subdir31

### 2
En la estructura de directorios creados. Mover el directorio dir2/subdir21 dentro de dir1 y copiar el directorio dir3/subdir31 al directorio dir2.

Ahora la estructura será:

    dir1
        subdir11
				subdir12
				subdir21
    dir2
        subdir31
    dir3
		    subdir31

### 3
Renombra el directorio dir1/subdir21 a subdir13 y renombra el directorio dir2/subdir31 a subdir21

Ahora la estructura será:

    dir1
		    subdir11
				subdir12
				subdir13
    dir2
		    subdir21
    dir3
		    subdir31