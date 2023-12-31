# Maximize available disk space for build tasks

If the available disk space on Github runners is too little for your build job, this action might be for you.
If not: please go on, there's nothing to see here.

This table shows the amount of free space you receive when using the action with the various options.

OS | Android SDKs removed | .NET SDKs removed | Haskell removed | CodeQL Removed | Cached Docker Images Removed | GB freed | GB free | Elapsed Time (seconds) |
---|:--------------------:|:-----------------:|:---------------:|:--------------:|:----------------------------:|:--------:|:-------:|:----------------------:|
ubuntu-20.04 |  |  |  |  |  | 52 | 77 | 4
ubuntu-20.04 |  |  |  |  | true | 57 | 82 | 27
ubuntu-20.04 |  |  |  | true |  | 57 | 82 | 2
ubuntu-20.04 |  |  |  | true | true | 62 | 87 | 8
ubuntu-20.04 |  |  | true |  |  | 52 | 77 | 2
ubuntu-20.04 |  |  | true |  | true | 57 | 82 | 20
ubuntu-20.04 |  |  | true | true |  | 57 | 82 | 3
ubuntu-20.04 |  |  | true | true | true | 62 | 87 | 23
ubuntu-20.04 |  | true |  |  |  | 54 | 79 | 3
ubuntu-20.04 |  | true |  |  | true | 59 | 84 | 22
ubuntu-20.04 |  | true |  | true |  | 58 | 83 | 4
ubuntu-20.04 |  | true |  | true | true | 64 | 89 | 26
ubuntu-20.04 |  | true | true |  |  | 54 | 79 | 4
ubuntu-20.04 |  | true | true |  | true | 59 | 84 | 29
ubuntu-20.04 |  | true | true | true |  | 58 | 83 | 5
ubuntu-20.04 |  | true | true | true | true | 64 | 89 | 20
ubuntu-20.04 | true |  |  |  |  | 64 | 89 | 8
ubuntu-20.04 | true |  |  |  | true | 69 | 94 | 89
ubuntu-20.04 | true |  |  | true |  | 69 | 94 | 74
ubuntu-20.04 | true |  |  | true | true | 74 | 99 | 27
ubuntu-20.04 | true |  | true |  |  | 64 | 89 | 67
ubuntu-20.04 | true |  | true |  | true | 69 | 94 | 70
ubuntu-20.04 | true |  | true | true |  | 69 | 94 | 48
ubuntu-20.04 | true |  | true | true | true | 74 | 99 | 106
ubuntu-20.04 | true | true |  |  |  | 66 | 91 | 68
ubuntu-20.04 | true | true |  |  | true | 71 | 96 | 96
ubuntu-20.04 | true | true |  | true |  | 70 | 95 | 11
ubuntu-20.04 | true | true |  | true | true | 76 | 101 | 73
ubuntu-20.04 | true | true | true |  |  | 66 | 91 | 14
ubuntu-20.04 | true | true | true |  | true | 71 | 96 | 86
ubuntu-20.04 | true | true | true | true |  | 70 | 95 | 13
ubuntu-20.04 | true | true | true | true | true | 76 | 101 | 21
ubuntu-22.04 |  |  |  |  |  | 53 | 79 | 2
ubuntu-22.04 |  |  |  |  | true | 57 | 83 | 9
ubuntu-22.04 |  |  |  | true |  | 57 | 83 | 4
ubuntu-22.04 |  |  |  | true | true | 62 | 88 | 25
ubuntu-22.04 |  |  | true |  |  | 53 | 79 | 2
ubuntu-22.04 |  |  | true |  | true | 57 | 83 | 28
ubuntu-22.04 |  |  | true | true |  | 57 | 83 | 4
ubuntu-22.04 |  |  | true | true | true | 62 | 88 | 10
ubuntu-22.04 |  | true |  |  |  | 54 | 80 | 6
ubuntu-22.04 |  | true |  |  | true | 59 | 85 | 34
ubuntu-22.04 |  | true |  | true |  | 59 | 85 | 10
ubuntu-22.04 |  | true |  | true | true | 63 | 89 | 33
ubuntu-22.04 |  | true | true |  |  | 54 | 80 | 6
ubuntu-22.04 |  | true | true |  | true | 59 | 85 | 45
ubuntu-22.04 |  | true | true | true |  | 59 | 85 | 8
ubuntu-22.04 |  | true | true | true | true | 63 | 89 | 9
ubuntu-22.04 | true |  |  |  |  | 65 | 91 | 80
ubuntu-22.04 | true |  |  |  | true | 69 | 95 | 131
ubuntu-22.04 | true |  |  | true |  | 69 | 95 | 18
ubuntu-22.04 | true |  |  | true | true | 74 | 100 | 77
ubuntu-22.04 | true |  | true |  |  | 65 | 91 | 15
ubuntu-22.04 | true |  | true |  | true | 69 | 95 | 26
ubuntu-22.04 | true |  | true | true |  | 69 | 95 | 67
ubuntu-22.04 | true |  | true | true | true | 74 | 100 | 118
ubuntu-22.04 | true | true |  |  |  | 66 | 92 | 80
ubuntu-22.04 | true | true |  |  | true | 71 | 97 | 124
ubuntu-22.04 | true | true |  | true |  | 71 | 97 | 230
ubuntu-22.04 | true | true |  | true | true | 75 | 101 | 95
ubuntu-22.04 | true | true | true |  |  | 66 | 92 | 12
ubuntu-22.04 | true | true | true |  | true | 71 | 97 | 80
ubuntu-22.04 | true | true | true | true |  | 71 | 97 | 99
ubuntu-22.04 | true | true | true | true | true | 75 | 101 | 21
