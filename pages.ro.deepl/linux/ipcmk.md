# ipcmk

> Creați resurse IPC (Inter-process Communication).
> Mai multe informații: <https://manned.org/ipcmk>.

- Creați un segment de memorie partajată:

`ipcmk --shmem {{segment_size_in_bytes}}`

- Creați un semafor:

`ipcmk --semaphore {{element_size}}`

- Creați o coadă de mesaje:

`ipcmk --queue`

- Creează un segment de memorie partajată cu permisiuni specifice (valoarea implicită este 0644):

`ipcmk --shmem {{segment_size_in_bytes}} {{octal_permissons}}`
