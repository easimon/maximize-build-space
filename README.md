# Maximize available disk space for build tasks

If the available disk space on Github runners is too little for your build job, this action might be for you.
If not: please go on, there's nothing to see here.

This table shows the amount of free space you receive when using the action with the various options.

OS | Android SDKs removed | .NET SDKs removed | Haskell removed | CodeQL Removed | Cached Docker Images Removed | GB freed | GB free | Elapsed Time (seconds) |
---|:--------------------:|:-----------------:|:---------------:|:--------------:|:----------------------------:|:--------:|:-------:|:----------------------:|
ubuntu-20.04 |  |  |  |  |  | 52 | 75 | 2
ubuntu-20.04 |  |  |  |  | true | 59 | 82 | 9
ubuntu-20.04 |  |  |  | true |  | 56 | 79 | 2
ubuntu-20.04 |  |  |  | true | true | 62 | 85 | 36
ubuntu-20.04 |  |  | true |  |  | 52 | 75 | 2
ubuntu-20.04 |  |  | true |  | true | 59 | 82 | 23
ubuntu-20.04 |  |  | true | true |  | 56 | 79 | 3
ubuntu-20.04 |  |  | true | true | true | 62 | 85 | 41
ubuntu-20.04 |  | true |  |  |  | 55 | 78 | 3
ubuntu-20.04 |  | true |  |  | true | 62 | 85 | 11
ubuntu-20.04 |  | true |  | true |  | 59 | 82 | 3
ubuntu-20.04 |  | true |  | true | true | 65 | 88 | 10
ubuntu-20.04 |  | true | true |  |  | 55 | 78 | 3
ubuntu-20.04 |  | true | true |  | true | 62 | 85 | 40
ubuntu-20.04 |  | true | true | true |  | 59 | 82 | 8
ubuntu-20.04 |  | true | true | true | true | 65 | 88 | 33
ubuntu-20.04 | true |  |  |  |  | 64 | 87 | 9
ubuntu-20.04 | true |  |  |  | true | 71 | 94 | 14
ubuntu-20.04 | true |  |  | true |  | 68 | 91 | 60
ubuntu-20.04 | true |  |  | true | true | 74 | 97 | 46
ubuntu-20.04 | true |  | true |  |  | 64 | 87 | 11
ubuntu-20.04 | true |  | true |  | true | 71 | 94 | 91
ubuntu-20.04 | true |  | true | true |  | 68 | 91 | 43
ubuntu-20.04 | true |  | true | true | true | 74 | 97 | 93
ubuntu-20.04 | true | true |  |  |  | 67 | 90 | 9
ubuntu-20.04 | true | true |  |  | true | 73 | 96 | 87
ubuntu-20.04 | true | true |  | true |  | 70 | 93 | 13
ubuntu-20.04 | true | true |  | true | true | 77 | 100 | 97
ubuntu-20.04 | true | true | true |  |  | 67 | 90 | 63
ubuntu-20.04 | true | true | true |  | true | 73 | 96 | 125
ubuntu-20.04 | true | true | true | true |  | 70 | 93 | 12
ubuntu-20.04 | true | true | true | true | true | 77 | 100 | 18
ubuntu-22.04 |  |  |  |  |  | 52 | 77 | 2
ubuntu-22.04 |  |  |  |  | true | 58 | 83 | 23
ubuntu-22.04 |  |  |  | true |  | 56 | 81 | 4
ubuntu-22.04 |  |  |  | true | true | 61 | 86 | 26
ubuntu-22.04 |  |  | true |  |  | 52 | 77 | 2
ubuntu-22.04 |  |  | true |  | true | 58 | 83 | 11
ubuntu-22.04 |  |  | true | true |  | 56 | 81 | 3
ubuntu-22.04 |  |  | true | true | true | 61 | 86 | 39
ubuntu-22.04 |  | true |  |  |  | 55 | 80 | 4
ubuntu-22.04 |  | true |  |  | true | 60 | 85 | 13
ubuntu-22.04 |  | true |  | true |  | 58 | 83 | 3
ubuntu-22.04 |  | true |  | true | true | 64 | 89 | 29
ubuntu-22.04 |  | true | true |  |  | 55 | 80 | 4
ubuntu-22.04 |  | true | true |  | true | 60 | 85 | 13
ubuntu-22.04 |  | true | true | true |  | 58 | 83 | 4
ubuntu-22.04 |  | true | true | true | true | 64 | 89 | 34
ubuntu-22.04 | true |  |  |  |  | 64 | 89 | 12
ubuntu-22.04 | true |  |  |  | true | 70 | 95 | 103
ubuntu-22.04 | true |  |  | true |  | 68 | 93 | 13
ubuntu-22.04 | true |  |  | true | true | 73 | 98 | 45
ubuntu-22.04 | true |  | true |  |  | 64 | 89 | 13
ubuntu-22.04 | true |  | true |  | true | 70 | 95 | 26
ubuntu-22.04 | true |  | true | true |  | 68 | 93 | 13
ubuntu-22.04 | true |  | true | true | true | 73 | 98 | 42
ubuntu-22.04 | true | true |  |  |  | 67 | 92 | 64
ubuntu-22.04 | true | true |  |  | true | 72 | 97 | 22
ubuntu-22.04 | true | true |  | true |  | 70 | 95 | 74
ubuntu-22.04 | true | true |  | true | true | 76 | 101 | 26
ubuntu-22.04 | true | true | true |  |  | 67 | 92 | 13
ubuntu-22.04 | true | true | true |  | true | 72 | 97 | 95
ubuntu-22.04 | true | true | true | true |  | 70 | 95 | 15
ubuntu-22.04 | true | true | true | true | true | 76 | 101 | 24
