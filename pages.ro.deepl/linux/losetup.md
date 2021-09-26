# losetup

> Configurați și controlați dispozitivele de buclă.
> Mai multe informații: <https://manned.org/losetup>.

- Lista dispozitivelor de buclă cu informații detaliate:

`losetup -a`

- Atașează un fișier la un anumit dispozitiv de buclă:

`sudo losetup /dev/{{loop}} /{{path/to/file}}`

- Atașați un fișier la un nou dispozitiv cu buclă liberă și scanați dispozitivul pentru partiții:

`sudo losetup --show --partscan -f /{{path/to/file}}`

- Atașați un fișier la un dispozitiv de buclă de numai citire:

`sudo losetup --read-only /dev/{{loop}} /{{path/to/file}}`

- Detașați toate dispozitivele de buclă:

`sudo losetup -D`

- Detașează un anumit dispozitiv de buclă:

`sudo losetup -d /dev/{{loop}}`
