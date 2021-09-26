# srun

> Creați un job slurm interactiv sau conectați-vă la un job existent.
> Mai multe informații: <https://slurm.schedmd.com/srun.html>.

- Depuneți o lucrare interactivă de bază:

`srun --pty /bin/bash`

- Trimiteți o sarcină interactivă cu diferite atribute:

`srun --ntasks-per-node={{num_cores}} --mem-per-cpu={{memory_MB}} --pty /bin/bash`

- Conectați-vă la un nod de lucru cu o sarcină în curs de execuție:

`srun --jobid={{job_id}} --pty /bin/bash`
