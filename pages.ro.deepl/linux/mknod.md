# mknod

> Creați fișiere speciale pentru dispozitive de bloc sau de caractere.
> Mai multe informații: <https://www.gnu.org/software/coreutils/mknod>.

- Creați un dispozitiv de bloc:

`sudo mknod {{path/to/device_file}} b {{major_device_number}} {{minor_device_number}}`

- Creați un dispozitiv de caractere:

`sudo mknod {{path/to/device_file}} c {{major_device_number}} {{minor_device_number}}`

- Creați un dispozitiv FIFO (coadă de așteptare):

`sudo mknod {{path/to/device_file}} p`

- Creați un fișier de dispozitiv cu un context de securitate SELinux implicit:

`sudo mknod -Z {{path/to/device_file}} {{type}} {{major_device_number}} {{minor_device_number}}`
