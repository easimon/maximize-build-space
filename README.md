# Maximize available disk space for build tasks

If the available disk space on Github runners is too little for your build job, this action might be for you.
If not: please go on, there's nothing to see here.

This table shows the amount of free space you receive when using the action with the various options.

OS | Android SDKs removed | .NET SDKs removed | Haskell removed | CodeQL Removed | Cached Docker Images Removed | GB freed | GB free | Elapsed Time (seconds) |
---|:--------------------:|:-----------------:|:---------------:|:--------------:|:----------------------------:|:--------:|:-------:|:----------------------:|
ubuntu-20.04 |  |  |  |  |  | 7 | 26 | 2
ubuntu-20.04 |  |  |  |  | true | 12 | 31 | 33
ubuntu-20.04 |  |  |  | true |  | 15 | 34 | 4
ubuntu-20.04 |  |  |  | true | true | 20 | 39 | 8
ubuntu-20.04 |  |  | true |  |  | 7 | 26 | 3
ubuntu-20.04 |  |  | true |  | true | 13 | 32 | 40
ubuntu-20.04 |  |  | true | true |  | 15 | 34 | 3
ubuntu-20.04 |  |  | true | true | true | 21 | 40 | 40
ubuntu-20.04 |  | true |  |  |  | 10 | 29 | 4
ubuntu-20.04 |  | true |  |  | true | 15 | 34 | 41
ubuntu-20.04 |  | true |  | true |  | 18 | 37 | 5
ubuntu-20.04 |  | true |  | true | true | 22 | 41 | 49
ubuntu-20.04 |  | true | true |  |  | 10 | 29 | 4
ubuntu-20.04 |  | true | true |  | true | 15 | 34 | 29
ubuntu-20.04 |  | true | true | true |  | 18 | 37 | 6
ubuntu-20.04 |  | true | true | true | true | 23 | 42 | 11
ubuntu-20.04 | true |  |  |  |  | 19 | 38 | 13
ubuntu-20.04 | true |  |  |  | true | 25 | 44 | 110
ubuntu-20.04 | true |  |  | true |  | 27 | 46 | 77
ubuntu-20.04 | true |  |  | true | true | 32 | 51 | 118
ubuntu-20.04 | true |  | true |  |  | 19 | 38 | 13
ubuntu-20.04 | true |  | true |  | true | 25 | 44 | 15
ubuntu-20.04 | true |  | true | true |  | 27 | 46 | 12
ubuntu-20.04 | true |  | true | true | true | 33 | 52 | 87
ubuntu-20.04 | true | true |  |  |  | 21 | 40 | 106
ubuntu-20.04 | true | true |  |  | true | 27 | 46 | 96
ubuntu-20.04 | true | true |  | true |  | 29 | 48 | 64
ubuntu-20.04 | true | true |  | true | true | 35 | 54 | 86
ubuntu-20.04 | true | true | true |  |  | 21 | 40 | 14
ubuntu-20.04 | true | true | true |  | true | 27 | 46 | 94
ubuntu-20.04 | true | true | true | true |  | 29 | 48 | 59
ubuntu-20.04 | true | true | true | true | true | 35 | 54 | 111
ubuntu-22.04 |  |  |  |  |  | 7 | 29 | 2
ubuntu-22.04 |  |  |  |  | true | 12 | 34 | 30
ubuntu-22.04 |  |  |  | true |  | 15 | 37 | 3
ubuntu-22.04 |  |  |  | true | true | 20 | 42 | 18
ubuntu-22.04 |  |  | true |  |  | 7 | 29 | 3
ubuntu-22.04 |  |  | true |  | true | 12 | 34 | 28
ubuntu-22.04 |  |  | true | true |  | 15 | 37 | 3
ubuntu-22.04 |  |  | true | true | true | 20 | 42 | 18
ubuntu-22.04 |  | true |  |  |  | 10 | 32 | 6
ubuntu-22.04 |  | true |  |  | true | 14 | 36 | 33
ubuntu-22.04 |  | true |  | true |  | 17 | 39 | 7
ubuntu-22.04 |  | true |  | true | true | 22 | 44 | 23
ubuntu-22.04 |  | true | true |  |  | 10 | 32 | 6
ubuntu-22.04 |  | true | true |  | true | 14 | 36 | 8
ubuntu-22.04 |  | true | true | true |  | 18 | 40 | 6
ubuntu-22.04 |  | true | true | true | true | 22 | 44 | 31
ubuntu-22.04 | true |  |  |  |  | 19 | 41 | 12
ubuntu-22.04 | true |  |  |  | true | 23 | 45 | 112
ubuntu-22.04 | true |  |  | true |  | 27 | 49 | 15
ubuntu-22.04 | true |  |  | true | true | 32 | 54 | 103
ubuntu-22.04 | true |  | true |  |  | 19 | 41 | 129
ubuntu-22.04 | true |  | true |  | true | 23 | 45 | 114
ubuntu-22.04 | true |  | true | true |  | 27 | 49 | 72
ubuntu-22.04 | true |  | true | true | true | 32 | 54 | 18
ubuntu-22.04 | true | true |  |  |  | 21 | 43 | 59
ubuntu-22.04 | true | true |  |  | true | 26 | 48 | 99
ubuntu-22.04 | true | true |  | true |  | 29 | 51 | 102
ubuntu-22.04 | true | true |  | true | true | 33 | 55 | 22
ubuntu-22.04 | true | true | true |  |  | 21 | 43 | 95
ubuntu-22.04 | true | true | true |  | true | 25 | 47 | 36
ubuntu-22.04 | true | true | true | true |  | 29 | 51 | 76
ubuntu-22.04 | true | true | true | true | true | 34 | 56 | 18
