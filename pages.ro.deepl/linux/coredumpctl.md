# coredumpctl

> Preluarea și procesarea descărcărilor de nucleu și a metadatelor salvate.
> Mai multe informații: <https://www.freedesktop.org/software/systemd/man/coredumpctl.html>.

- Lista tuturor descărcărilor de nucleu capturate:

`coredumpctl list`

- Lista descărcărilor de nucleu capturate pentru un program:

`coredumpctl list {{program}}`

- Afișează informații despre descărcările de nucleu care corespund unui program cu `PID`:

`coredumpctl info {{PID}}`

- Invocă depanatorul folosind ultima descărcare de nucleu a unui program:

`coredumpctl debug {{program}}`

- Extrage într-un fișier ultima descărcare de nucleu a unui program:

`coredumpctl --output={{path/to/file}} dump {{program}}`
