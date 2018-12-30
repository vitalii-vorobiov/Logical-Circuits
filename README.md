# Logical-Circuits

The task was to create a scheme that can reproduce boolean expression from the truth table

Truth Table
------
```
┌───┬───┬───┬───┬───┬───┬───┬───┬───┐
│ A │ 0 │ 0 │ 0 │ 0 │ 1 │ 1 │ 1 | 1 |
├───┼───┼───┼───┼───┼───┼───┼───┼───┤
│ B │ 0 | 0 │ 1 │ 1 │ 0 │ 0 │ 1 | 1 |
├───┼───┼───┼───┼───┼───┼───┼───┼───┤
│ C │ 0 | 1 │ 0 │ 1 │ 0 │ 1 │ 0 | 1 |
├───┼───┼───┼───┼───┼───┼───┼───┼───┤
│   │ 0 | 1 │ 0 │ 0 │ 1 │ 0 │ 0 | 1 |
└───┴───┴───┴───┴───────────────────┘
```

Boolean Expression
------

&Amacr;&Bmacr;C + A&Bmacr;&Cmacr; + ABC
