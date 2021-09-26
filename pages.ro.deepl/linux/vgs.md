# vgs

> Afișați informații despre grupurile de volume.
> A se vedea și: `lvm`.
> Mai multe informații: <https://man7.org/linux/man-pages/man8/vgs.8.html>.

- Afișați informații despre grupurile de volume:

`vgs`

- Afișează toate grupurile de volume:

`vgs -a`

- Modificați afișajul implicit pentru a afișa mai multe detalii:

`vgs -v`

- Afișați numai anumite câmpuri:

`vgs -o {{field_name_1}},{{field_name_2}}`

- Adăugați câmpul la afișarea implicită:

`vgs -o +{{field_name}}`

- Suprimarea liniei de titlu:

`vgs --noheadings`

- Utilizați separatorul pentru a separa câmpurile:

`vgs --separator =`
