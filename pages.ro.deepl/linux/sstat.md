# sstat

> Vizualizați informații despre lucrările în desfășurare.
> Mai multe informații: <https://slurm.schedmd.com/sstat.html>.

- Afișează informații despre starea unei liste de lucrări separate prin virgulă:

`sstat --jobs={{job_id}}`

- Afișează ID-ul lucrării, CPU-ul mediu și dimensiunea medie a memoriei virtuale a unei liste de lucrări separate prin virgulă, cu pipe-uri ca delimitatori de coloană:

`sstat --parsable --jobs={{job_id}} --format={{JobID}},{{AveCPU}},{{AveVMSize}}`

- Afișarea listei de câmpuri disponibile:

`sstat --helpformat`
