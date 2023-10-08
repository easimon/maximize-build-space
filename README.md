# Maximize available disk space for build tasks

If the available disk space on Github runners is too little for your build job, this action might be for you.
If not: please go on, there's nothing to see here.

This table shows the amount of free space you receive when using the action with the various options.

OS | Android SDKs removed | .NET SDKs removed | Haskell removed | CodeQL Removed | Cached Docker Images Removed | GB freed | GB free | Elapsed Time (seconds) |
---|:--------------------:|:-----------------:|:---------------:|:--------------:|:----------------------------:|:--------:|:-------:|:----------------------:|
ubuntu-20.04 |  |  |  |  |  | 7 | 28 | 2
ubuntu-20.04 |  |  |  |  | true | 13 | 34 | 12
ubuntu-20.04 |  |  |  | true |  | 11 | 32 | 4
ubuntu-20.04 |  |  |  | true | true | 17 | 38 | 32
ubuntu-20.04 |  |  | true |  |  | 7 | 28 | 2
ubuntu-20.04 |  |  | true |  | true | 13 | 34 | 30
ubuntu-20.04 |  |  | true | true |  | 11 | 32 | 4
ubuntu-20.04 |  |  | true | true | true | 17 | 38 | 13
ubuntu-20.04 |  | true |  |  |  | 9 | 30 | 4
ubuntu-20.04 |  | true |  |  | true | 15 | 36 | 43
ubuntu-20.04 |  | true |  | true |  | 13 | 34 | 7
ubuntu-20.04 |  | true |  | true | true | 19 | 40 | 50
ubuntu-20.04 |  | true | true |  |  | 9 | 30 | 5
ubuntu-20.04 |  | true | true |  | true | 15 | 36 | 11
ubuntu-20.04 |  | true | true | true |  | 13 | 34 | 3
ubuntu-20.04 |  | true | true | true | true | 19 | 40 | 43
ubuntu-20.04 | true |  |  |  |  | 21 | 42 | 61
ubuntu-20.04 | true |  |  |  | true | 27 | 48 | 21
ubuntu-20.04 | true |  |  | true |  | 25 | 46 | 63
ubuntu-20.04 | true |  |  | true | true | 31 | 52 | 27
ubuntu-20.04 | true |  | true |  |  | 21 | 42 | 66
ubuntu-20.04 | true |  | true |  | true | 27 | 48 | 15
ubuntu-20.04 | true |  | true | true |  | 25 | 46 | 9
ubuntu-20.04 | true |  | true | true | true | 31 | 52 | 97
ubuntu-20.04 | true | true |  |  |  | 23 | 44 | 12
ubuntu-20.04 | true | true |  |  | true | 29 | 50 | 80
ubuntu-20.04 | true | true |  | true |  | 27 | 48 | 94
ubuntu-20.04 | true | true |  | true | true | 33 | 54 | 99
ubuntu-20.04 | true | true | true |  |  | 23 | 44 | 10
ubuntu-20.04 | true | true | true |  | true | 29 | 50 | 21
ubuntu-20.04 | true | true | true | true |  | 27 | 48 | 82
ubuntu-20.04 | true | true | true | true | true | 33 | 54 | 90
ubuntu-22.04 |  |  |  |  |  | 7 | 26 | 1
ubuntu-22.04 |  |  |  |  | true | 13 | 32 | 8
ubuntu-22.04 |  |  |  | true |  | 15 | 34 | 4
ubuntu-22.04 |  |  |  | true | true | 21 | 40 | 21
ubuntu-22.04 |  |  | true |  |  | 7 | 26 | 1
ubuntu-22.04 |  |  | true |  | true | 13 | 32 | 9
ubuntu-22.04 |  |  | true | true |  | 15 | 34 | 3
ubuntu-22.04 |  |  | true | true | true | 21 | 40 | 25
ubuntu-22.04 |  | true |  |  |  | 10 | 29 | 5
ubuntu-22.04 |  | true |  |  | true | 15 | 34 | 31
ubuntu-22.04 |  | true |  | true |  | 18 | 37 | 5
ubuntu-22.04 |  | true |  | true | true | 23 | 42 | 11
ubuntu-22.04 |  | true | true |  |  | 10 | 29 | 5
ubuntu-22.04 |  | true | true |  | true | 15 | 34 | 15
ubuntu-22.04 |  | true | true | true |  | 18 | 37 | 6
ubuntu-22.04 |  | true | true | true | true | 23 | 42 | 30
ubuntu-22.04 | true |  |  |  |  | 21 | 40 | 72
ubuntu-22.04 | true |  |  |  | true | 27 | 46 | 91
ubuntu-22.04 | true |  |  | true |  | 29 | 48 | 73
ubuntu-22.04 | true |  |  | true | true | 35 | 54 | 118
ubuntu-22.04 | true |  | true |  |  | 21 | 40 | 65
ubuntu-22.04 | true |  | true |  | true | 27 | 46 | 23
ubuntu-22.04 | true |  | true | true |  | 29 | 48 | 59
ubuntu-22.04 | true |  | true | true | true | 35 | 54 | 20
ubuntu-22.04 | true | true |  |  |  | 23 | 42 | 76
ubuntu-22.04 | true | true |  |  | true | 29 | 48 | 75
ubuntu-22.04 | true | true |  | true |  | 31 | 50 | 73
ubuntu-22.04 | true | true |  | true | true | 37 | 56 | 105
ubuntu-22.04 | true | true | true |  |  | 23 | 42 | 68
ubuntu-22.04 | true | true | true |  | true | 29 | 48 | 87
ubuntu-22.04 | true | true | true | true |  | 31 | 50 | 80
ubuntu-22.04 | true | true | true | true | true | 37 | 56 | 103
