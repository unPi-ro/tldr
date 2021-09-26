# iw

> Afișați și manipulați dispozitivele fără fir.
> Mai multe informații: <https://manned.org/iw>.

- Scanați pentru rețelele fără fir disponibile:

`iw dev {{wlp}} scan`

- Alăturați-vă unei rețele wireless deschise:

`iw dev {{wlp}} connect {{SSID}}`

- Închideți conexiunea curentă:

`iw dev {{wlp}} disconnect`

- Afișează informații despre conexiunea curentă:

`iw dev {{wlp}} link`
