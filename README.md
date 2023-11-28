# Maximize available disk space for build tasks

If the available disk space on Github runners is too little for your build job, this action might be for you.
If not: please go on, there's nothing to see here.

This table shows the amount of free space you receive when using the action with the various options.

OS | Android SDKs removed | .NET SDKs removed | Haskell removed | CodeQL Removed | Cached Docker Images Removed | GB freed | GB free | Elapsed Time (seconds) |
---|:--------------------:|:-----------------:|:---------------:|:--------------:|:----------------------------:|:--------:|:-------:|:----------------------:|
ubuntu-20.04 |  |  |  |  |  | 52 | 75 | 2
ubuntu-20.04 |  |  |  |  | true | 59 | 82 | 34
ubuntu-20.04 |  |  |  | true |  | 56 | 79 | 2
ubuntu-20.04 |  |  |  | true | true | 62 | 85 | 31
ubuntu-20.04 |  |  | true |  |  | 52 | 75 | 2
ubuntu-20.04 |  |  | true |  | true | 59 | 82 | 40
ubuntu-20.04 |  |  | true | true |  | 56 | 79 | 3
ubuntu-20.04 |  |  | true | true | true | 62 | 85 | 32
ubuntu-20.04 |  | true |  |  |  | 55 | 78 | 6
ubuntu-20.04 |  | true |  |  | true | 62 | 85 | 29
ubuntu-20.04 |  | true |  | true |  | 59 | 82 | 7
ubuntu-20.04 |  | true |  | true | true | 65 | 88 | 10
ubuntu-20.04 |  | true | true |  |  | 55 | 78 | 6
ubuntu-20.04 |  | true | true |  | true | 62 | 85 | 10
ubuntu-20.04 |  | true | true | true |  | 59 | 82 | 5
ubuntu-20.04 |  | true | true | true | true | 65 | 88 | 14
ubuntu-20.04 | true |  |  |  |  | 64 | 87 | 9
ubuntu-20.04 | true |  |  |  | true | 71 | 94 | 17
ubuntu-20.04 | true |  |  | true |  | 68 | 91 | 9
ubuntu-20.04 | true |  |  | true | true | 74 | 97 | 38
ubuntu-20.04 | true |  | true |  |  | 64 | 87 | 11
ubuntu-20.04 | true |  | true |  | true | 71 | 94 | 100
ubuntu-20.04 | true |  | true | true |  | 68 | 91 | 55
ubuntu-20.04 | true |  | true | true | true | 74 | 97 | 114
ubuntu-20.04 | true | true |  |  |  | 67 | 90 | 9
ubuntu-20.04 | true | true |  |  | true | 73 | 96 | 40
ubuntu-20.04 | true | true |  | true |  | 70 | 93 | 10
ubuntu-20.04 | true | true |  | true | true | 77 | 100 | 97
ubuntu-20.04 | true | true | true |  |  | 67 | 90 | 12
ubuntu-20.04 | true | true | true |  | true | 73 | 96 | 15
ubuntu-20.04 | true | true | true | true |  | 70 | 93 | 75
ubuntu-20.04 | true | true | true | true | true | 77 | 100 | 101
ubuntu-22.04 |  |  |  |  |  | 52 | 77 | 2
ubuntu-22.04 |  |  |  |  | true | 58 | 83 | 11
ubuntu-22.04 |  |  |  | true |  | 56 | 81 | 9
ubuntu-22.04 |  |  |  | true | true | 61 | 86 | 33
ubuntu-22.04 |  |  | true |  |  | 52 | 77 | 1
ubuntu-22.04 |  |  | true |  | true | 58 | 83 | 11
ubuntu-22.04 |  |  | true | true |  | 56 | 81 | 3
ubuntu-22.04 |  |  | true | true | true | 61 | 86 | 26
ubuntu-22.04 |  | true |  |  |  | 55 | 80 | 6
ubuntu-22.04 |  | true |  |  | true | 60 | 85 | 23
ubuntu-22.04 |  | true |  | true |  | 58 | 83 | 5
ubuntu-22.04 |  | true |  | true | true | 64 | 89 | 32
ubuntu-22.04 |  | true | true |  |  | 55 | 80 | 6
ubuntu-22.04 |  | true | true |  | true | 60 | 85 | 33
ubuntu-22.04 |  | true | true | true |  | 58 | 83 | 6
ubuntu-22.04 |  | true | true | true | true | 64 | 89 | 32
ubuntu-22.04 | true |  |  |  |  | 64 | 89 | 81
ubuntu-22.04 | true |  |  |  | true | 70 | 95 | 21
ubuntu-22.04 | true |  |  | true |  | 68 | 93 | 17
ubuntu-22.04 | true |  |  | true | true | 73 | 98 | 25
ubuntu-22.04 | true |  | true |  |  | 64 | 89 | 13
ubuntu-22.04 | true |  | true |  | true | 70 | 95 | 24
ubuntu-22.04 | true |  | true | true |  | 68 | 93 | 84
ubuntu-22.04 | true |  | true | true | true | 73 | 98 | 106
ubuntu-22.04 | true | true |  |  |  | 67 | 92 | 88
ubuntu-22.04 | true | true |  |  | true | 72 | 97 | 35
ubuntu-22.04 | true | true |  | true |  | 70 | 95 | 17
ubuntu-22.04 | true | true |  | true | true | 76 | 101 | 24
ubuntu-22.04 | true | true | true |  |  | 67 | 92 | 73
ubuntu-22.04 | true | true | true |  | true | 72 | 97 | 29
ubuntu-22.04 | true | true | true | true |  | 70 | 95 | 15
ubuntu-22.04 | true | true | true | true | true | 76 | 101 | 23
