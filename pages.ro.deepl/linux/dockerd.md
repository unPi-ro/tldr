# dockerd

> Un proces persistent pentru a porni și gestiona containerele docker.
> Mai multe informații: <https://docs.docker.com/engine/reference/commandline/dockerd/>.

- Rulați demonul docker:

`dockerd`

- Rulați demonul docker și configurați-l pentru a asculta anumite socket-uri (UNIX și TCP):

`dockerd --host unix://{{path/to/tmp.sock}} --host tcp://{{ip}}`

- Se execută cu un fișier PID specific pentru demon:

`dockerd --pidfile {{path/to/pid_file}}`

- Se execută în modul de depanare:

`dockerd --debug`

- Executați și setați un anumit nivel de jurnal:

`dockerd --log-level={{debug|info|warn|error|fatal}}`
