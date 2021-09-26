# xmount

> Conversia din mers între mai multe tipuri de imagini de intrare și ieșire de pe hard disk cu suport opțional pentru memoria cache de scriere.
> Creează un sistem de fișiere virtual utilizând FUSE (Filesystem in Userspace) care conține o reprezentare virtuală a imaginii de intrare.
> Mai multe informații: <https://manned.org/xmount>.

- Montați un fișier imagine `.raw` într-un fișier container DMG:

`xmount --in {{raw}} {{path/to/image.dd}} --out {{dmg}} {{mountpoint}}`

- Montați un fișier imagine EWF cu suport pentru memorare în cache într-un fișier VHD din care să porniți:

`xmount --cache {{path/to/cache.ovl}} --in {{ewf}} {{path/to/image.E??}} --out {{vhd}} {{mountpoint}}`

- Montați prima partiție la sectorul 2048 într-un nou fișier imagine `.raw`:

`xmount --offset {{2048}} --in {{raw}} {{path/to/image.dd}} --out {{raw}} {{mountpoint}}`
