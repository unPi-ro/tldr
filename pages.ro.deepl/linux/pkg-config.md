# pkg-config

> Furnizați detalii despre bibliotecile instalate pentru compilarea aplicațiilor.
> Mai multe informații: <https://www.freedesktop.org/wiki/Software/pkg-config/>.

- Obține lista bibliotecilor și a dependențelor acestora:

`pkg-config --libs {{library1 library2 ...}}`

- Obține lista de biblioteci, dependențele lor și cflags corespunzătoare pentru gcc:

`pkg-config --cflags --libs {{library1 library2 ...}}`

- Compilați-vă codul cu libgtk-3, libwebkit2gtk-4.0 și toate dependențele lor:

`c++ example.cpp $(pkg-config --cflags --libs gtk+-3.0 webkit2gtk-4.0) -o example`
