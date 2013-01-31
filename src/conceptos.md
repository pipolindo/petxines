# Bash Shell Básica - Estructura de directorios

## Teoría
La estructura de directorios de un sistema linux se asemeja a un árbol, con sus ramas y subramas que parten de un único punto inicial.
A este punto le llamamos raíz o *root*.

Al abrir una consola, ésta se situa en lo que se conoce como, carpeta de usuario o directorio de usuario o "home" de usuario.
Podemos verlo mediante el comando *pwd* que nos dara como resultado: /home/<nombre_de_usuario>

### La raíz
Mediante el comando *cd ..* vamos a irnos moviendo por la estructura de directorios para llegar a la raiz. Así que si ejecutamos *cd ..* una vez
y seguidamente, un *pwd*, veremos que estamos en */home*. Si repetimos estas acciones nos habremos posicionado en la raiz */*.

### Directorios del sistema
Desde la raíz mediante el comando *ls -l* podremos ver todos los directorios de sistema que "cuelgan" de la raiz. No vamos a entrar en explicar
cada uno de estos directorios ya que para empezar a entender la estructura de directorios nos será suficiente centrarnos en conocer la existencia de
la raiz y de nuestra carpeta de usuario. Así que ahora volvamos a ella mediante *cd home* (podemos ver mediante un *pwd* que nos hemos situado dentro de
la carpeta */home*). Desde aquí mediante un *ls -l* veremos los directorios que de este directorio "cuelgan". Como mínimo estará el de nuestro usuario.
Entraremos dentro de él mediante *cd <nombre_de_directorio>*. Un *pwd* nos mostrará: /home/<nombre_de_usuario>

Es importante ver que lo que nos da como resultado un *pwd* es una ruta absoluta de donde nos encontramos. Entendemos por ruta absoluta al camino
necesario para llegar a dónde nos encontramos desde la raíz del sistema.

## Ejercicios
### 1
Desde tu *home* ves al directorio /tmp y lista su contenido.

### 2
Vuelve a tu *home* y muestra en qué directorio te encuentras.

