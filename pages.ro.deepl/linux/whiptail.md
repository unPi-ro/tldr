# whiptail

> Afișarea de casete de dialog bazate pe text din scripturi shell.

- Afișați un mesaj simplu:

`whiptail --title "{{title}}" --msgbox "{{message}}" {{height_in_chars}} {{width_in_chars}}`

- Afișează o alegere booleană, returnând rezultatul prin codul de ieșire:

`whiptail --title "{{title}}" --yesno "{{message}}" {{height_in_chars}} {{width_in_chars}}`

- Personalizați textul de pe butoanele da / nu:

`whiptail --title "{{title}}" --yes-button "{{text}}" --no-button "{{text}}" --yesno "{{message}}" {{height_in_chars}} {{width_in_chars}}`

- Afișează o casetă de introducere de text:

`{{result_variable_name}}="$(whiptail --title "{{title}}" --inputbox "{{message}}" {{height_in_chars}} {{width_in_chars}} {{default_text}} 3>&1 1>&2 2>&3)"`

- Afișați o casetă de introducere a parolei:

`{{result_variable_name}}="$(whiptail --title "{{title}}" --passwordbox "{{message}}" {{height_in_chars}} {{width_in_chars}} 3>&1 1>&2 2>&3)"`

- Afișează un meniu cu alegere multiplă:

`{{result_variable_name}}=$(whiptail --title "{{title}}" --menu "{{message}}" {{height_in_chars}} {{width_in_chars}} {{menu_display_height}} "{{value_1}}" "{{display_text_1}}" "{{value_n}}" "{{display_text_n}}" ..... 3>&1 1>&2 2>&3)`
