# Maximize available disk space for build tasks

If the available disk space on Github runners is too little for your build job, this action might be for you.
If not: please go on, there's nothing to see here.

This table shows the amount of free space you receive when using the action with the various options.

OS | Android SDKs removed | .NET SDKs removed | Haskell removed | CodeQL Removed | Cached Docker Images Removed | GB freed | GB free | Elapsed Time (seconds) |
---|:--------------------:|:-----------------:|:---------------:|:--------------:|:----------------------------:|:--------:|:-------:|:----------------------:|
ubuntu-20.04 |  |  |  |  |  | 62 | 83 | 2
ubuntu-20.04 |  |  |  |  | true | 65 | 86 | 61
ubuntu-20.04 |  |  |  | true |  | 67 | 88 | 4
ubuntu-20.04 |  |  |  | true | true | 70 | 91 | 7
ubuntu-20.04 |  |  | true |  |  | 62 | 83 | 2
ubuntu-20.04 |  |  | true |  | true | 65 | 86 | 7
ubuntu-20.04 |  |  | true | true |  | 67 | 88 | 8
ubuntu-20.04 |  |  | true | true | true | 70 | 91 | 46
ubuntu-20.04 |  | true |  |  |  | 64 | 85 | 4
ubuntu-20.04 |  | true |  |  | true | 66 | 87 | 40
ubuntu-20.04 |  | true |  | true |  | 69 | 90 | 4
ubuntu-20.04 |  | true |  | true | true | 71 | 92 | 48
ubuntu-20.04 |  | true | true |  |  | 64 | 85 | 4
ubuntu-20.04 |  | true | true |  | true | 66 | 87 | 8
ubuntu-20.04 |  | true | true | true |  | 69 | 90 | 4
ubuntu-20.04 |  | true | true | true | true | 71 | 92 | 59
ubuntu-20.04 | true |  |  |  |  | 70 | 91 | 14
ubuntu-20.04 | true |  |  |  | true | 72 | 93 | 99
ubuntu-20.04 | true |  |  | true |  | 75 | 96 | 90
ubuntu-20.04 | true |  |  | true | true | 77 | 98 | 133
ubuntu-20.04 | true |  | true |  |  | 70 | 91 | 12
ubuntu-20.04 | true |  | true |  | true | 72 | 93 | 16
ubuntu-20.04 | true |  | true | true |  | 75 | 96 | 100
ubuntu-20.04 | true |  | true | true | true | 77 | 98 | 15
ubuntu-20.04 | true | true |  |  |  | 71 | 92 | 87
ubuntu-20.04 | true | true |  |  | true | 74 | 95 | 25
ubuntu-20.04 | true | true |  | true |  | 76 | 97 | 174
ubuntu-20.04 | true | true |  | true | true | 79 | 100 | 20
ubuntu-20.04 | true | true | true |  |  | 71 | 92 | 82
ubuntu-20.04 | true | true | true |  | true | 74 | 95 | 167
ubuntu-20.04 | true | true | true | true |  | 76 | 97 | 73
ubuntu-20.04 | true | true | true | true | true | 79 | 100 | 118
ubuntu-22.04 |  |  |  |  |  | 62 | 84 | 2
ubuntu-22.04 |  |  |  |  | true | 65 | 87 | 6
ubuntu-22.04 |  |  |  | true |  | 67 | 89 | 4
ubuntu-22.04 |  |  |  | true | true | 70 | 92 | 8
ubuntu-22.04 |  |  | true |  |  | 62 | 84 | 2
ubuntu-22.04 |  |  | true |  | true | 65 | 87 | 25
ubuntu-22.04 |  |  | true | true |  | 67 | 89 | 4
ubuntu-22.04 |  |  | true | true | true | 70 | 92 | 8
ubuntu-22.04 |  | true |  |  |  | 64 | 86 | 4
ubuntu-22.04 |  | true |  |  | true | 66 | 88 | 9
ubuntu-22.04 |  | true |  | true |  | 69 | 91 | 4
ubuntu-22.04 |  | true |  | true | true | 71 | 93 | 7
ubuntu-22.04 |  | true | true |  |  | 64 | 86 | 4
ubuntu-22.04 |  | true | true |  | true | 66 | 88 | 6
ubuntu-22.04 |  | true | true | true |  | 69 | 91 | 4
ubuntu-22.04 |  | true | true | true | true | 71 | 93 | 7
ubuntu-22.04 | true |  |  |  |  | 70 | 92 | 11
ubuntu-22.04 | true |  |  |  | true | 72 | 94 | 14
ubuntu-22.04 | true |  |  | true |  | 75 | 97 | 17
ubuntu-22.04 | true |  |  | true | true | 77 | 99 | 23
ubuntu-22.04 | true |  | true |  |  | 70 | 92 | 11
ubuntu-22.04 | true |  | true |  | true | 72 | 94 | 81
ubuntu-22.04 | true |  | true | true |  | 75 | 97 | 16
ubuntu-22.04 | true |  | true | true | true | 77 | 99 | 24
ubuntu-22.04 | true | true |  |  |  | 71 | 93 | 86
ubuntu-22.04 | true | true |  |  | true | 74 | 96 | 26
ubuntu-22.04 | true | true |  | true |  | 76 | 98 | 18
ubuntu-22.04 | true | true |  | true | true | 79 | 101 | 90
ubuntu-22.04 | true | true | true |  |  | 71 | 93 | 76
ubuntu-22.04 | true | true | true |  | true | 74 | 96 | 17
ubuntu-22.04 | true | true | true | true |  | 76 | 98 | 14
ubuntu-22.04 | true | true | true | true | true | 79 | 101 | 122
