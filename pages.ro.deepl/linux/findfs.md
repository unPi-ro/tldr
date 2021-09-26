# findfs

> Găsește un sistem de fișiere după etichetă sau UUID.
> Mai multe informații: <https://mirrors.edge.kernel.org/pub/linux/utils/util-linux>.

- Căutați dispozitive de bloc după eticheta sistemului de fișiere:

`findfs LABEL={{label}}`

- Căutare după UUID-ul sistemului de fișiere:

`findfs UUID={{uuid}}`

- Căutați după eticheta partiției (GPT sau tabela de partiții MAC):

`findfs PARTLABEL={{partition_label}}`

- Căutați după UUID-ul partiției (numai în tabela de partiții GPT):

`findfs PARTUUID={{partition_uuid}}`
