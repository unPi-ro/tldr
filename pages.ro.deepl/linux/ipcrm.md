# ipcrm

> Ștergeți resursele IPC (Inter-process Communication).
> Mai multe informații: <https://manned.org/ipcrm>.

- Ștergeți un segment de memorie partajată după ID:

`ipcrm --shmem-id {{shmem_id}}`

- Ștergeți un segment de memorie partajată prin cheie:

`ipcrm --shmem-key {{shmem_key}}`

- Ștergeți o coadă IPC după ID:

`ipcrm --queue-id {{ipc_queue_id}}`

- Ștergeți o coadă IPC prin cheie:

`ipcrm --queue-key {{ipc_queue_key}}`

- Șterge un semafor după ID:

`ipcrm --semaphore-id {{semaphore_id}}`

- Șterge un semafor în funcție de cheie:

`ipcrm --semaphore-key {{semaphore_key}}`

- Ștergeți toate resursele IPC:

`ipcrm --all`
