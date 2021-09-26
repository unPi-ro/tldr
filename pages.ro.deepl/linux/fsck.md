# fsck

> Verificați integritatea unui sistem de fișiere sau reparați-l. Sistemul de fișiere trebuie să fie demontat în momentul în care se execută comanda.
> Mai multe informații: <https://manned.org/fsck>.

- Verificați sistemul de fișiere `/dev/sdX`, raportând orice blocuri deteriorate:

`fsck {{/dev/sdX}}`

- Verifică sistemul de fișiere `/dev/sdX`, raportând orice blocuri deteriorate și permițând utilizatorului să aleagă în mod interactiv să le repare pe fiecare:

`fsck -r {{/dev/sdX}}`

- Verifică sistemul de fișiere `/dev/sdX`, raportând orice blocuri deteriorate și reparându-le automat:

`fsck -a {{/dev/sdX}}`
