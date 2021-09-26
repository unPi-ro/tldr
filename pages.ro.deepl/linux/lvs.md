# lvs

> Afișați informații despre volumele logice.
> A se vedea și: `lvm`.
> Mai multe informații: <https://man7.org/linux/man-pages/man8/lvs.8.html>.

- Afișați informații despre volumele logice:

`lvs`

- Afișează toate volumele logice:

`lvs -a`

- Modificați afișajul implicit pentru a afișa mai multe detalii:

`lvs -v`

- Afișați numai anumite câmpuri:

`lvs -o {{field_name_1}},{{field_name_2}}`

- Adăugați câmpul la afișarea implicită:

`lvs -o +{{field_name}}`

- Suprimarea liniei de titlu:

`lvs --noheadings`

- Utilizați un separator pentru a separa câmpurile:

`lvs --separator {{=}}`
