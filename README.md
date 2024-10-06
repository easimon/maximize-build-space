# Maximize available disk space for build tasks

If the available disk space on Github runners is too little for your build job, this action might be for you.
If not: please go on, there's nothing to see here.

This table shows the amount of free space you receive when using the action with the various options.

OS | Android SDKs removed | .NET SDKs removed | Haskell removed | CodeQL Removed | Cached Docker Images Removed | GB freed | GB free | Elapsed Time (seconds) |
---|:--------------------:|:-----------------:|:---------------:|:--------------:|:----------------------------:|:--------:|:-------:|:----------------------:|
ubuntu-20.04 |  |  |  |  |  | 63 | 83 | 2
ubuntu-20.04 |  |  |  |  | true | 66 | 86 | 8
ubuntu-20.04 |  |  |  | true |  | 68 | 88 | 4
ubuntu-20.04 |  |  |  | true | true | 71 | 91 | 34
ubuntu-20.04 |  |  | true |  |  | 63 | 83 | 3
ubuntu-20.04 |  |  | true |  | true | 66 | 86 | 46
ubuntu-20.04 |  |  | true | true |  | 68 | 88 | 4
ubuntu-20.04 |  |  | true | true | true | 71 | 91 | 9
ubuntu-20.04 |  | true |  |  |  | 64 | 84 | 4
ubuntu-20.04 |  | true |  |  | true | 68 | 88 | 10
ubuntu-20.04 |  | true |  | true |  | 69 | 89 | 5
ubuntu-20.04 |  | true |  | true | true | 72 | 92 | 43
ubuntu-20.04 |  | true | true |  |  | 64 | 84 | 4
ubuntu-20.04 |  | true | true |  | true | 68 | 88 | 47
ubuntu-20.04 |  | true | true | true |  | 69 | 89 | 5
ubuntu-20.04 |  | true | true | true | true | 72 | 92 | 46
ubuntu-20.04 | true |  |  |  |  | 70 | 90 | 15
ubuntu-20.04 | true |  |  |  | true | 73 | 93 | 173
ubuntu-20.04 | true |  |  | true |  | 75 | 95 | 84
ubuntu-20.04 | true |  |  | true | true | 78 | 98 | 127
ubuntu-20.04 | true |  | true |  |  | 70 | 90 | 76
ubuntu-20.04 | true |  | true |  | true | 73 | 93 | 96
ubuntu-20.04 | true |  | true | true |  | 75 | 95 | 17
ubuntu-20.04 | true |  | true | true | true | 78 | 98 | 18
ubuntu-20.04 | true | true |  |  |  | 72 | 92 | 17
ubuntu-20.04 | true | true |  |  | true | 75 | 95 | 110
ubuntu-20.04 | true | true |  | true |  | 77 | 97 | 18
ubuntu-20.04 | true | true |  | true | true | 80 | 100 | 130
ubuntu-20.04 | true | true | true |  |  | 72 | 92 | 71
ubuntu-20.04 | true | true | true |  | true | 75 | 95 | 21
ubuntu-20.04 | true | true | true | true |  | 77 | 97 | 94
ubuntu-20.04 | true | true | true | true | true | 80 | 100 | 124
ubuntu-22.04 |  |  |  |  |  | 62 | 83 | 1
ubuntu-22.04 |  |  |  |  | true | 66 | 87 | 31
ubuntu-22.04 |  |  |  | true |  | 67 | 88 | 3
ubuntu-22.04 |  |  |  | true | true | 71 | 92 | 7
ubuntu-22.04 |  |  | true |  |  | 62 | 83 | 2
ubuntu-22.04 |  |  | true |  | true | 66 | 87 | 6
ubuntu-22.04 |  |  | true | true |  | 67 | 88 | 3
ubuntu-22.04 |  |  | true | true | true | 71 | 92 | 28
ubuntu-22.04 |  | true |  |  |  | 64 | 85 | 3
ubuntu-22.04 |  | true |  |  | true | 67 | 88 | 9
ubuntu-22.04 |  | true |  | true |  | 69 | 90 | 4
ubuntu-22.04 |  | true |  | true | true | 72 | 93 | 9
ubuntu-22.04 |  | true | true |  |  | 64 | 85 | 3
ubuntu-22.04 |  | true | true |  | true | 67 | 88 | 8
ubuntu-22.04 |  | true | true | true |  | 69 | 90 | 4
ubuntu-22.04 |  | true | true | true | true | 72 | 93 | 31
ubuntu-22.04 | true |  |  |  |  | 70 | 91 | 89
ubuntu-22.04 | true |  |  |  | true | 73 | 94 | 22
ubuntu-22.04 | true |  |  | true |  | 75 | 96 | 17
ubuntu-22.04 | true |  |  | true | true | 78 | 99 | 22
ubuntu-22.04 | true |  | true |  |  | 70 | 91 | 119
ubuntu-22.04 | true |  | true |  | true | 73 | 94 | 116
ubuntu-22.04 | true |  | true | true |  | 75 | 96 | 14
ubuntu-22.04 | true |  | true | true | true | 78 | 99 | 20
ubuntu-22.04 | true | true |  |  |  | 71 | 92 | 71
ubuntu-22.04 | true | true |  |  | true | 75 | 96 | 94
ubuntu-22.04 | true | true |  | true |  | 76 | 97 | 110
ubuntu-22.04 | true | true |  | true | true | 80 | 101 | 23
ubuntu-22.04 | true | true | true |  |  | 71 | 92 | 12
ubuntu-22.04 | true | true | true |  | true | 75 | 96 | 159
ubuntu-22.04 | true | true | true | true |  | 76 | 97 | 15
ubuntu-22.04 | true | true | true | true | true | 80 | 101 | 95
