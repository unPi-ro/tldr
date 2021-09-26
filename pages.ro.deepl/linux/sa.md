# sa

> Sintetizează informațiile contabile. Face parte din pachetul acct.
> Afișează comenzile apelate de utilizatori, inclusiv informații de bază privind timpul de procesare petrecut de CPU și ratele de I/O.

- Afișează invocările executabile per utilizator (numele de utilizator nu este afișat):

`sudo sa`

- Afișează invocările executabile per utilizator, indicând numele de utilizator responsabil:

`sudo sa --print-users`

- Lista resurselor utilizate recent de fiecare utilizator:

`sudo sa --user-summary`
