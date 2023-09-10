# Maximize available disk space for build tasks

If the available disk space on Github runners is too little for your build job, this action might be for you.
If not: please go on, there's nothing to see here.

This table shows the amount of free space you receive when using the action with the various options.

OS | Android SDKs removed | .NET SDKs removed | Haskell removed | CodeQL Removed | Cached Docker Images Removed | GB freed | GB free | Elapsed Time (seconds) |
---|:--------------------:|:-----------------:|:---------------:|:--------------:|:----------------------------:|:--------:|:-------:|:----------------------:|
ubuntu-20.04 |  |  |  |  |  | 7 | 26 | 1
ubuntu-20.04 |  |  |  |  | true | 13 | 31 | 41
ubuntu-20.04 |  |  |  | true |  | 15 | 34 | 3
ubuntu-20.04 |  |  |  | true | true | 20 | 39 | 46
ubuntu-20.04 |  |  | true |  |  | 7 | 26 | 3
ubuntu-20.04 |  |  | true |  | true | 13 | 31 | 10
ubuntu-20.04 |  |  | true | true |  | 15 | 34 | 3
ubuntu-20.04 |  |  | true | true | true | 21 | 39 | 40
ubuntu-20.04 |  | true |  |  |  | 9 | 28 | 3
ubuntu-20.04 |  | true |  |  | true | 15 | 33 | 45
ubuntu-20.04 |  | true |  | true |  | 17 | 36 | 6
ubuntu-20.04 |  | true |  | true | true | 23 | 41 | 42
ubuntu-20.04 |  | true | true |  |  | 10 | 28 | 2
ubuntu-20.04 |  | true | true |  | true | 15 | 33 | 40
ubuntu-20.04 |  | true | true | true |  | 17 | 36 | 5
ubuntu-20.04 |  | true | true | true | true | 23 | 41 | 9
ubuntu-20.04 | true |  |  |  |  | 19 | 37 | 82
ubuntu-20.04 | true |  |  |  | true | 25 | 43 | 127
ubuntu-20.04 | true |  |  | true |  | 27 | 45 | 70
ubuntu-20.04 | true |  |  | true | true | 33 | 51 | 77
ubuntu-20.04 | true |  | true |  |  | 19 | 37 | 76
ubuntu-20.04 | true |  | true |  | true | 25 | 43 | 117
ubuntu-20.04 | true |  | true | true |  | 27 | 45 | 11
ubuntu-20.04 | true |  | true | true | true | 32 | 51 | 97
ubuntu-20.04 | true | true |  |  |  | 21 | 39 | 15
ubuntu-20.04 | true | true |  |  | true | 27 | 45 | 128
ubuntu-20.04 | true | true |  | true |  | 29 | 47 | 69
ubuntu-20.04 | true | true |  | true | true | 35 | 53 | 126
ubuntu-20.04 | true | true | true |  |  | 21 | 39 | 79
ubuntu-20.04 | true | true | true |  | true | 26 | 45 | 89
ubuntu-20.04 | true | true | true | true |  | 29 | 48 | 70
ubuntu-20.04 | true | true | true | true | true | 35 | 53 | 107
ubuntu-22.04 |  |  |  |  |  | 7 | 28 | 2
ubuntu-22.04 |  |  |  |  | true | 11 | 33 | 29
ubuntu-22.04 |  |  |  | true |  | 15 | 36 | 4
ubuntu-22.04 |  |  |  | true | true | 19 | 41 | 37
ubuntu-22.04 |  |  | true |  |  | 7 | 28 | 2
ubuntu-22.04 |  |  | true |  | true | 12 | 33 | 32
ubuntu-22.04 |  |  | true | true |  | 15 | 36 | 4
ubuntu-22.04 |  |  | true | true | true | 20 | 41 | 11
ubuntu-22.04 |  | true |  |  |  | 9 | 30 | 6
ubuntu-22.04 |  | true |  |  | true | 14 | 35 | 30
ubuntu-22.04 |  | true |  | true |  | 17 | 39 | 4
ubuntu-22.04 |  | true |  | true | true | 21 | 43 | 39
ubuntu-22.04 |  | true | true |  |  | 9 | 31 | 7
ubuntu-22.04 |  | true | true |  | true | 13 | 35 | 32
ubuntu-22.04 |  | true | true | true |  | 17 | 38 | 6
ubuntu-22.04 |  | true | true | true | true | 21 | 43 | 44
ubuntu-22.04 | true |  |  |  |  | 19 | 40 | 95
ubuntu-22.04 | true |  |  |  | true | 23 | 45 | 106
ubuntu-22.04 | true |  |  | true |  | 27 | 48 | 12
ubuntu-22.04 | true |  |  | true | true | 31 | 53 | 16
ubuntu-22.04 | true |  | true |  |  | 19 | 40 | 10
ubuntu-22.04 | true |  | true |  | true | 23 | 45 | 45
ubuntu-22.04 | true |  | true | true |  | 27 | 49 | 100
ubuntu-22.04 | true |  | true | true | true | 32 | 53 | 77
ubuntu-22.04 | true | true |  |  |  | 21 | 42 | 13
ubuntu-22.04 | true | true |  |  | true | 25 | 47 | 91
ubuntu-22.04 | true | true |  | true |  | 29 | 50 | 90
ubuntu-22.04 | true | true |  | true | true | 34 | 55 | 23
ubuntu-22.04 | true | true | true |  |  | 21 | 43 | 10
ubuntu-22.04 | true | true | true |  | true | 26 | 47 | 16
ubuntu-22.04 | true | true | true | true |  | 29 | 50 | 77
ubuntu-22.04 | true | true | true | true | true | 34 | 55 | 24
