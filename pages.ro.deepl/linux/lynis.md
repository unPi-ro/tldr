# lynis

> Instrument de audit de sistem și de securitate.
> Mai multe informații: <https://cisofy.com/documentation/lynis/>.

- Verificați dacă Lynis este actualizat:

`sudo lynis update info`

- Efectuați un audit de securitate al sistemului:

`sudo lynis audit system`

- Executați un audit de securitate al unui fișier Docker:

`sudo lynis audit dockerfile {{path/to/dockerfile}}`
