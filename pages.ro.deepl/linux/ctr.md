# ctr

> Gestionați containerele și imaginile `containerd`.
> Mai multe informații: <https://containerd.io>.

- Lista tuturor containerelor (în funcțiune și oprite):

`ctr containers list`

- Enumeră toate imaginile:

`ctr images list`

- Trageți o imagine:

`ctr images pull {{image}}`

- Ziua pe imagine:

`ctr images tag {{souce_image}}:{{source_tag}} {{target_image}}:{{target_tag}}`
