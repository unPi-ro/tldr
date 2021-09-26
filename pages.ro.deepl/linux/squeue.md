# squeue

> Vizualizați lucrările aflate în coada de așteptare în planificatorul SLURM.

- Vizualizați coada de așteptare:

`squeue`

- Vizualizați lucrările puse în coadă de un anumit utilizator:

`squeue -u {{username}}`

- Vizualizați coada de așteptare și reîmprospătați la fiecare 5 secunde:

`squeue -i {{5}}`

- Vizualizați coada de așteptare cu orele de începere preconizate:

`squeue --start`
