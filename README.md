# Maximize available disk space for build tasks

If the available disk space on Github runners is too little for your build job, this action might be for you.
If not: please go on, there's nothing to see here.

This table shows the amount of free space you receive when using the action with the various options.

OS | Android SDKs removed | .NET SDKs removed | Haskell removed | CodeQL Removed | Cached Docker Images Removed | GB freed | GB free | Elapsed Time (seconds) |
---|:--------------------:|:-----------------:|:---------------:|:--------------:|:----------------------------:|:--------:|:-------:|:----------------------:|
ubuntu-20.04 |  |  |  |  |  | 52 | 77 | 3
ubuntu-20.04 |  |  |  |  | true | 58 | 83 | 8
ubuntu-20.04 |  |  |  | true |  | 57 | 82 | 3
ubuntu-20.04 |  |  |  | true | true | 62 | 87 | 23
ubuntu-20.04 |  |  | true |  |  | 52 | 77 | 4
ubuntu-20.04 |  |  | true |  | true | 58 | 83 | 29
ubuntu-20.04 |  |  | true | true |  | 57 | 82 | 3
ubuntu-20.04 |  |  | true | true | true | 62 | 87 | 8
ubuntu-20.04 |  | true |  |  |  | 54 | 79 | 3
ubuntu-20.04 |  | true |  |  | true | 59 | 84 | 25
ubuntu-20.04 |  | true |  | true |  | 59 | 84 | 5
ubuntu-20.04 |  | true |  | true | true | 64 | 89 | 18
ubuntu-20.04 |  | true | true |  |  | 54 | 79 | 4
ubuntu-20.04 |  | true | true |  | true | 59 | 84 | 25
ubuntu-20.04 |  | true | true | true |  | 59 | 84 | 4
ubuntu-20.04 |  | true | true | true | true | 64 | 89 | 26
ubuntu-20.04 | true |  |  |  |  | 64 | 89 | 49
ubuntu-20.04 | true |  |  |  | true | 69 | 94 | 15
ubuntu-20.04 | true |  |  | true |  | 69 | 94 | 70
ubuntu-20.04 | true |  |  | true | true | 74 | 99 | 73
ubuntu-20.04 | true |  | true |  |  | 64 | 89 | 77
ubuntu-20.04 | true |  | true |  | true | 69 | 94 | 70
ubuntu-20.04 | true |  | true | true |  | 69 | 94 | 61
ubuntu-20.04 | true |  | true | true | true | 74 | 99 | 62
ubuntu-20.04 | true | true |  |  |  | 66 | 91 | 39
ubuntu-20.04 | true | true |  |  | true | 71 | 96 | 28
ubuntu-20.04 | true | true |  | true |  | 70 | 95 | 51
ubuntu-20.04 | true | true |  | true | true | 76 | 101 | 15
ubuntu-20.04 | true | true | true |  |  | 66 | 91 | 45
ubuntu-20.04 | true | true | true |  | true | 71 | 96 | 13
ubuntu-20.04 | true | true | true | true |  | 70 | 95 | 11
ubuntu-20.04 | true | true | true | true | true | 76 | 101 | 21
ubuntu-22.04 |  |  |  |  |  | 53 | 79 | 2
ubuntu-22.04 |  |  |  |  | true | 57 | 83 | 22
ubuntu-22.04 |  |  |  | true |  | 57 | 83 | 4
ubuntu-22.04 |  |  |  | true | true | 62 | 88 | 9
ubuntu-22.04 |  |  | true |  |  | 53 | 79 | 1
ubuntu-22.04 |  |  | true |  | true | 57 | 83 | 19
ubuntu-22.04 |  |  | true | true |  | 57 | 83 | 4
ubuntu-22.04 |  |  | true | true | true | 62 | 88 | 9
ubuntu-22.04 |  | true |  |  |  | 54 | 80 | 5
ubuntu-22.04 |  | true |  |  | true | 59 | 85 | 9
ubuntu-22.04 |  | true |  | true |  | 59 | 85 | 5
ubuntu-22.04 |  | true |  | true | true | 63 | 89 | 12
ubuntu-22.04 |  | true | true |  |  | 54 | 80 | 4
ubuntu-22.04 |  | true | true |  | true | 59 | 85 | 9
ubuntu-22.04 |  | true | true | true |  | 59 | 85 | 5
ubuntu-22.04 |  | true | true | true | true | 63 | 89 | 11
ubuntu-22.04 | true |  |  |  |  | 65 | 91 | 93
ubuntu-22.04 | true |  |  |  | true | 69 | 95 | 104
ubuntu-22.04 | true |  |  | true |  | 69 | 95 | 14
ubuntu-22.04 | true |  |  | true | true | 74 | 100 | 80
ubuntu-22.04 | true |  | true |  |  | 65 | 91 | 12
ubuntu-22.04 | true |  | true |  | true | 69 | 95 | 24
ubuntu-22.04 | true |  | true | true |  | 69 | 95 | 75
ubuntu-22.04 | true |  | true | true | true | 74 | 100 | 99
ubuntu-22.04 | true | true |  |  |  | 66 | 92 | 59
ubuntu-22.04 | true | true |  |  | true | 71 | 97 | 20
ubuntu-22.04 | true | true |  | true |  | 71 | 97 | 90
ubuntu-22.04 | true | true |  | true | true | 75 | 101 | 114
ubuntu-22.04 | true | true | true |  |  | 66 | 92 | 74
ubuntu-22.04 | true | true | true |  | true | 71 | 97 | 116
ubuntu-22.04 | true | true | true | true |  | 71 | 97 | 86
ubuntu-22.04 | true | true | true | true | true | 75 | 101 | 21
