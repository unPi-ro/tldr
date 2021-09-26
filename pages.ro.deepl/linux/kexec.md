# kexec

> Reporniți direct într-un nou kernel.
> Mai multe informații: <https://manned.org/kexec>.

- Încarcă un nou kernel:

`kexec -l {{path/to/kernel}} --initrd={{path/to/initrd}} --command-line={{arguments}}`

- Încarcă un nou kernel cu parametrii de pornire actuali:

`kexec -l {{path/to/kernel}} --initrd={{path/to/initrd}} --reuse-cmdline`

- Execută un kernel încărcat în prezent:

`kexec -e`

- Descarcă kernelul țintă kexec curent:

`kexec -u`
