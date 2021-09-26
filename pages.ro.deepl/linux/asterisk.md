# asterisk

> Server de telefonie și de schimb (telefon).
> Folosit pentru rularea serverului în sine și pentru gestionarea unei instanțe care rulează deja.
> Mai multe informații: <https://wiki.asterisk.org/wiki/display/AST/Home>.

- [R]econectați-vă la un server în funcțiune și activați jurnalizarea la 3 niveluri de [v]erbozitate:

`asterisk -r -vvv`

- [R]econectați-vă la un server în funcțiune, executați o singură comandă și reveniți:

`asterisk -r -x "{{command}}"`

- Afișați clienții chan_SIP (telefoane):

`asterisk -r -x "sip show peers"`

- Afișați apelurile și canalele active:

`asterisk -r -x "core show channels"`

- Afișați cutiile poștale vocale:

`asterisk -r -x "voicemail show users"`

- Termină la canal:

`asterisk -r -x "hangup request {{channel_ID}}"`

- Reîncărcați configurația chan_SIP:

`asterisk -r -x "sip reload"`
