# update-alternatives

> Un instrument convenabil pentru menținerea legăturilor simbolice pentru a determina comenzile implicite.
> Mai multe informații: <https://manned.org/update-alternatives>.

- Adăugați o legătură simbolică:

`sudo update-alternatives --install {{path/to/symlink}} {{command_name}} {{path/to/command_binary}} {{priority}}`

- Configurați o legătură simbolică pentru `java`:

`sudo update-alternatives --config {{java}}`

- Elimină o legătură simbolică:

`sudo update-alternatives --remove {{java}} {{/opt/java/jdk1.8.0_102/bin/java}}`

- Afișează informații despre o comandă specificată:

`update-alternatives --display {{java}}`

- Afișează toate comenzile și selecția curentă a acestora:

`update-alternatives --get-selections`
