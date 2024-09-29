# Maximize available disk space for build tasks

If the available disk space on Github runners is too little for your build job, this action might be for you.
If not: please go on, there's nothing to see here.

This table shows the amount of free space you receive when using the action with the various options.

OS | Android SDKs removed | .NET SDKs removed | Haskell removed | CodeQL Removed | Cached Docker Images Removed | GB freed | GB free | Elapsed Time (seconds) |
---|:--------------------:|:-----------------:|:---------------:|:--------------:|:----------------------------:|:--------:|:-------:|:----------------------:|
ubuntu-20.04 |  |  |  |  |  | 63 | 83 | 2
ubuntu-20.04 |  |  |  |  | true | 66 | 86 | 10
ubuntu-20.04 |  |  |  | true |  | 68 | 88 | 4
ubuntu-20.04 |  |  |  | true | true | 71 | 91 | 10
ubuntu-20.04 |  |  | true |  |  | 63 | 83 | 2
ubuntu-20.04 |  |  | true |  | true | 66 | 86 | 37
ubuntu-20.04 |  |  | true | true |  | 68 | 88 | 4
ubuntu-20.04 |  |  | true | true | true | 71 | 91 | 59
ubuntu-20.04 |  | true |  |  |  | 64 | 84 | 5
ubuntu-20.04 |  | true |  |  | true | 68 | 88 | 45
ubuntu-20.04 |  | true |  | true |  | 69 | 89 | 5
ubuntu-20.04 |  | true |  | true | true | 72 | 92 | 59
ubuntu-20.04 |  | true | true |  |  | 64 | 84 | 4
ubuntu-20.04 |  | true | true |  | true | 68 | 88 | 10
ubuntu-20.04 |  | true | true | true |  | 69 | 89 | 6
ubuntu-20.04 |  | true | true | true | true | 72 | 92 | 50
ubuntu-20.04 | true |  |  |  |  | 70 | 90 | 95
ubuntu-20.04 | true |  |  |  | true | 73 | 93 | 230
ubuntu-20.04 | true |  |  | true |  | 75 | 95 | 12
ubuntu-20.04 | true |  |  | true | true | 78 | 98 | 122
ubuntu-20.04 | true |  | true |  |  | 70 | 90 | 285
ubuntu-20.04 | true |  | true |  | true | 73 | 93 | 106
ubuntu-20.04 | true |  | true | true |  | 75 | 95 | 68
ubuntu-20.04 | true |  | true | true | true | 78 | 98 | 76
ubuntu-20.04 | true | true |  |  |  | 72 | 92 | 15
ubuntu-20.04 | true | true |  |  | true | 75 | 95 | 131
ubuntu-20.04 | true | true |  | true |  | 77 | 97 | 108
ubuntu-20.04 | true | true |  | true | true | 80 | 100 | 74
ubuntu-20.04 | true | true | true |  |  | 72 | 92 | 16
ubuntu-20.04 | true | true | true |  | true | 75 | 95 | 143
ubuntu-20.04 | true | true | true | true |  | 77 | 97 | 95
ubuntu-20.04 | true | true | true | true | true | 80 | 100 | 147
ubuntu-22.04 |  |  |  |  |  | 63 | 84 | 1
ubuntu-22.04 |  |  |  |  | true | 66 | 87 | 30
ubuntu-22.04 |  |  |  | true |  | 67 | 88 | 3
ubuntu-22.04 |  |  |  | true | true | 71 | 92 | 7
ubuntu-22.04 |  |  | true |  |  | 62 | 83 | 2
ubuntu-22.04 |  |  | true |  | true | 66 | 87 | 7
ubuntu-22.04 |  |  | true | true |  | 67 | 88 | 4
ubuntu-22.04 |  |  | true | true | true | 71 | 92 | 39
ubuntu-22.04 |  | true |  |  |  | 64 | 85 | 4
ubuntu-22.04 |  | true |  |  | true | 67 | 88 | 6
ubuntu-22.04 |  | true |  | true |  | 69 | 90 | 4
ubuntu-22.04 |  | true |  | true | true | 72 | 93 | 44
ubuntu-22.04 |  | true | true |  |  | 64 | 85 | 3
ubuntu-22.04 |  | true | true |  | true | 67 | 88 | 7
ubuntu-22.04 |  | true | true | true |  | 69 | 90 | 5
ubuntu-22.04 |  | true | true | true | true | 72 | 93 | 44
ubuntu-22.04 | true |  |  |  |  | 70 | 91 | 13
ubuntu-22.04 | true |  |  |  | true | 73 | 94 | 132
ubuntu-22.04 | true |  |  | true |  | 75 | 96 | 12
ubuntu-22.04 | true |  |  | true | true | 78 | 99 | 15
ubuntu-22.04 | true |  | true |  |  | 70 | 91 | 114
ubuntu-22.04 | true |  | true |  | true | 73 | 94 | 15
ubuntu-22.04 | true |  | true | true |  | 75 | 96 | 14
ubuntu-22.04 | true |  | true | true | true | 78 | 99 | 144
ubuntu-22.04 | true | true |  |  |  | 71 | 92 | 89
ubuntu-22.04 | true | true |  |  | true | 75 | 96 | 141
ubuntu-22.04 | true | true |  | true |  | 76 | 97 | 84
ubuntu-22.04 | true | true |  | true | true | 80 | 101 | 17
ubuntu-22.04 | true | true | true |  |  | 71 | 92 | 75
ubuntu-22.04 | true | true | true |  | true | 75 | 96 | 20
ubuntu-22.04 | true | true | true | true |  | 76 | 97 | 13
ubuntu-22.04 | true | true | true | true | true | 80 | 101 | 20
