# kscreen-doctor

> Modificați și manipulați configurația ecranului din linia de comandă.
> Mai multe informații: <https://invent.kde.org/plasma/libkscreen>.

- Afișează informații despre ieșire:

`kscreen-doctor --outputs`

- Setează rotația unei ieșiri de afișare cu ID-ul 1 spre dreapta:

`kscreen-doctor {{output.1.rotation.right}}`

- Setați scara unei ieșiri de afișare cu ID-ul `HDMI-2` la 2 (200%):

`kscreen-doctor {{output.HDMI-2.scale.2}}`
