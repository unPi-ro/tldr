# rspamc

> Client în linie de comandă pentru serverele rspamd.

- Antrenați filtrul bayesian pentru a recunoaște un e-mail ca fiind spam:

`rspamc learn_spam {{path/to/email_file}}`

- Antrenați filtrul bayesian pentru a recunoaște un e-mail ca fiind un mesaj de tip "ham":

`rspamc learn_ham {{path/to/email_file}}`

- Generați un raport manual privind un e-mail:

`rspamc symbols {{path/to/email_file}}`

- Afișează statisticile serverului:

`rspamc stat`
