# sinfo

> Vizualizați informații despre nodurile și partițiile Slurm.
> Vedeți și `squeue` și `sbatch`, care fac parte, de asemenea, din managerul de sarcină de lucru Slurm.
> Mai multe informații: <https://slurm.schedmd.com/sinfo.html>.

- Afișează un rezumat rapid al clusterului:

`sinfo --summarize`

- Vizualizați starea detaliată a tuturor partițiilor din întregul cluster:

`sinfo`

- Vizualizați starea detaliată a unei partiții specifice:

`sinfo --partition {{partition_name}}`

- Vizualizați informații despre nodurile inactive:

`sinfo --states {{idle}}`

- Rezumați nodurile moarte:

`sinfo --dead`

- Enumerați nodurile moarte și motivele pentru care acestea au murit:

`sinfo --list-reasons`
