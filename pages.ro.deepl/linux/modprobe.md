# modprobe

> Adăugați sau eliminați module din nucleul Linux.
> Mai multe informații: <https://manned.org/modprobe>.

- Pretinde că încarcă un modul în kernel, dar nu o face de fapt:

`sudo modprobe --dry-run {{module_name}}`

- Încarcă un modul în kernel:

`sudo modprobe {{module_name}}`

- Elimină un modul din kernel:

`sudo modprobe --remove {{module_name}}`

- Elimină din kernel un modul și modulele care depind de el:

`sudo modprobe --remove-dependencies {{module_name}}`

- Afișează dependențele unui modul de kernel:

`sudo modprobe --show-depends {{module_name}}`
