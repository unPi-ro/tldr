# nologin

> Un shell alternativ care împiedică un utilizator să se logheze.

- Setați shell-ul de autentificare al unui utilizator la `nologin` pentru a împiedica utilizatorul să se autentifice:

`chsh -s {{user}} nologin`

- Personalizează mesajul pentru utilizatorii cu shell-ul de autentificare `nologin`:

`echo "{{declined_login_message}}" > /etc/nologin.txt`
