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

A'B'C + AB'C' + ABC = B'(A'C + AC') + ABC

Principle Scheme
------

<img src="https://github.com/vorobyovvitaliy/Logical-Circuits/blob/master/PrincipalScheme.png">

Functional Scheme
------

<img src="https://github.com/vorobyovvitaliy/Logical-Circuits/blob/master/FunctionalScheme.png">

Testing Video
------

<iframe width="1191" height="670" src="https://www.youtube.com/embed/D4BZn3lRx5I" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
