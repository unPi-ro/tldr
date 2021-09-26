# udisksctl

> Un program de linie de comandă utilizat pentru a interacționa cu procesul daemon udisksd.
> Mai multe informații: <http://storaged.org/doc/udisks2-api/latest/udisksctl.1.html>.

- Afișează informații de nivel înalt despre unitățile de disc și dispozitivele de bloc:

`udisksctl status`

- Afișează informații detaliate despre un dispozitiv:

`udisksctl info --block-device {{/dev/sdX}}`

- Afișează informații detaliate despre o partiție de dispozitiv:

`udisksctl info --block-device {{/dev/sdXN}}`

- Montați o partiție de dispozitiv și imprimați punctul de montare:

`udisksctl mount --block-device {{/dev/sdXN}}`

- Demontați o partiție de dispozitiv:

`udisksctl unmount --block-device {{/dev/sdXN}}`

- Monitorizați demonul pentru evenimente:

`udisksctl monitor`
