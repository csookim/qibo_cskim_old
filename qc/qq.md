#### Runcard(.yaml)

https://qibo.science/qibocal/stable/tutorials/basic.html#dummy-guide-for-single-qubit-calibration

#### commands

```sh
srun -p qw11q qq acquire temp_rc.yaml
```

```sh
qq acquire rc.yaml
qq fit 2024-09-12-006-changsoo-kim -o new_output
qq report new_output

qq auto rc.yaml -o new_output

qq upload new_output
```
