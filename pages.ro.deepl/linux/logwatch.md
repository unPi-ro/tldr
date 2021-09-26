# logwatch

> Sintetizează mai multe jurnale diferite pentru servicii comune (de exemplu, apache, pam_unix, sshd etc.) într-un singur raport.
> Mai multe informații: <https://manned.org/logwatch>.

- Analizați jurnalele pentru o serie de date la un anumit nivel de detaliere:

`logwatch --range {{yesterday|today|all|help}} --detail {{low|medium|others}}'`

- Restricționați raportul pentru a include numai informații pentru un serviciu selectat:

`logwatch --range {{all}} --service {{apache|pam_unix|etc}}`
