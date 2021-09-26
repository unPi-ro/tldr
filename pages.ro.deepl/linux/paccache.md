# paccache

> Un utilitar de curățare a cache-ului pacman.

- Elimină toate versiunile de pachete, cu excepția celor mai recente 3, din memoria cache pacman:

`paccache -r`

- Setați numărul de versiuni de pachete care trebuie păstrate:

`paccache -rk {{num_versions}}`

- Efectuați o execuție de probă și afișați numărul de pachete candidate la ștergere:

`paccache -d`

- Mutați pachetele candidate într-un director în loc să le ștergeți:

`paccache -m {{path/to/directory}}`
