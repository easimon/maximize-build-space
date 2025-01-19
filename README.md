# Maximize available disk space for build tasks

If the available disk space on Github runners is too little for your build job, this action might be for you.
If not: please go on, there's nothing to see here.

This table shows the amount of free space you receive when using the action with the various options.

OS | Android SDKs removed | .NET SDKs removed | Haskell removed | CodeQL Removed | Cached Docker Images Removed | GB freed | GB free | Elapsed Time (seconds) |
---|:--------------------:|:-----------------:|:---------------:|:--------------:|:----------------------------:|:--------:|:-------:|:----------------------:|
ubuntu-20.04 |  |  |  |  |  | 62 | 82 | 3
ubuntu-20.04 |  |  |  |  | true | 65 | 85 | 24
ubuntu-20.04 |  |  |  | true |  | 67 | 87 | 4
ubuntu-20.04 |  |  |  | true | true | 70 | 90 | 22
ubuntu-20.04 |  |  | true |  |  | 62 | 82 | 3
ubuntu-20.04 |  |  | true |  | true | 65 | 85 | 22
ubuntu-20.04 |  |  | true | true |  | 67 | 87 | 4
ubuntu-20.04 |  |  | true | true | true | 70 | 90 | 60
ubuntu-20.04 |  | true |  |  |  | 64 | 84 | 4
ubuntu-20.04 |  | true |  |  | true | 66 | 86 | 43
ubuntu-20.04 |  | true |  | true |  | 69 | 89 | 5
ubuntu-20.04 |  | true |  | true | true | 71 | 91 | 12
ubuntu-20.04 |  | true | true |  |  | 64 | 84 | 5
ubuntu-20.04 |  | true | true |  | true | 66 | 86 | 38
ubuntu-20.04 |  | true | true | true |  | 69 | 89 | 6
ubuntu-20.04 |  | true | true | true | true | 71 | 91 | 46
ubuntu-20.04 | true |  |  |  |  | 70 | 90 | 78
ubuntu-20.04 | true |  |  |  | true | 72 | 92 | 21
ubuntu-20.04 | true |  |  | true |  | 75 | 95 | 68
ubuntu-20.04 | true |  |  | true | true | 78 | 98 | 116
ubuntu-20.04 | true |  | true |  |  | 70 | 90 | 154
ubuntu-20.04 | true |  | true |  | true | 72 | 92 | 87
ubuntu-20.04 | true |  | true | true |  | 75 | 95 | 20
ubuntu-20.04 | true |  | true | true | true | 78 | 98 | 140
ubuntu-20.04 | true | true |  |  |  | 71 | 91 | 16
ubuntu-20.04 | true | true |  |  | true | 74 | 94 | 19
ubuntu-20.04 | true | true |  | true |  | 77 | 97 | 133
ubuntu-20.04 | true | true |  | true | true | 79 | 99 | 105
ubuntu-20.04 | true | true | true |  |  | 71 | 91 | 66
ubuntu-20.04 | true | true | true |  | true | 74 | 94 | 125
ubuntu-20.04 | true | true | true | true |  | 77 | 97 | 74
ubuntu-20.04 | true | true | true | true | true | 79 | 99 | 264
ubuntu-22.04 |  |  |  |  |  | 63 | 84 | 1
ubuntu-22.04 |  |  |  |  | true | 65 | 86 | 36
ubuntu-22.04 |  |  |  | true |  | 68 | 89 | 3
ubuntu-22.04 |  |  |  | true | true | 70 | 91 | 7
ubuntu-22.04 |  |  | true |  |  | 63 | 84 | 2
ubuntu-22.04 |  |  | true |  | true | 65 | 86 | 5
ubuntu-22.04 |  |  | true | true |  | 68 | 89 | 7
ubuntu-22.04 |  |  | true | true | true | 70 | 91 | 8
ubuntu-22.04 |  | true |  |  |  | 64 | 85 | 3
ubuntu-22.04 |  | true |  |  | true | 67 | 88 | 6
ubuntu-22.04 |  | true |  | true |  | 69 | 90 | 5
ubuntu-22.04 |  | true |  | true | true | 72 | 93 | 8
ubuntu-22.04 |  | true | true |  |  | 64 | 85 | 6
ubuntu-22.04 |  | true | true |  | true | 67 | 88 | 7
ubuntu-22.04 |  | true | true | true |  | 69 | 90 | 8
ubuntu-22.04 |  | true | true | true | true | 72 | 93 | 8
ubuntu-22.04 | true |  |  |  |  | 70 | 91 | 82
ubuntu-22.04 | true |  |  |  | true | 73 | 94 | 15
ubuntu-22.04 | true |  |  | true |  | 75 | 96 | 73
ubuntu-22.04 | true |  |  | true | true | 78 | 99 | 18
ubuntu-22.04 | true |  | true |  |  | 70 | 91 | 11
ubuntu-22.04 | true |  | true |  | true | 73 | 94 | 87
ubuntu-22.04 | true |  | true | true |  | 75 | 96 | 64
ubuntu-22.04 | true |  | true | true | true | 78 | 99 | 18
ubuntu-22.04 | true | true |  |  |  | 72 | 93 | 76
ubuntu-22.04 | true | true |  |  | true | 74 | 95 | 24
ubuntu-22.04 | true | true |  | true |  | 77 | 98 | 18
ubuntu-22.04 | true | true |  | true | true | 79 | 100 | 16
ubuntu-22.04 | true | true | true |  |  | 72 | 93 | 71
ubuntu-22.04 | true | true | true |  | true | 74 | 95 | 21
ubuntu-22.04 | true | true | true | true |  | 77 | 98 | 18
ubuntu-22.04 | true | true | true | true | true | 79 | 100 | 111
