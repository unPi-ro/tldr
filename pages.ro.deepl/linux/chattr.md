# chattr

> Modificați atributele fișierelor sau directoarelor.
> Mai multe informații: <https://manned.org/chattr>.

- Face ca un fișier sau un director să fie imuabil la modificări și ștergeri, chiar și de către superutilizator:

`chattr +i {{path/to/file_or_directory}}`

- Face ca un fișier sau un director să fie mutabil:

`chattr -i {{path/to/file_or_directory}}`

- Efectuați în mod recurent o imuabilitate a unui întreg director și a conținutului acestuia:

`chattr -R +i {{path/to/directory}}`
