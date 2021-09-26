# ac

> Tipăriți statisticile privind durata de conectare a utilizatorilor.
> Mai multe informații: <https://www.gnu.org/software/acct/manual/accounting.html#ac>.

- Tipărește cât timp a fost conectat utilizatorul curent, în ore:

`ac`

- Imprimați cât timp au fost conectați utilizatorii, în ore:

`ac --individual-totals`

- Tipărește cât timp a fost conectat un anumit utilizator, în ore:

`ac --individual-totals {{username}}`

- Imprimați cât timp a fost conectat un anumit utilizator în ore pe zi (cu total):

`ac --daily-totals --individual-totals {{username}}`

- De asemenea, afișați detalii suplimentare:

`ac --compatibility`
