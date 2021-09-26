# blkdiscard

> Elimină sectoarele de dispozitiv de pe dispozitivele de stocare. Util pentru SSD-uri.
> Mai multe informații: <https://manned.org/blkdiscard>.

- Elimină toate sectoarele de pe un dispozitiv, eliminând toate datele:

`blkdiscard /dev/{{device}}`

- Eliminarea în siguranță a tuturor blocurilor de pe un dispozitiv, eliminând toate datele:

`blkdiscard --secure /dev/{{device}}`

- Eliminați primii 100 MB ai unui dispozitiv:

`blkdiscard --length {{100MB}} /dev/{{device}}`
