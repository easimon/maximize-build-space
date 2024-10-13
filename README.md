# Maximize available disk space for build tasks

If the available disk space on Github runners is too little for your build job, this action might be for you.
If not: please go on, there's nothing to see here.

This table shows the amount of free space you receive when using the action with the various options.

OS | Android SDKs removed | .NET SDKs removed | Haskell removed | CodeQL Removed | Cached Docker Images Removed | GB freed | GB free | Elapsed Time (seconds) |
---|:--------------------:|:-----------------:|:---------------:|:--------------:|:----------------------------:|:--------:|:-------:|:----------------------:|
ubuntu-20.04 |  |  |  |  |  | 63 | 83 | 2
ubuntu-20.04 |  |  |  |  | true | 66 | 86 | 9
ubuntu-20.04 |  |  |  | true |  | 68 | 88 | 3
ubuntu-20.04 |  |  |  | true | true | 71 | 91 | 9
ubuntu-20.04 |  |  | true |  |  | 63 | 83 | 2
ubuntu-20.04 |  |  | true |  | true | 66 | 86 | 52
ubuntu-20.04 |  |  | true | true |  | 68 | 88 | 4
ubuntu-20.04 |  |  | true | true | true | 71 | 91 | 59
ubuntu-20.04 |  | true |  |  |  | 64 | 84 | 3
ubuntu-20.04 |  | true |  |  | true | 68 | 88 | 36
ubuntu-20.04 |  | true |  | true |  | 69 | 89 | 4
ubuntu-20.04 |  | true |  | true | true | 72 | 92 | 47
ubuntu-20.04 |  | true | true |  |  | 64 | 84 | 4
ubuntu-20.04 |  | true | true |  | true | 68 | 88 | 58
ubuntu-20.04 |  | true | true | true |  | 69 | 89 | 5
ubuntu-20.04 |  | true | true | true | true | 72 | 92 | 9
ubuntu-20.04 | true |  |  |  |  | 70 | 90 | 13
ubuntu-20.04 | true |  |  |  | true | 73 | 93 | 126
ubuntu-20.04 | true |  |  | true |  | 75 | 95 | 57
ubuntu-20.04 | true |  |  | true | true | 78 | 98 | 78
ubuntu-20.04 | true |  | true |  |  | 70 | 90 | 14
ubuntu-20.04 | true |  | true |  | true | 73 | 93 | 93
ubuntu-20.04 | true |  | true | true |  | 75 | 95 | 54
ubuntu-20.04 | true |  | true | true | true | 78 | 98 | 27
ubuntu-20.04 | true | true |  |  |  | 72 | 92 | 57
ubuntu-20.04 | true | true |  |  | true | 75 | 95 | 21
ubuntu-20.04 | true | true |  | true |  | 77 | 97 | 18
ubuntu-20.04 | true | true |  | true | true | 80 | 100 | 185
ubuntu-20.04 | true | true | true |  |  | 72 | 92 | 16
ubuntu-20.04 | true | true | true |  | true | 75 | 95 | 22
ubuntu-20.04 | true | true | true | true |  | 77 | 97 | 86
ubuntu-20.04 | true | true | true | true | true | 80 | 100 | 120
ubuntu-22.04 |  |  |  |  |  | 62 | 84 | 2
ubuntu-22.04 |  |  |  |  | true | 65 | 87 | 25
ubuntu-22.04 |  |  |  | true |  | 67 | 89 | 4
ubuntu-22.04 |  |  |  | true | true | 70 | 92 | 8
ubuntu-22.04 |  |  | true |  |  | 62 | 84 | 2
ubuntu-22.04 |  |  | true |  | true | 65 | 87 | 8
ubuntu-22.04 |  |  | true | true |  | 67 | 89 | 3
ubuntu-22.04 |  |  | true | true | true | 70 | 92 | 59
ubuntu-22.04 |  | true |  |  |  | 64 | 86 | 4
ubuntu-22.04 |  | true |  |  | true | 67 | 89 | 6
ubuntu-22.04 |  | true |  | true |  | 69 | 91 | 4
ubuntu-22.04 |  | true |  | true | true | 72 | 94 | 23
ubuntu-22.04 |  | true | true |  |  | 64 | 86 | 4
ubuntu-22.04 |  | true | true |  | true | 67 | 89 | 32
ubuntu-22.04 |  | true | true | true |  | 69 | 91 | 5
ubuntu-22.04 |  | true | true | true | true | 72 | 94 | 9
ubuntu-22.04 | true |  |  |  |  | 70 | 92 | 12
ubuntu-22.04 | true |  |  |  | true | 73 | 95 | 115
ubuntu-22.04 | true |  |  | true |  | 74 | 96 | 18
ubuntu-22.04 | true |  |  | true | true | 78 | 100 | 15
ubuntu-22.04 | true |  | true |  |  | 70 | 92 | 12
ubuntu-22.04 | true |  | true |  | true | 73 | 95 | 19
ubuntu-22.04 | true |  | true | true |  | 74 | 96 | 86
ubuntu-22.04 | true |  | true | true | true | 78 | 100 | 18
ubuntu-22.04 | true | true |  |  |  | 71 | 93 | 98
ubuntu-22.04 | true | true |  |  | true | 74 | 96 | 28
ubuntu-22.04 | true | true |  | true |  | 76 | 98 | 125
ubuntu-22.04 | true | true |  | true | true | 79 | 101 | 92
ubuntu-22.04 | true | true | true |  |  | 71 | 93 | 100
ubuntu-22.04 | true | true | true |  | true | 74 | 96 | 95
ubuntu-22.04 | true | true | true | true |  | 76 | 98 | 16
ubuntu-22.04 | true | true | true | true | true | 79 | 101 | 17
