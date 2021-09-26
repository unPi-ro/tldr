# bpftrace

> Limbaj de urmărire de nivel înalt pentru Linux eBPF.
> Mai multe informații: <https://github.com/iovisor/bpftrace>.

- Afișează versiunea bpftrace:

`bpftrace -V`

- Enumeră toate sondele disponibile:

`sudo bpftrace -l`

- Executați un program de tip one-liner (de exemplu, syscall count by program):

`sudo bpftrace -e '{{tracepoint:raw_syscalls:sys_enter { @[comm] = count(); }}}'`

- Rulați un program dintr-un fișier:

`sudo bpftrace {{path/to/file}}`

- Urmăriți un program în funcție de PID:

`sudo bpftrace -e '{{tracepoint:raw_syscalls:sys_enter /pid == 123/ { @[comm] = count(); }}}'`

- Efectuați o execuție de probă și afișați rezultatul în format eBPF:

`sudo bpftrace -d -e '{{one_line_program}}'`
