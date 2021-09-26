# daemonize

> Rulați o comandă (care nu se dă pe sine ca daemon) ca daemon Unix.
> Mai multe informații: <http://software.clapper.org/daemonize/>.

- Rulați o comandă ca demon:

`daemonize {{command}} {{command_arguments}}`

- Scrie PID-ul în fișierul specificat:

`daemonize -p {{path/to/pidfile}} {{command}} {{command_arguments}}`

- Utilizați un fișier de blocare pentru a vă asigura că doar o singură instanță rulează în același timp:

`daemonize -l {{path/to/lockfile}} {{command}} {{command_arguments}}`

- Utilizați contul de utilizator specificat:

`sudo daemonize -u {{user}} {{command}} {{command_arguments}}`
