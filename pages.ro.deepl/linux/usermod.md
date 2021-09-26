# usermod

> Modifică un cont de utilizator.
> Mai multe informații: <https://manned.org/usermod>.

- Schimbați numele unui utilizator:

`usermod -l {{newname}} {{user}}`

- Adăugați utilizatorul la grupurile suplimentare (atenție la spațiile albe):

`usermod -a -G {{group1,group2}} {{user}}`

- Creați un nou director principal pentru un utilizator și mutați-i fișierele în el:

`usermod -m -d {{path/to/home}} {{user}}`
