# bluetoothctl

> Gestionați dispozitivele Bluetooth din linia de comandă.
> Mai multe informații: <https://www.npmjs.com/package/bluetoothctl>.

- Intrați în shell-ul bluetoothctl:

`bluetoothctl`

- Lista de dispozitive:

`bluetoothctl -- devices`

- Împerecheați un dispozitiv:

`bluetoothctl -- pair {{mac_address}}`

- Îndepărtați un dispozitiv:

`bluetoothctl -- remove {{mac_address}}`

- Conectați un dispozitiv împerecheat:

`bluetoothctl -- connect {{mac_address}}`

- Deconectați un dispozitiv împerecheat:

`bluetoothctl -- disconnect {{mac_address}}`
