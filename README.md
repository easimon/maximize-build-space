# Maximize available disk space for build tasks

If the available disk space on Github runners is too little for your build job, this action might be for you.
If not: please go on, there's nothing to see here.

This table shows the amount of free space you receive when using the action with the various options.

OS | Android SDKs removed | .NET SDKs removed | Haskell removed | CodeQL Removed | Cached Docker Images Removed | GB freed | GB free | Elapsed Time (seconds) |
---|:--------------------:|:-----------------:|:---------------:|:--------------:|:----------------------------:|:--------:|:-------:|:----------------------:|
ubuntu-20.04 |  |  |  |  |  | 63 | 83 | 2
ubuntu-20.04 |  |  |  |  | true | 66 | 86 | 126
ubuntu-20.04 |  |  |  | true |  | 68 | 88 | 3
ubuntu-20.04 |  |  |  | true | true | 71 | 91 | 133
ubuntu-20.04 |  |  | true |  |  | 63 | 83 | 2
ubuntu-20.04 |  |  | true |  | true | 66 | 86 | 36
ubuntu-20.04 |  |  | true | true |  | 68 | 88 | 3
ubuntu-20.04 |  |  | true | true | true | 71 | 91 | 34
ubuntu-20.04 |  | true |  |  |  | 64 | 84 | 3
ubuntu-20.04 |  | true |  |  | true | 67 | 87 | 29
ubuntu-20.04 |  | true |  | true |  | 69 | 89 | 3
ubuntu-20.04 |  | true |  | true | true | 72 | 92 | 71
ubuntu-20.04 |  | true | true |  |  | 64 | 84 | 3
ubuntu-20.04 |  | true | true |  | true | 67 | 87 | 32
ubuntu-20.04 |  | true | true | true |  | 69 | 89 | 5
ubuntu-20.04 |  | true | true | true | true | 72 | 92 | 37
ubuntu-20.04 | true |  |  |  |  | 71 | 91 | 71
ubuntu-20.04 | true |  |  |  | true | 75 | 95 | 17
ubuntu-20.04 | true |  |  | true |  | 76 | 96 | 54
ubuntu-20.04 | true |  |  | true | true | 80 | 100 | 100
ubuntu-20.04 | true |  | true |  |  | 71 | 91 | 59
ubuntu-20.04 | true |  | true |  | true | 75 | 95 | 12
ubuntu-20.04 | true |  | true | true |  | 76 | 96 | 61
ubuntu-20.04 | true |  | true | true | true | 80 | 100 | 74
ubuntu-20.04 | true | true |  |  |  | 73 | 93 | 8
ubuntu-20.04 | true | true |  |  | true | 76 | 96 | 94
ubuntu-20.04 | true | true |  | true |  | 78 | 98 | 54
ubuntu-20.04 | true | true |  | true | true | 81 | 101 | 132
ubuntu-20.04 | true | true | true |  |  | 73 | 93 | 46
ubuntu-20.04 | true | true | true |  | true | 76 | 96 | 81
ubuntu-20.04 | true | true | true | true |  | 78 | 98 | 68
ubuntu-20.04 | true | true | true | true | true | 81 | 101 | 33
ubuntu-22.04 |  |  |  |  |  | 63 | 84 | 2
ubuntu-22.04 |  |  |  |  | true | 66 | 87 | 6
ubuntu-22.04 |  |  |  | true |  | 68 | 89 | 3
ubuntu-22.04 |  |  |  | true | true | 71 | 92 | 32
ubuntu-22.04 |  |  | true |  |  | 63 | 84 | 3
ubuntu-22.04 |  |  | true |  | true | 66 | 87 | 20
ubuntu-22.04 |  |  | true | true |  | 68 | 89 | 4
ubuntu-22.04 |  |  | true | true | true | 71 | 92 | 8
ubuntu-22.04 |  | true |  |  |  | 64 | 85 | 3
ubuntu-22.04 |  | true |  |  | true | 68 | 89 | 36
ubuntu-22.04 |  | true |  | true |  | 69 | 90 | 6
ubuntu-22.04 |  | true |  | true | true | 73 | 94 | 25
ubuntu-22.04 |  | true | true |  |  | 64 | 85 | 4
ubuntu-22.04 |  | true | true |  | true | 68 | 89 | 9
ubuntu-22.04 |  | true | true | true |  | 69 | 90 | 5
ubuntu-22.04 |  | true | true | true | true | 73 | 94 | 10
ubuntu-22.04 | true |  |  |  |  | 72 | 93 | 70
ubuntu-22.04 | true |  |  |  | true | 75 | 96 | 16
ubuntu-22.04 | true |  |  | true |  | 77 | 98 | 15
ubuntu-22.04 | true |  |  | true | true | 80 | 101 | 19
ubuntu-22.04 | true |  | true |  |  | 72 | 93 | 11
ubuntu-22.04 | true |  | true |  | true | 75 | 96 | 15
ubuntu-22.04 | true |  | true | true |  | 77 | 98 | 13
ubuntu-22.04 | true |  | true | true | true | 80 | 101 | 103
ubuntu-22.04 | true | true |  |  |  | 73 | 94 | 12
ubuntu-22.04 | true | true |  |  | true | 76 | 97 | 82
ubuntu-22.04 | true | true |  | true |  | 78 | 99 | 79
ubuntu-22.04 | true | true |  | true | true | 81 | 102 | 19
ubuntu-22.04 | true | true | true |  |  | 73 | 94 | 82
ubuntu-22.04 | true | true | true |  | true | 76 | 97 | 97
ubuntu-22.04 | true | true | true | true |  | 78 | 99 | 91
ubuntu-22.04 | true | true | true | true | true | 81 | 102 | 14
