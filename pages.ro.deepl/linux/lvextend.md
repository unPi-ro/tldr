# lvextend

> Creșteți dimensiunea unui volum logic.
> A se vedea și: `lvm`.
> Mai multe informații: <https://man7.org/linux/man-pages/man8/lvextend.8.html>.

- Creșteți dimensiunea unui volum la 120 GB:

`lvextend --size {{120G}} {{logical_volume}}`

- Creșteți dimensiunea unui volum cu 40 GB, precum și a sistemului de fișiere care stă la baza acestuia:

`lvextend --size +{{40G}} -r {{logical_volume}}`

- Creșteți dimensiunea unui volum la 100% din spațiul fizic liber al volumului:

`lvextend --size {{100}}%FREE {{logical_volume}}`
