# Maximize available disk space for build tasks

If the available disk space on Github runners is too little for your build job, this action might be for you.
If not: please go on, there's nothing to see here.

This table shows the amount of free space you receive when using the action with the various options.

OS | Android SDKs removed | .NET SDKs removed | Haskell removed | CodeQL Removed | Cached Docker Images Removed | GB freed | GB free | Elapsed Time (seconds) |
---|:--------------------:|:-----------------:|:---------------:|:--------------:|:----------------------------:|:--------:|:-------:|:----------------------:|
ubuntu-20.04 |  |  |  |  |  | 63 | 83 | 2
ubuntu-20.04 |  |  |  |  | true | 66 | 86 | 7
ubuntu-20.04 |  |  |  | true |  | 68 | 88 | 3
ubuntu-20.04 |  |  |  | true | true | 71 | 91 | 47
ubuntu-20.04 |  |  | true |  |  | 63 | 83 | 2
ubuntu-20.04 |  |  | true |  | true | 66 | 86 | 5
ubuntu-20.04 |  |  | true | true |  | 68 | 88 | 3
ubuntu-20.04 |  |  | true | true | true | 71 | 91 | 6
ubuntu-20.04 |  | true |  |  |  | 64 | 84 | 3
ubuntu-20.04 |  | true |  |  | true | 67 | 87 | 7
ubuntu-20.04 |  | true |  | true |  | 69 | 89 | 3
ubuntu-20.04 |  | true |  | true | true | 72 | 92 | 8
ubuntu-20.04 |  | true | true |  |  | 64 | 84 | 2
ubuntu-20.04 |  | true | true |  | true | 67 | 87 | 25
ubuntu-20.04 |  | true | true | true |  | 69 | 89 | 4
ubuntu-20.04 |  | true | true | true | true | 72 | 92 | 7
ubuntu-20.04 | true |  |  |  |  | 71 | 91 | 41
ubuntu-20.04 | true |  |  |  | true | 75 | 95 | 58
ubuntu-20.04 | true |  |  | true |  | 76 | 96 | 43
ubuntu-20.04 | true |  |  | true | true | 79 | 99 | 12
ubuntu-20.04 | true |  | true |  |  | 71 | 91 | 7
ubuntu-20.04 | true |  | true |  | true | 75 | 95 | 8
ubuntu-20.04 | true |  | true | true |  | 76 | 96 | 9
ubuntu-20.04 | true |  | true | true | true | 79 | 99 | 50
ubuntu-20.04 | true | true |  |  |  | 73 | 93 | 53
ubuntu-20.04 | true | true |  |  | true | 76 | 96 | 74
ubuntu-20.04 | true | true |  | true |  | 78 | 98 | 43
ubuntu-20.04 | true | true |  | true | true | 81 | 101 | 88
ubuntu-20.04 | true | true | true |  |  | 73 | 93 | 41
ubuntu-20.04 | true | true | true |  | true | 76 | 96 | 93
ubuntu-20.04 | true | true | true | true |  | 78 | 98 | 33
ubuntu-20.04 | true | true | true | true | true | 81 | 101 | 55
ubuntu-22.04 |  |  |  |  |  | 62 | 83 | 1
ubuntu-22.04 |  |  |  |  | true | 66 | 87 | 8
ubuntu-22.04 |  |  |  | true |  | 67 | 88 | 3
ubuntu-22.04 |  |  |  | true | true | 71 | 92 | 38
ubuntu-22.04 |  |  | true |  |  | 62 | 83 | 2
ubuntu-22.04 |  |  | true |  | true | 66 | 87 | 6
ubuntu-22.04 |  |  | true | true |  | 67 | 88 | 4
ubuntu-22.04 |  |  | true | true | true | 71 | 92 | 7
ubuntu-22.04 |  | true |  |  |  | 64 | 85 | 4
ubuntu-22.04 |  | true |  |  | true | 67 | 88 | 7
ubuntu-22.04 |  | true |  | true |  | 69 | 90 | 4
ubuntu-22.04 |  | true |  | true | true | 72 | 93 | 9
ubuntu-22.04 |  | true | true |  |  | 64 | 85 | 3
ubuntu-22.04 |  | true | true |  | true | 67 | 88 | 39
ubuntu-22.04 |  | true | true | true |  | 69 | 90 | 6
ubuntu-22.04 |  | true | true | true | true | 72 | 93 | 41
ubuntu-22.04 | true |  |  |  |  | 71 | 92 | 12
ubuntu-22.04 | true |  |  |  | true | 74 | 95 | 78
ubuntu-22.04 | true |  |  | true |  | 76 | 97 | 13
ubuntu-22.04 | true |  |  | true | true | 79 | 100 | 20
ubuntu-22.04 | true |  | true |  |  | 71 | 92 | 66
ubuntu-22.04 | true |  | true |  | true | 74 | 95 | 17
ubuntu-22.04 | true |  | true | true |  | 76 | 97 | 63
ubuntu-22.04 | true |  | true | true | true | 79 | 100 | 17
ubuntu-22.04 | true | true |  |  |  | 73 | 94 | 9
ubuntu-22.04 | true | true |  |  | true | 76 | 97 | 98
ubuntu-22.04 | true | true |  | true |  | 78 | 99 | 13
ubuntu-22.04 | true | true |  | true | true | 81 | 102 | 18
ubuntu-22.04 | true | true | true |  |  | 73 | 94 | 12
ubuntu-22.04 | true | true | true |  | true | 76 | 97 | 90
ubuntu-22.04 | true | true | true | true |  | 78 | 99 | 65
ubuntu-22.04 | true | true | true | true | true | 81 | 102 | 19
