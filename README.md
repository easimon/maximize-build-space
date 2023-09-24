# Maximize available disk space for build tasks

If the available disk space on Github runners is too little for your build job, this action might be for you.
If not: please go on, there's nothing to see here.

This table shows the amount of free space you receive when using the action with the various options.

OS | Android SDKs removed | .NET SDKs removed | Haskell removed | CodeQL Removed | Cached Docker Images Removed | GB freed | GB free | Elapsed Time (seconds) |
---|:--------------------:|:-----------------:|:---------------:|:--------------:|:----------------------------:|:--------:|:-------:|:----------------------:|
ubuntu-20.04 |  |  |  |  |  | 7 | 27 | 2
ubuntu-20.04 |  |  |  |  | true | 12 | 32 | 41
ubuntu-20.04 |  |  |  | true |  | 15 | 35 | 3
ubuntu-20.04 |  |  |  | true | true | 21 | 41 | 58
ubuntu-20.04 |  |  | true |  |  | 7 | 27 | 2
ubuntu-20.04 |  |  | true |  | true | 12 | 32 | 37
ubuntu-20.04 |  |  | true | true |  | 15 | 35 | 4
ubuntu-20.04 |  |  | true | true | true | 20 | 40 | 40
ubuntu-20.04 |  | true |  |  |  | 10 | 30 | 3
ubuntu-20.04 |  | true |  |  | true | 14 | 34 | 46
ubuntu-20.04 |  | true |  | true |  | 17 | 37 | 7
ubuntu-20.04 |  | true |  | true | true | 22 | 42 | 43
ubuntu-20.04 |  | true | true |  |  | 9 | 29 | 9
ubuntu-20.04 |  | true | true |  | true | 15 | 35 | 40
ubuntu-20.04 |  | true | true | true |  | 17 | 37 | 10
ubuntu-20.04 |  | true | true | true | true | 22 | 42 | 32
ubuntu-20.04 | true |  |  |  |  | 19 | 39 | 10
ubuntu-20.04 | true |  |  |  | true | 24 | 44 | 87
ubuntu-20.04 | true |  |  | true |  | 27 | 47 | 84
ubuntu-20.04 | true |  |  | true | true | 32 | 52 | 102
ubuntu-20.04 | true |  | true |  |  | 19 | 39 | 9
ubuntu-20.04 | true |  | true |  | true | 24 | 44 | 100
ubuntu-20.04 | true |  | true | true |  | 27 | 47 | 71
ubuntu-20.04 | true |  | true | true | true | 33 | 53 | 40
ubuntu-20.04 | true | true |  |  |  | 21 | 41 | 71
ubuntu-20.04 | true | true |  |  | true | 26 | 46 | 15
ubuntu-20.04 | true | true |  | true |  | 29 | 49 | 83
ubuntu-20.04 | true | true |  | true | true | 34 | 54 | 50
ubuntu-20.04 | true | true | true |  |  | 21 | 41 | 64
ubuntu-20.04 | true | true | true |  | true | 26 | 46 | 98
ubuntu-20.04 | true | true | true | true |  | 29 | 49 | 78
ubuntu-20.04 | true | true | true | true | true | 34 | 54 | 98
ubuntu-22.04 |  |  |  |  |  | 7 | 29 | 2
ubuntu-22.04 |  |  |  |  | true | 11 | 33 | 35
ubuntu-22.04 |  |  |  | true |  | 15 | 37 | 3
ubuntu-22.04 |  |  |  | true | true | 20 | 42 | 7
ubuntu-22.04 |  |  | true |  |  | 7 | 29 | 2
ubuntu-22.04 |  |  | true |  | true | 11 | 33 | 26
ubuntu-22.04 |  |  | true | true |  | 15 | 37 | 3
ubuntu-22.04 |  |  | true | true | true | 20 | 42 | 40
ubuntu-22.04 |  | true |  |  |  | 9 | 31 | 3
ubuntu-22.04 |  | true |  |  | true | 14 | 36 | 34
ubuntu-22.04 |  | true |  | true |  | 17 | 39 | 7
ubuntu-22.04 |  | true |  | true | true | 22 | 44 | 31
ubuntu-22.04 |  | true | true |  |  | 9 | 31 | 6
ubuntu-22.04 |  | true | true |  | true | 14 | 36 | 31
ubuntu-22.04 |  | true | true | true |  | 17 | 39 | 6
ubuntu-22.04 |  | true | true | true | true | 22 | 44 | 11
ubuntu-22.04 | true |  |  |  |  | 19 | 41 | 83
ubuntu-22.04 | true |  |  |  | true | 23 | 45 | 92
ubuntu-22.04 | true |  |  | true |  | 27 | 49 | 73
ubuntu-22.04 | true |  |  | true | true | 31 | 53 | 90
ubuntu-22.04 | true |  | true |  |  | 19 | 41 | 61
ubuntu-22.04 | true |  | true |  | true | 23 | 45 | 73
ubuntu-22.04 | true |  | true | true |  | 27 | 49 | 73
ubuntu-22.04 | true |  | true | true | true | 31 | 53 | 105
ubuntu-22.04 | true | true |  |  |  | 21 | 43 | 63
ubuntu-22.04 | true | true |  |  | true | 25 | 47 | 98
ubuntu-22.04 | true | true |  | true |  | 29 | 51 | 75
ubuntu-22.04 | true | true |  | true | true | 34 | 56 | 34
ubuntu-22.04 | true | true | true |  |  | 21 | 43 | 15
ubuntu-22.04 | true | true | true |  | true | 25 | 47 | 99
ubuntu-22.04 | true | true | true | true |  | 29 | 51 | 11
ubuntu-22.04 | true | true | true | true | true | 34 | 56 | 103
