# Maximize available disk space for build tasks

If the available disk space on Github runners is too little for your build job, this action might be for you.
If not: please go on, there's nothing to see here.

This table shows the amount of free space you receive when using the action with the various options.

OS | Android SDKs removed | .NET SDKs removed | Haskell removed | CodeQL Removed | Cached Docker Images Removed | GB freed | GB free | Elapsed Time (seconds) |
---|:--------------------:|:-----------------:|:---------------:|:--------------:|:----------------------------:|:--------:|:-------:|:----------------------:|
ubuntu-20.04 |  |  |  |  |  | 63 | 82 | 1
ubuntu-20.04 |  |  |  |  | true | 66 | 85 | 17
ubuntu-20.04 |  |  |  | true |  | 67 | 86 | 3
ubuntu-20.04 |  |  |  | true | true | 71 | 90 | 5
ubuntu-20.04 |  |  | true |  |  | 63 | 82 | 2
ubuntu-20.04 |  |  | true |  | true | 66 | 85 | 23
ubuntu-20.04 |  |  | true | true |  | 67 | 86 | 2
ubuntu-20.04 |  |  | true | true | true | 71 | 90 | 6
ubuntu-20.04 |  | true |  |  |  | 64 | 83 | 7
ubuntu-20.04 |  | true |  |  | true | 67 | 86 | 28
ubuntu-20.04 |  | true |  | true |  | 69 | 88 | 3
ubuntu-20.04 |  | true |  | true | true | 72 | 91 | 7
ubuntu-20.04 |  | true | true |  |  | 64 | 83 | 6
ubuntu-20.04 |  | true | true |  | true | 67 | 86 | 20
ubuntu-20.04 |  | true | true | true |  | 69 | 88 | 4
ubuntu-20.04 |  | true | true | true | true | 72 | 91 | 24
ubuntu-20.04 | true |  |  |  |  | 71 | 90 | 42
ubuntu-20.04 | true |  |  |  | true | 74 | 93 | 57
ubuntu-20.04 | true |  |  | true |  | 76 | 95 | 41
ubuntu-20.04 | true |  |  | true | true | 79 | 98 | 54
ubuntu-20.04 | true |  | true |  |  | 71 | 90 | 39
ubuntu-20.04 | true |  | true |  | true | 74 | 93 | 56
ubuntu-20.04 | true |  | true | true |  | 76 | 95 | 39
ubuntu-20.04 | true |  | true | true | true | 79 | 98 | 65
ubuntu-20.04 | true | true |  |  |  | 73 | 92 | 48
ubuntu-20.04 | true | true |  |  | true | 76 | 95 | 14
ubuntu-20.04 | true | true |  | true |  | 78 | 97 | 139
ubuntu-20.04 | true | true |  | true | true | 81 | 100 | 14
ubuntu-20.04 | true | true | true |  |  | 73 | 92 | 48
ubuntu-20.04 | true | true | true |  | true | 76 | 95 | 15
ubuntu-20.04 | true | true | true | true |  | 78 | 97 | 51
ubuntu-20.04 | true | true | true | true | true | 81 | 100 | 64
ubuntu-22.04 |  |  |  |  |  | 62 | 82 | 2
ubuntu-22.04 |  |  |  |  | true | 65 | 85 | 7
ubuntu-22.04 |  |  |  | true |  | 67 | 87 | 3
ubuntu-22.04 |  |  |  | true | true | 70 | 90 | 8
ubuntu-22.04 |  |  | true |  |  | 62 | 82 | 2
ubuntu-22.04 |  |  | true |  | true | 65 | 85 | 35
ubuntu-22.04 |  |  | true | true |  | 67 | 87 | 3
ubuntu-22.04 |  |  | true | true | true | 70 | 90 | 45
ubuntu-22.04 |  | true |  |  |  | 64 | 84 | 3
ubuntu-22.04 |  | true |  |  | true | 67 | 87 | 43
ubuntu-22.04 |  | true |  | true |  | 69 | 89 | 5
ubuntu-22.04 |  | true |  | true | true | 72 | 92 | 27
ubuntu-22.04 |  | true | true |  |  | 64 | 84 | 4
ubuntu-22.04 |  | true | true |  | true | 67 | 87 | 24
ubuntu-22.04 |  | true | true | true |  | 69 | 89 | 4
ubuntu-22.04 |  | true | true | true | true | 72 | 92 | 9
ubuntu-22.04 | true |  |  |  |  | 71 | 91 | 71
ubuntu-22.04 | true |  |  |  | true | 74 | 94 | 97
ubuntu-22.04 | true |  |  | true |  | 76 | 96 | 10
ubuntu-22.04 | true |  |  | true | true | 79 | 99 | 15
ubuntu-22.04 | true |  | true |  |  | 71 | 91 | 72
ubuntu-22.04 | true |  | true |  | true | 74 | 94 | 105
ubuntu-22.04 | true |  | true | true |  | 76 | 96 | 11
ubuntu-22.04 | true |  | true | true | true | 79 | 99 | 95
ubuntu-22.04 | true | true |  |  |  | 72 | 92 | 84
ubuntu-22.04 | true | true |  |  | true | 76 | 96 | 57
ubuntu-22.04 | true | true |  | true |  | 77 | 97 | 66
ubuntu-22.04 | true | true |  | true | true | 80 | 100 | 109
ubuntu-22.04 | true | true | true |  |  | 72 | 92 | 12
ubuntu-22.04 | true | true | true |  | true | 76 | 96 | 16
ubuntu-22.04 | true | true | true | true |  | 77 | 97 | 66
ubuntu-22.04 | true | true | true | true | true | 80 | 100 | 109
