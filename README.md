# Maximize available disk space for build tasks

If the available disk space on Github runners is too little for your build job, this action might be for you.
If not: please go on, there's nothing to see here.

This table shows the amount of free space you receive when using the action with the various options.

OS | Android SDKs removed | .NET SDKs removed | Haskell removed | CodeQL Removed | Cached Docker Images Removed | GB freed | GB free | Elapsed Time (seconds) |
---|:--------------------:|:-----------------:|:---------------:|:--------------:|:----------------------------:|:--------:|:-------:|:----------------------:|
ubuntu-20.04 |  |  |  |  |  | 52 | 75 | 2
ubuntu-20.04 |  |  |  |  | true | 59 | 82 | 38
ubuntu-20.04 |  |  |  | true |  | 56 | 79 | 3
ubuntu-20.04 |  |  |  | true | true | 62 | 85 | 8
ubuntu-20.04 |  |  | true |  |  | 52 | 75 | 2
ubuntu-20.04 |  |  | true |  | true | 59 | 82 | 43
ubuntu-20.04 |  |  | true | true |  | 56 | 79 | 3
ubuntu-20.04 |  |  | true | true | true | 62 | 85 | 10
ubuntu-20.04 |  | true |  |  |  | 55 | 78 | 6
ubuntu-20.04 |  | true |  |  | true | 62 | 85 | 30
ubuntu-20.04 |  | true |  | true |  | 59 | 82 | 3
ubuntu-20.04 |  | true |  | true | true | 65 | 88 | 10
ubuntu-20.04 |  | true | true |  |  | 55 | 78 | 4
ubuntu-20.04 |  | true | true |  | true | 62 | 85 | 48
ubuntu-20.04 |  | true | true | true |  | 59 | 82 | 2
ubuntu-20.04 |  | true | true | true | true | 65 | 88 | 13
ubuntu-20.04 | true |  |  |  |  | 64 | 87 | 65
ubuntu-20.04 | true |  |  |  | true | 71 | 94 | 70
ubuntu-20.04 | true |  |  | true |  | 68 | 91 | 66
ubuntu-20.04 | true |  |  | true | true | 74 | 97 | 15
ubuntu-20.04 | true |  | true |  |  | 64 | 87 | 67
ubuntu-20.04 | true |  | true |  | true | 71 | 94 | 91
ubuntu-20.04 | true |  | true | true |  | 68 | 91 | 68
ubuntu-20.04 | true |  | true | true | true | 74 | 97 | 15
ubuntu-20.04 | true | true |  |  |  | 67 | 90 | 65
ubuntu-20.04 | true | true |  |  | true | 73 | 96 | 22
ubuntu-20.04 | true | true |  | true |  | 70 | 93 | 60
ubuntu-20.04 | true | true |  | true | true | 77 | 100 | 88
ubuntu-20.04 | true | true | true |  |  | 67 | 90 | 13
ubuntu-20.04 | true | true | true |  | true | 73 | 96 | 83
ubuntu-20.04 | true | true | true | true |  | 70 | 93 | 12
ubuntu-20.04 | true | true | true | true | true | 77 | 100 | 71
ubuntu-22.04 |  |  |  |  |  | 52 | 77 | 2
ubuntu-22.04 |  |  |  |  | true | 58 | 83 | 10
ubuntu-22.04 |  |  |  | true |  | 56 | 81 | 4
ubuntu-22.04 |  |  |  | true | true | 61 | 86 | 11
ubuntu-22.04 |  |  | true |  |  | 52 | 77 | 2
ubuntu-22.04 |  |  | true |  | true | 58 | 83 | 32
ubuntu-22.04 |  |  | true | true |  | 56 | 81 | 4
ubuntu-22.04 |  |  | true | true | true | 61 | 86 | 27
ubuntu-22.04 |  | true |  |  |  | 55 | 80 | 4
ubuntu-22.04 |  | true |  |  | true | 60 | 85 | 11
ubuntu-22.04 |  | true |  | true |  | 58 | 83 | 4
ubuntu-22.04 |  | true |  | true | true | 64 | 89 | 21
ubuntu-22.04 |  | true | true |  |  | 55 | 80 | 6
ubuntu-22.04 |  | true | true |  | true | 60 | 85 | 13
ubuntu-22.04 |  | true | true | true |  | 58 | 83 | 4
ubuntu-22.04 |  | true | true | true | true | 64 | 89 | 15
ubuntu-22.04 | true |  |  |  |  | 64 | 89 | 13
ubuntu-22.04 | true |  |  |  | true | 70 | 95 | 23
ubuntu-22.04 | true |  |  | true |  | 68 | 93 | 13
ubuntu-22.04 | true |  |  | true | true | 73 | 98 | 48
ubuntu-22.04 | true |  | true |  |  | 64 | 89 | 78
ubuntu-22.04 | true |  | true |  | true | 70 | 95 | 87
ubuntu-22.04 | true |  | true | true |  | 68 | 93 | 15
ubuntu-22.04 | true |  | true | true | true | 73 | 98 | 127
ubuntu-22.04 | true | true |  |  |  | 67 | 92 | 98
ubuntu-22.04 | true | true |  |  | true | 72 | 97 | 100
ubuntu-22.04 | true | true |  | true |  | 70 | 95 | 16
ubuntu-22.04 | true | true |  | true | true | 76 | 101 | 25
ubuntu-22.04 | true | true | true |  |  | 67 | 92 | 12
ubuntu-22.04 | true | true | true |  | true | 72 | 97 | 24
ubuntu-22.04 | true | true | true | true |  | 70 | 95 | 15
ubuntu-22.04 | true | true | true | true | true | 76 | 101 | 23
