# Maximize available disk space for build tasks

If the available disk space on Github runners is too little for your build job, this action might be for you.
If not: please go on, there's nothing to see here.

This table shows the amount of free space you receive when using the action with the various options.

OS | Android SDKs removed | .NET SDKs removed | Haskell removed | CodeQL Removed | Cached Docker Images Removed | GB freed | GB free | Elapsed Time (seconds) |
---|:--------------------:|:-----------------:|:---------------:|:--------------:|:----------------------------:|:--------:|:-------:|:----------------------:|
ubuntu-20.04 |  |  |  |  |  | 63 | 84 | 2
ubuntu-20.04 |  |  |  |  | true | 66 | 87 | 20
ubuntu-20.04 |  |  |  | true |  | 67 | 88 | 4
ubuntu-20.04 |  |  |  | true | true | 71 | 92 | 21
ubuntu-20.04 |  |  | true |  |  | 63 | 84 | 2
ubuntu-20.04 |  |  | true |  | true | 66 | 87 | 19
ubuntu-20.04 |  |  | true | true |  | 67 | 88 | 4
ubuntu-20.04 |  |  | true | true | true | 71 | 92 | 7
ubuntu-20.04 |  | true |  |  |  | 64 | 85 | 4
ubuntu-20.04 |  | true |  |  | true | 67 | 88 | 10
ubuntu-20.04 |  | true |  | true |  | 69 | 90 | 5
ubuntu-20.04 |  | true |  | true | true | 72 | 93 | 21
ubuntu-20.04 |  | true | true |  |  | 64 | 85 | 5
ubuntu-20.04 |  | true | true |  | true | 67 | 88 | 16
ubuntu-20.04 |  | true | true | true |  | 69 | 90 | 5
ubuntu-20.04 |  | true | true | true | true | 72 | 93 | 10
ubuntu-20.04 | true |  |  |  |  | 70 | 91 | 91
ubuntu-20.04 | true |  |  |  | true | 73 | 94 | 24
ubuntu-20.04 | true |  |  | true |  | 75 | 96 | 14
ubuntu-20.04 | true |  |  | true | true | 78 | 99 | 31
ubuntu-20.04 | true |  | true |  |  | 70 | 91 | 12
ubuntu-20.04 | true |  | true |  | true | 73 | 94 | 23
ubuntu-20.04 | true |  | true | true |  | 75 | 96 | 100
ubuntu-20.04 | true |  | true | true | true | 78 | 99 | 105
ubuntu-20.04 | true | true |  |  |  | 72 | 93 | 20
ubuntu-20.04 | true | true |  |  | true | 75 | 96 | 90
ubuntu-20.04 | true | true |  | true |  | 76 | 97 | 81
ubuntu-20.04 | true | true |  | true | true | 80 | 101 | 26
ubuntu-20.04 | true | true | true |  |  | 72 | 93 | 77
ubuntu-20.04 | true | true | true |  | true | 75 | 96 | 23
ubuntu-20.04 | true | true | true | true |  | 76 | 97 | 99
ubuntu-20.04 | true | true | true | true | true | 80 | 101 | 76
ubuntu-22.04 |  |  |  |  |  | 63 | 85 | 2
ubuntu-22.04 |  |  |  |  | true | 66 | 88 | 8
ubuntu-22.04 |  |  |  | true |  | 68 | 90 | 4
ubuntu-22.04 |  |  |  | true | true | 71 | 93 | 8
ubuntu-22.04 |  |  | true |  |  | 63 | 85 | 1
ubuntu-22.04 |  |  | true |  | true | 66 | 88 | 7
ubuntu-22.04 |  |  | true | true |  | 68 | 90 | 3
ubuntu-22.04 |  |  | true | true | true | 71 | 93 | 9
ubuntu-22.04 |  | true |  |  |  | 64 | 86 | 3
ubuntu-22.04 |  | true |  |  | true | 67 | 89 | 7
ubuntu-22.04 |  | true |  | true |  | 69 | 91 | 5
ubuntu-22.04 |  | true |  | true | true | 72 | 94 | 8
ubuntu-22.04 |  | true | true |  |  | 64 | 86 | 4
ubuntu-22.04 |  | true | true |  | true | 67 | 89 | 6
ubuntu-22.04 |  | true | true | true |  | 69 | 91 | 4
ubuntu-22.04 |  | true | true | true | true | 72 | 94 | 8
ubuntu-22.04 | true |  |  |  |  | 70 | 92 | 18
ubuntu-22.04 | true |  |  |  | true | 73 | 95 | 16
ubuntu-22.04 | true |  |  | true |  | 75 | 97 | 84
ubuntu-22.04 | true |  |  | true | true | 78 | 100 | 21
ubuntu-22.04 | true |  | true |  |  | 70 | 92 | 11
ubuntu-22.04 | true |  | true |  | true | 73 | 95 | 100
ubuntu-22.04 | true |  | true | true |  | 75 | 97 | 13
ubuntu-22.04 | true |  | true | true | true | 78 | 100 | 24
ubuntu-22.04 | true | true |  |  |  | 72 | 94 | 66
ubuntu-22.04 | true | true |  |  | true | 75 | 97 | 16
ubuntu-22.04 | true | true |  | true |  | 77 | 99 | 87
ubuntu-22.04 | true | true |  | true | true | 80 | 102 | 18
ubuntu-22.04 | true | true | true |  |  | 72 | 94 | 74
ubuntu-22.04 | true | true | true |  | true | 75 | 97 | 72
ubuntu-22.04 | true | true | true | true |  | 77 | 99 | 79
ubuntu-22.04 | true | true | true | true | true | 80 | 102 | 19
