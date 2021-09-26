# beep

> Un utilitar pentru a emite un semnal sonor în difuzorul PC-ului.
> Mai multe informații: <https://github.com/spkr-beep/beep>.

- Redă un semnal sonor:

`beep`

- Redă un semnal sonor care se repetă:

`beep -r {{repetitions}}`

- Redă un semnal sonor la o frecvență (Hz) și o durată (milisecunde) specificate:

`beep -f {{frequency}} -l {{duration}}`

- Redă fiecare nouă frecvență și durată ca un semnal sonor distinct:

`beep -f {{frequency}} -l {{duration}} -n -f {{frequency}} -l {{duration}}`

- Cântă scara de Do major:

`beep -f 262 -n -f 294 -n -f 330 -n -f 349 -n -f 392 -n -f 440 -n -f 494 -n -f 523`
