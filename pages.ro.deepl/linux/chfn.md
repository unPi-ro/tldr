# chfn

> Actualizarea informațiilor `finger` pentru un utilizator.
> Mai multe informații: <https://manned.org/chfn>.

- Actualizează câmpul "Name" al unui utilizator în ieșirea lui `finger`:

`chfn -f {{new_display_name}} {{username}}`

- Actualizează câmpul "Office Room Number" al unui utilizator pentru ieșirea lui `finger`:

`chfn -o {{new_office_room_number}} {{username}}`

- Actualizează câmpul "Număr de telefon de la birou" al unui utilizator pentru ieșirea lui `finger`:

`chfn -p {{new_office_telephone_number}} {{username}}`

- Actualizează câmpul "Home Phone Number" al unui utilizator pentru ieșirea lui `finger`:

`chfn -h {{new_home_telephone_number}} {{username}}`
