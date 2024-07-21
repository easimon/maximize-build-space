# Maximize available disk space for build tasks

If the available disk space on Github runners is too little for your build job, this action might be for you.
If not: please go on, there's nothing to see here.

This table shows the amount of free space you receive when using the action with the various options.

OS | Android SDKs removed | .NET SDKs removed | Haskell removed | CodeQL Removed | Cached Docker Images Removed | GB freed | GB free | Elapsed Time (seconds) |
---|:--------------------:|:-----------------:|:---------------:|:--------------:|:----------------------------:|:--------:|:-------:|:----------------------:|
ubuntu-20.04 |  |  |  |  |  | 62 | 82 | 2
ubuntu-20.04 |  |  |  |  | true | 65 | 85 | 21
ubuntu-20.04 |  |  |  | true |  | 67 | 87 | 4
ubuntu-20.04 |  |  |  | true | true | 70 | 90 | 26
ubuntu-20.04 |  |  | true |  |  | 62 | 82 | 2
ubuntu-20.04 |  |  | true |  | true | 65 | 85 | 22
ubuntu-20.04 |  |  | true | true |  | 67 | 87 | 5
ubuntu-20.04 |  |  | true | true | true | 70 | 90 | 30
ubuntu-20.04 |  | true |  |  |  | 64 | 84 | 4
ubuntu-20.04 |  | true |  |  | true | 67 | 87 | 34
ubuntu-20.04 |  | true |  | true |  | 69 | 89 | 5
ubuntu-20.04 |  | true |  | true | true | 72 | 92 | 8
ubuntu-20.04 |  | true | true |  |  | 64 | 84 | 6
ubuntu-20.04 |  | true | true |  | true | 67 | 87 | 21
ubuntu-20.04 |  | true | true | true |  | 69 | 89 | 6
ubuntu-20.04 |  | true | true | true | true | 72 | 92 | 53
ubuntu-20.04 | true |  |  |  |  | 71 | 91 | 46
ubuntu-20.04 | true |  |  |  | true | 74 | 94 | 62
ubuntu-20.04 | true |  |  | true |  | 76 | 96 | 14
ubuntu-20.04 | true |  |  | true | true | 79 | 99 | 44
ubuntu-20.04 | true |  | true |  |  | 71 | 91 | 10
ubuntu-20.04 | true |  | true |  | true | 74 | 94 | 69
ubuntu-20.04 | true |  | true | true |  | 76 | 96 | 12
ubuntu-20.04 | true |  | true | true | true | 79 | 99 | 100
ubuntu-20.04 | true | true |  |  |  | 73 | 93 | 69
ubuntu-20.04 | true | true |  |  | true | 76 | 96 | 45
ubuntu-20.04 | true | true |  | true |  | 78 | 98 | 15
ubuntu-20.04 | true | true |  | true | true | 81 | 101 | 34
ubuntu-20.04 | true | true | true |  |  | 73 | 93 | 59
ubuntu-20.04 | true | true | true |  | true | 76 | 96 | 87
ubuntu-20.04 | true | true | true | true |  | 78 | 98 | 15
ubuntu-20.04 | true | true | true | true | true | 81 | 101 | 84
ubuntu-22.04 |  |  |  |  |  | 63 | 84 | 2
ubuntu-22.04 |  |  |  |  | true | 66 | 87 | 31
ubuntu-22.04 |  |  |  | true |  | 67 | 88 | 4
ubuntu-22.04 |  |  |  | true | true | 71 | 92 | 27
ubuntu-22.04 |  |  | true |  |  | 63 | 84 | 2
ubuntu-22.04 |  |  | true |  | true | 66 | 87 | 29
ubuntu-22.04 |  |  | true | true |  | 68 | 89 | 4
ubuntu-22.04 |  |  | true | true | true | 71 | 92 | 30
ubuntu-22.04 |  | true |  |  |  | 64 | 85 | 4
ubuntu-22.04 |  | true |  |  | true | 67 | 88 | 23
ubuntu-22.04 |  | true |  | true |  | 69 | 90 | 5
ubuntu-22.04 |  | true |  | true | true | 72 | 93 | 36
ubuntu-22.04 |  | true | true |  |  | 64 | 85 | 5
ubuntu-22.04 |  | true | true |  | true | 67 | 88 | 29
ubuntu-22.04 |  | true | true | true |  | 69 | 90 | 5
ubuntu-22.04 |  | true | true | true | true | 72 | 93 | 7
ubuntu-22.04 | true |  |  |  |  | 72 | 93 | 79
ubuntu-22.04 | true |  |  |  | true | 75 | 96 | 20
ubuntu-22.04 | true |  |  | true |  | 76 | 97 | 67
ubuntu-22.04 | true |  |  | true | true | 80 | 101 | 14
ubuntu-22.04 | true |  | true |  |  | 72 | 93 | 63
ubuntu-22.04 | true |  | true |  | true | 75 | 96 | 152
ubuntu-22.04 | true |  | true | true |  | 76 | 97 | 60
ubuntu-22.04 | true |  | true | true | true | 80 | 101 | 69
ubuntu-22.04 | true | true |  |  |  | 73 | 94 | 71
ubuntu-22.04 | true | true |  |  | true | 76 | 97 | 96
ubuntu-22.04 | true | true |  | true |  | 78 | 99 | 114
ubuntu-22.04 | true | true |  | true | true | 81 | 102 | 107
ubuntu-22.04 | true | true | true |  |  | 73 | 94 | 63
ubuntu-22.04 | true | true | true |  | true | 76 | 97 | 14
ubuntu-22.04 | true | true | true | true |  | 78 | 99 | 58
ubuntu-22.04 | true | true | true | true | true | 81 | 102 | 76
