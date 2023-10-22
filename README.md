# Maximize available disk space for build tasks

If the available disk space on Github runners is too little for your build job, this action might be for you.
If not: please go on, there's nothing to see here.

This table shows the amount of free space you receive when using the action with the various options.

OS | Android SDKs removed | .NET SDKs removed | Haskell removed | CodeQL Removed | Cached Docker Images Removed | GB freed | GB free | Elapsed Time (seconds) |
---|:--------------------:|:-----------------:|:---------------:|:--------------:|:----------------------------:|:--------:|:-------:|:----------------------:|
ubuntu-20.04 |  |  |  |  |  | 7 | 30 | 2
ubuntu-20.04 |  |  |  |  | true | 13 | 36 | 60
ubuntu-20.04 |  |  |  | true |  | 10 | 33 | 4
ubuntu-20.04 |  |  |  | true | true | 17 | 40 | 14
ubuntu-20.04 |  |  | true |  |  | 7 | 30 | 3
ubuntu-20.04 |  |  | true |  | true | 13 | 36 | 45
ubuntu-20.04 |  |  | true | true |  | 10 | 33 | 4
ubuntu-20.04 |  |  | true | true | true | 17 | 40 | 56
ubuntu-20.04 |  | true |  |  |  | 9 | 32 | 5
ubuntu-20.04 |  | true |  |  | true | 15 | 38 | 62
ubuntu-20.04 |  | true |  | true |  | 12 | 35 | 6
ubuntu-20.04 |  | true |  | true | true | 19 | 42 | 12
ubuntu-20.04 |  | true | true |  |  | 9 | 32 | 5
ubuntu-20.04 |  | true | true |  | true | 15 | 38 | 15
ubuntu-20.04 |  | true | true | true |  | 12 | 35 | 4
ubuntu-20.04 |  | true | true | true | true | 19 | 42 | 74
ubuntu-20.04 | true |  |  |  |  | 21 | 44 | 91
ubuntu-20.04 | true |  |  |  | true | 27 | 50 | 26
ubuntu-20.04 | true |  |  | true |  | 24 | 47 | 72
ubuntu-20.04 | true |  |  | true | true | 31 | 54 | 127
ubuntu-20.04 | true |  | true |  |  | 21 | 44 | 70
ubuntu-20.04 | true |  | true |  | true | 27 | 50 | 16
ubuntu-20.04 | true |  | true | true |  | 24 | 47 | 58
ubuntu-20.04 | true |  | true | true | true | 31 | 54 | 127
ubuntu-20.04 | true | true |  |  |  | 23 | 46 | 15
ubuntu-20.04 | true | true |  |  | true | 29 | 52 | 55
ubuntu-20.04 | true | true |  | true |  | 26 | 49 | 15
ubuntu-20.04 | true | true |  | true | true | 33 | 56 | 30
ubuntu-20.04 | true | true | true |  |  | 23 | 46 | 87
ubuntu-20.04 | true | true | true |  | true | 29 | 52 | 23
ubuntu-20.04 | true | true | true | true |  | 26 | 49 | 99
ubuntu-20.04 | true | true | true | true | true | 33 | 56 | 120
ubuntu-22.04 |  |  |  |  |  | 7 | 32 | 2
ubuntu-22.04 |  |  |  |  | true | 13 | 38 | 33
ubuntu-22.04 |  |  |  | true |  | 11 | 36 | 2
ubuntu-22.04 |  |  |  | true | true | 16 | 41 | 27
ubuntu-22.04 |  |  | true |  |  | 7 | 32 | 2
ubuntu-22.04 |  |  | true |  | true | 13 | 38 | 11
ubuntu-22.04 |  |  | true | true |  | 11 | 36 | 3
ubuntu-22.04 |  |  | true | true | true | 16 | 41 | 20
ubuntu-22.04 |  | true |  |  |  | 9 | 34 | 5
ubuntu-22.04 |  | true |  |  | true | 15 | 40 | 46
ubuntu-22.04 |  | true |  | true |  | 13 | 38 | 3
ubuntu-22.04 |  | true |  | true | true | 18 | 43 | 28
ubuntu-22.04 |  | true | true |  |  | 9 | 34 | 3
ubuntu-22.04 |  | true | true |  | true | 15 | 40 | 34
ubuntu-22.04 |  | true | true | true |  | 13 | 38 | 3
ubuntu-22.04 |  | true | true | true | true | 18 | 43 | 49
ubuntu-22.04 | true |  |  |  |  | 21 | 46 | 13
ubuntu-22.04 | true |  |  |  | true | 27 | 52 | 30
ubuntu-22.04 | true |  |  | true |  | 25 | 50 | 13
ubuntu-22.04 | true |  |  | true | true | 30 | 55 | 112
ubuntu-22.04 | true |  | true |  |  | 21 | 46 | 65
ubuntu-22.04 | true |  | true |  | true | 27 | 52 | 114
ubuntu-22.04 | true |  | true | true |  | 25 | 50 | 76
ubuntu-22.04 | true |  | true | true | true | 30 | 55 | 32
ubuntu-22.04 | true | true |  |  |  | 23 | 48 | 65
ubuntu-22.04 | true | true |  |  | true | 29 | 54 | 21
ubuntu-22.04 | true | true |  | true |  | 27 | 52 | 11
ubuntu-22.04 | true | true |  | true | true | 32 | 57 | 52
ubuntu-22.04 | true | true | true |  |  | 23 | 48 | 73
ubuntu-22.04 | true | true | true |  | true | 29 | 54 | 20
ubuntu-22.04 | true | true | true | true |  | 27 | 52 | 11
ubuntu-22.04 | true | true | true | true | true | 32 | 57 | 59
