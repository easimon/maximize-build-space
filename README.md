# Maximize available disk space for build tasks

If the available disk space on Github runners is too little for your build job, this action might be for you.
If not: please go on, there's nothing to see here.

This table shows the amount of free space you receive when using the action with the various options.

OS | Android SDKs removed | .NET SDKs removed | Haskell removed | CodeQL Removed | Cached Docker Images Removed | GB freed | GB free | Elapsed Time (seconds) |
---|:--------------------:|:-----------------:|:---------------:|:--------------:|:----------------------------:|:--------:|:-------:|:----------------------:|
ubuntu-20.04 |  |  |  |  |  | 62 | 83 | 2
ubuntu-20.04 |  |  |  |  | true | 65 | 86 | 78
ubuntu-20.04 |  |  |  | true |  | 67 | 88 | 4
ubuntu-20.04 |  |  |  | true | true | 70 | 91 | 54
ubuntu-20.04 |  |  | true |  |  | 62 | 83 | 2
ubuntu-20.04 |  |  | true |  | true | 65 | 86 | 42
ubuntu-20.04 |  |  | true | true |  | 67 | 88 | 4
ubuntu-20.04 |  |  | true | true | true | 70 | 91 | 9
ubuntu-20.04 |  | true |  |  |  | 64 | 85 | 5
ubuntu-20.04 |  | true |  |  | true | 66 | 87 | 7
ubuntu-20.04 |  | true |  | true |  | 69 | 90 | 6
ubuntu-20.04 |  | true |  | true | true | 71 | 92 | 60
ubuntu-20.04 |  | true | true |  |  | 64 | 85 | 5
ubuntu-20.04 |  | true | true |  | true | 66 | 87 | 8
ubuntu-20.04 |  | true | true | true |  | 69 | 90 | 6
ubuntu-20.04 |  | true | true | true | true | 71 | 92 | 8
ubuntu-20.04 | true |  |  |  |  | 70 | 91 | 13
ubuntu-20.04 | true |  |  |  | true | 72 | 93 | 102
ubuntu-20.04 | true |  |  | true |  | 75 | 96 | 66
ubuntu-20.04 | true |  |  | true | true | 77 | 98 | 16
ubuntu-20.04 | true |  | true |  |  | 70 | 91 | 14
ubuntu-20.04 | true |  | true |  | true | 72 | 93 | 114
ubuntu-20.04 | true |  | true | true |  | 75 | 96 | 64
ubuntu-20.04 | true |  | true | true | true | 77 | 98 | 100
ubuntu-20.04 | true | true |  |  |  | 71 | 92 | 93
ubuntu-20.04 | true | true |  |  | true | 74 | 95 | 153
ubuntu-20.04 | true | true |  | true |  | 76 | 97 | 99
ubuntu-20.04 | true | true |  | true | true | 79 | 100 | 170
ubuntu-20.04 | true | true | true |  |  | 71 | 92 | 51
ubuntu-20.04 | true | true | true |  | true | 74 | 95 | 94
ubuntu-20.04 | true | true | true | true |  | 76 | 97 | 16
ubuntu-20.04 | true | true | true | true | true | 79 | 100 | 26
ubuntu-22.04 |  |  |  |  |  | 62 | 84 | 2
ubuntu-22.04 |  |  |  |  | true | 65 | 87 | 5
ubuntu-22.04 |  |  |  | true |  | 67 | 89 | 4
ubuntu-22.04 |  |  |  | true | true | 70 | 92 | 18
ubuntu-22.04 |  |  | true |  |  | 62 | 84 | 2
ubuntu-22.04 |  |  | true |  | true | 65 | 87 | 23
ubuntu-22.04 |  |  | true | true |  | 67 | 89 | 4
ubuntu-22.04 |  |  | true | true | true | 70 | 92 | 8
ubuntu-22.04 |  | true |  |  |  | 64 | 86 | 5
ubuntu-22.04 |  | true |  |  | true | 66 | 88 | 15
ubuntu-22.04 |  | true |  | true |  | 69 | 91 | 4
ubuntu-22.04 |  | true |  | true | true | 71 | 93 | 7
ubuntu-22.04 |  | true | true |  |  | 64 | 86 | 4
ubuntu-22.04 |  | true | true |  | true | 66 | 88 | 19
ubuntu-22.04 |  | true | true | true |  | 69 | 91 | 4
ubuntu-22.04 |  | true | true | true | true | 71 | 93 | 8
ubuntu-22.04 | true |  |  |  |  | 70 | 92 | 87
ubuntu-22.04 | true |  |  |  | true | 72 | 94 | 136
ubuntu-22.04 | true |  |  | true |  | 75 | 97 | 16
ubuntu-22.04 | true |  |  | true | true | 77 | 99 | 84
ubuntu-22.04 | true |  | true |  |  | 70 | 92 | 19
ubuntu-22.04 | true |  | true |  | true | 72 | 94 | 106
ubuntu-22.04 | true |  | true | true |  | 75 | 97 | 16
ubuntu-22.04 | true |  | true | true | true | 77 | 99 | 21
ubuntu-22.04 | true | true |  |  |  | 71 | 93 | 14
ubuntu-22.04 | true | true |  |  | true | 74 | 96 | 102
ubuntu-22.04 | true | true |  | true |  | 76 | 98 | 21
ubuntu-22.04 | true | true |  | true | true | 79 | 101 | 129
ubuntu-22.04 | true | true | true |  |  | 71 | 93 | 16
ubuntu-22.04 | true | true | true |  | true | 74 | 96 | 85
ubuntu-22.04 | true | true | true | true |  | 76 | 98 | 96
ubuntu-22.04 | true | true | true | true | true | 79 | 101 | 100
