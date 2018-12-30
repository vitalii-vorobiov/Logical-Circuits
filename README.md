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

[![Testing Video](https://img.youtube.com/vi/YOUTUBE_VIDEO_ID_HERE/0.jpg)](https://youtu.be/D4BZn3lRx5I)
