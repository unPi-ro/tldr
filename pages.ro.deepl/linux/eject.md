# eject

> Ejectați CD-urile, dischetele și unitățile de bandă.
> Mai multe informații: <https://manned.org/eject>.

- Afișați dispozitivul implicit:

`eject -d`

- Ejectați dispozitivul implicit:

`eject`

- Expulsează un anumit dispozitiv (ordinea implicită este cd-rom, scsi, floppy și bandă):

`eject {{/dev/cdrom}}`

- Comută dacă tava unui dispozitiv este deschisă sau închisă:

`eject -T {{/dev/cdrom}}`

- Ejectați o unitate de CD:

`eject -r {{/dev/cdrom}}`

- Ejectați o unitate de dischetă:

`eject -f {{/mnt/floppy}}`

- Ejectați o unitate de bandă:

`eject -q {{/mnt/tape}}`
