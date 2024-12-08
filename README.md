# Maximize available disk space for build tasks

If the available disk space on Github runners is too little for your build job, this action might be for you.
If not: please go on, there's nothing to see here.

This table shows the amount of free space you receive when using the action with the various options.

OS | Android SDKs removed | .NET SDKs removed | Haskell removed | CodeQL Removed | Cached Docker Images Removed | GB freed | GB free | Elapsed Time (seconds) |
---|:--------------------:|:-----------------:|:---------------:|:--------------:|:----------------------------:|:--------:|:-------:|:----------------------:|
ubuntu-20.04 |  |  |  |  |  | 62 | 83 | 2
ubuntu-20.04 |  |  |  |  | true | 65 | 86 | 7
ubuntu-20.04 |  |  |  | true |  | 67 | 88 | 4
ubuntu-20.04 |  |  |  | true | true | 70 | 91 | 8
ubuntu-20.04 |  |  | true |  |  | 62 | 83 | 2
ubuntu-20.04 |  |  | true |  | true | 65 | 86 | 8
ubuntu-20.04 |  |  | true | true |  | 67 | 88 | 5
ubuntu-20.04 |  |  | true | true | true | 70 | 91 | 31
ubuntu-20.04 |  | true |  |  |  | 64 | 85 | 5
ubuntu-20.04 |  | true |  |  | true | 66 | 87 | 9
ubuntu-20.04 |  | true |  | true |  | 69 | 90 | 5
ubuntu-20.04 |  | true |  | true | true | 71 | 92 | 48
ubuntu-20.04 |  | true | true |  |  | 64 | 85 | 5
ubuntu-20.04 |  | true | true |  | true | 66 | 87 | 36
ubuntu-20.04 |  | true | true | true |  | 69 | 90 | 5
ubuntu-20.04 |  | true | true | true | true | 71 | 92 | 10
ubuntu-20.04 | true |  |  |  |  | 70 | 91 | 17
ubuntu-20.04 | true |  |  |  | true | 72 | 93 | 21
ubuntu-20.04 | true |  |  | true |  | 75 | 96 | 17
ubuntu-20.04 | true |  |  | true | true | 77 | 98 | 90
ubuntu-20.04 | true |  | true |  |  | 70 | 91 | 71
ubuntu-20.04 | true |  | true |  | true | 72 | 93 | 47
ubuntu-20.04 | true |  | true | true |  | 75 | 96 | 90
ubuntu-20.04 | true |  | true | true | true | 77 | 98 | 21
ubuntu-20.04 | true | true |  |  |  | 71 | 92 | 15
ubuntu-20.04 | true | true |  |  | true | 74 | 95 | 83
ubuntu-20.04 | true | true |  | true |  | 76 | 97 | 69
ubuntu-20.04 | true | true |  | true | true | 79 | 100 | 109
ubuntu-20.04 | true | true | true |  |  | 71 | 92 | 137
ubuntu-20.04 | true | true | true |  | true | 74 | 95 | 113
ubuntu-20.04 | true | true | true | true |  | 76 | 97 | 22
ubuntu-20.04 | true | true | true | true | true | 79 | 100 | 146
ubuntu-22.04 |  |  |  |  |  | 62 | 84 | 2
ubuntu-22.04 |  |  |  |  | true | 65 | 87 | 26
ubuntu-22.04 |  |  |  | true |  | 67 | 89 | 3
ubuntu-22.04 |  |  |  | true | true | 70 | 92 | 6
ubuntu-22.04 |  |  | true |  |  | 62 | 84 | 2
ubuntu-22.04 |  |  | true |  | true | 65 | 87 | 20
ubuntu-22.04 |  |  | true | true |  | 67 | 89 | 3
ubuntu-22.04 |  |  | true | true | true | 70 | 92 | 7
ubuntu-22.04 |  | true |  |  |  | 64 | 86 | 3
ubuntu-22.04 |  | true |  |  | true | 66 | 88 | 34
ubuntu-22.04 |  | true |  | true |  | 69 | 91 | 5
ubuntu-22.04 |  | true |  | true | true | 71 | 93 | 8
ubuntu-22.04 |  | true | true |  |  | 64 | 86 | 3
ubuntu-22.04 |  | true | true |  | true | 66 | 88 | 7
ubuntu-22.04 |  | true | true | true |  | 69 | 91 | 5
ubuntu-22.04 |  | true | true | true | true | 71 | 93 | 9
ubuntu-22.04 | true |  |  |  |  | 70 | 92 | 14
ubuntu-22.04 | true |  |  |  | true | 72 | 94 | 20
ubuntu-22.04 | true |  |  | true |  | 75 | 97 | 75
ubuntu-22.04 | true |  |  | true | true | 78 | 100 | 25
ubuntu-22.04 | true |  | true |  |  | 70 | 92 | 83
ubuntu-22.04 | true |  | true |  | true | 72 | 94 | 87
ubuntu-22.04 | true |  | true | true |  | 75 | 97 | 15
ubuntu-22.04 | true |  | true | true | true | 78 | 100 | 116
ubuntu-22.04 | true | true |  |  |  | 72 | 94 | 11
ubuntu-22.04 | true | true |  |  | true | 74 | 96 | 20
ubuntu-22.04 | true | true |  | true |  | 77 | 99 | 20
ubuntu-22.04 | true | true |  | true | true | 79 | 101 | 82
ubuntu-22.04 | true | true | true |  |  | 72 | 94 | 88
ubuntu-22.04 | true | true | true |  | true | 74 | 96 | 20
ubuntu-22.04 | true | true | true | true |  | 77 | 99 | 15
ubuntu-22.04 | true | true | true | true | true | 79 | 101 | 23
