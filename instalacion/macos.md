# MacOS

---
description: Cómo preparar el espacio de compilación en MacOS Catalina o superior
---

### 1. Instalar Brew

Primero de todo, necesitamos tener a nuestra disposición un instalador de paquetes. En nuestro caso usaremos Brew.&#x20;

Para instalarlo, abrimos la terminal e introducimos:

```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

Nota: para instalar Brew necesitamos permisos de administrador

Nota 2: si es la primera vez que instalamos Brew, se descargará a su vez la línea de comandos de XCode

### 2. Instalar GCC

Lo siguiente es instalar un compilador. Vamos a usar GCC (GNU Compiler Collection) debido a su versatilidad.

Para instalarlo introducimos este sencillo comando en el terminal:

```
brew install gcc
```

### 3. Instalar OpenMP

Para utilizar OpenMP en MacOS, lo instalamos en forma de librería.

Introducimos el siguiente comando en la terminal:

```
brew install libomp
```

Una vez completados estos pasos, el dispositivo debería estar preparado para compilar y ejecutar programas que utilicen OpenMP.
