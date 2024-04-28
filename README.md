# Maximize available disk space for build tasks

If the available disk space on Github runners is too little for your build job, this action might be for you.
If not: please go on, there's nothing to see here.

This table shows the amount of free space you receive when using the action with the various options.

OS | Android SDKs removed | .NET SDKs removed | Haskell removed | CodeQL Removed | Cached Docker Images Removed | GB freed | GB free | Elapsed Time (seconds) |
---|:--------------------:|:-----------------:|:---------------:|:--------------:|:----------------------------:|:--------:|:-------:|:----------------------:|
ubuntu-20.04 |  |  |  |  |  | 63 | 83 | 4
ubuntu-20.04 |  |  |  |  | true | 66 | 86 | 44
ubuntu-20.04 |  |  |  | true |  | 68 | 88 | 2
ubuntu-20.04 |  |  |  | true | true | 71 | 91 | 61
ubuntu-20.04 |  |  | true |  |  | 63 | 83 | 2
ubuntu-20.04 |  |  | true |  | true | 66 | 86 | 47
ubuntu-20.04 |  |  | true | true |  | 68 | 88 | 3
ubuntu-20.04 |  |  | true | true | true | 71 | 91 | 7
ubuntu-20.04 |  | true |  |  |  | 64 | 84 | 3
ubuntu-20.04 |  | true |  |  | true | 67 | 87 | 31
ubuntu-20.04 |  | true |  | true |  | 69 | 89 | 4
ubuntu-20.04 |  | true |  | true | true | 72 | 92 | 52
ubuntu-20.04 |  | true | true |  |  | 64 | 84 | 3
ubuntu-20.04 |  | true | true |  | true | 67 | 87 | 5
ubuntu-20.04 |  | true | true | true |  | 69 | 89 | 5
ubuntu-20.04 |  | true | true | true | true | 72 | 92 | 7
ubuntu-20.04 | true |  |  |  |  | 71 | 91 | 8
ubuntu-20.04 | true |  |  |  | true | 75 | 95 | 67
ubuntu-20.04 | true |  |  | true |  | 76 | 96 | 43
ubuntu-20.04 | true |  |  | true | true | 79 | 99 | 12
ubuntu-20.04 | true |  | true |  |  | 71 | 91 | 41
ubuntu-20.04 | true |  | true |  | true | 75 | 95 | 88
ubuntu-20.04 | true |  | true | true |  | 76 | 96 | 45
ubuntu-20.04 | true |  | true | true | true | 79 | 99 | 17
ubuntu-20.04 | true | true |  |  |  | 73 | 93 | 38
ubuntu-20.04 | true | true |  |  | true | 76 | 96 | 83
ubuntu-20.04 | true | true |  | true |  | 78 | 98 | 40
ubuntu-20.04 | true | true |  | true | true | 81 | 101 | 93
ubuntu-20.04 | true | true | true |  |  | 73 | 93 | 43
ubuntu-20.04 | true | true | true |  | true | 76 | 96 | 74
ubuntu-20.04 | true | true | true | true |  | 78 | 98 | 12
ubuntu-20.04 | true | true | true | true | true | 81 | 101 | 89
ubuntu-22.04 |  |  |  |  |  | 62 | 83 | 1
ubuntu-22.04 |  |  |  |  | true | 66 | 87 | 24
ubuntu-22.04 |  |  |  | true |  | 67 | 88 | 4
ubuntu-22.04 |  |  |  | true | true | 71 | 92 | 8
ubuntu-22.04 |  |  | true |  |  | 62 | 83 | 1
ubuntu-22.04 |  |  | true |  | true | 66 | 87 | 31
ubuntu-22.04 |  |  | true | true |  | 67 | 88 | 4
ubuntu-22.04 |  |  | true | true | true | 71 | 92 | 34
ubuntu-22.04 |  | true |  |  |  | 64 | 85 | 4
ubuntu-22.04 |  | true |  |  | true | 67 | 88 | 9
ubuntu-22.04 |  | true |  | true |  | 69 | 90 | 6
ubuntu-22.04 |  | true |  | true | true | 72 | 93 | 9
ubuntu-22.04 |  | true | true |  |  | 64 | 85 | 3
ubuntu-22.04 |  | true | true |  | true | 67 | 88 | 29
ubuntu-22.04 |  | true | true | true |  | 69 | 90 | 6
ubuntu-22.04 |  | true | true | true | true | 72 | 93 | 28
ubuntu-22.04 | true |  |  |  |  | 71 | 92 | 11
ubuntu-22.04 | true |  |  |  | true | 74 | 95 | 18
ubuntu-22.04 | true |  |  | true |  | 76 | 97 | 11
ubuntu-22.04 | true |  |  | true | true | 79 | 100 | 20
ubuntu-22.04 | true |  | true |  |  | 71 | 92 | 69
ubuntu-22.04 | true |  | true |  | true | 74 | 95 | 17
ubuntu-22.04 | true |  | true | true |  | 76 | 97 | 75
ubuntu-22.04 | true |  | true | true | true | 79 | 100 | 104
ubuntu-22.04 | true | true |  |  |  | 73 | 94 | 11
ubuntu-22.04 | true | true |  |  | true | 76 | 97 | 104
ubuntu-22.04 | true | true |  | true |  | 78 | 99 | 12
ubuntu-22.04 | true | true |  | true | true | 81 | 102 | 19
ubuntu-22.04 | true | true | true |  |  | 73 | 94 | 13
ubuntu-22.04 | true | true | true |  | true | 76 | 97 | 113
ubuntu-22.04 | true | true | true | true |  | 78 | 99 | 11
ubuntu-22.04 | true | true | true | true | true | 81 | 102 | 16
