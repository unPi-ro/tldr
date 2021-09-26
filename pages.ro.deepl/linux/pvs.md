# pvs

> Afișați informații despre volumele fizice.
> A se vedea și: `lvm`.
> Mai multe informații: <https://man7.org/linux/man-pages/man8/pvs.8.html>.

- Afișează informații despre volumele fizice:

`pvs`

- Afișarea volumelor nefizice:

`pvs -a`

- Modificați afișajul implicit pentru a afișa mai multe detalii:

`pvs -v`

- Afișați numai anumite câmpuri:

`pvs -o {{field_name_1}},{{field_name_2}}`

- Adăugați câmpul la afișarea implicită:

`pvs -o +{{field_name}}`

- Suprimarea liniei de titlu:

`pvs --noheadings`

- Utilizați separatorul pentru a separa câmpurile:

`pvs --separator {{special_character}}`
