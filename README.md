# Maximize available disk space for build tasks

If the available disk space on Github runners is too little for your build job, this action might be for you.
If not: please go on, there's nothing to see here.

This table shows the amount of free space you receive when using the action with the various options.

OS | Android SDKs removed | .NET SDKs removed | Haskell removed | CodeQL Removed | Cached Docker Images Removed | GB freed | GB free | Elapsed Time (seconds) |
---|:--------------------:|:-----------------:|:---------------:|:--------------:|:----------------------------:|:--------:|:-------:|:----------------------:|
ubuntu-20.04 |  |  |  |  |  | 62 | 83 | 3
ubuntu-20.04 |  |  |  |  | true | 65 | 86 | 7
ubuntu-20.04 |  |  |  | true |  | 67 | 88 | 4
ubuntu-20.04 |  |  |  | true | true | 69 | 90 | 16
ubuntu-20.04 |  |  | true |  |  | 62 | 83 | 2
ubuntu-20.04 |  |  | true |  | true | 65 | 86 | 8
ubuntu-20.04 |  |  | true | true |  | 67 | 88 | 4
ubuntu-20.04 |  |  | true | true | true | 69 | 90 | 8
ubuntu-20.04 |  | true |  |  |  | 63 | 84 | 4
ubuntu-20.04 |  | true |  |  | true | 66 | 87 | 12
ubuntu-20.04 |  | true |  | true |  | 68 | 89 | 7
ubuntu-20.04 |  | true |  | true | true | 70 | 91 | 14
ubuntu-20.04 |  | true | true |  |  | 63 | 84 | 4
ubuntu-20.04 |  | true | true |  | true | 66 | 87 | 6
ubuntu-20.04 |  | true | true | true |  | 68 | 89 | 5
ubuntu-20.04 |  | true | true | true | true | 70 | 91 | 9
ubuntu-20.04 | true |  |  |  |  | 70 | 91 | 76
ubuntu-20.04 | true |  |  |  | true | 72 | 93 | 17
ubuntu-20.04 | true |  |  | true |  | 75 | 96 | 72
ubuntu-20.04 | true |  |  | true | true | 77 | 98 | 94
ubuntu-20.04 | true |  | true |  |  | 70 | 91 | 17
ubuntu-20.04 | true |  | true |  | true | 72 | 93 | 73
ubuntu-20.04 | true |  | true | true |  | 75 | 96 | 20
ubuntu-20.04 | true |  | true | true | true | 77 | 98 | 78
ubuntu-20.04 | true | true |  |  |  | 71 | 92 | 94
ubuntu-20.04 | true | true |  |  | true | 73 | 94 | 74
ubuntu-20.04 | true | true |  | true |  | 76 | 97 | 16
ubuntu-20.04 | true | true |  | true | true | 78 | 99 | 73
ubuntu-20.04 | true | true | true |  |  | 71 | 92 | 89
ubuntu-20.04 | true | true | true |  | true | 73 | 94 | 89
ubuntu-20.04 | true | true | true | true |  | 76 | 97 | 22
ubuntu-20.04 | true | true | true | true | true | 78 | 99 | 112
ubuntu-22.04 |  |  |  |  |  | 62 | 84 | 1
ubuntu-22.04 |  |  |  |  | true | 65 | 87 | 23
ubuntu-22.04 |  |  |  | true |  | 67 | 89 | 4
ubuntu-22.04 |  |  |  | true | true | 70 | 92 | 7
ubuntu-22.04 |  |  | true |  |  | 62 | 84 | 2
ubuntu-22.04 |  |  | true |  | true | 65 | 87 | 6
ubuntu-22.04 |  |  | true | true |  | 67 | 89 | 4
ubuntu-22.04 |  |  | true | true | true | 70 | 92 | 6
ubuntu-22.04 |  | true |  |  |  | 63 | 85 | 5
ubuntu-22.04 |  | true |  |  | true | 66 | 88 | 7
ubuntu-22.04 |  | true |  | true |  | 68 | 90 | 4
ubuntu-22.04 |  | true |  | true | true | 71 | 93 | 26
ubuntu-22.04 |  | true | true |  |  | 63 | 85 | 7
ubuntu-22.04 |  | true | true |  | true | 66 | 88 | 8
ubuntu-22.04 |  | true | true | true |  | 68 | 90 | 4
ubuntu-22.04 |  | true | true | true | true | 71 | 93 | 7
ubuntu-22.04 | true |  |  |  |  | 70 | 92 | 15
ubuntu-22.04 | true |  |  |  | true | 73 | 95 | 22
ubuntu-22.04 | true |  |  | true |  | 75 | 97 | 17
ubuntu-22.04 | true |  |  | true | true | 77 | 99 | 20
ubuntu-22.04 | true |  | true |  |  | 70 | 92 | 61
ubuntu-22.04 | true |  | true |  | true | 73 | 95 | 19
ubuntu-22.04 | true |  | true | true |  | 75 | 97 | 19
ubuntu-22.04 | true |  | true | true | true | 77 | 99 | 20
ubuntu-22.04 | true | true |  |  |  | 71 | 93 | 17
ubuntu-22.04 | true | true |  |  | true | 74 | 96 | 21
ubuntu-22.04 | true | true |  | true |  | 76 | 98 | 89
ubuntu-22.04 | true | true |  | true | true | 78 | 100 | 126
ubuntu-22.04 | true | true | true |  |  | 71 | 93 | 13
ubuntu-22.04 | true | true | true |  | true | 74 | 96 | 23
ubuntu-22.04 | true | true | true | true |  | 76 | 98 | 17
ubuntu-22.04 | true | true | true | true | true | 78 | 100 | 17
