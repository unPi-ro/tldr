# clamav

> Program antivirus open-source.
> Conceput în special pentru scanarea e-mailurilor pe gateway-urile de poștă electronică, dar poate fi utilizat și în alte contexte.
> Mai multe informații: <https://www.clamav.net>.

- Actualizați definițiile virusurilor:

`freshclam`

- Scanați un fișier pentru viruși:

`clamscan {{path/to/file}}`

- Scanează directoarele în mod recursiv și tipărește fișierele infectate:

`clamscan --recursive --infected {{path/to/directory}}`

- Scanează directoarele în mod recursiv și le mută în carantină:

`clamscan --recursive --move={{directory}}`
