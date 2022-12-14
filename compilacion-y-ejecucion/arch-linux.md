---
description: >-
  Como compilar y ejecutar programas en C/C++ con OpenMP en cualquier
  distribución de Linux basada en Arch (ej: Manjaro)
---

# Arch Linux

### 1. Compilación

Dirigimos la terminal a la carpeta donde se encuentra el archivo (puedes encontrar ejemplos terminados en [esta sección](../recursos/ejemplos-de-programas.md)) que queremos compilar:

```shell
cd <ruta de la carpeta>
```

Compilamos el archivo usando GCC y la flag -fopenmp (todos los archivos que usen sintaxis de OpenMP requieren esta flag):

```shell
gcc -fopenmp <nombre del archivo>
```

{% hint style="info" %}
&#x20;En algunos ejemplos se requiere de la flag -lm para realizar operaciones matemáticas.
{% endhint %}

### 2. Ejecución

Para ejecutar el programa recién compilado usamos un simple comando:

```shell
./a.out
```

Una vez hecho esto, el programa debería ejecutarse satisfactoriamente en la terminal.
