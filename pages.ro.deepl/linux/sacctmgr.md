# sacctmgr

> Vizualizați, configurați și gestionați conturile Slurm.
> Mai multe informații: <https://slurm.schedmd.com/sacctmgr.html>.

- Afișează configurația curentă:

`sacctmgr show configuration`

- Adăugați un cluster la baza de date slurm:

`sacctmgr add cluster {{cluster_name}}`

- Adăugați un cont în baza de date slurm:

`sacctmgr add account {{account_name}} cluster={{cluster_of_account}}`

- Afișează detalii despre utilizator/asociație/cluster/cont:

`sacctmgr show {{user/association/cluster/account}}`
