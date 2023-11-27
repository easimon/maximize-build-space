# Maximize available disk space for build tasks

If the available disk space on Github runners is too little for your build job, this action might be for you.
If not: please go on, there's nothing to see here.

This table shows the amount of free space you receive when using the action with the various options.

OS | Android SDKs removed | .NET SDKs removed | Haskell removed | CodeQL Removed | Cached Docker Images Removed | GB freed | GB free | Elapsed Time (seconds) |
---|:--------------------:|:-----------------:|:---------------:|:--------------:|:----------------------------:|:--------:|:-------:|:----------------------:|
ubuntu-20.04 |  |  |  |  |  | 52 | 75 | 2
ubuntu-20.04 |  |  |  |  | true | 59 | 82 | 26
ubuntu-20.04 |  |  |  | true |  | 56 | 79 | 3
ubuntu-20.04 |  |  |  | true | true | 62 | 85 | 40
ubuntu-20.04 |  |  | true |  |  | 52 | 75 | 2
ubuntu-20.04 |  |  | true |  | true | 59 | 82 | 9
ubuntu-20.04 |  |  | true | true |  | 56 | 79 | 3
ubuntu-20.04 |  |  | true | true | true | 62 | 85 | 8
ubuntu-20.04 |  | true |  |  |  | 55 | 78 | 6
ubuntu-20.04 |  | true |  |  | true | 62 | 85 | 27
ubuntu-20.04 |  | true |  | true |  | 59 | 82 | 5
ubuntu-20.04 |  | true |  | true | true | 65 | 88 | 39
ubuntu-20.04 |  | true | true |  |  | 55 | 78 | 3
ubuntu-20.04 |  | true | true |  | true | 62 | 85 | 30
ubuntu-20.04 |  | true | true | true |  | 59 | 82 | 2
ubuntu-20.04 |  | true | true | true | true | 65 | 88 | 38
ubuntu-20.04 | true |  |  |  |  | 64 | 87 | 10
ubuntu-20.04 | true |  |  |  | true | 71 | 94 | 45
ubuntu-20.04 | true |  |  | true |  | 68 | 91 | 9
ubuntu-20.04 | true |  |  | true | true | 74 | 97 | 45
ubuntu-20.04 | true |  | true |  |  | 64 | 87 | 10
ubuntu-20.04 | true |  | true |  | true | 71 | 94 | 102
ubuntu-20.04 | true |  | true | true |  | 68 | 91 | 62
ubuntu-20.04 | true |  | true | true | true | 74 | 97 | 20
ubuntu-20.04 | true | true |  |  |  | 67 | 90 | 8
ubuntu-20.04 | true | true |  |  | true | 73 | 96 | 94
ubuntu-20.04 | true | true |  | true |  | 70 | 93 | 67
ubuntu-20.04 | true | true |  | true | true | 77 | 100 | 15
ubuntu-20.04 | true | true | true |  |  | 67 | 90 | 8
ubuntu-20.04 | true | true | true |  | true | 73 | 96 | 18
ubuntu-20.04 | true | true | true | true |  | 70 | 93 | 11
ubuntu-20.04 | true | true | true | true | true | 77 | 100 | 18
ubuntu-22.04 |  |  |  |  |  | 52 | 77 | 2
ubuntu-22.04 |  |  |  |  | true | 58 | 83 | 25
ubuntu-22.04 |  |  |  | true |  | 56 | 81 | 3
ubuntu-22.04 |  |  |  | true | true | 61 | 86 | 30
ubuntu-22.04 |  |  | true |  |  | 52 | 77 | 2
ubuntu-22.04 |  |  | true |  | true | 58 | 83 | 27
ubuntu-22.04 |  |  | true | true |  | 56 | 81 | 3
ubuntu-22.04 |  |  | true | true | true | 61 | 86 | 30
ubuntu-22.04 |  | true |  |  |  | 55 | 80 | 4
ubuntu-22.04 |  | true |  |  | true | 60 | 85 | 30
ubuntu-22.04 |  | true |  | true |  | 58 | 83 | 4
ubuntu-22.04 |  | true |  | true | true | 64 | 89 | 13
ubuntu-22.04 |  | true | true |  |  | 55 | 80 | 5
ubuntu-22.04 |  | true | true |  | true | 60 | 85 | 29
ubuntu-22.04 |  | true | true | true |  | 58 | 83 | 4
ubuntu-22.04 |  | true | true | true | true | 64 | 89 | 12
ubuntu-22.04 | true |  |  |  |  | 64 | 89 | 13
ubuntu-22.04 | true |  |  |  | true | 70 | 95 | 24
ubuntu-22.04 | true |  |  | true |  | 68 | 93 | 16
ubuntu-22.04 | true |  |  | true | true | 73 | 98 | 37
ubuntu-22.04 | true |  | true |  |  | 64 | 89 | 15
ubuntu-22.04 | true |  | true |  | true | 70 | 95 | 40
ubuntu-22.04 | true |  | true | true |  | 68 | 93 | 65
ubuntu-22.04 | true |  | true | true | true | 73 | 98 | 22
ubuntu-22.04 | true | true |  |  |  | 67 | 92 | 76
ubuntu-22.04 | true | true |  |  | true | 72 | 97 | 117
ubuntu-22.04 | true | true |  | true |  | 70 | 95 | 16
ubuntu-22.04 | true | true |  | true | true | 76 | 101 | 89
ubuntu-22.04 | true | true | true |  |  | 67 | 92 | 12
ubuntu-22.04 | true | true | true |  | true | 72 | 97 | 35
ubuntu-22.04 | true | true | true | true |  | 70 | 95 | 15
ubuntu-22.04 | true | true | true | true | true | 76 | 101 | 118
