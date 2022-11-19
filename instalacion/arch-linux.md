# Arch Linux


  Cómo preparar el espacio de compilación en cualquier distribución de Linux basada en Arch (ej: Manjaro)
---


### 1. Actualizar la base de datos del gestor de paquetes

Para asegurarnos de que descargamos una versión actualizada de GCC y OpenMP, actualizamos la base de datos de Pacman con este comando:

```
sudo pacman -Syu
```

### 2. Instalar GCC

Lo siguiente es instalar un compilador. Vamos a usar GCC (GNU Compiler Collection) debido a su versatilidad.

Para instalarlo introducimos este comando en el terminal:

```
sudo pacman -S gcc
```

### 3. Instalar OpenMP

Por último, necesitamos instalar la librería OpenMP.

Para ello utilizamos el siguiente comando:

```
sudo pacman -S openmp
```

Una vez completados estos pasos, el dispositivo debería estar preparado para compilar y ejecutar programas que utilicen OpenMP.
