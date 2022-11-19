# MacOS

  Como compilar y ejecutar programas en C/C++ con OpenMP en MacOS Catalina o
  superior
---



### 1. Compilación

Dirigimos la terminal a la carpeta donde se encuentra el archivo (puedes encontrar ejemplos terminados en [esta sección](../recursos/ejemplos-de-programas.md)) que queremos compilar:

```
cd <ruta de la carpeta>
```

Compilamos el archivo usando GCC y la flag -fopenmp (todos los archivos que usen sintaxis de OpenMP requieren esta flag):

```
gcc-12 -fopenmp <nombre del archivo>
```

Nota 1:
En algunos ejemplos se requiere de la flag -lm para realizar operaciones matemáticas.


Nota 2:
Dependiendo de la versión de GCC, el comando puede ser diferente. El formato es
"gcc-\<versión>". Para saber la versión introduce "brew info gcc".

### 2. Ejecución

Para ejecutar el programa recién compilado usamos un simple comando:

```
./a.out
```

Una vez hecho esto, el programa debería ejecutarse satisfactoriamente en la terminal.
