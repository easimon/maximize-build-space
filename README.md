# Maximize available disk space for build tasks

If the available disk space on Github runners is too little for your build job, this action might be for you.
If not: please go on, there's nothing to see here.

This table shows the amount of free space you receive when using the action with the various options.

OS | Android SDKs removed | .NET SDKs removed | Haskell removed | CodeQL Removed | Cached Docker Images Removed | GB freed | GB free | Elapsed Time (seconds) |
---|:--------------------:|:-----------------:|:---------------:|:--------------:|:----------------------------:|:--------:|:-------:|:----------------------:|
ubuntu-20.04 |  |  |  |  |  | 53 | 76 | 2
ubuntu-20.04 |  |  |  |  | true | 58 | 81 | 36
ubuntu-20.04 |  |  |  | true |  | 57 | 80 | 3
ubuntu-20.04 |  |  |  | true | true | 63 | 86 | 25
ubuntu-20.04 |  |  | true |  |  | 53 | 76 | 2
ubuntu-20.04 |  |  | true |  | true | 58 | 81 | 7
ubuntu-20.04 |  |  | true | true |  | 57 | 80 | 3
ubuntu-20.04 |  |  | true | true | true | 63 | 86 | 24
ubuntu-20.04 |  | true |  |  |  | 55 | 78 | 3
ubuntu-20.04 |  | true |  |  | true | 61 | 84 | 10
ubuntu-20.04 |  | true |  | true |  | 60 | 83 | 5
ubuntu-20.04 |  | true |  | true | true | 65 | 88 | 28
ubuntu-20.04 |  | true | true |  |  | 55 | 78 | 3
ubuntu-20.04 |  | true | true |  | true | 61 | 84 | 8
ubuntu-20.04 |  | true | true | true |  | 60 | 83 | 4
ubuntu-20.04 |  | true | true | true | true | 65 | 88 | 24
ubuntu-20.04 | true |  |  |  |  | 65 | 88 | 12
ubuntu-20.04 | true |  |  |  | true | 70 | 93 | 34
ubuntu-20.04 | true |  |  | true |  | 69 | 92 | 14
ubuntu-20.04 | true |  |  | true | true | 75 | 98 | 34
ubuntu-20.04 | true |  | true |  |  | 65 | 88 | 9
ubuntu-20.04 | true |  | true |  | true | 70 | 93 | 16
ubuntu-20.04 | true |  | true | true |  | 69 | 92 | 56
ubuntu-20.04 | true |  | true | true | true | 75 | 98 | 14
ubuntu-20.04 | true | true |  |  |  | 67 | 90 | 9
ubuntu-20.04 | true | true |  |  | true | 72 | 95 | 93
ubuntu-20.04 | true | true |  | true |  | 72 | 95 | 60
ubuntu-20.04 | true | true |  | true | true | 77 | 100 | 16
ubuntu-20.04 | true | true | true |  |  | 67 | 90 | 67
ubuntu-20.04 | true | true | true |  | true | 72 | 95 | 40
ubuntu-20.04 | true | true | true | true |  | 72 | 95 | 11
ubuntu-20.04 | true | true | true | true | true | 77 | 100 | 187
ubuntu-22.04 |  |  |  |  |  | 52 | 77 | 2
ubuntu-22.04 |  |  |  |  | true | 57 | 82 | 23
ubuntu-22.04 |  |  |  | true |  | 57 | 82 | 4
ubuntu-22.04 |  |  |  | true | true | 62 | 87 | 19
ubuntu-22.04 |  |  | true |  |  | 52 | 77 | 2
ubuntu-22.04 |  |  | true |  | true | 57 | 82 | 9
ubuntu-22.04 |  |  | true | true |  | 57 | 82 | 4
ubuntu-22.04 |  |  | true | true | true | 62 | 87 | 10
ubuntu-22.04 |  | true |  |  |  | 55 | 80 | 5
ubuntu-22.04 |  | true |  |  | true | 60 | 85 | 9
ubuntu-22.04 |  | true |  | true |  | 60 | 85 | 5
ubuntu-22.04 |  | true |  | true | true | 64 | 89 | 10
ubuntu-22.04 |  | true | true |  |  | 55 | 80 | 4
ubuntu-22.04 |  | true | true |  | true | 60 | 85 | 11
ubuntu-22.04 |  | true | true | true |  | 60 | 85 | 4
ubuntu-22.04 |  | true | true | true | true | 64 | 89 | 10
ubuntu-22.04 | true |  |  |  |  | 64 | 89 | 13
ubuntu-22.04 | true |  |  |  | true | 69 | 94 | 84
ubuntu-22.04 | true |  |  | true |  | 69 | 94 | 15
ubuntu-22.04 | true |  |  | true | true | 73 | 98 | 65
ubuntu-22.04 | true |  | true |  |  | 64 | 89 | 15
ubuntu-22.04 | true |  | true |  | true | 69 | 94 | 98
ubuntu-22.04 | true |  | true | true |  | 69 | 94 | 75
ubuntu-22.04 | true |  | true | true | true | 73 | 98 | 20
ubuntu-22.04 | true | true |  |  |  | 67 | 92 | 85
ubuntu-22.04 | true | true |  |  | true | 71 | 96 | 116
ubuntu-22.04 | true | true |  | true |  | 72 | 97 | 15
ubuntu-22.04 | true | true |  | true | true | 76 | 101 | 22
ubuntu-22.04 | true | true | true |  |  | 67 | 92 | 14
ubuntu-22.04 | true | true | true |  | true | 71 | 96 | 78
ubuntu-22.04 | true | true | true | true |  | 72 | 97 | 79
ubuntu-22.04 | true | true | true | true | true | 76 | 101 | 32
