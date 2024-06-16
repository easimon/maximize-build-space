# Maximize available disk space for build tasks

If the available disk space on Github runners is too little for your build job, this action might be for you.
If not: please go on, there's nothing to see here.

This table shows the amount of free space you receive when using the action with the various options.

OS | Android SDKs removed | .NET SDKs removed | Haskell removed | CodeQL Removed | Cached Docker Images Removed | GB freed | GB free | Elapsed Time (seconds) |
---|:--------------------:|:-----------------:|:---------------:|:--------------:|:----------------------------:|:--------:|:-------:|:----------------------:|
ubuntu-20.04 |  |  |  |  |  | 63 | 83 | 7
ubuntu-20.04 |  |  |  |  | true | 66 | 86 | 82
ubuntu-20.04 |  |  |  | true |  | 67 | 87 | 3
ubuntu-20.04 |  |  |  | true | true | 71 | 91 | 35
ubuntu-20.04 |  |  | true |  |  | 63 | 83 | 2
ubuntu-20.04 |  |  | true |  | true | 66 | 86 | 7
ubuntu-20.04 |  |  | true | true |  | 67 | 87 | 2
ubuntu-20.04 |  |  | true | true | true | 71 | 91 | 48
ubuntu-20.04 |  | true |  |  |  | 64 | 84 | 2
ubuntu-20.04 |  | true |  |  | true | 67 | 87 | 6
ubuntu-20.04 |  | true |  | true |  | 69 | 89 | 4
ubuntu-20.04 |  | true |  | true | true | 72 | 92 | 74
ubuntu-20.04 |  | true | true |  |  | 64 | 84 | 3
ubuntu-20.04 |  | true | true |  | true | 67 | 87 | 56
ubuntu-20.04 |  | true | true | true |  | 69 | 89 | 4
ubuntu-20.04 |  | true | true | true | true | 72 | 92 | 73
ubuntu-20.04 | true |  |  |  |  | 71 | 91 | 48
ubuntu-20.04 | true |  |  |  | true | 74 | 94 | 12
ubuntu-20.04 | true |  |  | true |  | 76 | 96 | 9
ubuntu-20.04 | true |  |  | true | true | 79 | 99 | 81
ubuntu-20.04 | true |  | true |  |  | 71 | 91 | 9
ubuntu-20.04 | true |  | true |  | true | 74 | 94 | 96
ubuntu-20.04 | true |  | true | true |  | 76 | 96 | 56
ubuntu-20.04 | true |  | true | true | true | 79 | 99 | 98
ubuntu-20.04 | true | true |  |  |  | 73 | 93 | 95
ubuntu-20.04 | true | true |  |  | true | 76 | 96 | 136
ubuntu-20.04 | true | true |  | true |  | 78 | 98 | 10
ubuntu-20.04 | true | true |  | true | true | 81 | 101 | 99
ubuntu-20.04 | true | true | true |  |  | 73 | 93 | 13
ubuntu-20.04 | true | true | true |  | true | 76 | 96 | 13
ubuntu-20.04 | true | true | true | true |  | 78 | 98 | 41
ubuntu-20.04 | true | true | true | true | true | 81 | 101 | 103
ubuntu-22.04 |  |  |  |  |  | 63 | 84 | 2
ubuntu-22.04 |  |  |  |  | true | 66 | 87 | 6
ubuntu-22.04 |  |  |  | true |  | 68 | 89 | 4
ubuntu-22.04 |  |  |  | true | true | 71 | 92 | 33
ubuntu-22.04 |  |  | true |  |  | 63 | 84 | 2
ubuntu-22.04 |  |  | true |  | true | 66 | 87 | 8
ubuntu-22.04 |  |  | true | true |  | 68 | 89 | 4
ubuntu-22.04 |  |  | true | true | true | 71 | 92 | 24
ubuntu-22.04 |  | true |  |  |  | 64 | 85 | 3
ubuntu-22.04 |  | true |  |  | true | 67 | 88 | 7
ubuntu-22.04 |  | true |  | true |  | 69 | 90 | 5
ubuntu-22.04 |  | true |  | true | true | 72 | 93 | 9
ubuntu-22.04 |  | true | true |  |  | 64 | 85 | 5
ubuntu-22.04 |  | true | true |  | true | 67 | 88 | 19
ubuntu-22.04 |  | true | true | true |  | 69 | 90 | 6
ubuntu-22.04 |  | true | true | true | true | 72 | 93 | 37
ubuntu-22.04 | true |  |  |  |  | 72 | 93 | 53
ubuntu-22.04 | true |  |  |  | true | 75 | 96 | 15
ubuntu-22.04 | true |  |  | true |  | 76 | 97 | 13
ubuntu-22.04 | true |  |  | true | true | 80 | 101 | 17
ubuntu-22.04 | true |  | true |  |  | 72 | 93 | 41
ubuntu-22.04 | true |  | true |  | true | 75 | 96 | 18
ubuntu-22.04 | true |  | true | true |  | 76 | 97 | 13
ubuntu-22.04 | true |  | true | true | true | 80 | 101 | 15
ubuntu-22.04 | true | true |  |  |  | 73 | 94 | 57
ubuntu-22.04 | true | true |  |  | true | 76 | 97 | 19
ubuntu-22.04 | true | true |  | true |  | 78 | 99 | 59
ubuntu-22.04 | true | true |  | true | true | 81 | 102 | 15
ubuntu-22.04 | true | true | true |  |  | 73 | 94 | 59
ubuntu-22.04 | true | true | true |  | true | 76 | 97 | 25
ubuntu-22.04 | true | true | true | true |  | 78 | 99 | 66
ubuntu-22.04 | true | true | true | true | true | 81 | 102 | 29
