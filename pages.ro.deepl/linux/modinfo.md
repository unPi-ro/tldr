# modinfo

> Extrageți informații despre un modul de kernel Linux.
> Mai multe informații: <https://manned.org/modinfo>.

- Enumeră toate atributele unui modul de kernel:

`modinfo {{kernel_module}}`

- Enumeră numai atributul specificat:

`modinfo -F {{author|description|license|parm|filename}} {{kernel_module}}`
