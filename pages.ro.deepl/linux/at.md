# at

> Execută comenzile la un moment specificat.
> Mai multe informații: <https://man.archlinux.org/man/at.1>.

- Deschideți un prompt `at` pentru a crea un nou set de comenzi programate, apăsați `Ctrl D` pentru a salva și ieși:

`at {{hh:mm}}`

- Executați comenzile și trimiteți rezultatul prin e-mail cu ajutorul unui program de corespondență locală, cum ar fi Sendmail:

`at {{hh:mm}} -m`

- Execută un script la momentul dat:

`at {{hh:mm}} -f {{path/to/file}}`

- Afișarea unei notificări de sistem la ora 23:00 pe 18 februarie:

`echo "notify-send '{{Wake up!}}'" | at {{11pm}} {{Feb 18}}`
