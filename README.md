# Maximize available disk space for build tasks

If the available disk space on Github runners is too little for your build job, this action might be for you.
If not: please go on, there's nothing to see here.

This table shows the amount of free space you receive when using the action with the various options.

OS | Android SDKs removed | .NET SDKs removed | Haskell removed | CodeQL Removed | Cached Docker Images Removed | GB freed | GB free | Elapsed Time (seconds) |
---|:--------------------:|:-----------------:|:---------------:|:--------------:|:----------------------------:|:--------:|:-------:|:----------------------:|
ubuntu-20.04 |  |  |  |  |  | 63 | 83 | 2
ubuntu-20.04 |  |  |  |  | true | 66 | 86 | 70
ubuntu-20.04 |  |  |  | true |  | 68 | 88 | 2
ubuntu-20.04 |  |  |  | true | true | 71 | 91 | 54
ubuntu-20.04 |  |  | true |  |  | 63 | 83 | 2
ubuntu-20.04 |  |  | true |  | true | 66 | 86 | 54
ubuntu-20.04 |  |  | true | true |  | 68 | 88 | 3
ubuntu-20.04 |  |  | true | true | true | 71 | 91 | 62
ubuntu-20.04 |  | true |  |  |  | 64 | 84 | 4
ubuntu-20.04 |  | true |  |  | true | 67 | 87 | 9
ubuntu-20.04 |  | true |  | true |  | 69 | 89 | 2
ubuntu-20.04 |  | true |  | true | true | 72 | 92 | 56
ubuntu-20.04 |  | true | true |  |  | 64 | 84 | 7
ubuntu-20.04 |  | true | true |  | true | 67 | 87 | 32
ubuntu-20.04 |  | true | true | true |  | 69 | 89 | 4
ubuntu-20.04 |  | true | true | true | true | 72 | 92 | 7
ubuntu-20.04 | true |  |  |  |  | 71 | 91 | 88
ubuntu-20.04 | true |  |  |  | true | 75 | 95 | 138
ubuntu-20.04 | true |  |  | true |  | 76 | 96 | 60
ubuntu-20.04 | true |  |  | true | true | 79 | 99 | 116
ubuntu-20.04 | true |  | true |  |  | 71 | 91 | 102
ubuntu-20.04 | true |  | true |  | true | 75 | 95 | 44
ubuntu-20.04 | true |  | true | true |  | 76 | 96 | 55
ubuntu-20.04 | true |  | true | true | true | 79 | 99 | 11
ubuntu-20.04 | true | true |  |  |  | 73 | 93 | 57
ubuntu-20.04 | true | true |  |  | true | 76 | 96 | 59
ubuntu-20.04 | true | true |  | true |  | 78 | 98 | 9
ubuntu-20.04 | true | true |  | true | true | 81 | 101 | 126
ubuntu-20.04 | true | true | true |  |  | 73 | 93 | 9
ubuntu-20.04 | true | true | true |  | true | 76 | 96 | 109
ubuntu-20.04 | true | true | true | true |  | 78 | 98 | 8
ubuntu-20.04 | true | true | true | true | true | 81 | 101 | 108
ubuntu-22.04 |  |  |  |  |  | 63 | 84 | 2
ubuntu-22.04 |  |  |  |  | true | 66 | 87 | 7
ubuntu-22.04 |  |  |  | true |  | 68 | 89 | 3
ubuntu-22.04 |  |  |  | true | true | 71 | 92 | 10
ubuntu-22.04 |  |  | true |  |  | 63 | 84 | 1
ubuntu-22.04 |  |  | true |  | true | 66 | 87 | 8
ubuntu-22.04 |  |  | true | true |  | 68 | 89 | 4
ubuntu-22.04 |  |  | true | true | true | 71 | 92 | 25
ubuntu-22.04 |  | true |  |  |  | 65 | 86 | 4
ubuntu-22.04 |  | true |  |  | true | 68 | 89 | 37
ubuntu-22.04 |  | true |  | true |  | 69 | 90 | 6
ubuntu-22.04 |  | true |  | true | true | 73 | 94 | 9
ubuntu-22.04 |  | true | true |  |  | 65 | 86 | 4
ubuntu-22.04 |  | true | true |  | true | 68 | 89 | 11
ubuntu-22.04 |  | true | true | true |  | 69 | 90 | 5
ubuntu-22.04 |  | true | true | true | true | 73 | 94 | 9
ubuntu-22.04 | true |  |  |  |  | 72 | 93 | 9
ubuntu-22.04 | true |  |  |  | true | 75 | 96 | 14
ubuntu-22.04 | true |  |  | true |  | 77 | 98 | 12
ubuntu-22.04 | true |  |  | true | true | 80 | 101 | 16
ubuntu-22.04 | true |  | true |  |  | 72 | 93 | 10
ubuntu-22.04 | true |  | true |  | true | 75 | 96 | 14
ubuntu-22.04 | true |  | true | true |  | 77 | 98 | 12
ubuntu-22.04 | true |  | true | true | true | 80 | 101 | 71
ubuntu-22.04 | true | true |  |  |  | 73 | 94 | 14
ubuntu-22.04 | true | true |  |  | true | 76 | 97 | 17
ubuntu-22.04 | true | true |  | true |  | 78 | 99 | 12
ubuntu-22.04 | true | true |  | true | true | 81 | 102 | 94
ubuntu-22.04 | true | true | true |  |  | 73 | 94 | 11
ubuntu-22.04 | true | true | true |  | true | 76 | 97 | 17
ubuntu-22.04 | true | true | true | true |  | 78 | 99 | 61
ubuntu-22.04 | true | true | true | true | true | 81 | 102 | 56
