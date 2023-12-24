# Maximize available disk space for build tasks

If the available disk space on Github runners is too little for your build job, this action might be for you.
If not: please go on, there's nothing to see here.

This table shows the amount of free space you receive when using the action with the various options.

OS | Android SDKs removed | .NET SDKs removed | Haskell removed | CodeQL Removed | Cached Docker Images Removed | GB freed | GB free | Elapsed Time (seconds) |
---|:--------------------:|:-----------------:|:---------------:|:--------------:|:----------------------------:|:--------:|:-------:|:----------------------:|
ubuntu-20.04 |  |  |  |  |  | 52 | 77 | 2
ubuntu-20.04 |  |  |  |  | true | 57 | 82 | 24
ubuntu-20.04 |  |  |  | true |  | 57 | 82 | 4
ubuntu-20.04 |  |  |  | true | true | 62 | 87 | 20
ubuntu-20.04 |  |  | true |  |  | 52 | 77 | 2
ubuntu-20.04 |  |  | true |  | true | 57 | 82 | 22
ubuntu-20.04 |  |  | true | true |  | 57 | 82 | 3
ubuntu-20.04 |  |  | true | true | true | 62 | 87 | 35
ubuntu-20.04 |  | true |  |  |  | 54 | 79 | 4
ubuntu-20.04 |  | true |  |  | true | 59 | 84 | 28
ubuntu-20.04 |  | true |  | true |  | 58 | 83 | 4
ubuntu-20.04 |  | true |  | true | true | 64 | 89 | 24
ubuntu-20.04 |  | true | true |  |  | 54 | 79 | 6
ubuntu-20.04 |  | true | true |  | true | 59 | 84 | 32
ubuntu-20.04 |  | true | true | true |  | 58 | 83 | 4
ubuntu-20.04 |  | true | true | true | true | 64 | 89 | 22
ubuntu-20.04 | true |  |  |  |  | 64 | 89 | 48
ubuntu-20.04 | true |  |  |  | true | 69 | 94 | 100
ubuntu-20.04 | true |  |  | true |  | 69 | 94 | 71
ubuntu-20.04 | true |  |  | true | true | 74 | 99 | 112
ubuntu-20.04 | true |  | true |  |  | 64 | 89 | 48
ubuntu-20.04 | true |  | true |  | true | 69 | 94 | 75
ubuntu-20.04 | true |  | true | true |  | 69 | 94 | 67
ubuntu-20.04 | true |  | true | true | true | 74 | 99 | 87
ubuntu-20.04 | true | true |  |  |  | 66 | 91 | 80
ubuntu-20.04 | true | true |  |  | true | 71 | 96 | 85
ubuntu-20.04 | true | true |  | true |  | 70 | 95 | 74
ubuntu-20.04 | true | true |  | true | true | 76 | 101 | 99
ubuntu-20.04 | true | true | true |  |  | 66 | 91 | 76
ubuntu-20.04 | true | true | true |  | true | 71 | 96 | 98
ubuntu-20.04 | true | true | true | true |  | 70 | 95 | 10
ubuntu-20.04 | true | true | true | true | true | 76 | 101 | 88
ubuntu-22.04 |  |  |  |  |  | 53 | 79 | 2
ubuntu-22.04 |  |  |  |  | true | 57 | 83 | 9
ubuntu-22.04 |  |  |  | true |  | 57 | 83 | 4
ubuntu-22.04 |  |  |  | true | true | 62 | 88 | 38
ubuntu-22.04 |  |  | true |  |  | 53 | 79 | 2
ubuntu-22.04 |  |  | true |  | true | 57 | 83 | 50
ubuntu-22.04 |  |  | true | true |  | 57 | 83 | 5
ubuntu-22.04 |  |  | true | true | true | 62 | 88 | 10
ubuntu-22.04 |  | true |  |  |  | 54 | 80 | 4
ubuntu-22.04 |  | true |  |  | true | 59 | 85 | 30
ubuntu-22.04 |  | true |  | true |  | 59 | 85 | 5
ubuntu-22.04 |  | true |  | true | true | 63 | 89 | 40
ubuntu-22.04 |  | true | true |  |  | 54 | 80 | 6
ubuntu-22.04 |  | true | true |  | true | 59 | 85 | 38
ubuntu-22.04 |  | true | true | true |  | 59 | 85 | 8
ubuntu-22.04 |  | true | true | true | true | 63 | 89 | 37
ubuntu-22.04 | true |  |  |  |  | 65 | 91 | 70
ubuntu-22.04 | true |  |  |  | true | 69 | 95 | 96
ubuntu-22.04 | true |  |  | true |  | 69 | 95 | 22
ubuntu-22.04 | true |  |  | true | true | 74 | 100 | 22
ubuntu-22.04 | true |  | true |  |  | 65 | 91 | 12
ubuntu-22.04 | true |  | true |  | true | 69 | 95 | 35
ubuntu-22.04 | true |  | true | true |  | 69 | 95 | 85
ubuntu-22.04 | true |  | true | true | true | 74 | 100 | 129
ubuntu-22.04 | true | true |  |  |  | 66 | 92 | 12
ubuntu-22.04 | true | true |  |  | true | 71 | 97 | 19
ubuntu-22.04 | true | true |  | true |  | 71 | 97 | 81
ubuntu-22.04 | true | true |  | true | true | 75 | 101 | 104
ubuntu-22.04 | true | true | true |  |  | 66 | 92 | 16
ubuntu-22.04 | true | true | true |  | true | 71 | 97 | 23
ubuntu-22.04 | true | true | true | true |  | 71 | 97 | 76
ubuntu-22.04 | true | true | true | true | true | 75 | 101 | 41
