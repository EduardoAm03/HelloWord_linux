# Hola Mundo en C++

Este repositorio contiene un simple programa "Hola Mundo" escrito en C++ para ejecutarse en un entorno Linux.

## Requisitos

- Linux (o un entorno similar compatible con g++)
- g++ (GNU Compiler Collection)
- Visual Studio Code (Para copilar)

## Instrucciones de uso

1. **Instalar Visual Studio Code**: Si aún no tienes instalado Visual Studio Code, descárgalo e instálalo desde [Visual Studio Code website](https://code.visualstudio.com/).
> 
2. **Instalar la extensión C++**: Abre Visual Studio Code, ve a la pestaña de Extensiones (Ctrl+Shift+X), busca "C++" y haz clic en "Instalar" en la extensión proporcionada por Microsoft.

3. **Abrir el proyecto en Visual Studio Code**: Abre Visual Studio Code y navega hasta el directorio donde clonaste el repositorio.

4. **Crear o abrir un archivo C++**: Crea un nuevo archivo con extensión `.cpp` (por ejemplo, `hola_mundo.cpp`) y escribe o copia el siguiente código:

    ```cpp
    #include <iostream>

    int main() {
        std::cout << "Hola mundo" << std::endl;
        return 0;
    }
    ```

5. **Compilar y ejecutar el programa**: Ahora es tiempo de copilar el codigo con **F5** en el teclado, se abrira el terminal de Visual Studio en donde se visualizara de la siguiente manera:

	`Hola mundo`

	Deberías ver el mensaje "Hola mundo" impreso en la terminal.
