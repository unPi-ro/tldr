# taskset

> Obțineți sau setați afinitatea CPU a unui proces sau porniți un proces nou cu o afinitate CPU definită.

- Obține afinitatea CPU a unui proces în desfășurare în funcție de PID:

`taskset --pid --cpu-list {{pid}}`

- Setați afinitatea CPU a unui proces în curs de execuție în funcție de PID:

`taskset --pid --cpu-list {{cpu_id}} {{pid}}`

- Porniți un nou proces cu afinitate pentru un singur procesor:

`taskset --cpu-list {{cpu_id}} {{command}}`

- Porniți un nou proces cu afinitate pentru mai multe unități centrale de procesare nesecvențiale:

`taskset --cpu-list {{cpu_id_1}} {{cpu_id_2}} {{cpu_id_3}}`

- Porniți un nou proces cu afinitate pentru procesoarele 1 până la 4:

`taskset --cpu-list {{cpu_id_1}},{{cpu_id_4}}`
