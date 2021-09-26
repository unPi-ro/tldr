# cpufreq-set

> Un instrument pentru a modifica setările de frecvență a procesorului.
> Valoarea frecvenței ar trebui să fie cuprinsă între valoarea de ieșire a comenzii `cpufreq-info -l`.
> Mai multe informații: <https://manned.org/cpufreq-set>.

- Setați politica de frecvență a CPU a CPU 1 la "userspace":

`sudo cpufreq-set -c {{1}} -g {{userspace}}`

- Setați frecvența minimă curentă a CPU 1:

`sudo cpufreq-set -c {{1}} --min {{min_frequency}}`

- Setați frecvența maximă curentă a CPU 1:

`sudo cpufreq-set -c {{1}} --max {{max_frequency}}`

- Setați frecvența de lucru curentă a CPU 1:

`sudo cpufreq-set -c {{1}} -f {{work_frequency}}`
