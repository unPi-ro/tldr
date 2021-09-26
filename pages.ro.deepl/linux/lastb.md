# lastb

> Afișați o listă a ultimilor utilizatori conectați.
> Mai multe informații: <https://manned.org/lastb>.

- Afișează o listă cu toți utilizatorii conectați ultima dată:

`sudo lastb`

- Afișează o listă cu toți utilizatorii conectați ultima dată de la un anumit moment:

`sudo lastb --since {{YYYY-MM-DD}}`

- Afișează o listă cu toți utilizatorii conectați ultima dată până la un anumit moment:

`sudo lastb --until {{YYYY-MM-DD}}`

- Afișează o listă a tuturor utilizatorilor conectați la un anumit moment:

`sudo lastb --present {{hh:mm}}`

- Afișează o listă cu toți utilizatorii conectați ultima dată și transformă IP-ul într-un nume de gazdă:

`sudo lastb --dns`
