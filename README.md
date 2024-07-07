# Maximize available disk space for build tasks

If the available disk space on Github runners is too little for your build job, this action might be for you.
If not: please go on, there's nothing to see here.

This table shows the amount of free space you receive when using the action with the various options.

OS | Android SDKs removed | .NET SDKs removed | Haskell removed | CodeQL Removed | Cached Docker Images Removed | GB freed | GB free | Elapsed Time (seconds) |
---|:--------------------:|:-----------------:|:---------------:|:--------------:|:----------------------------:|:--------:|:-------:|:----------------------:|
ubuntu-20.04 |  |  |  |  |  | 62 | 82 | 2
ubuntu-20.04 |  |  |  |  | true | 66 | 86 | 8
ubuntu-20.04 |  |  |  | true |  | 67 | 87 | 4
ubuntu-20.04 |  |  |  | true | true | 71 | 91 | 65
ubuntu-20.04 |  |  | true |  |  | 62 | 82 | 2
ubuntu-20.04 |  |  | true |  | true | 66 | 86 | 52
ubuntu-20.04 |  |  | true | true |  | 67 | 87 | 2
ubuntu-20.04 |  |  | true | true | true | 71 | 91 | 59
ubuntu-20.04 |  | true |  |  |  | 64 | 84 | 4
ubuntu-20.04 |  | true |  |  | true | 67 | 87 | 6
ubuntu-20.04 |  | true |  | true |  | 69 | 89 | 4
ubuntu-20.04 |  | true |  | true | true | 72 | 92 | 6
ubuntu-20.04 |  | true | true |  |  | 64 | 84 | 4
ubuntu-20.04 |  | true | true |  | true | 67 | 87 | 52
ubuntu-20.04 |  | true | true | true |  | 69 | 89 | 4
ubuntu-20.04 |  | true | true | true | true | 72 | 92 | 62
ubuntu-20.04 | true |  |  |  |  | 71 | 91 | 8
ubuntu-20.04 | true |  |  |  | true | 75 | 95 | 14
ubuntu-20.04 | true |  |  | true |  | 76 | 96 | 12
ubuntu-20.04 | true |  |  | true | true | 79 | 99 | 134
ubuntu-20.04 | true |  | true |  |  | 71 | 91 | 48
ubuntu-20.04 | true |  | true |  | true | 75 | 95 | 12
ubuntu-20.04 | true |  | true | true |  | 76 | 96 | 49
ubuntu-20.04 | true |  | true | true | true | 79 | 99 | 104
ubuntu-20.04 | true | true |  |  |  | 73 | 93 | 9
ubuntu-20.04 | true | true |  |  | true | 76 | 96 | 61
ubuntu-20.04 | true | true |  | true |  | 78 | 98 | 11
ubuntu-20.04 | true | true |  | true | true | 81 | 101 | 49
ubuntu-20.04 | true | true | true |  |  | 73 | 93 | 8
ubuntu-20.04 | true | true | true |  | true | 76 | 96 | 13
ubuntu-20.04 | true | true | true | true |  | 78 | 98 | 12
ubuntu-20.04 | true | true | true | true | true | 81 | 101 | 96
ubuntu-22.04 |  |  |  |  |  | 63 | 84 | 1
ubuntu-22.04 |  |  |  |  | true | 66 | 87 | 33
ubuntu-22.04 |  |  |  | true |  | 68 | 89 | 4
ubuntu-22.04 |  |  |  | true | true | 71 | 92 | 8
ubuntu-22.04 |  |  | true |  |  | 63 | 84 | 2
ubuntu-22.04 |  |  | true |  | true | 66 | 87 | 8
ubuntu-22.04 |  |  | true | true |  | 68 | 89 | 3
ubuntu-22.04 |  |  | true | true | true | 71 | 92 | 34
ubuntu-22.04 |  | true |  |  |  | 64 | 85 | 5
ubuntu-22.04 |  | true |  |  | true | 67 | 88 | 34
ubuntu-22.04 |  | true |  | true |  | 69 | 90 | 5
ubuntu-22.04 |  | true |  | true | true | 72 | 93 | 8
ubuntu-22.04 |  | true | true |  |  | 64 | 85 | 4
ubuntu-22.04 |  | true | true |  | true | 67 | 88 | 6
ubuntu-22.04 |  | true | true | true |  | 69 | 90 | 4
ubuntu-22.04 |  | true | true | true | true | 72 | 93 | 28
ubuntu-22.04 | true |  |  |  |  | 72 | 93 | 12
ubuntu-22.04 | true |  |  |  | true | 75 | 96 | 92
ubuntu-22.04 | true |  |  | true |  | 77 | 98 | 79
ubuntu-22.04 | true |  |  | true | true | 80 | 101 | 16
ubuntu-22.04 | true |  | true |  |  | 72 | 93 | 62
ubuntu-22.04 | true |  | true |  | true | 75 | 96 | 23
ubuntu-22.04 | true |  | true | true |  | 77 | 98 | 59
ubuntu-22.04 | true |  | true | true | true | 80 | 101 | 15
ubuntu-22.04 | true | true |  |  |  | 73 | 94 | 68
ubuntu-22.04 | true | true |  |  | true | 76 | 97 | 14
ubuntu-22.04 | true | true |  | true |  | 78 | 99 | 13
ubuntu-22.04 | true | true |  | true | true | 81 | 102 | 18
ubuntu-22.04 | true | true | true |  |  | 73 | 94 | 10
ubuntu-22.04 | true | true | true |  | true | 76 | 97 | 121
ubuntu-22.04 | true | true | true | true |  | 78 | 99 | 70
ubuntu-22.04 | true | true | true | true | true | 81 | 102 | 16
