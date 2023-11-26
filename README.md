# Maximize available disk space for build tasks

If the available disk space on Github runners is too little for your build job, this action might be for you.
If not: please go on, there's nothing to see here.

This table shows the amount of free space you receive when using the action with the various options.

OS | Android SDKs removed | .NET SDKs removed | Haskell removed | CodeQL Removed | Cached Docker Images Removed | GB freed | GB free | Elapsed Time (seconds) |
---|:--------------------:|:-----------------:|:---------------:|:--------------:|:----------------------------:|:--------:|:-------:|:----------------------:|
ubuntu-20.04 |  |  |  |  |  | 52 | 75 | 2
ubuntu-20.04 |  |  |  |  | true | 59 | 82 | 36
ubuntu-20.04 |  |  |  | true |  | 56 | 79 | 3
ubuntu-20.04 |  |  |  | true | true | 62 | 85 | 31
ubuntu-20.04 |  |  | true |  |  | 52 | 75 | 2
ubuntu-20.04 |  |  | true |  | true | 59 | 82 | 33
ubuntu-20.04 |  |  | true | true |  | 56 | 79 | 3
ubuntu-20.04 |  |  | true | true | true | 62 | 85 | 43
ubuntu-20.04 |  | true |  |  |  | 55 | 78 | 7
ubuntu-20.04 |  | true |  |  | true | 62 | 85 | 34
ubuntu-20.04 |  | true |  | true |  | 59 | 82 | 6
ubuntu-20.04 |  | true |  | true | true | 65 | 88 | 10
ubuntu-20.04 |  | true | true |  |  | 55 | 78 | 6
ubuntu-20.04 |  | true | true |  | true | 62 | 85 | 12
ubuntu-20.04 |  | true | true | true |  | 59 | 82 | 7
ubuntu-20.04 |  | true | true | true | true | 65 | 88 | 28
ubuntu-20.04 | true |  |  |  |  | 64 | 87 | 54
ubuntu-20.04 | true |  |  |  | true | 71 | 94 | 101
ubuntu-20.04 | true |  |  | true |  | 68 | 91 | 48
ubuntu-20.04 | true |  |  | true | true | 74 | 97 | 68
ubuntu-20.04 | true |  | true |  |  | 64 | 87 | 10
ubuntu-20.04 | true |  | true |  | true | 71 | 94 | 19
ubuntu-20.04 | true |  | true | true |  | 68 | 91 | 10
ubuntu-20.04 | true |  | true | true | true | 74 | 97 | 90
ubuntu-20.04 | true | true |  |  |  | 67 | 90 | 56
ubuntu-20.04 | true | true |  |  | true | 73 | 96 | 115
ubuntu-20.04 | true | true |  | true |  | 70 | 93 | 61
ubuntu-20.04 | true | true |  | true | true | 77 | 100 | 80
ubuntu-20.04 | true | true | true |  |  | 67 | 90 | 71
ubuntu-20.04 | true | true | true |  | true | 73 | 96 | 83
ubuntu-20.04 | true | true | true | true |  | 70 | 93 | 65
ubuntu-20.04 | true | true | true | true | true | 77 | 100 | 86
ubuntu-22.04 |  |  |  |  |  | 52 | 77 | 2
ubuntu-22.04 |  |  |  |  | true | 58 | 83 | 27
ubuntu-22.04 |  |  |  | true |  | 56 | 81 | 4
ubuntu-22.04 |  |  |  | true | true | 61 | 86 | 28
ubuntu-22.04 |  |  | true |  |  | 52 | 77 | 2
ubuntu-22.04 |  |  | true |  | true | 58 | 83 | 13
ubuntu-22.04 |  |  | true | true |  | 56 | 81 | 4
ubuntu-22.04 |  |  | true | true | true | 61 | 86 | 11
ubuntu-22.04 |  | true |  |  |  | 55 | 80 | 4
ubuntu-22.04 |  | true |  |  | true | 60 | 85 | 29
ubuntu-22.04 |  | true |  | true |  | 58 | 83 | 3
ubuntu-22.04 |  | true |  | true | true | 64 | 89 | 32
ubuntu-22.04 |  | true | true |  |  | 55 | 80 | 6
ubuntu-22.04 |  | true | true |  | true | 60 | 85 | 12
ubuntu-22.04 |  | true | true | true |  | 58 | 83 | 6
ubuntu-22.04 |  | true | true | true | true | 64 | 89 | 29
ubuntu-22.04 | true |  |  |  |  | 64 | 89 | 16
ubuntu-22.04 | true |  |  |  | true | 70 | 95 | 18
ubuntu-22.04 | true |  |  | true |  | 68 | 93 | 17
ubuntu-22.04 | true |  |  | true | true | 73 | 98 | 94
ubuntu-22.04 | true |  | true |  |  | 64 | 89 | 15
ubuntu-22.04 | true |  | true |  | true | 70 | 95 | 103
ubuntu-22.04 | true |  | true | true |  | 68 | 93 | 52
ubuntu-22.04 | true |  | true | true | true | 73 | 98 | 89
ubuntu-22.04 | true | true |  |  |  | 67 | 92 | 90
ubuntu-22.04 | true | true |  |  | true | 72 | 97 | 24
ubuntu-22.04 | true | true |  | true |  | 70 | 95 | 14
ubuntu-22.04 | true | true |  | true | true | 76 | 101 | 124
ubuntu-22.04 | true | true | true |  |  | 67 | 92 | 97
ubuntu-22.04 | true | true | true |  | true | 72 | 97 | 21
ubuntu-22.04 | true | true | true | true |  | 70 | 95 | 15
ubuntu-22.04 | true | true | true | true | true | 76 | 101 | 25
