# partx

> Analizează o tabelă de partiții și spune-i nucleului despre ea.
> Mai multe informații: <https://man7.org/linux/man-pages/man8/partx.8.html>.

- Enumeră partițiile de pe un dispozitiv bloc sau o imagine de disc:

`sudo partx --list {{path/to/device_or_disk_image}}`

- Adaugă în nucleu toate partițiile găsite într-un anumit dispozitiv de blocuri:

`sudo partx --add --verbose {{path/to/device_or_disk_image}}`

- Șterge toate partițiile găsite din kernel (nu modifică partițiile de pe disc):

`sudo partx --delete {{path/to/device_or_disk_image}}`
