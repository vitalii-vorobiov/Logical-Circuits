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

A'B'C + AB'C' + ABC

Principle Scheme
------

<img src="https://github.com/vorobyovvitaliy/Logical-Circuits/blob/master/PrincipalScheme.png">

Functional Scheme
------

<img src="https://github.com/vorobyovvitaliy/Logical-Circuits/blob/master/FunctionalScheme.png">
