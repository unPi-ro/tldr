# boltctl

> Controlați dispozitivele thunderbolt.
> Mai multe informații: <https://manned.org/boltctl>.

- Lista dispozitivelor conectate (și autorizate):

`boltctl`

- Enumerați dispozitivele conectate, inclusiv cele neautorizate:

`boltctl list`

- Autorizarea temporară a unui dispozitiv:

`boltctl authorize {{device_uuid}}`

- Autorizarea și memorarea unui dispozitiv:

`boltctl enroll {{device_uuid}}`

- Revocați un dispozitiv autorizat anterior:

`boltctl forget {{device_uuid}}`

- Afișați mai multe informații despre un dispozitiv:

`boltctl info {{device_uuid}}`
