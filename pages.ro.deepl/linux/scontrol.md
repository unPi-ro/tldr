# scontrol

> Vizualizați informații despre lucrări și modificați-le.
> Mai multe informații: <https://slurm.schedmd.com/scontrol.html>.

- Afișează informații pentru job:

`scontrol show job {{job_id}}`

- Suspendă o listă de lucrări în curs de execuție, separate prin virgulă:

`scontrol suspend {{job_id}}`

- Reluați o listă de lucrări suspendate, separate prin virgulă:

`scontrol resume {{job_id}}`

- Conține o listă, separată prin virgulă, de lucrări aflate în coadă (utilizați comanda `release` pentru a permite programarea lucrărilor):

`scontrol hold {{job_id}}`

- Eliberați o listă de locuri de muncă suspendate, separate prin virgulă:

`scontrol release {{job_id}}`
