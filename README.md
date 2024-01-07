# Maximize available disk space for build tasks

If the available disk space on Github runners is too little for your build job, this action might be for you.
If not: please go on, there's nothing to see here.

This table shows the amount of free space you receive when using the action with the various options.

OS | Android SDKs removed | .NET SDKs removed | Haskell removed | CodeQL Removed | Cached Docker Images Removed | GB freed | GB free | Elapsed Time (seconds) |
---|:--------------------:|:-----------------:|:---------------:|:--------------:|:----------------------------:|:--------:|:-------:|:----------------------:|
ubuntu-20.04 |  |  |  |  |  | 52 | 77 | 1
ubuntu-20.04 |  |  |  |  | true | 57 | 82 | 16
ubuntu-20.04 |  |  |  | true |  | 57 | 82 | 2
ubuntu-20.04 |  |  |  | true | true | 62 | 87 | 20
ubuntu-20.04 |  |  | true |  |  | 52 | 77 | 2
ubuntu-20.04 |  |  | true |  | true | 57 | 82 | 7
ubuntu-20.04 |  |  | true | true |  | 57 | 82 | 3
ubuntu-20.04 |  |  | true | true | true | 62 | 87 | 21
ubuntu-20.04 |  | true |  |  |  | 54 | 79 | 5
ubuntu-20.04 |  | true |  |  | true | 59 | 84 | 26
ubuntu-20.04 |  | true |  | true |  | 58 | 83 | 4
ubuntu-20.04 |  | true |  | true | true | 64 | 89 | 21
ubuntu-20.04 |  | true | true |  |  | 54 | 79 | 3
ubuntu-20.04 |  | true | true |  | true | 59 | 84 | 20
ubuntu-20.04 |  | true | true | true |  | 58 | 83 | 5
ubuntu-20.04 |  | true | true | true | true | 64 | 89 | 23
ubuntu-20.04 | true |  |  |  |  | 64 | 89 | 87
ubuntu-20.04 | true |  |  |  | true | 69 | 94 | 14
ubuntu-20.04 | true |  |  | true |  | 69 | 94 | 67
ubuntu-20.04 | true |  |  | true | true | 74 | 99 | 76
ubuntu-20.04 | true |  | true |  |  | 64 | 89 | 78
ubuntu-20.04 | true |  | true |  | true | 69 | 94 | 90
ubuntu-20.04 | true |  | true | true |  | 69 | 94 | 63
ubuntu-20.04 | true |  | true | true | true | 74 | 99 | 31
ubuntu-20.04 | true | true |  |  |  | 66 | 91 | 65
ubuntu-20.04 | true | true |  |  | true | 71 | 96 | 17
ubuntu-20.04 | true | true |  | true |  | 70 | 95 | 79
ubuntu-20.04 | true | true |  | true | true | 76 | 101 | 70
ubuntu-20.04 | true | true | true |  |  | 66 | 91 | 54
ubuntu-20.04 | true | true | true |  | true | 71 | 96 | 97
ubuntu-20.04 | true | true | true | true |  | 70 | 95 | 79
ubuntu-20.04 | true | true | true | true | true | 76 | 101 | 30
ubuntu-22.04 |  |  |  |  |  | 53 | 79 | 2
ubuntu-22.04 |  |  |  |  | true | 57 | 83 | 36
ubuntu-22.04 |  |  |  | true |  | 57 | 83 | 4
ubuntu-22.04 |  |  |  | true | true | 62 | 88 | 10
ubuntu-22.04 |  |  | true |  |  | 53 | 79 | 2
ubuntu-22.04 |  |  | true |  | true | 57 | 83 | 37
ubuntu-22.04 |  |  | true | true |  | 57 | 83 | 4
ubuntu-22.04 |  |  | true | true | true | 62 | 88 | 39
ubuntu-22.04 |  | true |  |  |  | 54 | 80 | 6
ubuntu-22.04 |  | true |  |  | true | 59 | 85 | 44
ubuntu-22.04 |  | true |  | true |  | 59 | 85 | 6
ubuntu-22.04 |  | true |  | true | true | 63 | 89 | 11
ubuntu-22.04 |  | true | true |  |  | 54 | 80 | 4
ubuntu-22.04 |  | true | true |  | true | 59 | 85 | 8
ubuntu-22.04 |  | true | true | true |  | 59 | 85 | 5
ubuntu-22.04 |  | true | true | true | true | 63 | 89 | 12
ubuntu-22.04 | true |  |  |  |  | 65 | 91 | 17
ubuntu-22.04 | true |  |  |  | true | 69 | 95 | 19
ubuntu-22.04 | true |  |  | true |  | 69 | 95 | 17
ubuntu-22.04 | true |  |  | true | true | 74 | 100 | 137
ubuntu-22.04 | true |  | true |  |  | 65 | 91 | 16
ubuntu-22.04 | true |  | true |  | true | 69 | 95 | 23
ubuntu-22.04 | true |  | true | true |  | 69 | 95 | 85
ubuntu-22.04 | true |  | true | true | true | 74 | 100 | 24
ubuntu-22.04 | true | true |  |  |  | 66 | 92 | 16
ubuntu-22.04 | true | true |  |  | true | 71 | 97 | 120
ubuntu-22.04 | true | true |  | true |  | 71 | 97 | 73
ubuntu-22.04 | true | true |  | true | true | 75 | 101 | 112
ubuntu-22.04 | true | true | true |  |  | 66 | 92 | 17
ubuntu-22.04 | true | true | true |  | true | 71 | 97 | 122
ubuntu-22.04 | true | true | true | true |  | 71 | 97 | 95
ubuntu-22.04 | true | true | true | true | true | 75 | 101 | 20
