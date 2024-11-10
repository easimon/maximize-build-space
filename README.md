# Maximize available disk space for build tasks

If the available disk space on Github runners is too little for your build job, this action might be for you.
If not: please go on, there's nothing to see here.

This table shows the amount of free space you receive when using the action with the various options.

OS | Android SDKs removed | .NET SDKs removed | Haskell removed | CodeQL Removed | Cached Docker Images Removed | GB freed | GB free | Elapsed Time (seconds) |
---|:--------------------:|:-----------------:|:---------------:|:--------------:|:----------------------------:|:--------:|:-------:|:----------------------:|
ubuntu-20.04 |  |  |  |  |  | 62 | 82 | 2
ubuntu-20.04 |  |  |  |  | true | 66 | 86 | 47
ubuntu-20.04 |  |  |  | true |  | 67 | 87 | 4
ubuntu-20.04 |  |  |  | true | true | 70 | 90 | 10
ubuntu-20.04 |  |  | true |  |  | 62 | 82 | 2
ubuntu-20.04 |  |  | true |  | true | 66 | 86 | 26
ubuntu-20.04 |  |  | true | true |  | 67 | 87 | 5
ubuntu-20.04 |  |  | true | true | true | 70 | 90 | 56
ubuntu-20.04 |  | true |  |  |  | 64 | 84 | 3
ubuntu-20.04 |  | true |  |  | true | 67 | 87 | 43
ubuntu-20.04 |  | true |  | true |  | 68 | 88 | 6
ubuntu-20.04 |  | true |  | true | true | 72 | 92 | 10
ubuntu-20.04 |  | true | true |  |  | 64 | 84 | 5
ubuntu-20.04 |  | true | true |  | true | 67 | 87 | 60
ubuntu-20.04 |  | true | true | true |  | 68 | 88 | 5
ubuntu-20.04 |  | true | true | true | true | 72 | 92 | 54
ubuntu-20.04 | true |  |  |  |  | 69 | 89 | 15
ubuntu-20.04 | true |  |  |  | true | 73 | 93 | 17
ubuntu-20.04 | true |  |  | true |  | 74 | 94 | 16
ubuntu-20.04 | true |  |  | true | true | 78 | 98 | 59
ubuntu-20.04 | true |  | true |  |  | 69 | 89 | 15
ubuntu-20.04 | true |  | true |  | true | 73 | 93 | 111
ubuntu-20.04 | true |  | true | true |  | 74 | 94 | 20
ubuntu-20.04 | true |  | true | true | true | 78 | 98 | 56
ubuntu-20.04 | true | true |  |  |  | 71 | 91 | 182
ubuntu-20.04 | true | true |  |  | true | 74 | 94 | 21
ubuntu-20.04 | true | true |  | true |  | 76 | 96 | 65
ubuntu-20.04 | true | true |  | true | true | 79 | 99 | 111
ubuntu-20.04 | true | true | true |  |  | 71 | 91 | 88
ubuntu-20.04 | true | true | true |  | true | 74 | 94 | 23
ubuntu-20.04 | true | true | true | true |  | 76 | 96 | 66
ubuntu-20.04 | true | true | true | true | true | 79 | 99 | 122
ubuntu-22.04 |  |  |  |  |  | 62 | 83 | 2
ubuntu-22.04 |  |  |  |  | true | 66 | 87 | 53
ubuntu-22.04 |  |  |  | true |  | 67 | 88 | 4
ubuntu-22.04 |  |  |  | true | true | 71 | 92 | 8
ubuntu-22.04 |  |  | true |  |  | 62 | 83 | 2
ubuntu-22.04 |  |  | true |  | true | 66 | 87 | 22
ubuntu-22.04 |  |  | true | true |  | 67 | 88 | 3
ubuntu-22.04 |  |  | true | true | true | 71 | 92 | 58
ubuntu-22.04 |  | true |  |  |  | 64 | 85 | 4
ubuntu-22.04 |  | true |  |  | true | 67 | 88 | 10
ubuntu-22.04 |  | true |  | true |  | 69 | 90 | 5
ubuntu-22.04 |  | true |  | true | true | 72 | 93 | 58
ubuntu-22.04 |  | true | true |  |  | 64 | 85 | 3
ubuntu-22.04 |  | true | true |  | true | 67 | 88 | 10
ubuntu-22.04 |  | true | true | true |  | 69 | 90 | 4
ubuntu-22.04 |  | true | true | true | true | 72 | 93 | 8
ubuntu-22.04 | true |  |  |  |  | 70 | 91 | 11
ubuntu-22.04 | true |  |  |  | true | 73 | 94 | 16
ubuntu-22.04 | true |  |  | true |  | 75 | 96 | 17
ubuntu-22.04 | true |  |  | true | true | 78 | 99 | 22
ubuntu-22.04 | true |  | true |  |  | 70 | 91 | 15
ubuntu-22.04 | true |  | true |  | true | 73 | 94 | 318
ubuntu-22.04 | true |  | true | true |  | 75 | 96 | 116
ubuntu-22.04 | true |  | true | true | true | 78 | 99 | 22
ubuntu-22.04 | true | true |  |  |  | 71 | 92 | 98
ubuntu-22.04 | true | true |  |  | true | 75 | 96 | 130
ubuntu-22.04 | true | true |  | true |  | 76 | 97 | 101
ubuntu-22.04 | true | true |  | true | true | 80 | 101 | 25
ubuntu-22.04 | true | true | true |  |  | 71 | 92 | 83
ubuntu-22.04 | true | true | true |  | true | 75 | 96 | 17
ubuntu-22.04 | true | true | true | true |  | 76 | 97 | 81
ubuntu-22.04 | true | true | true | true | true | 80 | 101 | 22
