# Maximize available disk space for build tasks

If the available disk space on Github runners is too little for your build job, this action might be for you.
If not: please go on, there's nothing to see here.

This table shows the amount of free space you receive when using the action with the various options.

OS | Android SDKs removed | .NET SDKs removed | Haskell removed | CodeQL Removed | Cached Docker Images Removed | GB freed | GB free | Elapsed Time (seconds) |
---|:--------------------:|:-----------------:|:---------------:|:--------------:|:----------------------------:|:--------:|:-------:|:----------------------:|
ubuntu-20.04 |  |  |  |  |  | 63 | 82 | 2
ubuntu-20.04 |  |  |  |  | true | 66 | 85 | 28
ubuntu-20.04 |  |  |  | true |  | 68 | 87 | 3
ubuntu-20.04 |  |  |  | true | true | 71 | 90 | 7
ubuntu-20.04 |  |  | true |  |  | 63 | 82 | 3
ubuntu-20.04 |  |  | true |  | true | 66 | 85 | 25
ubuntu-20.04 |  |  | true | true |  | 68 | 87 | 5
ubuntu-20.04 |  |  | true | true | true | 71 | 90 | 34
ubuntu-20.04 |  | true |  |  |  | 65 | 84 | 4
ubuntu-20.04 |  | true |  |  | true | 68 | 87 | 23
ubuntu-20.04 |  | true |  | true |  | 69 | 88 | 4
ubuntu-20.04 |  | true |  | true | true | 72 | 91 | 64
ubuntu-20.04 |  | true | true |  |  | 64 | 84 | 4
ubuntu-20.04 |  | true | true |  | true | 68 | 87 | 25
ubuntu-20.04 |  | true | true | true |  | 69 | 89 | 5
ubuntu-20.04 |  | true | true | true | true | 72 | 91 | 27
ubuntu-20.04 | true |  |  |  |  | 72 | 91 | 9
ubuntu-20.04 | true |  |  |  | true | 75 | 94 | 51
ubuntu-20.04 | true |  |  | true |  | 76 | 95 | 52
ubuntu-20.04 | true |  |  | true | true | 80 | 99 | 11
ubuntu-20.04 | true |  | true |  |  | 72 | 91 | 44
ubuntu-20.04 | true |  | true |  | true | 75 | 94 | 12
ubuntu-20.04 | true |  | true | true |  | 76 | 95 | 9
ubuntu-20.04 | true |  | true | true | true | 80 | 99 | 82
ubuntu-20.04 | true | true |  |  |  | 73 | 92 | 57
ubuntu-20.04 | true | true |  |  | true | 76 | 95 | 126
ubuntu-20.04 | true | true |  | true |  | 78 | 98 | 66
ubuntu-20.04 | true | true |  | true | true | 81 | 100 | 136
ubuntu-20.04 | true | true | true |  |  | 73 | 92 | 79
ubuntu-20.04 | true | true | true |  | true | 76 | 95 | 68
ubuntu-20.04 | true | true | true | true |  | 78 | 97 | 13
ubuntu-20.04 | true | true | true | true | true | 81 | 100 | 92
ubuntu-22.04 |  |  |  |  |  | 63 | 83 | 2
ubuntu-22.04 |  |  |  |  | true | 66 | 86 | 7
ubuntu-22.04 |  |  |  | true |  | 68 | 88 | 3
ubuntu-22.04 |  |  |  | true | true | 71 | 91 | 30
ubuntu-22.04 |  |  | true |  |  | 63 | 83 | 2
ubuntu-22.04 |  |  | true |  | true | 66 | 86 | 30
ubuntu-22.04 |  |  | true | true |  | 68 | 88 | 3
ubuntu-22.04 |  |  | true | true | true | 71 | 91 | 25
ubuntu-22.04 |  | true |  |  |  | 64 | 84 | 4
ubuntu-22.04 |  | true |  |  | true | 67 | 87 | 39
ubuntu-22.04 |  | true |  | true |  | 69 | 89 | 5
ubuntu-22.04 |  | true |  | true | true | 72 | 92 | 36
ubuntu-22.04 |  | true | true |  |  | 64 | 84 | 4
ubuntu-22.04 |  | true | true |  | true | 67 | 87 | 29
ubuntu-22.04 |  | true | true | true |  | 69 | 89 | 4
ubuntu-22.04 |  | true | true | true | true | 72 | 92 | 28
ubuntu-22.04 | true |  |  |  |  | 71 | 91 | 56
ubuntu-22.04 | true |  |  |  | true | 75 | 95 | 15
ubuntu-22.04 | true |  |  | true |  | 76 | 96 | 63
ubuntu-22.04 | true |  |  | true | true | 79 | 99 | 116
ubuntu-22.04 | true |  | true |  |  | 71 | 91 | 13
ubuntu-22.04 | true |  | true |  | true | 75 | 95 | 16
ubuntu-22.04 | true |  | true | true |  | 76 | 96 | 12
ubuntu-22.04 | true |  | true | true | true | 79 | 99 | 112
ubuntu-22.04 | true | true |  |  |  | 73 | 93 | 67
ubuntu-22.04 | true | true |  |  | true | 76 | 96 | 89
ubuntu-22.04 | true | true |  | true |  | 78 | 98 | 60
ubuntu-22.04 | true | true |  | true | true | 81 | 101 | 88
ubuntu-22.04 | true | true | true |  |  | 73 | 93 | 55
ubuntu-22.04 | true | true | true |  | true | 76 | 96 | 16
ubuntu-22.04 | true | true | true | true |  | 78 | 98 | 11
ubuntu-22.04 | true | true | true | true | true | 81 | 101 | 101
