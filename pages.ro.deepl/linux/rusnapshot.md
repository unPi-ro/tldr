# rusnapshot

> Utilitar de instantanee BTRFS scris în Rust.
> Mai multe informații: <https://github.com/Edu4rdSHL/rusnapshot>.

- Creați un instantaneu utilizând un fișier de configurare:

`sudo rusnapshot --config {{path/to/config.toml}} --cr`

- Lista instantaneelor create:

`sudo rusnapshot -c {{path/to/config.toml}} --list`

- Ștergeți un instantaneu după ID sau după numele instantaneului:

`sudo rusnapshot -c {{path/to/config.toml}} --del --id {{snapshot_id}}`

- Șterge toate instantaneele `hourly`:

`sudo rusnapshot -c {{path/to/config.toml}} --list --keep {{0}} --clean --kind {{hourly}}`

- Creați un instantaneu de citire-scriere:

`sudo rusnapshot -c {{path/to/config.toml}} --cr --rw`

- Restaurați un instantaneu:

`sudo rusnapshot -c {{path/to/config.toml}} --id {{snapshot_id}} --restore`
