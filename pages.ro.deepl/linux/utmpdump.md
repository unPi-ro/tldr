# utmpdump

> Aruncați și încărcați fișierele de contabilitate btmp, utmp și wtmp.

- Aruncă fișierul `/var/log/wtmp` pe ieșirea standard ca text simplu:

`utmpdump {{/var/log/wtmp}}`

- Încarcă un fișier descărcat anterior în `/var/log/wtmp`:

`utmpdump -r {{dumpfile}} > {{/var/log/wtmp}}`
