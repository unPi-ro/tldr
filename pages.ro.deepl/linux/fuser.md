# fuser

> Afișează ID-urile proceselor care utilizează în prezent fișiere sau socket-uri.
> Mai multe informații: <https://manned.org/fuser>.

- Aflați ce procese accesează un fișier sau un director:

`fuser {{path/to/file_or_directory}}`

- Afișează mai multe câmpuri (`USER`, `PID`, `ACCESS` și `COMMAND`):

`fuser --verbose {{path/to/file_or_directory}}`

- Identificarea proceselor care utilizează un socket TCP:

`fuser --namespace tcp {{port}}`

- Ucide toate procesele care accesează un fișier sau un director (trimite semnalul `SIGKILL`):

`fuser --kill {{path/to/file_or_directory}}`

- Aflați ce procese accesează sistemul de fișiere care conține un anumit fișier sau director:

`fuser --mount {{path/to/file_or_directory}}`
