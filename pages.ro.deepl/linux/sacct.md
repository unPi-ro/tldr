# sacct

> Afișați datele contabile de la serviciul Slurm.
> Mai multe informații: <https://slurm.schedmd.com/sacct.html>.

- Afișează ID-ul lucrării, numele lucrării, partiția, contul, numărul de CPU-uri alocate, starea lucrării și codurile de ieșire pentru lucrările recente:

`sacct`

- Afișează ID-ul lucrării, starea lucrării, codul de ieșire a lucrării pentru lucrările recente:

`sacct --brief`

- Afișează alocările unei lucrări:

`sacct --jobs {{job_id}} --allocations`

- Afișează timpul scurs, numele lucrării, numărul de unități centrale de procesare solicitate și memoria solicitată pentru o lucrare:

`sacct --jobs {{job_id}} --format={{elapsed}},{{jobname}},{{reqcpus}},{{reqmem}}`
