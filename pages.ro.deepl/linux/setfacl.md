# setfacl

> Setați listele de control al accesului la fișiere (ACL).

- Modificarea ACL a unui fișier pentru un utilizator cu acces de citire și scriere:

`setfacl -m u:{{username}}:rw {{file}}`

- Modificarea ACL-ului implicit al unui fișier pentru toți utilizatorii:

`setfacl -d -m u::rw {{file}}`

- Elimină ACL a unui fișier pentru un utilizator:

`setfacl -x u:{{username}} {{file}}`

- Elimină toate intrările ACL ale unui fișier:

`setfacl -b {{file}}`
