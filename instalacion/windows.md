# Windows

Cómo preparar el espacio de compilación en Windows 10 o superior
---

### 1. Instalar GCC

Usaremos GCC como compilador debido a su versatilidad y cantidad de utilidades que trae incluidas.

Para instalar GCC en Windows tenemos dos opciones:

* Compilarlo nosotros mismos ([+info](https://gcc.gnu.org/git.html))
* Descargar binarios precompilados

En nuestro caso, para ahorrar tiempo, descargaremos unos binarios precompilados desde cualquiera de estos enlaces:

* WinLib: [64bit](https://github.com/brechtsanders/winlibs\_mingw/releases/download/12.2.0-14.0.6-10.0.0-ucrt-r2/winlibs-x86\_64-posix-seh-gcc-12.2.0-llvm-14.0.6-mingw-w64ucrt-10.0.0-r2.7z) o [32bit](https://github.com/brechtsanders/winlibs\_mingw/releases/download/12.2.0-14.0.6-10.0.0-ucrt-r2/winlibs-i686-posix-dwarf-gcc-12.2.0-llvm-14.0.6-mingw-w64ucrt-10.0.0-r2.7z)

Una vez descargado el archivo, lo extraemos con [7zip](https://www.7-zip.org/download.html).

OpenGCC viene con OpenMP incluido en los binarios de WinLib asi que no necesitaremos hacer nada más.
