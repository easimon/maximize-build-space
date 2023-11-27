# Maximize available disk space for build tasks

If the available disk space on Github runners is too little for your build job, this action might be for you.
If not: please go on, there's nothing to see here.

This table shows the amount of free space you receive when using the action with the various options.

OS | Android SDKs removed | .NET SDKs removed | Haskell removed | CodeQL Removed | Cached Docker Images Removed | GB freed | GB free | Elapsed Time (seconds) |
---|:--------------------:|:-----------------:|:---------------:|:--------------:|:----------------------------:|:--------:|:-------:|:----------------------:|
ubuntu-20.04 |  |  |  |  |  | 52 | 75 | 2
ubuntu-20.04 |  |  |  |  | true | 59 | 82 | 7
ubuntu-20.04 |  |  |  | true |  | 56 | 79 | 3
ubuntu-20.04 |  |  |  | true | true | 62 | 85 | 10
ubuntu-20.04 |  |  | true |  |  | 52 | 75 | 2
ubuntu-20.04 |  |  | true |  | true | 59 | 82 | 29
ubuntu-20.04 |  |  | true | true |  | 56 | 79 | 3
ubuntu-20.04 |  |  | true | true | true | 62 | 85 | 9
ubuntu-20.04 |  | true |  |  |  | 55 | 78 | 4
ubuntu-20.04 |  | true |  |  | true | 62 | 85 | 12
ubuntu-20.04 |  | true |  | true |  | 59 | 82 | 3
ubuntu-20.04 |  | true |  | true | true | 65 | 88 | 39
ubuntu-20.04 |  | true | true |  |  | 55 | 78 | 3
ubuntu-20.04 |  | true | true |  | true | 62 | 85 | 42
ubuntu-20.04 |  | true | true | true |  | 59 | 82 | 3
ubuntu-20.04 |  | true | true | true | true | 65 | 88 | 11
ubuntu-20.04 | true |  |  |  |  | 64 | 87 | 9
ubuntu-20.04 | true |  |  |  | true | 71 | 94 | 17
ubuntu-20.04 | true |  |  | true |  | 68 | 91 | 67
ubuntu-20.04 | true |  |  | true | true | 74 | 97 | 16
ubuntu-20.04 | true |  | true |  |  | 64 | 87 | 11
ubuntu-20.04 | true |  | true |  | true | 71 | 94 | 65
ubuntu-20.04 | true |  | true | true |  | 68 | 91 | 8
ubuntu-20.04 | true |  | true | true | true | 74 | 97 | 104
ubuntu-20.04 | true | true |  |  |  | 67 | 90 | 12
ubuntu-20.04 | true | true |  |  | true | 73 | 96 | 45
ubuntu-20.04 | true | true |  | true |  | 70 | 93 | 14
ubuntu-20.04 | true | true |  | true | true | 77 | 100 | 94
ubuntu-20.04 | true | true | true |  |  | 67 | 90 | 59
ubuntu-20.04 | true | true | true |  | true | 73 | 96 | 41
ubuntu-20.04 | true | true | true | true |  | 70 | 93 | 13
ubuntu-20.04 | true | true | true | true | true | 77 | 100 | 42
ubuntu-22.04 |  |  |  |  |  | 52 | 77 | 2
ubuntu-22.04 |  |  |  |  | true | 58 | 83 | 12
ubuntu-22.04 |  |  |  | true |  | 56 | 81 | 4
ubuntu-22.04 |  |  |  | true | true | 61 | 86 | 10
ubuntu-22.04 |  |  | true |  |  | 52 | 77 | 2
ubuntu-22.04 |  |  | true |  | true | 58 | 83 | 12
ubuntu-22.04 |  |  | true | true |  | 56 | 81 | 3
ubuntu-22.04 |  |  | true | true | true | 61 | 86 | 13
ubuntu-22.04 |  | true |  |  |  | 55 | 80 | 4
ubuntu-22.04 |  | true |  |  | true | 60 | 85 | 13
ubuntu-22.04 |  | true |  | true |  | 58 | 83 | 6
ubuntu-22.04 |  | true |  | true | true | 64 | 89 | 30
ubuntu-22.04 |  | true | true |  |  | 55 | 80 | 4
ubuntu-22.04 |  | true | true |  | true | 60 | 85 | 35
ubuntu-22.04 |  | true | true | true |  | 58 | 83 | 7
ubuntu-22.04 |  | true | true | true | true | 64 | 89 | 40
ubuntu-22.04 | true |  |  |  |  | 64 | 89 | 11
ubuntu-22.04 | true |  |  |  | true | 70 | 95 | 44
ubuntu-22.04 | true |  |  | true |  | 68 | 93 | 14
ubuntu-22.04 | true |  |  | true | true | 73 | 98 | 39
ubuntu-22.04 | true |  | true |  |  | 64 | 89 | 71
ubuntu-22.04 | true |  | true |  | true | 70 | 95 | 20
ubuntu-22.04 | true |  | true | true |  | 68 | 93 | 15
ubuntu-22.04 | true |  | true | true | true | 73 | 98 | 26
ubuntu-22.04 | true | true |  |  |  | 67 | 92 | 16
ubuntu-22.04 | true | true |  |  | true | 72 | 97 | 39
ubuntu-22.04 | true | true |  | true |  | 70 | 95 | 97
ubuntu-22.04 | true | true |  | true | true | 76 | 101 | 23
ubuntu-22.04 | true | true | true |  |  | 67 | 92 | 58
ubuntu-22.04 | true | true | true |  | true | 72 | 97 | 41
ubuntu-22.04 | true | true | true | true |  | 70 | 95 | 92
ubuntu-22.04 | true | true | true | true | true | 76 | 101 | 43
