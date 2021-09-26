# sm

> Afișează un mesaj scurt pe ecran complet.
> Mai multe informații: <https://github.com/nomeata/screen-message>.

- Afișarea unui mesaj pe tot ecranul:

`sm "{{Hello World!}}"`

- Afișarea unui mesaj cu culori inversate:

`sm -i "{{Hello World!}}"`

- Afișează un mesaj cu o culoare de prim-plan personalizată:

`sm -f {{blue}} "{{Hello World!}}"`

- Afișați un mesaj cu o culoare de fundal personalizată:

`sm -b {{#008888}} "{{Hello World!}}"`

- Afișează un mesaj rotit de 3 ori (în pași de 90 de grade, în sens invers acelor de ceasornic):

`sm -r {{3}} "{{Hello World!}}"`

- Afișează un mesaj folosind rezultatul unei alte comenzi:

`{{echo "Hello World!"}} | sm -`
