# lvresize

> Modificați dimensiunea unui volum logic.
> A se vedea și: `lvm`.
> Mai multe informații: <https://man7.org/linux/man-pages/man8/lvresize.8.html>.

- Modificați dimensiunea unui volum logic la 120 GB:

`lvresize --size {{120G}} {{volume_group}}/{{logical_volume}}`

- Extindeți dimensiunea unui volum logic, precum și a sistemului de fișiere de bază cu 120 GB:

`lvresize --size +{{120G}} --resizefs {{volume_group}}/{{logical_volume}}`

- Extindeți dimensiunea unui volum logic la 100% din spațiul liber al volumului fizic:

`lvresize --size {{100}}%FREE {{volume_group}}/{{logical_volume}}`

- Reduceți dimensiunea unui volum logic, precum și a sistemului de fișiere de bază cu 120 GB:

`lvresize --size -{{120G}} --resizefs {{volume_group}}/{{logical_volume}}`
