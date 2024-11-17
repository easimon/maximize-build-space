# Maximize available disk space for build tasks

If the available disk space on Github runners is too little for your build job, this action might be for you.
If not: please go on, there's nothing to see here.

This table shows the amount of free space you receive when using the action with the various options.

OS | Android SDKs removed | .NET SDKs removed | Haskell removed | CodeQL Removed | Cached Docker Images Removed | GB freed | GB free | Elapsed Time (seconds) |
---|:--------------------:|:-----------------:|:---------------:|:--------------:|:----------------------------:|:--------:|:-------:|:----------------------:|
ubuntu-20.04 |  |  |  |  |  | 63 | 82 | 3
ubuntu-20.04 |  |  |  |  | true | 66 | 85 | 34
ubuntu-20.04 |  |  |  | true |  | 68 | 87 | 4
ubuntu-20.04 |  |  |  | true | true | 71 | 90 | 9
ubuntu-20.04 |  |  | true |  |  | 63 | 82 | 2
ubuntu-20.04 |  |  | true |  | true | 66 | 85 | 99
ubuntu-20.04 |  |  | true | true |  | 68 | 87 | 4
ubuntu-20.04 |  |  | true | true | true | 71 | 90 | 11
ubuntu-20.04 |  | true |  |  |  | 64 | 83 | 4
ubuntu-20.04 |  | true |  |  | true | 68 | 87 | 75
ubuntu-20.04 |  | true |  | true |  | 69 | 88 | 6
ubuntu-20.04 |  | true |  | true | true | 73 | 92 | 65
ubuntu-20.04 |  | true | true |  |  | 64 | 83 | 4
ubuntu-20.04 |  | true | true |  | true | 68 | 87 | 8
ubuntu-20.04 |  | true | true | true |  | 69 | 88 | 4
ubuntu-20.04 |  | true | true | true | true | 73 | 92 | 39
ubuntu-20.04 | true |  |  |  |  | 70 | 89 | 61
ubuntu-20.04 | true |  |  |  | true | 74 | 93 | 83
ubuntu-20.04 | true |  |  | true |  | 75 | 94 | 68
ubuntu-20.04 | true |  |  | true | true | 79 | 98 | 158
ubuntu-20.04 | true |  | true |  |  | 70 | 89 | 66
ubuntu-20.04 | true |  | true |  | true | 74 | 93 | 90
ubuntu-20.04 | true |  | true | true |  | 75 | 94 | 16
ubuntu-20.04 | true |  | true | true | true | 79 | 98 | 97
ubuntu-20.04 | true | true |  |  |  | 72 | 91 | 64
ubuntu-20.04 | true | true |  |  | true | 75 | 94 | 111
ubuntu-20.04 | true | true |  | true |  | 77 | 96 | 48
ubuntu-20.04 | true | true |  | true | true | 80 | 99 | 135
ubuntu-20.04 | true | true | true |  |  | 72 | 91 | 56
ubuntu-20.04 | true | true | true |  | true | 75 | 94 | 19
ubuntu-20.04 | true | true | true | true |  | 77 | 96 | 53
ubuntu-20.04 | true | true | true | true | true | 80 | 99 | 84
ubuntu-22.04 |  |  |  |  |  | 62 | 83 | 2
ubuntu-22.04 |  |  |  |  | true | 66 | 87 | 12
ubuntu-22.04 |  |  |  | true |  | 67 | 88 | 4
ubuntu-22.04 |  |  |  | true | true | 71 | 92 | 10
ubuntu-22.04 |  |  | true |  |  | 62 | 83 | 2
ubuntu-22.04 |  |  | true |  | true | 66 | 87 | 11
ubuntu-22.04 |  |  | true | true |  | 67 | 88 | 4
ubuntu-22.04 |  |  | true | true | true | 71 | 92 | 30
ubuntu-22.04 |  | true |  |  |  | 64 | 85 | 4
ubuntu-22.04 |  | true |  |  | true | 67 | 88 | 11
ubuntu-22.04 |  | true |  | true |  | 69 | 90 | 6
ubuntu-22.04 |  | true |  | true | true | 72 | 93 | 8
ubuntu-22.04 |  | true | true |  |  | 64 | 85 | 6
ubuntu-22.04 |  | true | true |  | true | 67 | 88 | 9
ubuntu-22.04 |  | true | true | true |  | 69 | 90 | 4
ubuntu-22.04 |  | true | true | true | true | 72 | 93 | 26
ubuntu-22.04 | true |  |  |  |  | 70 | 91 | 13
ubuntu-22.04 | true |  |  |  | true | 73 | 94 | 19
ubuntu-22.04 | true |  |  | true |  | 75 | 96 | 13
ubuntu-22.04 | true |  |  | true | true | 78 | 99 | 82
ubuntu-22.04 | true |  | true |  |  | 70 | 91 | 12
ubuntu-22.04 | true |  | true |  | true | 73 | 94 | 23
ubuntu-22.04 | true |  | true | true |  | 75 | 96 | 16
ubuntu-22.04 | true |  | true | true | true | 78 | 99 | 26
ubuntu-22.04 | true | true |  |  |  | 71 | 92 | 12
ubuntu-22.04 | true | true |  |  | true | 75 | 96 | 17
ubuntu-22.04 | true | true |  | true |  | 76 | 97 | 69
ubuntu-22.04 | true | true |  | true | true | 80 | 101 | 27
ubuntu-22.04 | true | true | true |  |  | 71 | 92 | 14
ubuntu-22.04 | true | true | true |  | true | 75 | 96 | 93
ubuntu-22.04 | true | true | true | true |  | 76 | 97 | 17
ubuntu-22.04 | true | true | true | true | true | 80 | 101 | 90
