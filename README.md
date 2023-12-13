# Resource-Constrained Reconfigurable Assembly Line Balancing Problem Dataset

## Fileformat

The Resource-constrained reconfigurable assembly line balancing problem dataset is composed of two files in ".txt" file format.

“PPGraph_Operation.txt” describes the relevant information of the operation.
The information in each line is as follows：
```yaml
<number of operation> <name of operation> <name of first resource>(process time in `s`) <name of second resource>(process time in `s`)……
```

“PPGraph_Precedence.txt” describes the relevant information of the operation precedence.
The information in each line is as follows：
```yaml
<first operation> <second operation>.
```

That represents a process precedence, indicating that the first operation is better than the second operation.

## License

This work is licensed under a [Creative Commons Attribution 4.0 International](https://creativecommons.org/licenses/by/4.0/) license.

```yaml
SPDX-License-Identifier: CC-BY-4.0
```
