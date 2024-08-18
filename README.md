# Maximize available disk space for build tasks

If the available disk space on Github runners is too little for your build job, this action might be for you.
If not: please go on, there's nothing to see here.

This table shows the amount of free space you receive when using the action with the various options.

OS | Android SDKs removed | .NET SDKs removed | Haskell removed | CodeQL Removed | Cached Docker Images Removed | GB freed | GB free | Elapsed Time (seconds) |
---|:--------------------:|:-----------------:|:---------------:|:--------------:|:----------------------------:|:--------:|:-------:|:----------------------:|
ubuntu-20.04 |  |  |  |  |  | 62 | 80 | 2
ubuntu-20.04 |  |  |  |  | true | 65 | 83 | 49
ubuntu-20.04 |  |  |  | true |  | 67 | 85 | 5
ubuntu-20.04 |  |  |  | true | true | 70 | 88 | 74
ubuntu-20.04 |  |  | true |  |  | 62 | 80 | 2
ubuntu-20.04 |  |  | true |  | true | 65 | 83 | 56
ubuntu-20.04 |  |  | true | true |  | 67 | 85 | 4
ubuntu-20.04 |  |  | true | true | true | 70 | 88 | 37
ubuntu-20.04 |  | true |  |  |  | 64 | 82 | 6
ubuntu-20.04 |  | true |  |  | true | 67 | 85 | 34
ubuntu-20.04 |  | true |  | true |  | 69 | 87 | 6
ubuntu-20.04 |  | true |  | true | true | 72 | 90 | 109
ubuntu-20.04 |  | true | true |  |  | 64 | 82 | 5
ubuntu-20.04 |  | true | true |  | true | 67 | 85 | 52
ubuntu-20.04 |  | true | true | true |  | 69 | 87 | 5
ubuntu-20.04 |  | true | true | true | true | 72 | 90 | 72
ubuntu-20.04 | true |  |  |  |  | 73 | 91 | 87
ubuntu-20.04 | true |  |  |  | true | 76 | 94 | 142
ubuntu-20.04 | true |  |  | true |  | 78 | 96 | 52
ubuntu-20.04 | true |  |  | true | true | 81 | 99 | 20
ubuntu-20.04 | true |  | true |  |  | 73 | 91 | 50
ubuntu-20.04 | true |  | true |  | true | 76 | 94 | 111
ubuntu-20.04 | true |  | true | true |  | 78 | 96 | 55
ubuntu-20.04 | true |  | true | true | true | 81 | 99 | 92
ubuntu-20.04 | true | true |  |  |  | 75 | 93 | 53
ubuntu-20.04 | true | true |  |  | true | 78 | 96 | 113
ubuntu-20.04 | true | true |  | true |  | 80 | 98 | 13
ubuntu-20.04 | true | true |  | true | true | 83 | 101 | 118
ubuntu-20.04 | true | true | true |  |  | 75 | 93 | 46
ubuntu-20.04 | true | true | true |  | true | 78 | 96 | 23
ubuntu-20.04 | true | true | true | true |  | 80 | 98 | 64
ubuntu-20.04 | true | true | true | true | true | 83 | 101 | 91
ubuntu-22.04 |  |  |  |  |  | 63 | 82 | 2
ubuntu-22.04 |  |  |  |  | true | 66 | 85 | 7
ubuntu-22.04 |  |  |  | true |  | 67 | 86 | 4
ubuntu-22.04 |  |  |  | true | true | 71 | 90 | 26
ubuntu-22.04 |  |  | true |  |  | 63 | 82 | 2
ubuntu-22.04 |  |  | true |  | true | 66 | 85 | 8
ubuntu-22.04 |  |  | true | true |  | 67 | 86 | 4
ubuntu-22.04 |  |  | true | true | true | 71 | 90 | 8
ubuntu-22.04 |  | true |  |  |  | 64 | 83 | 3
ubuntu-22.04 |  | true |  |  | true | 67 | 86 | 9
ubuntu-22.04 |  | true |  | true |  | 69 | 88 | 5
ubuntu-22.04 |  | true |  | true | true | 72 | 91 | 9
ubuntu-22.04 |  | true | true |  |  | 64 | 83 | 5
ubuntu-22.04 |  | true | true |  | true | 67 | 86 | 7
ubuntu-22.04 |  | true | true | true |  | 69 | 88 | 4
ubuntu-22.04 |  | true | true | true | true | 72 | 91 | 9
ubuntu-22.04 | true |  |  |  |  | 73 | 92 | 11
ubuntu-22.04 | true |  |  |  | true | 77 | 96 | 18
ubuntu-22.04 | true |  |  | true |  | 78 | 97 | 12
ubuntu-22.04 | true |  |  | true | true | 81 | 100 | 24
ubuntu-22.04 | true |  | true |  |  | 73 | 92 | 12
ubuntu-22.04 | true |  | true |  | true | 77 | 96 | 24
ubuntu-22.04 | true |  | true | true |  | 78 | 97 | 15
ubuntu-22.04 | true |  | true | true | true | 81 | 100 | 103
ubuntu-22.04 | true | true |  |  |  | 75 | 94 | 45
ubuntu-22.04 | true | true |  |  | true | 78 | 97 | 89
ubuntu-22.04 | true | true |  | true |  | 80 | 99 | 14
ubuntu-22.04 | true | true |  | true | true | 83 | 102 | 17
ubuntu-22.04 | true | true | true |  |  | 75 | 94 | 50
ubuntu-22.04 | true | true | true |  | true | 78 | 97 | 78
ubuntu-22.04 | true | true | true | true |  | 80 | 99 | 14
ubuntu-22.04 | true | true | true | true | true | 83 | 102 | 24
