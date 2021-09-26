# e2fsck

> Verificați un sistem de fișiere Linux ext2/ext3/ext4. Sistemul de fișiere trebuie să fie demontat în momentul în care se execută comanda.
> Mai multe informații: <https://manned.org/e2fsck>.

- Verifică sistemul de fișiere și raportează orice blocuri deteriorate:

`e2fsck {{/dev/sdXN}}`

- Verifică sistemul de fișiere și repară automat orice blocuri deteriorate:

`e2fsck -p {{/dev/sdXN}}`

- Verifică sistemul de fișiere în modul doar pentru citire:

`e2fsck -c {{/dev/sdXN}}`
