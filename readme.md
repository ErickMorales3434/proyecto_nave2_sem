# requisitos para compilar el proyecto
## descargar sfml de [SFML](https://www.sfml-dev.org/)




### Compilar con estos comandos<h1>
### `g++ -DSFML_STATIC -c main.cpp -IC:\\SFML-3.0.2\\include -o build/main.o`

### usa `g++ build/main.o -LC:\\SFML-3.0.2\\lib\\ -static -static-libstdc++ -lsfml-window-s -lsfml-graphics-s -lsfml-system-s -lopengl32 -lfreetype -lgdi32 -lwinmm`  <h2>

### `start a.exe`