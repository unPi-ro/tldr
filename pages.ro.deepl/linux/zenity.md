# zenity

> Afișarea dialogurilor din linia de comandă/scripturi shell.
> Întoarce valorile introduse de utilizator sau 1 în caz de eroare.

- Afișează fereastra de dialog a întrebărilor implicite:

`zenity --question`

- Afișează o fereastră de dialog cu informații care afișează textul "Hello!":

`zenity --info --text="{{Hello!}}"`

- Afișează un formular cu nume/parolă și afișează datele separate prin ";":

`zenity --forms --add-entry="{{Name}}" --add-password="{{Password}}" --separator="{{;}}"`

- Afișarea unui formular de selectare a fișierelor în care utilizatorul poate selecta numai directoare:

`zenity --file-selection --directory`

- Afișează o bară de progres care își actualizează mesajul la fiecare secundă și afișează un procent de progres:

`{{(echo "#1"; sleep 1; echo "50"; echo "#2"; sleep 1; echo "100")}} | zenity --progress`
