# sxiv

> Simple X Image Viewer.
> Mai multe informații: <https://github.com/muennich/sxiv>.

- Deschideți o imagine:

`sxiv {{path/to/file}}`

- Deschideți o imagine în modul ecran complet:

`sxiv -f {{path/to/file}}`

- Deschide o listă de imagini separate prin linii noi, citind numele fișierelor de la intrarea standard:

`echo {{path/to/file}} | sxiv -i`

- Deschideți o listă de imagini separate prin spații sub forma unei prezentări de diapozitive:

`sxiv -S {{seconds}} {{path/to/file}}`

- Deschideți o listă de imagini separate prin spații în modul miniatură:

`sxiv -t {{path/to/file}}`
