# Maximize available disk space for build tasks

If the available disk space on Github runners is too little for your build job, this action might be for you.
If not: please go on, there's nothing to see here.

This table shows the amount of free space you receive when using the action with the various options.

OS | Android SDKs removed | .NET SDKs removed | Haskell removed | CodeQL Removed | Cached Docker Images Removed | GB freed | GB free | Elapsed Time (seconds) |
---|:--------------------:|:-----------------:|:---------------:|:--------------:|:----------------------------:|:--------:|:-------:|:----------------------:|
ubuntu-20.04 |  |  |  |  |  | 7 | 24 | 3
ubuntu-20.04 |  |  |  |  | true | 14 | 31 | 43
ubuntu-20.04 |  |  |  | true |  | 15 | 32 | 4
ubuntu-20.04 |  |  |  | true | true | 22 | 39 | 19
ubuntu-20.04 |  |  | true |  |  | 7 | 24 | 2
ubuntu-20.04 |  |  | true |  | true | 14 | 31 | 36
ubuntu-20.04 |  |  | true | true |  | 15 | 32 | 3
ubuntu-20.04 |  |  | true | true | true | 22 | 39 | 36
ubuntu-20.04 |  | true |  |  |  | 10 | 27 | 3
ubuntu-20.04 |  | true |  |  | true | 16 | 33 | 44
ubuntu-20.04 |  | true |  | true |  | 18 | 35 | 6
ubuntu-20.04 |  | true |  | true | true | 24 | 41 | 45
ubuntu-20.04 |  | true | true |  |  | 10 | 27 | 6
ubuntu-20.04 |  | true | true |  | true | 16 | 33 | 51
ubuntu-20.04 |  | true | true | true |  | 18 | 35 | 9
ubuntu-20.04 |  | true | true | true | true | 24 | 41 | 58
ubuntu-20.04 | true |  |  |  |  | 21 | 38 | 12
ubuntu-20.04 | true |  |  |  | true | 27 | 44 | 50
ubuntu-20.04 | true |  |  | true |  | 29 | 46 | 67
ubuntu-20.04 | true |  |  | true | true | 36 | 53 | 153
ubuntu-20.04 | true |  | true |  |  | 21 | 38 | 66
ubuntu-20.04 | true |  | true |  | true | 27 | 44 | 129
ubuntu-20.04 | true |  | true | true |  | 29 | 46 | 71
ubuntu-20.04 | true |  | true | true | true | 36 | 53 | 127
ubuntu-20.04 | true | true |  |  |  | 23 | 40 | 65
ubuntu-20.04 | true | true |  |  | true | 29 | 46 | 126
ubuntu-20.04 | true | true |  | true |  | 31 | 48 | 65
ubuntu-20.04 | true | true |  | true | true | 38 | 55 | 59
ubuntu-20.04 | true | true | true |  |  | 23 | 40 | 63
ubuntu-20.04 | true | true | true |  | true | 29 | 46 | 134
ubuntu-20.04 | true | true | true | true |  | 31 | 48 | 17
ubuntu-20.04 | true | true | true | true | true | 38 | 55 | 109
ubuntu-22.04 |  |  |  |  |  | 7 | 27 | 1
ubuntu-22.04 |  |  |  |  | true | 13 | 32 | 41
ubuntu-22.04 |  |  |  | true |  | 15 | 35 | 3
ubuntu-22.04 |  |  |  | true | true | 20 | 40 | 21
ubuntu-22.04 |  |  | true |  |  | 7 | 27 | 2
ubuntu-22.04 |  |  | true |  | true | 12 | 32 | 35
ubuntu-22.04 |  |  | true | true |  | 15 | 35 | 4
ubuntu-22.04 |  |  | true | true | true | 21 | 40 | 37
ubuntu-22.04 |  | true |  |  |  | 10 | 29 | 4
ubuntu-22.04 |  | true |  |  | true | 15 | 34 | 13
ubuntu-22.04 |  | true |  | true |  | 17 | 37 | 11
ubuntu-22.04 |  | true |  | true | true | 23 | 43 | 10
ubuntu-22.04 |  | true | true |  |  | 9 | 29 | 7
ubuntu-22.04 |  | true | true |  | true | 14 | 34 | 37
ubuntu-22.04 |  | true | true | true |  | 17 | 37 | 6
ubuntu-22.04 |  | true | true | true | true | 23 | 43 | 52
ubuntu-22.04 | true |  |  |  |  | 21 | 41 | 11
ubuntu-22.04 | true |  |  |  | true | 26 | 46 | 31
ubuntu-22.04 | true |  |  | true |  | 29 | 49 | 64
ubuntu-22.04 | true |  |  | true | true | 34 | 54 | 27
ubuntu-22.04 | true |  | true |  |  | 21 | 41 | 67
ubuntu-22.04 | true |  | true |  | true | 26 | 46 | 88
ubuntu-22.04 | true |  | true | true |  | 29 | 49 | 74
ubuntu-22.04 | true |  | true | true | true | 34 | 54 | 17
ubuntu-22.04 | true | true |  |  |  | 23 | 43 | 10
ubuntu-22.04 | true | true |  |  | true | 28 | 48 | 22
ubuntu-22.04 | true | true |  | true |  | 31 | 51 | 75
ubuntu-22.04 | true | true |  | true | true | 36 | 56 | 140
ubuntu-22.04 | true | true | true |  |  | 23 | 43 | 67
ubuntu-22.04 | true | true | true |  | true | 28 | 48 | 18
ubuntu-22.04 | true | true | true | true |  | 31 | 51 | 11
ubuntu-22.04 | true | true | true | true | true | 36 | 56 | 110
