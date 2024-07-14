# Maximize available disk space for build tasks

If the available disk space on Github runners is too little for your build job, this action might be for you.
If not: please go on, there's nothing to see here.

This table shows the amount of free space you receive when using the action with the various options.

OS | Android SDKs removed | .NET SDKs removed | Haskell removed | CodeQL Removed | Cached Docker Images Removed | GB freed | GB free | Elapsed Time (seconds) |
---|:--------------------:|:-----------------:|:---------------:|:--------------:|:----------------------------:|:--------:|:-------:|:----------------------:|
ubuntu-20.04 |  |  |  |  |  | 62 | 82 | 2
ubuntu-20.04 |  |  |  |  | true | 65 | 85 | 47
ubuntu-20.04 |  |  |  | true |  | 67 | 87 | 3
ubuntu-20.04 |  |  |  | true | true | 70 | 90 | 38
ubuntu-20.04 |  |  | true |  |  | 62 | 82 | 2
ubuntu-20.04 |  |  | true |  | true | 65 | 85 | 30
ubuntu-20.04 |  |  | true | true |  | 67 | 87 | 3
ubuntu-20.04 |  |  | true | true | true | 70 | 90 | 38
ubuntu-20.04 |  | true |  |  |  | 64 | 84 | 4
ubuntu-20.04 |  | true |  |  | true | 67 | 87 | 8
ubuntu-20.04 |  | true |  | true |  | 69 | 89 | 4
ubuntu-20.04 |  | true |  | true | true | 72 | 92 | 55
ubuntu-20.04 |  | true | true |  |  | 64 | 84 | 3
ubuntu-20.04 |  | true | true |  | true | 67 | 87 | 8
ubuntu-20.04 |  | true | true | true |  | 69 | 89 | 4
ubuntu-20.04 |  | true | true | true | true | 72 | 92 | 67
ubuntu-20.04 | true |  |  |  |  | 71 | 91 | 58
ubuntu-20.04 | true |  |  |  | true | 74 | 94 | 106
ubuntu-20.04 | true |  |  | true |  | 76 | 96 | 65
ubuntu-20.04 | true |  |  | true | true | 79 | 99 | 95
ubuntu-20.04 | true |  | true |  |  | 71 | 91 | 53
ubuntu-20.04 | true |  | true |  | true | 74 | 94 | 57
ubuntu-20.04 | true |  | true | true |  | 76 | 96 | 65
ubuntu-20.04 | true |  | true | true | true | 79 | 99 | 19
ubuntu-20.04 | true | true |  |  |  | 73 | 93 | 15
ubuntu-20.04 | true | true |  |  | true | 76 | 96 | 93
ubuntu-20.04 | true | true |  | true |  | 78 | 98 | 12
ubuntu-20.04 | true | true |  | true | true | 81 | 101 | 96
ubuntu-20.04 | true | true | true |  |  | 73 | 93 | 13
ubuntu-20.04 | true | true | true |  | true | 76 | 96 | 185
ubuntu-20.04 | true | true | true | true |  | 78 | 98 | 90
ubuntu-20.04 | true | true | true | true | true | 81 | 101 | 100
ubuntu-22.04 |  |  |  |  |  | 63 | 84 | 1
ubuntu-22.04 |  |  |  |  | true | 66 | 87 | 17
ubuntu-22.04 |  |  |  | true |  | 67 | 88 | 4
ubuntu-22.04 |  |  |  | true | true | 71 | 92 | 28
ubuntu-22.04 |  |  | true |  |  | 63 | 84 | 2
ubuntu-22.04 |  |  | true |  | true | 66 | 87 | 8
ubuntu-22.04 |  |  | true | true |  | 67 | 88 | 3
ubuntu-22.04 |  |  | true | true | true | 71 | 92 | 28
ubuntu-22.04 |  | true |  |  |  | 64 | 85 | 4
ubuntu-22.04 |  | true |  |  | true | 67 | 88 | 8
ubuntu-22.04 |  | true |  | true |  | 69 | 90 | 6
ubuntu-22.04 |  | true |  | true | true | 72 | 93 | 9
ubuntu-22.04 |  | true | true |  |  | 64 | 85 | 3
ubuntu-22.04 |  | true | true |  | true | 67 | 88 | 7
ubuntu-22.04 |  | true | true | true |  | 69 | 90 | 5
ubuntu-22.04 |  | true | true | true | true | 72 | 93 | 12
ubuntu-22.04 | true |  |  |  |  | 72 | 93 | 43
ubuntu-22.04 | true |  |  |  | true | 75 | 96 | 17
ubuntu-22.04 | true |  |  | true |  | 76 | 97 | 12
ubuntu-22.04 | true |  |  | true | true | 80 | 101 | 15
ubuntu-22.04 | true |  | true |  |  | 72 | 93 | 12
ubuntu-22.04 | true |  | true |  | true | 75 | 96 | 15
ubuntu-22.04 | true |  | true | true |  | 76 | 97 | 60
ubuntu-22.04 | true |  | true | true | true | 80 | 101 | 58
ubuntu-22.04 | true | true |  |  |  | 73 | 94 | 47
ubuntu-22.04 | true | true |  |  | true | 76 | 97 | 76
ubuntu-22.04 | true | true |  | true |  | 78 | 99 | 51
ubuntu-22.04 | true | true |  | true | true | 81 | 102 | 17
ubuntu-22.04 | true | true | true |  |  | 73 | 94 | 16
ubuntu-22.04 | true | true | true |  | true | 76 | 97 | 69
ubuntu-22.04 | true | true | true | true |  | 78 | 99 | 16
ubuntu-22.04 | true | true | true | true | true | 81 | 102 | 92
