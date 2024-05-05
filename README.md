# Maximize available disk space for build tasks

If the available disk space on Github runners is too little for your build job, this action might be for you.
If not: please go on, there's nothing to see here.

This table shows the amount of free space you receive when using the action with the various options.

OS | Android SDKs removed | .NET SDKs removed | Haskell removed | CodeQL Removed | Cached Docker Images Removed | GB freed | GB free | Elapsed Time (seconds) |
---|:--------------------:|:-----------------:|:---------------:|:--------------:|:----------------------------:|:--------:|:-------:|:----------------------:|
ubuntu-20.04 |  |  |  |  |  | 63 | 83 | 2
ubuntu-20.04 |  |  |  |  | true | 66 | 86 | 46
ubuntu-20.04 |  |  |  | true |  | 68 | 88 | 3
ubuntu-20.04 |  |  |  | true | true | 71 | 91 | 5
ubuntu-20.04 |  |  | true |  |  | 63 | 83 | 2
ubuntu-20.04 |  |  | true |  | true | 66 | 86 | 4
ubuntu-20.04 |  |  | true | true |  | 68 | 88 | 5
ubuntu-20.04 |  |  | true | true | true | 71 | 91 | 6
ubuntu-20.04 |  | true |  |  |  | 64 | 84 | 3
ubuntu-20.04 |  | true |  |  | true | 67 | 87 | 30
ubuntu-20.04 |  | true |  | true |  | 69 | 89 | 4
ubuntu-20.04 |  | true |  | true | true | 72 | 92 | 7
ubuntu-20.04 |  | true | true |  |  | 64 | 84 | 4
ubuntu-20.04 |  | true | true |  | true | 67 | 87 | 6
ubuntu-20.04 |  | true | true | true |  | 69 | 89 | 5
ubuntu-20.04 |  | true | true | true | true | 72 | 92 | 51
ubuntu-20.04 | true |  |  |  |  | 71 | 91 | 9
ubuntu-20.04 | true |  |  |  | true | 75 | 95 | 81
ubuntu-20.04 | true |  |  | true |  | 76 | 96 | 40
ubuntu-20.04 | true |  |  | true | true | 79 | 99 | 90
ubuntu-20.04 | true |  | true |  |  | 71 | 91 | 40
ubuntu-20.04 | true |  | true |  | true | 75 | 95 | 55
ubuntu-20.04 | true |  | true | true |  | 76 | 96 | 45
ubuntu-20.04 | true |  | true | true | true | 79 | 99 | 91
ubuntu-20.04 | true | true |  |  |  | 73 | 93 | 9
ubuntu-20.04 | true | true |  |  | true | 76 | 96 | 49
ubuntu-20.04 | true | true |  | true |  | 78 | 98 | 45
ubuntu-20.04 | true | true |  | true | true | 81 | 101 | 14
ubuntu-20.04 | true | true | true |  |  | 73 | 93 | 7
ubuntu-20.04 | true | true | true |  | true | 76 | 96 | 102
ubuntu-20.04 | true | true | true | true |  | 78 | 98 | 53
ubuntu-20.04 | true | true | true | true | true | 81 | 101 | 101
ubuntu-22.04 |  |  |  |  |  | 62 | 83 | 2
ubuntu-22.04 |  |  |  |  | true | 66 | 87 | 10
ubuntu-22.04 |  |  |  | true |  | 67 | 88 | 3
ubuntu-22.04 |  |  |  | true | true | 71 | 92 | 8
ubuntu-22.04 |  |  | true |  |  | 62 | 83 | 2
ubuntu-22.04 |  |  | true |  | true | 66 | 87 | 6
ubuntu-22.04 |  |  | true | true |  | 67 | 88 | 4
ubuntu-22.04 |  |  | true | true | true | 71 | 92 | 8
ubuntu-22.04 |  | true |  |  |  | 64 | 85 | 4
ubuntu-22.04 |  | true |  |  | true | 67 | 88 | 43
ubuntu-22.04 |  | true |  | true |  | 69 | 90 | 5
ubuntu-22.04 |  | true |  | true | true | 72 | 93 | 43
ubuntu-22.04 |  | true | true |  |  | 64 | 85 | 4
ubuntu-22.04 |  | true | true |  | true | 67 | 88 | 26
ubuntu-22.04 |  | true | true | true |  | 69 | 90 | 5
ubuntu-22.04 |  | true | true | true | true | 72 | 93 | 8
ubuntu-22.04 | true |  |  |  |  | 71 | 92 | 10
ubuntu-22.04 | true |  |  |  | true | 74 | 95 | 78
ubuntu-22.04 | true |  |  | true |  | 76 | 97 | 12
ubuntu-22.04 | true |  |  | true | true | 79 | 100 | 79
ubuntu-22.04 | true |  | true |  |  | 71 | 92 | 71
ubuntu-22.04 | true |  | true |  | true | 74 | 95 | 46
ubuntu-22.04 | true |  | true | true |  | 76 | 97 | 12
ubuntu-22.04 | true |  | true | true | true | 79 | 100 | 94
ubuntu-22.04 | true | true |  |  |  | 73 | 94 | 61
ubuntu-22.04 | true | true |  |  | true | 76 | 97 | 64
ubuntu-22.04 | true | true |  | true |  | 78 | 99 | 11
ubuntu-22.04 | true | true |  | true | true | 81 | 102 | 15
ubuntu-22.04 | true | true | true |  |  | 73 | 94 | 12
ubuntu-22.04 | true | true | true |  | true | 76 | 97 | 14
ubuntu-22.04 | true | true | true | true |  | 78 | 99 | 12
ubuntu-22.04 | true | true | true | true | true | 81 | 102 | 15
