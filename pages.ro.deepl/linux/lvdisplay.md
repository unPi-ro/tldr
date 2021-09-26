# lvdisplay

> Afișați informații despre volumele logice Logical Volume Manager (LVM).
> A se vedea și: `lvm`.
> Mai multe informații: <https://man7.org/linux/man-pages/man8/lvdisplay.8.html>.

- Afișează informații despre toate volumele logice:

`sudo lvdisplay`

- Afișați informații despre toate volumele logice din grupul de volume vg1:

`sudo lvdisplay {{vg1}}`

- Afișați informații despre volumul logic lv1 din grupul de volume vg1:

`sudo lvdisplay {{vg1/lv1}}`
