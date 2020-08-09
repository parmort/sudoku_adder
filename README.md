## Sudoku Adder

This is a small command-line utility that adds unique numbers from 1-9 to a
specified sum.

### Usage

`sudoku_adder <sum> [length]`

- `sum`: The desired sum
- `length`: The desired number of digits

### Examples

```
$ ./sudoku_adder 10
[1, 2, 3, 4]
[1, 2, 7]
[1, 3, 6]
[1, 4, 5]
[1, 9]
[2, 3, 5]
[2, 8]
[3, 7]
[4, 6]
```

```
$ ./sudoku_adder 18 3
[1, 8, 9]
[2, 7, 9]
[3, 6, 9]
[3, 7, 8]
[4, 5, 9]
[4, 6, 8]
[5, 6, 7]
```

### License

Really? It's a 45-line script. I'm not gonna license that.
