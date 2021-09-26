# ddrescue

> Instrument de recuperare a datelor care citește date de pe dispozitive de bloc deteriorate.
> Mai multe informații: <https://www.gnu.org/software/ddrescue/>.

- Efectuați o imagine a unui dispozitiv, creând un fișier jurnal:

`sudo ddrescue {{/dev/sdb}} {{path/to/image.dd}} {{path/to/log.txt}}`

- Clonați discul A pe discul B, creând un fișier jurnal:

`sudo ddrescue --force --no-scrape {{/dev/sdX}} {{/dev/sdY}} {{path/to/log.txt}}`
