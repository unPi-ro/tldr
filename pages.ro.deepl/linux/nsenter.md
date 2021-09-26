# nsenter

> Executați o nouă comandă în spațiul de nume al unui proces în curs de execuție.
> Este deosebit de util pentru imaginile docker sau chroot jails.
> Mai multe informații: <https://github.com/jpetazzo/nsenter/>.

- Executați comanda în spațiul de nume al rețelei de procese existente:

`nsenter -t {{pid}} -n {{command}} {{command_arguments}}`

- Executați o nouă comandă într-un spațiu de nume de procese ps-table existent:

`nsenter -t {{pid}} -p {{command}} {{command_arguments}}`

- Executați comanda în spațiul de nume IPC al proceselor existente:

`nsenter -t {{pid}} -i {{command}} {{command_arguments}}`
