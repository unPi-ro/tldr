# vgchange

> Modificați atributele unui grup de volume Logical Volume Manager (LVM).
> A se vedea și: `lvm`.
> Mai multe informații: <https://manned.org/vgchange>.

- Modificați starea de activare a volumelor logice din toate grupurile de volume:

`sudo vgchange --activate {{y|n}}`

- Schimbă starea de activare a volumelor logice din grupul de volume specificat (se determină cu `vgscan`):

`sudo vgchange --activate {{y|n}} {{volume_group}}}`
