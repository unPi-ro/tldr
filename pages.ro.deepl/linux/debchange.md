# debchange

> Instrument pentru întreținerea fișierului debian/changelog într-un pachet sursă Debian.
> Mai multe informații: <https://manpages.debian.org/debchange>.

- Adăugați o nouă versiune pentru o încărcare non-maintainer la jurnalul de modificări:

`debchange --nmu`

- Adăugați o intrare în jurnalul de modificări la versiunea curentă:

`debchange --append`

- Adăugați o intrare în jurnalul de modificări pentru a închide problema cu ID-ul specificat:

`debchange --closes {{bug_id}}`
