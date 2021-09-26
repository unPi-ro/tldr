# rofi

> Un lansator de aplicații și un comutator de ferestre.
> Mai multe informații: <https://github.com/davatorium/rofi>.

- Afișați lista de aplicații:

`rofi -show drun`

- Afișează lista tuturor comenzilor:

`rofi -show run`

- Comutați între ferestre:

`rofi -show window`

- Transmite o listă de elemente la stdin și imprimă elementul selectat la stdout:

`printf "{{Choice1\nChoice2\nChoice3}}" | rofi -dmenu`
