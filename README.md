# Maximize available disk space for build tasks

If the available disk space on Github runners is too little for your build job, this action might be for you.
If not: please go on, there's nothing to see here.

This table shows the amount of free space you receive when using the action with the various options.

OS | Android SDKs removed | .NET SDKs removed | Haskell removed | CodeQL Removed | Cached Docker Images Removed | GB freed | GB free | Elapsed Time (seconds) |
---|:--------------------:|:-----------------:|:---------------:|:--------------:|:----------------------------:|:--------:|:-------:|:----------------------:|
ubuntu-20.04 |  |  |  |  |  | 52 | 75 | 2
ubuntu-20.04 |  |  |  |  | true | 59 | 82 | 36
ubuntu-20.04 |  |  |  | true |  | 56 | 79 | 3
ubuntu-20.04 |  |  |  | true | true | 62 | 85 | 43
ubuntu-20.04 |  |  | true |  |  | 52 | 75 | 2
ubuntu-20.04 |  |  | true |  | true | 59 | 82 | 41
ubuntu-20.04 |  |  | true | true |  | 56 | 79 | 12
ubuntu-20.04 |  |  | true | true | true | 62 | 85 | 10
ubuntu-20.04 |  | true |  |  |  | 55 | 78 | 3
ubuntu-20.04 |  | true |  |  | true | 62 | 85 | 44
ubuntu-20.04 |  | true |  | true |  | 59 | 82 | 3
ubuntu-20.04 |  | true |  | true | true | 65 | 88 | 10
ubuntu-20.04 |  | true | true |  |  | 55 | 78 | 3
ubuntu-20.04 |  | true | true |  | true | 62 | 85 | 47
ubuntu-20.04 |  | true | true | true |  | 59 | 82 | 5
ubuntu-20.04 |  | true | true | true | true | 65 | 88 | 11
ubuntu-20.04 | true |  |  |  |  | 64 | 87 | 9
ubuntu-20.04 | true |  |  |  | true | 71 | 94 | 76
ubuntu-20.04 | true |  |  | true |  | 68 | 91 | 51
ubuntu-20.04 | true |  |  | true | true | 74 | 97 | 109
ubuntu-20.04 | true |  | true |  |  | 64 | 87 | 9
ubuntu-20.04 | true |  | true |  | true | 71 | 94 | 15
ubuntu-20.04 | true |  | true | true |  | 68 | 91 | 72
ubuntu-20.04 | true |  | true | true | true | 74 | 97 | 16
ubuntu-20.04 | true | true |  |  |  | 67 | 90 | 13
ubuntu-20.04 | true | true |  |  | true | 73 | 96 | 17
ubuntu-20.04 | true | true |  | true |  | 70 | 93 | 12
ubuntu-20.04 | true | true |  | true | true | 77 | 100 | 18
ubuntu-20.04 | true | true | true |  |  | 67 | 90 | 65
ubuntu-20.04 | true | true | true |  | true | 73 | 96 | 17
ubuntu-20.04 | true | true | true | true |  | 70 | 93 | 9
ubuntu-20.04 | true | true | true | true | true | 77 | 100 | 15
ubuntu-22.04 |  |  |  |  |  | 52 | 77 | 1
ubuntu-22.04 |  |  |  |  | true | 58 | 83 | 9
ubuntu-22.04 |  |  |  | true |  | 56 | 81 | 3
ubuntu-22.04 |  |  |  | true | true | 61 | 86 | 15
ubuntu-22.04 |  |  | true |  |  | 52 | 77 | 2
ubuntu-22.04 |  |  | true |  | true | 58 | 83 | 31
ubuntu-22.04 |  |  | true | true |  | 56 | 81 | 3
ubuntu-22.04 |  |  | true | true | true | 61 | 86 | 32
ubuntu-22.04 |  | true |  |  |  | 55 | 80 | 4
ubuntu-22.04 |  | true |  |  | true | 60 | 85 | 12
ubuntu-22.04 |  | true |  | true |  | 58 | 83 | 4
ubuntu-22.04 |  | true |  | true | true | 64 | 89 | 13
ubuntu-22.04 |  | true | true |  |  | 55 | 80 | 3
ubuntu-22.04 |  | true | true |  | true | 60 | 85 | 14
ubuntu-22.04 |  | true | true | true |  | 58 | 83 | 5
ubuntu-22.04 |  | true | true | true | true | 64 | 89 | 11
ubuntu-22.04 | true |  |  |  |  | 64 | 89 | 12
ubuntu-22.04 | true |  |  |  | true | 70 | 95 | 98
ubuntu-22.04 | true |  |  | true |  | 68 | 93 | 15
ubuntu-22.04 | true |  |  | true | true | 73 | 98 | 45
ubuntu-22.04 | true |  | true |  |  | 64 | 89 | 12
ubuntu-22.04 | true |  | true |  | true | 70 | 95 | 112
ubuntu-22.04 | true |  | true | true |  | 68 | 93 | 90
ubuntu-22.04 | true |  | true | true | true | 73 | 98 | 128
ubuntu-22.04 | true | true |  |  |  | 67 | 92 | 14
ubuntu-22.04 | true | true |  |  | true | 72 | 97 | 21
ubuntu-22.04 | true | true |  | true |  | 70 | 95 | 19
ubuntu-22.04 | true | true |  | true | true | 76 | 101 | 23
ubuntu-22.04 | true | true | true |  |  | 67 | 92 | 13
ubuntu-22.04 | true | true | true |  | true | 72 | 97 | 21
ubuntu-22.04 | true | true | true | true |  | 70 | 95 | 15
ubuntu-22.04 | true | true | true | true | true | 76 | 101 | 24
