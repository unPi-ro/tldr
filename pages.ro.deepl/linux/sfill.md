# sfill

> Suprascrieți în siguranță spațiul liber și nodurile din partiția în care se află directorul specificat.
> Mai multe informații: <https://manned.org/sfill>.

- Suprascrieți spațiul liber și inodes de pe un disc cu 38 de scrieri (lent, dar sigur):

`sfill {{/path/to/mounted_disk_directory}}`

- Suprascrie spațiul liber și inodele unui disc cu 6 scrieri (rapid, dar mai puțin sigur) și afișează starea:

`sfill -l -v {{/path/to/mounted_disk_directory}}`

- Suprascrierea spațiului liber și a inodelor unui disc cu 1 scriere (foarte rapid, dar nesigur) și afișarea stării:

`sfill -ll -v {{/path/to/mounted_disk_directory}}`

- Suprascrie numai spațiul liber de pe un disc:

`sfill -I {{/path/to/mounted_disk_directory}}`

- Suprascrie numai inodele libere de pe un disc:

`sfill -i {{/path/to/mounted_disk_directory}}`
