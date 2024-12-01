# Maximize available disk space for build tasks

If the available disk space on Github runners is too little for your build job, this action might be for you.
If not: please go on, there's nothing to see here.

This table shows the amount of free space you receive when using the action with the various options.

OS | Android SDKs removed | .NET SDKs removed | Haskell removed | CodeQL Removed | Cached Docker Images Removed | GB freed | GB free | Elapsed Time (seconds) |
---|:--------------------:|:-----------------:|:---------------:|:--------------:|:----------------------------:|:--------:|:-------:|:----------------------:|
ubuntu-20.04 |  |  |  |  |  | 62 | 83 | 2
ubuntu-20.04 |  |  |  |  | true | 65 | 86 | 7
ubuntu-20.04 |  |  |  | true |  | 67 | 88 | 5
ubuntu-20.04 |  |  |  | true | true | 70 | 91 | 8
ubuntu-20.04 |  |  | true |  |  | 62 | 83 | 3
ubuntu-20.04 |  |  | true |  | true | 65 | 86 | 43
ubuntu-20.04 |  |  | true | true |  | 67 | 88 | 4
ubuntu-20.04 |  |  | true | true | true | 70 | 91 | 42
ubuntu-20.04 |  | true |  |  |  | 64 | 85 | 4
ubuntu-20.04 |  | true |  |  | true | 66 | 87 | 8
ubuntu-20.04 |  | true |  | true |  | 69 | 90 | 6
ubuntu-20.04 |  | true |  | true | true | 71 | 92 | 10
ubuntu-20.04 |  | true | true |  |  | 64 | 85 | 4
ubuntu-20.04 |  | true | true |  | true | 66 | 87 | 44
ubuntu-20.04 |  | true | true | true |  | 69 | 90 | 6
ubuntu-20.04 |  | true | true | true | true | 71 | 92 | 9
ubuntu-20.04 | true |  |  |  |  | 70 | 91 | 93
ubuntu-20.04 | true |  |  |  | true | 72 | 93 | 115
ubuntu-20.04 | true |  |  | true |  | 75 | 96 | 62
ubuntu-20.04 | true |  |  | true | true | 77 | 98 | 18
ubuntu-20.04 | true |  | true |  |  | 70 | 91 | 17
ubuntu-20.04 | true |  | true |  | true | 72 | 93 | 130
ubuntu-20.04 | true |  | true | true |  | 75 | 96 | 76
ubuntu-20.04 | true |  | true | true | true | 77 | 98 | 116
ubuntu-20.04 | true | true |  |  |  | 71 | 92 | 77
ubuntu-20.04 | true | true |  |  | true | 74 | 95 | 111
ubuntu-20.04 | true | true |  | true |  | 76 | 97 | 89
ubuntu-20.04 | true | true |  | true | true | 79 | 100 | 20
ubuntu-20.04 | true | true | true |  |  | 71 | 92 | 12
ubuntu-20.04 | true | true | true |  | true | 74 | 95 | 110
ubuntu-20.04 | true | true | true | true |  | 76 | 97 | 71
ubuntu-20.04 | true | true | true | true | true | 79 | 100 | 81
ubuntu-22.04 |  |  |  |  |  | 62 | 84 | 1
ubuntu-22.04 |  |  |  |  | true | 65 | 87 | 7
ubuntu-22.04 |  |  |  | true |  | 67 | 89 | 4
ubuntu-22.04 |  |  |  | true | true | 70 | 92 | 7
ubuntu-22.04 |  |  | true |  |  | 62 | 84 | 2
ubuntu-22.04 |  |  | true |  | true | 65 | 87 | 23
ubuntu-22.04 |  |  | true | true |  | 67 | 89 | 3
ubuntu-22.04 |  |  | true | true | true | 70 | 92 | 7
ubuntu-22.04 |  | true |  |  |  | 64 | 86 | 4
ubuntu-22.04 |  | true |  |  | true | 66 | 88 | 18
ubuntu-22.04 |  | true |  | true |  | 69 | 91 | 4
ubuntu-22.04 |  | true |  | true | true | 71 | 93 | 8
ubuntu-22.04 |  | true | true |  |  | 64 | 86 | 5
ubuntu-22.04 |  | true | true |  | true | 66 | 88 | 7
ubuntu-22.04 |  | true | true | true |  | 69 | 91 | 4
ubuntu-22.04 |  | true | true | true | true | 71 | 93 | 9
ubuntu-22.04 | true |  |  |  |  | 70 | 92 | 18
ubuntu-22.04 | true |  |  |  | true | 72 | 94 | 21
ubuntu-22.04 | true |  |  | true |  | 75 | 97 | 87
ubuntu-22.04 | true |  |  | true | true | 77 | 99 | 21
ubuntu-22.04 | true |  | true |  |  | 70 | 92 | 14
ubuntu-22.04 | true |  | true |  | true | 72 | 94 | 179
ubuntu-22.04 | true |  | true | true |  | 75 | 97 | 14
ubuntu-22.04 | true |  | true | true | true | 77 | 99 | 18
ubuntu-22.04 | true | true |  |  |  | 72 | 94 | 15
ubuntu-22.04 | true | true |  |  | true | 74 | 96 | 112
ubuntu-22.04 | true | true |  | true |  | 77 | 99 | 20
ubuntu-22.04 | true | true |  | true | true | 79 | 101 | 15
ubuntu-22.04 | true | true | true |  |  | 72 | 94 | 14
ubuntu-22.04 | true | true | true |  | true | 74 | 96 | 168
ubuntu-22.04 | true | true | true | true |  | 77 | 99 | 18
ubuntu-22.04 | true | true | true | true | true | 79 | 101 | 20
