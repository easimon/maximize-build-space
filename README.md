# Maximize available disk space for build tasks

If the available disk space on Github runners is too little for your build job, this action might be for you.
If not: please go on, there's nothing to see here.

This table shows the amount of free space you receive when using the action with the various options.

OS | Android SDKs removed | .NET SDKs removed | Haskell removed | CodeQL Removed | Cached Docker Images Removed | GB freed | GB free | Elapsed Time (seconds) |
---|:--------------------:|:-----------------:|:---------------:|:--------------:|:----------------------------:|:--------:|:-------:|:----------------------:|
ubuntu-20.04 |  |  |  |  |  | 62 | 81 | 2
ubuntu-20.04 |  |  |  |  | true | 65 | 84 | 69
ubuntu-20.04 |  |  |  | true |  | 67 | 86 | 2
ubuntu-20.04 |  |  |  | true | true | 70 | 89 | 36
ubuntu-20.04 |  |  | true |  |  | 62 | 81 | 2
ubuntu-20.04 |  |  | true |  | true | 65 | 84 | 53
ubuntu-20.04 |  |  | true | true |  | 67 | 86 | 3
ubuntu-20.04 |  |  | true | true | true | 70 | 89 | 100
ubuntu-20.04 |  | true |  |  |  | 64 | 83 | 5
ubuntu-20.04 |  | true |  |  | true | 67 | 86 | 8
ubuntu-20.04 |  | true |  | true |  | 68 | 87 | 3
ubuntu-20.04 |  | true |  | true | true | 72 | 91 | 36
ubuntu-20.04 |  | true | true |  |  | 64 | 83 | 3
ubuntu-20.04 |  | true | true |  | true | 67 | 86 | 24
ubuntu-20.04 |  | true | true | true |  | 68 | 87 | 6
ubuntu-20.04 |  | true | true | true | true | 72 | 91 | 35
ubuntu-20.04 | true |  |  |  |  | 71 | 90 | 7
ubuntu-20.04 | true |  |  |  | true | 74 | 93 | 65
ubuntu-20.04 | true |  |  | true |  | 76 | 95 | 11
ubuntu-20.04 | true |  |  | true | true | 79 | 98 | 11
ubuntu-20.04 | true |  | true |  |  | 71 | 90 | 44
ubuntu-20.04 | true |  | true |  | true | 74 | 93 | 46
ubuntu-20.04 | true |  | true | true |  | 76 | 95 | 9
ubuntu-20.04 | true |  | true | true | true | 79 | 98 | 76
ubuntu-20.04 | true | true |  |  |  | 72 | 91 | 116
ubuntu-20.04 | true | true |  |  | true | 75 | 94 | 12
ubuntu-20.04 | true | true |  | true |  | 77 | 96 | 11
ubuntu-20.04 | true | true |  | true | true | 80 | 99 | 77
ubuntu-20.04 | true | true | true |  |  | 72 | 91 | 48
ubuntu-20.04 | true | true | true |  | true | 75 | 94 | 91
ubuntu-20.04 | true | true | true | true |  | 77 | 96 | 51
ubuntu-20.04 | true | true | true | true | true | 80 | 99 | 108
ubuntu-22.04 |  |  |  |  |  | 63 | 82 | 2
ubuntu-22.04 |  |  |  |  | true | 66 | 85 | 17
ubuntu-22.04 |  |  |  | true |  | 67 | 86 | 3
ubuntu-22.04 |  |  |  | true | true | 71 | 90 | 31
ubuntu-22.04 |  |  | true |  |  | 63 | 82 | 4
ubuntu-22.04 |  |  | true |  | true | 66 | 85 | 26
ubuntu-22.04 |  |  | true | true |  | 67 | 86 | 3
ubuntu-22.04 |  |  | true | true | true | 71 | 90 | 20
ubuntu-22.04 |  | true |  |  |  | 64 | 83 | 3
ubuntu-22.04 |  | true |  |  | true | 67 | 86 | 29
ubuntu-22.04 |  | true |  | true |  | 69 | 88 | 5
ubuntu-22.04 |  | true |  | true | true | 72 | 91 | 29
ubuntu-22.04 |  | true | true |  |  | 64 | 83 | 6
ubuntu-22.04 |  | true | true |  | true | 67 | 86 | 29
ubuntu-22.04 |  | true | true | true |  | 69 | 88 | 5
ubuntu-22.04 |  | true | true | true | true | 72 | 91 | 32
ubuntu-22.04 | true |  |  |  |  | 71 | 90 | 10
ubuntu-22.04 | true |  |  |  | true | 74 | 93 | 17
ubuntu-22.04 | true |  |  | true |  | 76 | 95 | 10
ubuntu-22.04 | true |  |  | true | true | 79 | 98 | 85
ubuntu-22.04 | true |  | true |  |  | 71 | 90 | 61
ubuntu-22.04 | true |  | true |  | true | 74 | 93 | 31
ubuntu-22.04 | true |  | true | true |  | 76 | 95 | 71
ubuntu-22.04 | true |  | true | true | true | 79 | 98 | 66
ubuntu-22.04 | true | true |  |  |  | 73 | 92 | 53
ubuntu-22.04 | true | true |  |  | true | 76 | 95 | 103
ubuntu-22.04 | true | true |  | true |  | 78 | 97 | 10
ubuntu-22.04 | true | true |  | true | true | 81 | 100 | 16
ubuntu-22.04 | true | true | true |  |  | 73 | 92 | 11
ubuntu-22.04 | true | true | true |  | true | 76 | 95 | 14
ubuntu-22.04 | true | true | true | true |  | 78 | 97 | 10
ubuntu-22.04 | true | true | true | true | true | 81 | 100 | 118
