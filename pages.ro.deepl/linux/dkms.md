# dkms

> Un cadru care permite construirea dinamică a modulelor de kernel.
> Mai multe informații: <https://github.com/dell/dkms>.

- Listează modulele instalate în prezent:

`dkms status`

- Reconstituie toate modulele pentru nucleul care rulează în prezent:

`dkms autoinstall`

- Instalează versiunea 1.2.1 a modulului acpi_call pentru nucleul care rulează în prezent:

`dkms install -m {{acpi_call}} -v {{1.2.1}}`

- Îndepărtați versiunea 1.2.1 a modulului acpi_call din toate nucleele:

`dkms remove -m {{acpi_call}} -v {{1.2.1}} --all`
