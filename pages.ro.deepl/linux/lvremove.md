# lvremove

> Eliminați unul sau mai multe volume logice.
> A se vedea și: `lvm`.
> Mai multe informații: <https://man7.org/linux/man-pages/man8/lvremove.8.html>.

- Eliminați un volum logic dintr-un grup de volume:

`sudo lvremove {{volume_group}}/{{logical_volume}}`

- Eliminați toate volumele logice dintr-un grup de volume:

`sudo lvremove {{volume_group}}`
