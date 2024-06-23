# Maximize available disk space for build tasks

If the available disk space on Github runners is too little for your build job, this action might be for you.
If not: please go on, there's nothing to see here.

This table shows the amount of free space you receive when using the action with the various options.

OS | Android SDKs removed | .NET SDKs removed | Haskell removed | CodeQL Removed | Cached Docker Images Removed | GB freed | GB free | Elapsed Time (seconds) |
---|:--------------------:|:-----------------:|:---------------:|:--------------:|:----------------------------:|:--------:|:-------:|:----------------------:|
ubuntu-20.04 |  |  |  |  |  | 63 | 83 | 2
ubuntu-20.04 |  |  |  |  | true | 66 | 86 | 44
ubuntu-20.04 |  |  |  | true |  | 67 | 87 | 2
ubuntu-20.04 |  |  |  | true | true | 71 | 91 | 21
ubuntu-20.04 |  |  | true |  |  | 63 | 83 | 1
ubuntu-20.04 |  |  | true |  | true | 66 | 86 | 40
ubuntu-20.04 |  |  | true | true |  | 67 | 87 | 3
ubuntu-20.04 |  |  | true | true | true | 71 | 91 | 24
ubuntu-20.04 |  | true |  |  |  | 64 | 84 | 6
ubuntu-20.04 |  | true |  |  | true | 67 | 87 | 37
ubuntu-20.04 |  | true |  | true |  | 69 | 89 | 3
ubuntu-20.04 |  | true |  | true | true | 72 | 92 | 36
ubuntu-20.04 |  | true | true |  |  | 64 | 84 | 3
ubuntu-20.04 |  | true | true |  | true | 67 | 87 | 6
ubuntu-20.04 |  | true | true | true |  | 69 | 89 | 4
ubuntu-20.04 |  | true | true | true | true | 72 | 92 | 28
ubuntu-20.04 | true |  |  |  |  | 71 | 91 | 12
ubuntu-20.04 | true |  |  |  | true | 74 | 94 | 89
ubuntu-20.04 | true |  |  | true |  | 76 | 96 | 13
ubuntu-20.04 | true |  |  | true | true | 79 | 99 | 11
ubuntu-20.04 | true |  | true |  |  | 71 | 91 | 8
ubuntu-20.04 | true |  | true |  | true | 74 | 94 | 28
ubuntu-20.04 | true |  | true | true |  | 76 | 96 | 11
ubuntu-20.04 | true |  | true | true | true | 79 | 99 | 97
ubuntu-20.04 | true | true |  |  |  | 73 | 93 | 10
ubuntu-20.04 | true | true |  |  | true | 76 | 96 | 119
ubuntu-20.04 | true | true |  | true |  | 78 | 98 | 8
ubuntu-20.04 | true | true |  | true | true | 81 | 101 | 35
ubuntu-20.04 | true | true | true |  |  | 73 | 93 | 8
ubuntu-20.04 | true | true | true |  | true | 76 | 96 | 48
ubuntu-20.04 | true | true | true | true |  | 78 | 98 | 49
ubuntu-20.04 | true | true | true | true | true | 81 | 101 | 152
ubuntu-22.04 |  |  |  |  |  | 63 | 84 | 2
ubuntu-22.04 |  |  |  |  | true | 66 | 87 | 93
ubuntu-22.04 |  |  |  | true |  | 68 | 89 | 4
ubuntu-22.04 |  |  |  | true | true | 71 | 92 | 7
ubuntu-22.04 |  |  | true |  |  | 63 | 84 | 2
ubuntu-22.04 |  |  | true |  | true | 66 | 87 | 10
ubuntu-22.04 |  |  | true | true |  | 68 | 89 | 3
ubuntu-22.04 |  |  | true | true | true | 71 | 92 | 8
ubuntu-22.04 |  | true |  |  |  | 64 | 85 | 4
ubuntu-22.04 |  | true |  |  | true | 67 | 88 | 25
ubuntu-22.04 |  | true |  | true |  | 69 | 90 | 6
ubuntu-22.04 |  | true |  | true | true | 72 | 93 | 28
ubuntu-22.04 |  | true | true |  |  | 64 | 85 | 3
ubuntu-22.04 |  | true | true |  | true | 67 | 88 | 7
ubuntu-22.04 |  | true | true | true |  | 69 | 90 | 5
ubuntu-22.04 |  | true | true | true | true | 72 | 93 | 26
ubuntu-22.04 | true |  |  |  |  | 71 | 92 | 46
ubuntu-22.04 | true |  |  |  | true | 75 | 96 | 19
ubuntu-22.04 | true |  |  | true |  | 76 | 97 | 10
ubuntu-22.04 | true |  |  | true | true | 80 | 101 | 347
ubuntu-22.04 | true |  | true |  |  | 71 | 92 | 55
ubuntu-22.04 | true |  | true |  | true | 75 | 96 | 87
ubuntu-22.04 | true |  | true | true |  | 76 | 97 | 53
ubuntu-22.04 | true |  | true | true | true | 80 | 101 | 71
ubuntu-22.04 | true | true |  |  |  | 73 | 94 | 11
ubuntu-22.04 | true | true |  |  | true | 76 | 97 | 81
ubuntu-22.04 | true | true |  | true |  | 78 | 99 | 14
ubuntu-22.04 | true | true |  | true | true | 81 | 102 | 98
ubuntu-22.04 | true | true | true |  |  | 73 | 94 | 11
ubuntu-22.04 | true | true | true |  | true | 76 | 97 | 15
ubuntu-22.04 | true | true | true | true |  | 78 | 99 | 49
ubuntu-22.04 | true | true | true | true | true | 81 | 102 | 75
