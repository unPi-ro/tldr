# sbatch

> Trimiteți o sarcină de lucru pe loturi către planificatorul SLURM.

- Trimiteți o lucrare pe loturi:

`sbatch {{path/to/job.sh}}`

- Trimiteți o lucrare pe loturi cu un nume personalizat:

`sbatch --job-name={{myjob}} {{path/to/job.sh}}`

- Trimiteți o lucrare pe loturi cu o limită de timp de 30 de minute:

`sbatch --time={{00:30:00}} {{path/to/job.sh}}`

- Trimiteți o lucrare și solicitați mai multe noduri:

`sbatch --nodes={{3}} {{path/to/job.sh}}`
