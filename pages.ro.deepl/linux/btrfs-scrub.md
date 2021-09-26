# btrfs scrub

> Scrutează sistemele de fișiere btrfs pentru a verifica integritatea datelor.
> Se recomandă să efectuați o spălare o dată pe lună.
> Mai multe informații: <https://btrfs.wiki.kernel.org/index.php/Manpage/btrfs-scrub>.

- Începeți o curățare:

`sudo btrfs scrub start {{path/to/btrfs_mount}}`

- Afișează starea unei operații de spălare în curs de desfășurare sau a ultimei operații finalizate:

`sudo btrfs scrub status {{path/to/btrfs_mount}}`

- Anulați o spălare în curs de desfășurare:

`sudo btrfs scrub cancel {{path/to/btrfs_mount}}`

- Reluarea unei operații de spălare anulate anterior:

`sudo btrfs scrub resume {{path/to/btrfs_mount}}`

- Începeți o spălare, dar așteptați până când se termină spălarea înainte de a ieși:

`sudo btrfs scrub start -B {{path/to/btrfs_mount}}`

- Pornește o curățare în modul liniștit (nu imprimă erori sau statistici):

`sudo btrfs scrub start -q {{path/to/btrfs_mount}}`
