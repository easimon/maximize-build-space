# Maximize available disk space for build tasks

If the available disk space on Github runners is too little for your build job, this action might be for you.
If not: please go on, there's nothing to see here.

This table shows the amount of free space you receive when using the action with the various options.

OS | Android SDKs removed | .NET SDKs removed | Haskell removed | CodeQL Removed | Cached Docker Images Removed | GB freed | GB free | Elapsed Time (seconds) |
---|:--------------------:|:-----------------:|:---------------:|:--------------:|:----------------------------:|:--------:|:-------:|:----------------------:|
ubuntu-20.04 |  |  |  |  |  | 62 | 82 | 2
ubuntu-20.04 |  |  |  |  | true | 65 | 85 | 71
ubuntu-20.04 |  |  |  | true |  | 67 | 87 | 4
ubuntu-20.04 |  |  |  | true | true | 70 | 90 | 65
ubuntu-20.04 |  |  | true |  |  | 62 | 82 | 2
ubuntu-20.04 |  |  | true |  | true | 65 | 85 | 6
ubuntu-20.04 |  |  | true | true |  | 67 | 87 | 4
ubuntu-20.04 |  |  | true | true | true | 70 | 90 | 10
ubuntu-20.04 |  | true |  |  |  | 64 | 84 | 4
ubuntu-20.04 |  | true |  |  | true | 67 | 87 | 61
ubuntu-20.04 |  | true |  | true |  | 69 | 89 | 5
ubuntu-20.04 |  | true |  | true | true | 72 | 92 | 35
ubuntu-20.04 |  | true | true |  |  | 64 | 84 | 3
ubuntu-20.04 |  | true | true |  | true | 67 | 87 | 76
ubuntu-20.04 |  | true | true | true |  | 69 | 89 | 5
ubuntu-20.04 |  | true | true | true | true | 72 | 92 | 67
ubuntu-20.04 | true |  |  |  |  | 71 | 91 | 56
ubuntu-20.04 | true |  |  |  | true | 74 | 94 | 170
ubuntu-20.04 | true |  |  | true |  | 76 | 96 | 82
ubuntu-20.04 | true |  |  | true | true | 79 | 99 | 17
ubuntu-20.04 | true |  | true |  |  | 71 | 91 | 56
ubuntu-20.04 | true |  | true |  | true | 74 | 94 | 46
ubuntu-20.04 | true |  | true | true |  | 76 | 96 | 71
ubuntu-20.04 | true |  | true | true | true | 79 | 99 | 109
ubuntu-20.04 | true | true |  |  |  | 73 | 93 | 12
ubuntu-20.04 | true | true |  |  | true | 76 | 96 | 102
ubuntu-20.04 | true | true |  | true |  | 78 | 98 | 14
ubuntu-20.04 | true | true |  | true | true | 81 | 101 | 228
ubuntu-20.04 | true | true | true |  |  | 73 | 93 | 152
ubuntu-20.04 | true | true | true |  | true | 76 | 96 | 133
ubuntu-20.04 | true | true | true | true |  | 78 | 98 | 15
ubuntu-20.04 | true | true | true | true | true | 81 | 101 | 155
ubuntu-22.04 |  |  |  |  |  | 63 | 84 | 2
ubuntu-22.04 |  |  |  |  | true | 66 | 87 | 27
ubuntu-22.04 |  |  |  | true |  | 67 | 88 | 4
ubuntu-22.04 |  |  |  | true | true | 71 | 92 | 7
ubuntu-22.04 |  |  | true |  |  | 63 | 84 | 1
ubuntu-22.04 |  |  | true |  | true | 66 | 87 | 96
ubuntu-22.04 |  |  | true | true |  | 67 | 88 | 3
ubuntu-22.04 |  |  | true | true | true | 71 | 92 | 28
ubuntu-22.04 |  | true |  |  |  | 64 | 85 | 4
ubuntu-22.04 |  | true |  |  | true | 67 | 88 | 8
ubuntu-22.04 |  | true |  | true |  | 69 | 90 | 4
ubuntu-22.04 |  | true |  | true | true | 72 | 93 | 82
ubuntu-22.04 |  | true | true |  |  | 64 | 85 | 4
ubuntu-22.04 |  | true | true |  | true | 67 | 88 | 7
ubuntu-22.04 |  | true | true | true |  | 69 | 90 | 5
ubuntu-22.04 |  | true | true | true | true | 72 | 93 | 8
ubuntu-22.04 | true |  |  |  |  | 72 | 93 | 60
ubuntu-22.04 | true |  |  |  | true | 75 | 96 | 14
ubuntu-22.04 | true |  |  | true |  | 76 | 97 | 15
ubuntu-22.04 | true |  |  | true | true | 80 | 101 | 15
ubuntu-22.04 | true |  | true |  |  | 72 | 93 | 14
ubuntu-22.04 | true |  | true |  | true | 75 | 96 | 13
ubuntu-22.04 | true |  | true | true |  | 76 | 97 | 12
ubuntu-22.04 | true |  | true | true | true | 80 | 101 | 15
ubuntu-22.04 | true | true |  |  |  | 73 | 94 | 84
ubuntu-22.04 | true | true |  |  | true | 76 | 97 | 116
ubuntu-22.04 | true | true |  | true |  | 78 | 99 | 15
ubuntu-22.04 | true | true |  | true | true | 81 | 102 | 16
ubuntu-22.04 | true | true | true |  |  | 73 | 94 | 64
ubuntu-22.04 | true | true | true |  | true | 76 | 97 | 96
ubuntu-22.04 | true | true | true | true |  | 78 | 99 | 65
ubuntu-22.04 | true | true | true | true | true | 81 | 102 | 76
