# Maximize available disk space for build tasks

If the available disk space on Github runners is too little for your build job, this action might be for you.
If not: please go on, there's nothing to see here.

This table shows the amount of free space you receive when using the action with the various options.

OS | Android SDKs removed | .NET SDKs removed | Haskell removed | CodeQL Removed | Cached Docker Images Removed | GB freed | GB free | Elapsed Time (seconds) |
---|:--------------------:|:-----------------:|:---------------:|:--------------:|:----------------------------:|:--------:|:-------:|:----------------------:|
ubuntu-20.04 |  |  |  |  |  | 53 | 75 | 2
ubuntu-20.04 |  |  |  |  | true | 59 | 81 | 9
ubuntu-20.04 |  |  |  | true |  | 56 | 78 | 2
ubuntu-20.04 |  |  |  | true | true | 63 | 85 | 8
ubuntu-20.04 |  |  | true |  |  | 7 | 29 | 2
ubuntu-20.04 |  |  | true |  | true | 59 | 81 | 7
ubuntu-20.04 |  |  | true | true |  | 11 | 33 | 3
ubuntu-20.04 |  |  | true | true | true | 17 | 39 | 38
ubuntu-20.04 |  | true |  |  |  | 55 | 77 | 2
ubuntu-20.04 |  | true |  |  | true | 61 | 83 | 11
ubuntu-20.04 |  | true |  | true |  | 58 | 80 | 4
ubuntu-20.04 |  | true |  | true | true | 19 | 41 | 16
ubuntu-20.04 |  | true | true |  |  | 9 | 31 | 4
ubuntu-20.04 |  | true | true |  | true | 16 | 38 | 14
ubuntu-20.04 |  | true | true | true |  | 13 | 35 | 4
ubuntu-20.04 |  | true | true | true | true | 19 | 41 | 52
ubuntu-20.04 | true |  |  |  |  | 21 | 43 | 59
ubuntu-20.04 | true |  |  |  | true | 73 | 95 | 82
ubuntu-20.04 | true |  |  | true |  | 25 | 47 | 14
ubuntu-20.04 | true |  |  | true | true | 77 | 99 | 19
ubuntu-20.04 | true |  | true |  |  | 21 | 43 | 15
ubuntu-20.04 | true |  | true |  | true | 28 | 50 | 89
ubuntu-20.04 | true |  | true | true |  | 70 | 92 | 10
ubuntu-20.04 | true |  | true | true | true | 77 | 99 | 19
ubuntu-20.04 | true | true |  |  |  | 69 | 91 | 55
ubuntu-20.04 | true | true |  |  | true | 30 | 52 | 92
ubuntu-20.04 | true | true |  | true |  | 27 | 49 | 66
ubuntu-20.04 | true | true |  | true | true | 33 | 55 | 18
ubuntu-20.04 | true | true | true |  |  | 23 | 45 | 64
ubuntu-20.04 | true | true | true |  | true | 75 | 97 | 17
ubuntu-20.04 | true | true | true | true |  | 27 | 49 | 65
ubuntu-20.04 | true | true | true | true | true | 79 | 101 | 19
ubuntu-22.04 |  |  |  |  |  | 7 | 31 | 2
ubuntu-22.04 |  |  |  |  | true | 12 | 36 | 41
ubuntu-22.04 |  |  |  | true |  | 10 | 34 | 4
ubuntu-22.04 |  |  |  | true | true | 61 | 85 | 40
ubuntu-22.04 |  |  | true |  |  | 7 | 31 | 2
ubuntu-22.04 |  |  | true |  | true | 58 | 82 | 11
ubuntu-22.04 |  |  | true | true |  | 56 | 80 | 3
ubuntu-22.04 |  |  | true | true | true | 61 | 85 | 31
ubuntu-22.04 |  | true |  |  |  | 9 | 33 | 6
ubuntu-22.04 |  | true |  |  | true | 14 | 38 | 40
ubuntu-22.04 |  | true |  | true |  | 58 | 82 | 4
ubuntu-22.04 |  | true |  | true | true | 64 | 88 | 15
ubuntu-22.04 |  | true | true |  |  | 54 | 78 | 6
ubuntu-22.04 |  | true | true |  | true | 60 | 84 | 14
ubuntu-22.04 |  | true | true | true |  | 58 | 82 | 3
ubuntu-22.04 |  | true | true | true | true | 64 | 88 | 75
ubuntu-22.04 | true |  |  |  |  | 66 | 90 | 55
ubuntu-22.04 | true |  |  |  | true | 72 | 96 | 96
ubuntu-22.04 | true |  |  | true |  | 70 | 94 | 50
ubuntu-22.04 | true |  |  | true | true | 30 | 54 | 95
ubuntu-22.04 | true |  | true |  |  | 21 | 45 | 14
ubuntu-22.04 | true |  | true |  | true | 72 | 96 | 45
ubuntu-22.04 | true |  | true | true |  | 70 | 94 | 13
ubuntu-22.04 | true |  | true | true | true | 30 | 54 | 17
ubuntu-22.04 | true | true |  |  |  | 23 | 47 | 54
ubuntu-22.04 | true | true |  |  | true | 28 | 52 | 86
ubuntu-22.04 | true | true |  | true |  | 72 | 96 | 58
ubuntu-22.04 | true | true |  | true | true | 78 | 102 | 86
ubuntu-22.04 | true | true | true |  |  | 68 | 92 | 63
ubuntu-22.04 | true | true | true |  | true | 74 | 98 | 44
ubuntu-22.04 | true | true | true | true |  | 26 | 50 | 67
ubuntu-22.04 | true | true | true | true | true | 78 | 102 | 23
