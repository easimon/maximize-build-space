# Maximize available disk space for build tasks

If the available disk space on Github runners is too little for your build job, this action might be for you.
If not: please go on, there's nothing to see here.

This table shows the amount of free space you receive when using the action with the various options.

OS | Android SDKs removed | .NET SDKs removed | Haskell removed | CodeQL Removed | Cached Docker Images Removed | GB freed | GB free | Elapsed Time (seconds) |
---|:--------------------:|:-----------------:|:---------------:|:--------------:|:----------------------------:|:--------:|:-------:|:----------------------:|
ubuntu-20.04 |  |  |  |  |  | 52 | 77 | 9
ubuntu-20.04 |  |  |  |  | true | 57 | 82 | 29
ubuntu-20.04 |  |  |  | true |  | 57 | 82 | 3
ubuntu-20.04 |  |  |  | true | true | 62 | 87 | 22
ubuntu-20.04 |  |  | true |  |  | 52 | 77 | 2
ubuntu-20.04 |  |  | true |  | true | 57 | 82 | 18
ubuntu-20.04 |  |  | true | true |  | 57 | 82 | 3
ubuntu-20.04 |  |  | true | true | true | 62 | 87 | 7
ubuntu-20.04 |  | true |  |  |  | 54 | 79 | 4
ubuntu-20.04 |  | true |  |  | true | 59 | 84 | 23
ubuntu-20.04 |  | true |  | true |  | 58 | 83 | 6
ubuntu-20.04 |  | true |  | true | true | 64 | 89 | 30
ubuntu-20.04 |  | true | true |  |  | 54 | 79 | 3
ubuntu-20.04 |  | true | true |  | true | 59 | 84 | 38
ubuntu-20.04 |  | true | true | true |  | 58 | 83 | 3
ubuntu-20.04 |  | true | true | true | true | 64 | 89 | 21
ubuntu-20.04 | true |  |  |  |  | 64 | 89 | 9
ubuntu-20.04 | true |  |  |  | true | 69 | 94 | 91
ubuntu-20.04 | true |  |  | true |  | 69 | 94 | 71
ubuntu-20.04 | true |  |  | true | true | 74 | 99 | 103
ubuntu-20.04 | true |  | true |  |  | 64 | 89 | 107
ubuntu-20.04 | true |  | true |  | true | 69 | 94 | 86
ubuntu-20.04 | true |  | true | true |  | 69 | 94 | 12
ubuntu-20.04 | true |  | true | true | true | 74 | 99 | 84
ubuntu-20.04 | true | true |  |  |  | 65 | 90 | 10
ubuntu-20.04 | true | true |  |  | true | 71 | 96 | 74
ubuntu-20.04 | true | true |  | true |  | 70 | 95 | 82
ubuntu-20.04 | true | true |  | true | true | 75 | 100 | 116
ubuntu-20.04 | true | true | true |  |  | 65 | 90 | 55
ubuntu-20.04 | true | true | true |  | true | 71 | 96 | 27
ubuntu-20.04 | true | true | true | true |  | 70 | 95 | 68
ubuntu-20.04 | true | true | true | true | true | 75 | 100 | 98
ubuntu-22.04 |  |  |  |  |  | 52 | 78 | 1
ubuntu-22.04 |  |  |  |  | true | 57 | 83 | 19
ubuntu-22.04 |  |  |  | true |  | 57 | 83 | 4
ubuntu-22.04 |  |  |  | true | true | 62 | 88 | 15
ubuntu-22.04 |  |  | true |  |  | 52 | 78 | 2
ubuntu-22.04 |  |  | true |  | true | 57 | 83 | 21
ubuntu-22.04 |  |  | true | true |  | 57 | 83 | 3
ubuntu-22.04 |  |  | true | true | true | 62 | 88 | 8
ubuntu-22.04 |  | true |  |  |  | 54 | 80 | 4
ubuntu-22.04 |  | true |  |  | true | 58 | 84 | 8
ubuntu-22.04 |  | true |  | true |  | 59 | 85 | 6
ubuntu-22.04 |  | true |  | true | true | 63 | 89 | 10
ubuntu-22.04 |  | true | true |  |  | 54 | 80 | 4
ubuntu-22.04 |  | true | true |  | true | 58 | 84 | 9
ubuntu-22.04 |  | true | true | true |  | 59 | 85 | 5
ubuntu-22.04 |  | true | true | true | true | 63 | 89 | 21
ubuntu-22.04 | true |  |  |  |  | 64 | 90 | 74
ubuntu-22.04 | true |  |  |  | true | 69 | 95 | 87
ubuntu-22.04 | true |  |  | true |  | 69 | 95 | 61
ubuntu-22.04 | true |  |  | true | true | 73 | 99 | 23
ubuntu-22.04 | true |  | true |  |  | 64 | 90 | 13
ubuntu-22.04 | true |  | true |  | true | 69 | 95 | 17
ubuntu-22.04 | true |  | true | true |  | 69 | 95 | 11
ubuntu-22.04 | true |  | true | true | true | 73 | 99 | 59
ubuntu-22.04 | true | true |  |  |  | 66 | 92 | 59
ubuntu-22.04 | true | true |  |  | true | 70 | 96 | 17
ubuntu-22.04 | true | true |  | true |  | 70 | 96 | 73
ubuntu-22.04 | true | true |  | true | true | 75 | 101 | 76
ubuntu-22.04 | true | true | true |  |  | 66 | 92 | 14
ubuntu-22.04 | true | true | true |  | true | 70 | 96 | 19
ubuntu-22.04 | true | true | true | true |  | 70 | 96 | 15
ubuntu-22.04 | true | true | true | true | true | 75 | 101 | 101
