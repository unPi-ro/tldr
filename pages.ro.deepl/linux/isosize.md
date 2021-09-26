# isosize

> Afișați dimensiunea unui fișier ISO.
> Mai multe informații: <https://manned.org/isosize>.

- Afișează dimensiunea unui fișier ISO:

`isosize {{path/to/file.iso}}`

- Afișează numărul de blocuri și dimensiunea blocurilor unui fișier ISO:

`isosize --sectors {{path/to/file.iso}}`

- Afișează dimensiunea unui fișier ISO împărțită la un anumit număr (utilizabil numai dacă nu se indică --sectors):

`isosize --divisor={{number}} {{path/to/file.iso}}`
