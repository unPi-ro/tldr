# radeontop

> Arată utilizarea GPU-urilor AMD.
> Poate necesita privilegii de root, în funcție de sistem.
> Mai multe informații: <https://github.com/clbr/radeontop>.

- Afișează gradul de utilizare a GPU-ului AMD implicit:

`radeontop`

- Activează ieșirea colorată:

`radeontop --color`

- Selectați un anumit GPU (numărul de magistrală este primul număr de la ieșirea din `lspci`):

`radeontop --bus {{bus_number}}`

- Specificați rata de reîmprospătare a afișajului (o rată mai mare înseamnă mai multă încărcare a GPU-ului):

`radeontop --ticks {{samples_per_second}}`
