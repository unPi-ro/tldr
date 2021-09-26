# genkernel

> Utilitar Gentoo Linux pentru compilarea și instalarea nucleelor.
> Mai multe informații: <https://wiki.gentoo.org/wiki/Genkernel>.

- Compilați și instalați automat un kernel generic:

`sudo genkernel all`

- Construiți și instalați doar bzImage|initramfs|kernel|ramdisk:

`sudo genkernel {{bzImage|initramfs|kernel|ramdisk}}`

- Aplicați modificările la configurația kernelului înainte de compilare și instalare:

`sudo genkernel --menuconfig all`

- Generarea unui nucleu cu un nume personalizat:

`sudo genkernel --kernname={{custom_name}} all`

- Utilizați o sursă de kernel în afara directorului implicit `/usr/src/linux`:

`sudo genkernel --kerneldir={{path/to/directory}} all`
