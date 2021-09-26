# disown

> Permiteți subproceselor să trăiască dincolo de shell-ul la care sunt atașate.
> Vezi și comanda `jobs`.
> Mai multe informații: <https://www.gnu.org/software/bash/manual/bash.html#index-disown>.

- Renunță la postul actual:

`disown`

- Respingeți o anumită sarcină:

`disown %{{job_number}}`

- Renunță la toate locurile de muncă:

`disown -a`

- Păstrați lucrarea (nu o dezaprobați), dar marcați-o astfel încât să nu se mai primească niciun SIGHUP la ieșirea din shell:

`disown -h %{{job_number}}`
