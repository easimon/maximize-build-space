# Maximize available disk space for build tasks

If the available disk space on Github runners is too little for your build job, this action might be for you.
If not: please go on, there's nothing to see here.

This table shows the amount of free space you receive when using the action with the various options.

OS | Android SDKs removed | .NET SDKs removed | Haskell removed | CodeQL Removed | Cached Docker Images Removed | GB freed | GB free | Elapsed Time (seconds) |
---|:--------------------:|:-----------------:|:---------------:|:--------------:|:----------------------------:|:--------:|:-------:|:----------------------:|
ubuntu-20.04 |  |  |  |  |  | 62 | 81 | 2
ubuntu-20.04 |  |  |  |  | true | 65 | 84 | 26
ubuntu-20.04 |  |  |  | true |  | 67 | 86 | 3
ubuntu-20.04 |  |  |  | true | true | 70 | 89 | 34
ubuntu-20.04 |  |  | true |  |  | 62 | 81 | 2
ubuntu-20.04 |  |  | true |  | true | 65 | 84 | 29
ubuntu-20.04 |  |  | true | true |  | 67 | 86 | 2
ubuntu-20.04 |  |  | true | true | true | 70 | 89 | 32
ubuntu-20.04 |  | true |  |  |  | 64 | 83 | 4
ubuntu-20.04 |  | true |  |  | true | 67 | 86 | 28
ubuntu-20.04 |  | true |  | true |  | 69 | 88 | 7
ubuntu-20.04 |  | true |  | true | true | 72 | 91 | 9
ubuntu-20.04 |  | true | true |  |  | 64 | 83 | 4
ubuntu-20.04 |  | true | true |  | true | 67 | 86 | 33
ubuntu-20.04 |  | true | true | true |  | 69 | 88 | 5
ubuntu-20.04 |  | true | true | true | true | 72 | 91 | 120
ubuntu-20.04 | true |  |  |  |  | 71 | 90 | 49
ubuntu-20.04 | true |  |  |  | true | 74 | 93 | 12
ubuntu-20.04 | true |  |  | true |  | 76 | 95 | 44
ubuntu-20.04 | true |  |  | true | true | 79 | 98 | 12
ubuntu-20.04 | true |  | true |  |  | 71 | 90 | 59
ubuntu-20.04 | true |  | true |  | true | 74 | 93 | 116
ubuntu-20.04 | true |  | true | true |  | 76 | 95 | 12
ubuntu-20.04 | true |  | true | true | true | 79 | 98 | 82
ubuntu-20.04 | true | true |  |  |  | 72 | 91 | 8
ubuntu-20.04 | true | true |  |  | true | 76 | 95 | 10
ubuntu-20.04 | true | true |  | true |  | 77 | 96 | 13
ubuntu-20.04 | true | true |  | true | true | 80 | 99 | 14
ubuntu-20.04 | true | true | true |  |  | 72 | 91 | 9
ubuntu-20.04 | true | true | true |  | true | 76 | 95 | 88
ubuntu-20.04 | true | true | true | true |  | 77 | 96 | 39
ubuntu-20.04 | true | true | true | true | true | 80 | 99 | 110
ubuntu-22.04 |  |  |  |  |  | 62 | 82 | 2
ubuntu-22.04 |  |  |  |  | true | 65 | 85 | 7
ubuntu-22.04 |  |  |  | true |  | 67 | 87 | 3
ubuntu-22.04 |  |  |  | true | true | 70 | 90 | 7
ubuntu-22.04 |  |  | true |  |  | 62 | 82 | 2
ubuntu-22.04 |  |  | true |  | true | 65 | 85 | 7
ubuntu-22.04 |  |  | true | true |  | 67 | 87 | 4
ubuntu-22.04 |  |  | true | true | true | 70 | 90 | 22
ubuntu-22.04 |  | true |  |  |  | 64 | 84 | 3
ubuntu-22.04 |  | true |  |  | true | 67 | 87 | 8
ubuntu-22.04 |  | true |  | true |  | 69 | 89 | 5
ubuntu-22.04 |  | true |  | true | true | 72 | 92 | 30
ubuntu-22.04 |  | true | true |  |  | 64 | 84 | 4
ubuntu-22.04 |  | true | true |  | true | 67 | 87 | 43
ubuntu-22.04 |  | true | true | true |  | 69 | 89 | 6
ubuntu-22.04 |  | true | true | true | true | 72 | 92 | 29
ubuntu-22.04 | true |  |  |  |  | 71 | 91 | 62
ubuntu-22.04 | true |  |  |  | true | 74 | 94 | 121
ubuntu-22.04 | true |  |  | true |  | 76 | 96 | 55
ubuntu-22.04 | true |  |  | true | true | 79 | 99 | 67
ubuntu-22.04 | true |  | true |  |  | 71 | 91 | 55
ubuntu-22.04 | true |  | true |  | true | 74 | 94 | 12
ubuntu-22.04 | true |  | true | true |  | 76 | 96 | 71
ubuntu-22.04 | true |  | true | true | true | 79 | 99 | 92
ubuntu-22.04 | true | true |  |  |  | 72 | 92 | 54
ubuntu-22.04 | true | true |  |  | true | 76 | 96 | 106
ubuntu-22.04 | true | true |  | true |  | 77 | 97 | 14
ubuntu-22.04 | true | true |  | true | true | 80 | 100 | 102
ubuntu-22.04 | true | true | true |  |  | 72 | 92 | 11
ubuntu-22.04 | true | true | true |  | true | 76 | 96 | 98
ubuntu-22.04 | true | true | true | true |  | 77 | 97 | 81
ubuntu-22.04 | true | true | true | true | true | 80 | 100 | 18
