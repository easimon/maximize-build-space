# Maximize available disk space for build tasks

If the available disk space on Github runners is too little for your build job, this action might be for you.
If not: please go on, there's nothing to see here.

This table shows the amount of free space you receive when using the action with the various options.

OS | Android SDKs removed | .NET SDKs removed | Haskell removed | CodeQL Removed | Cached Docker Images Removed | GB freed | GB free | Elapsed Time (seconds) |
---|:--------------------:|:-----------------:|:---------------:|:--------------:|:----------------------------:|:--------:|:-------:|:----------------------:|
ubuntu-20.04 |  |  |  |  |  | 8 | 27 | 3
ubuntu-20.04 |  |  |  |  | true | 13 | 32 | 13
ubuntu-20.04 |  |  |  | true |  | 16 | 35 | 4
ubuntu-20.04 |  |  |  | true | true | 22 | 41 | 35
ubuntu-20.04 |  |  | true |  |  | 7 | 26 | 2
ubuntu-20.04 |  |  | true |  | true | 13 | 32 | 35
ubuntu-20.04 |  |  | true | true |  | 16 | 35 | 4
ubuntu-20.04 |  |  | true | true | true | 22 | 41 | 10
ubuntu-20.04 |  | true |  |  |  | 9 | 28 | 6
ubuntu-20.04 |  | true |  |  | true | 15 | 34 | 32
ubuntu-20.04 |  | true |  | true |  | 17 | 36 | 8
ubuntu-20.04 |  | true |  | true | true | 24 | 43 | 29
ubuntu-20.04 |  | true | true |  |  | 9 | 28 | 5
ubuntu-20.04 |  | true | true |  | true | 15 | 34 | 34
ubuntu-20.04 |  | true | true | true |  | 17 | 36 | 9
ubuntu-20.04 |  | true | true | true | true | 24 | 43 | 36
ubuntu-20.04 | true |  |  |  |  | 19 | 38 | 15
ubuntu-20.04 | true |  |  |  | true | 26 | 45 | 104
ubuntu-20.04 | true |  |  | true |  | 27 | 46 | 11
ubuntu-20.04 | true |  |  | true | true | 33 | 52 | 49
ubuntu-20.04 | true |  | true |  |  | 19 | 38 | 56
ubuntu-20.04 | true |  | true |  | true | 26 | 45 | 86
ubuntu-20.04 | true |  | true | true |  | 27 | 46 | 12
ubuntu-20.04 | true |  | true | true | true | 34 | 53 | 36
ubuntu-20.04 | true | true |  |  |  | 21 | 40 | 9
ubuntu-20.04 | true | true |  |  | true | 27 | 46 | 40
ubuntu-20.04 | true | true |  | true |  | 29 | 48 | 11
ubuntu-20.04 | true | true |  | true | true | 35 | 54 | 212
ubuntu-20.04 | true | true | true |  |  | 21 | 40 | 71
ubuntu-20.04 | true | true | true |  | true | 27 | 46 | 109
ubuntu-20.04 | true | true | true | true |  | 29 | 48 | 30
ubuntu-20.04 | true | true | true | true | true | 35 | 54 | 98
ubuntu-22.04 |  |  |  |  |  | 7 | 29 | 2
ubuntu-22.04 |  |  |  |  | true | 12 | 34 | 23
ubuntu-22.04 |  |  |  | true |  | 15 | 37 | 3
ubuntu-22.04 |  |  |  | true | true | 21 | 43 | 32
ubuntu-22.04 |  |  | true |  |  | 7 | 29 | 2
ubuntu-22.04 |  |  | true |  | true | 12 | 34 | 25
ubuntu-22.04 |  |  | true | true |  | 15 | 37 | 3
ubuntu-22.04 |  |  | true | true | true | 21 | 43 | 21
ubuntu-22.04 |  | true |  |  |  | 9 | 31 | 4
ubuntu-22.04 |  | true |  |  | true | 14 | 36 | 30
ubuntu-22.04 |  | true |  | true |  | 16 | 38 | 4
ubuntu-22.04 |  | true |  | true | true | 22 | 44 | 25
ubuntu-22.04 |  | true | true |  |  | 9 | 31 | 4
ubuntu-22.04 |  | true | true |  | true | 14 | 36 | 29
ubuntu-22.04 |  | true | true | true |  | 16 | 38 | 4
ubuntu-22.04 |  | true | true | true | true | 22 | 44 | 32
ubuntu-22.04 | true |  |  |  |  | 19 | 41 | 19
ubuntu-22.04 | true |  |  |  | true | 24 | 46 | 88
ubuntu-22.04 | true |  |  | true |  | 27 | 49 | 15
ubuntu-22.04 | true |  |  | true | true | 32 | 54 | 75
ubuntu-22.04 | true |  | true |  |  | 19 | 41 | 91
ubuntu-22.04 | true |  | true |  | true | 24 | 46 | 78
ubuntu-22.04 | true |  | true | true |  | 27 | 49 | 86
ubuntu-22.04 | true |  | true | true | true | 32 | 54 | 24
ubuntu-22.04 | true | true |  |  |  | 21 | 43 | 10
ubuntu-22.04 | true | true |  |  | true | 26 | 48 | 28
ubuntu-22.04 | true | true |  | true |  | 29 | 51 | 12
ubuntu-22.04 | true | true |  | true | true | 34 | 56 | 82
ubuntu-22.04 | true | true | true |  |  | 21 | 43 | 117
ubuntu-22.04 | true | true | true |  | true | 26 | 48 | 25
ubuntu-22.04 | true | true | true | true |  | 29 | 51 | 20
ubuntu-22.04 | true | true | true | true | true | 34 | 56 | 95
