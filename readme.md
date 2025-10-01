<h1>Compilar con estos comandos<h1>
<h2>g++ -DSFML_STATIC -c main.cpp -IC:\\SFML-3.0.2\\include -o build/main.o<h2>

<h2>usa ´g++ build/main.o -LC:\\SFML-3.0.2\\lib\\ -static -static-libstdc++ -lsfml-window-s -lsfml-graphics-s -lsfml-system-s -lopengl32 -lfreetype -lgdi32 -lwinmm <h2>

    <h2>start a.exe <h2