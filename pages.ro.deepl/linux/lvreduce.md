# lvreduce

> Reduceți dimensiunea unui volum logic.
> A se vedea și: `lvm`.
> Mai multe informații: <https://man7.org/linux/man-pages/man8/lvreduce.8.html>.

- Reduceți dimensiunea unui volum la 120 GB:

`lvreduce --size {{120G}} {{logical_volume}}`

- Reducerea dimensiunii unui volum cu 40 GB, precum și a sistemului de fișiere de bază:

`lvreduce --size -{{40G}} -r {{logical_volume}}`
