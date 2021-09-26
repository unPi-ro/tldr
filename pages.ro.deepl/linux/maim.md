# maim

> Utilitar pentru captură de ecran.
> Mai multe informații: <https://github.com/naelstrof/maim>.

- Capturează o captură de ecran și o salvează în calea dată:

`maim {{path/to/screenshot.png}}`

- Capturați o captură de ecran a regiunii selectate:

`maim --select {{path/to/screenshot.png}}`

- Captură o captură de ecran a regiunii selectate și o salvează în clipboard (necesită `xclip`):

`maim --select | xclip -selection clipboard -target image/png`

- Captură o captură de ecran a ferestrei active curente (necesită `xdotool`):

`maim --window $(xdotool getactivewindow) {{path/to/screenshot.png}}`
