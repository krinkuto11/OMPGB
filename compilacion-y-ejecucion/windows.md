---
description: >-
  Como compilar y ejecutar programas en C/C++ con OpenMP en Windows 10 o
  superior
---

# Windows

### 1. Compilación

Para empezar, abrimos la terminal y la dirigimos al directorio donde está presente el compilador GCC.

En el caso de haber extraido la suite GCC en el directorio de descargas, el comando sería tal que así (sustituyendo con tu nombre de usuario el texto entre "<>" sin incluír el símbolo en sí):

```shell
cd C:\Users\<nombre de usuario>\Downloads\mingw64\bin
```

Una vez hecho esto, ya podemos compilar cualquier archivo. En nuestro caso vamos a usar uno de los ejemplos que se pueden encontrar [aquí](../recursos/ejemplos-de-programas.md).

Se debe usar la flag -fopenmp para todos los programas que incluyan sintaxis de OpenMP.

```shell
gcc -fopenmp <nombre de archivo>
```

{% hint style="info" %}
&#x20;En algunos ejemplos se requiere de la flag -lm para realizar operaciones matemáticas.
{% endhint %}

### 2. Ejecución

Una vez se haya compilado nuestro archivo, el compilador habrá creado un ejecutable con el nombre "a" en el mismo directorio (/mingw64/bin). Para ejecutar el programa usaremos el comando:

```shell
a.exe
```

Una vez hecho esto, el programa debería ejecutarse satisfactoriamente en la terminal.
