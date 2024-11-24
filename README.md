# Maximize available disk space for build tasks

If the available disk space on Github runners is too little for your build job, this action might be for you.
If not: please go on, there's nothing to see here.

This table shows the amount of free space you receive when using the action with the various options.

OS | Android SDKs removed | .NET SDKs removed | Haskell removed | CodeQL Removed | Cached Docker Images Removed | GB freed | GB free | Elapsed Time (seconds) |
---|:--------------------:|:-----------------:|:---------------:|:--------------:|:----------------------------:|:--------:|:-------:|:----------------------:|
ubuntu-20.04 |  |  |  |  |  | 62 | 83 | 2
ubuntu-20.04 |  |  |  |  | true | 65 | 86 | 28
ubuntu-20.04 |  |  |  | true |  | 67 | 88 | 4
ubuntu-20.04 |  |  |  | true | true | 70 | 91 | 33
ubuntu-20.04 |  |  | true |  |  | 62 | 83 | 2
ubuntu-20.04 |  |  | true |  | true | 65 | 86 | 7
ubuntu-20.04 |  |  | true | true |  | 67 | 88 | 5
ubuntu-20.04 |  |  | true | true | true | 70 | 91 | 35
ubuntu-20.04 |  | true |  |  |  | 64 | 85 | 5
ubuntu-20.04 |  | true |  |  | true | 66 | 87 | 8
ubuntu-20.04 |  | true |  | true |  | 69 | 90 | 6
ubuntu-20.04 |  | true |  | true | true | 71 | 92 | 10
ubuntu-20.04 |  | true | true |  |  | 64 | 85 | 6
ubuntu-20.04 |  | true | true |  | true | 66 | 87 | 39
ubuntu-20.04 |  | true | true | true |  | 69 | 90 | 5
ubuntu-20.04 |  | true | true | true | true | 71 | 92 | 21
ubuntu-20.04 | true |  |  |  |  | 70 | 91 | 12
ubuntu-20.04 | true |  |  |  | true | 72 | 93 | 30
ubuntu-20.04 | true |  |  | true |  | 75 | 96 | 13
ubuntu-20.04 | true |  |  | true | true | 77 | 98 | 223
ubuntu-20.04 | true |  | true |  |  | 70 | 91 | 126
ubuntu-20.04 | true |  | true |  | true | 72 | 93 | 111
ubuntu-20.04 | true |  | true | true |  | 75 | 96 | 12
ubuntu-20.04 | true |  | true | true | true | 77 | 98 | 19
ubuntu-20.04 | true | true |  |  |  | 71 | 92 | 101
ubuntu-20.04 | true | true |  |  | true | 74 | 95 | 16
ubuntu-20.04 | true | true |  | true |  | 76 | 97 | 71
ubuntu-20.04 | true | true |  | true | true | 79 | 100 | 130
ubuntu-20.04 | true | true | true |  |  | 71 | 92 | 17
ubuntu-20.04 | true | true | true |  | true | 74 | 95 | 117
ubuntu-20.04 | true | true | true | true |  | 76 | 97 | 212
ubuntu-20.04 | true | true | true | true | true | 79 | 100 | 126
ubuntu-22.04 |  |  |  |  |  | 62 | 84 | 1
ubuntu-22.04 |  |  |  |  | true | 65 | 87 | 6
ubuntu-22.04 |  |  |  | true |  | 67 | 89 | 4
ubuntu-22.04 |  |  |  | true | true | 70 | 92 | 34
ubuntu-22.04 |  |  | true |  |  | 62 | 84 | 1
ubuntu-22.04 |  |  | true |  | true | 65 | 87 | 17
ubuntu-22.04 |  |  | true | true |  | 67 | 89 | 3
ubuntu-22.04 |  |  | true | true | true | 70 | 92 | 6
ubuntu-22.04 |  | true |  |  |  | 64 | 86 | 5
ubuntu-22.04 |  | true |  |  | true | 66 | 88 | 8
ubuntu-22.04 |  | true |  | true |  | 69 | 91 | 5
ubuntu-22.04 |  | true |  | true | true | 71 | 93 | 26
ubuntu-22.04 |  | true | true |  |  | 64 | 86 | 4
ubuntu-22.04 |  | true | true |  | true | 66 | 88 | 44
ubuntu-22.04 |  | true | true | true |  | 69 | 91 | 5
ubuntu-22.04 |  | true | true | true | true | 71 | 93 | 31
ubuntu-22.04 | true |  |  |  |  | 70 | 92 | 11
ubuntu-22.04 | true |  |  |  | true | 72 | 94 | 140
ubuntu-22.04 | true |  |  | true |  | 75 | 97 | 21
ubuntu-22.04 | true |  |  | true | true | 77 | 99 | 103
ubuntu-22.04 | true |  | true |  |  | 70 | 92 | 89
ubuntu-22.04 | true |  | true |  | true | 72 | 94 | 20
ubuntu-22.04 | true |  | true | true |  | 75 | 97 | 116
ubuntu-22.04 | true |  | true | true | true | 77 | 99 | 18
ubuntu-22.04 | true | true |  |  |  | 71 | 93 | 12
ubuntu-22.04 | true | true |  |  | true | 74 | 96 | 141
ubuntu-22.04 | true | true |  | true |  | 76 | 98 | 89
ubuntu-22.04 | true | true |  | true | true | 79 | 101 | 148
ubuntu-22.04 | true | true | true |  |  | 71 | 93 | 115
ubuntu-22.04 | true | true | true |  | true | 74 | 96 | 131
ubuntu-22.04 | true | true | true | true |  | 76 | 98 | 66
ubuntu-22.04 | true | true | true | true | true | 79 | 101 | 18
