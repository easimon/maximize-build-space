# Maximize available disk space for build tasks

If the available disk space on Github runners is too little for your build job, this action might be for you.
If not: please go on, there's nothing to see here.

This table shows the amount of free space you receive when using the action with the various options.

OS | Android SDKs removed | .NET SDKs removed | Haskell removed | CodeQL Removed | Cached Docker Images Removed | GB freed | GB free | Elapsed Time (seconds) |
---|:--------------------:|:-----------------:|:---------------:|:--------------:|:----------------------------:|:--------:|:-------:|:----------------------:|
ubuntu-20.04 |  |  |  |  |  | 62 | 83 | 3
ubuntu-20.04 |  |  |  |  | true | 65 | 86 | 23
ubuntu-20.04 |  |  |  | true |  | 67 | 88 | 2
ubuntu-20.04 |  |  |  | true | true | 70 | 91 | 25
ubuntu-20.04 |  |  | true |  |  | 62 | 83 | 2
ubuntu-20.04 |  |  | true |  | true | 65 | 86 | 4
ubuntu-20.04 |  |  | true | true |  | 67 | 88 | 3
ubuntu-20.04 |  |  | true | true | true | 70 | 91 | 7
ubuntu-20.04 |  | true |  |  |  | 64 | 85 | 3
ubuntu-20.04 |  | true |  |  | true | 67 | 88 | 8
ubuntu-20.04 |  | true |  | true |  | 69 | 90 | 6
ubuntu-20.04 |  | true |  | true | true | 72 | 93 | 24
ubuntu-20.04 |  | true | true |  |  | 64 | 85 | 2
ubuntu-20.04 |  | true | true |  | true | 67 | 88 | 24
ubuntu-20.04 |  | true | true | true |  | 69 | 90 | 4
ubuntu-20.04 |  | true | true | true | true | 72 | 93 | 25
ubuntu-20.04 | true |  |  |  |  | 71 | 92 | 63
ubuntu-20.04 | true |  |  |  | true | 74 | 95 | 12
ubuntu-20.04 | true |  |  | true |  | 76 | 97 | 55
ubuntu-20.04 | true |  |  | true | true | 79 | 100 | 53
ubuntu-20.04 | true |  | true |  |  | 71 | 92 | 37
ubuntu-20.04 | true |  | true |  | true | 74 | 95 | 84
ubuntu-20.04 | true |  | true | true |  | 76 | 97 | 10
ubuntu-20.04 | true |  | true | true | true | 79 | 100 | 83
ubuntu-20.04 | true | true |  |  |  | 72 | 93 | 83
ubuntu-20.04 | true | true |  |  | true | 75 | 96 | 14
ubuntu-20.04 | true | true |  | true |  | 77 | 98 | 10
ubuntu-20.04 | true | true |  | true | true | 80 | 101 | 75
ubuntu-20.04 | true | true | true |  |  | 72 | 93 | 9
ubuntu-20.04 | true | true | true |  | true | 75 | 96 | 36
ubuntu-20.04 | true | true | true | true |  | 77 | 98 | 10
ubuntu-20.04 | true | true | true | true | true | 80 | 101 | 36
ubuntu-22.04 |  |  |  |  |  | 63 | 84 | 1
ubuntu-22.04 |  |  |  |  | true | 66 | 87 | 8
ubuntu-22.04 |  |  |  | true |  | 67 | 88 | 4
ubuntu-22.04 |  |  |  | true | true | 71 | 92 | 10
ubuntu-22.04 |  |  | true |  |  | 63 | 84 | 2
ubuntu-22.04 |  |  | true |  | true | 66 | 87 | 6
ubuntu-22.04 |  |  | true | true |  | 67 | 88 | 4
ubuntu-22.04 |  |  | true | true | true | 71 | 92 | 30
ubuntu-22.04 |  | true |  |  |  | 64 | 85 | 5
ubuntu-22.04 |  | true |  |  | true | 67 | 88 | 29
ubuntu-22.04 |  | true |  | true |  | 69 | 90 | 5
ubuntu-22.04 |  | true |  | true | true | 72 | 93 | 28
ubuntu-22.04 |  | true | true |  |  | 64 | 85 | 4
ubuntu-22.04 |  | true | true |  | true | 67 | 88 | 8
ubuntu-22.04 |  | true | true | true |  | 69 | 90 | 4
ubuntu-22.04 |  | true | true | true | true | 72 | 93 | 11
ubuntu-22.04 | true |  |  |  |  | 71 | 92 | 12
ubuntu-22.04 | true |  |  |  | true | 74 | 95 | 92
ubuntu-22.04 | true |  |  | true |  | 76 | 97 | 52
ubuntu-22.04 | true |  |  | true | true | 79 | 100 | 96
ubuntu-22.04 | true |  | true |  |  | 71 | 92 | 10
ubuntu-22.04 | true |  | true |  | true | 74 | 95 | 31
ubuntu-22.04 | true |  | true | true |  | 76 | 97 | 14
ubuntu-22.04 | true |  | true | true | true | 79 | 100 | 74
ubuntu-22.04 | true | true |  |  |  | 73 | 94 | 12
ubuntu-22.04 | true | true |  |  | true | 76 | 97 | 70
ubuntu-22.04 | true | true |  | true |  | 78 | 99 | 14
ubuntu-22.04 | true | true |  | true | true | 81 | 102 | 76
ubuntu-22.04 | true | true | true |  |  | 73 | 94 | 14
ubuntu-22.04 | true | true | true |  | true | 76 | 97 | 19
ubuntu-22.04 | true | true | true | true |  | 78 | 99 | 62
ubuntu-22.04 | true | true | true | true | true | 81 | 102 | 83
