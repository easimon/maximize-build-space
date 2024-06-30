# Maximize available disk space for build tasks

If the available disk space on Github runners is too little for your build job, this action might be for you.
If not: please go on, there's nothing to see here.

This table shows the amount of free space you receive when using the action with the various options.

OS | Android SDKs removed | .NET SDKs removed | Haskell removed | CodeQL Removed | Cached Docker Images Removed | GB freed | GB free | Elapsed Time (seconds) |
---|:--------------------:|:-----------------:|:---------------:|:--------------:|:----------------------------:|:--------:|:-------:|:----------------------:|
ubuntu-20.04 |  |  |  |  |  | 62 | 82 | 4
ubuntu-20.04 |  |  |  |  | true | 65 | 85 | 41
ubuntu-20.04 |  |  |  | true |  | 67 | 87 | 3
ubuntu-20.04 |  |  |  | true | true | 70 | 90 | 47
ubuntu-20.04 |  |  | true |  |  | 62 | 82 | 2
ubuntu-20.04 |  |  | true |  | true | 65 | 85 | 34
ubuntu-20.04 |  |  | true | true |  | 67 | 87 | 2
ubuntu-20.04 |  |  | true | true | true | 70 | 90 | 34
ubuntu-20.04 |  | true |  |  |  | 64 | 84 | 4
ubuntu-20.04 |  | true |  |  | true | 67 | 87 | 7
ubuntu-20.04 |  | true |  | true |  | 69 | 89 | 3
ubuntu-20.04 |  | true |  | true | true | 72 | 92 | 37
ubuntu-20.04 |  | true | true |  |  | 64 | 84 | 4
ubuntu-20.04 |  | true | true |  | true | 67 | 87 | 34
ubuntu-20.04 |  | true | true | true |  | 69 | 89 | 6
ubuntu-20.04 |  | true | true | true | true | 72 | 92 | 8
ubuntu-20.04 | true |  |  |  |  | 71 | 91 | 74
ubuntu-20.04 | true |  |  |  | true | 74 | 94 | 15
ubuntu-20.04 | true |  |  | true |  | 76 | 96 | 10
ubuntu-20.04 | true |  |  | true | true | 79 | 99 | 187
ubuntu-20.04 | true |  | true |  |  | 71 | 91 | 10
ubuntu-20.04 | true |  | true |  | true | 74 | 94 | 101
ubuntu-20.04 | true |  | true | true |  | 76 | 96 | 96
ubuntu-20.04 | true |  | true | true | true | 79 | 99 | 52
ubuntu-20.04 | true | true |  |  |  | 73 | 93 | 60
ubuntu-20.04 | true | true |  |  | true | 76 | 96 | 65
ubuntu-20.04 | true | true |  | true |  | 78 | 98 | 8
ubuntu-20.04 | true | true |  | true | true | 81 | 101 | 44
ubuntu-20.04 | true | true | true |  |  | 73 | 93 | 58
ubuntu-20.04 | true | true | true |  | true | 76 | 96 | 13
ubuntu-20.04 | true | true | true | true |  | 78 | 98 | 10
ubuntu-20.04 | true | true | true | true | true | 81 | 101 | 17
ubuntu-22.04 |  |  |  |  |  | 63 | 84 | 2
ubuntu-22.04 |  |  |  |  | true | 66 | 87 | 8
ubuntu-22.04 |  |  |  | true |  | 67 | 88 | 4
ubuntu-22.04 |  |  |  | true | true | 71 | 92 | 24
ubuntu-22.04 |  |  | true |  |  | 63 | 84 | 2
ubuntu-22.04 |  |  | true |  | true | 66 | 87 | 21
ubuntu-22.04 |  |  | true | true |  | 67 | 88 | 4
ubuntu-22.04 |  |  | true | true | true | 71 | 92 | 8
ubuntu-22.04 |  | true |  |  |  | 64 | 85 | 4
ubuntu-22.04 |  | true |  |  | true | 67 | 88 | 7
ubuntu-22.04 |  | true |  | true |  | 69 | 90 | 6
ubuntu-22.04 |  | true |  | true | true | 72 | 93 | 30
ubuntu-22.04 |  | true | true |  |  | 64 | 85 | 6
ubuntu-22.04 |  | true | true |  | true | 67 | 88 | 8
ubuntu-22.04 |  | true | true | true |  | 69 | 90 | 6
ubuntu-22.04 |  | true | true | true | true | 72 | 93 | 8
ubuntu-22.04 | true |  |  |  |  | 71 | 92 | 62
ubuntu-22.04 | true |  |  |  | true | 75 | 96 | 34
ubuntu-22.04 | true |  |  | true |  | 76 | 97 | 55
ubuntu-22.04 | true |  |  | true | true | 80 | 101 | 77
ubuntu-22.04 | true |  | true |  |  | 71 | 92 | 63
ubuntu-22.04 | true |  | true |  | true | 75 | 96 | 16
ubuntu-22.04 | true |  | true | true |  | 76 | 97 | 16
ubuntu-22.04 | true |  | true | true | true | 80 | 101 | 71
ubuntu-22.04 | true | true |  |  |  | 73 | 94 | 10
ubuntu-22.04 | true | true |  |  | true | 76 | 97 | 20
ubuntu-22.04 | true | true |  | true |  | 78 | 99 | 85
ubuntu-22.04 | true | true |  | true | true | 81 | 102 | 102
ubuntu-22.04 | true | true | true |  |  | 73 | 94 | 56
ubuntu-22.04 | true | true | true |  | true | 76 | 97 | 15
ubuntu-22.04 | true | true | true | true |  | 78 | 99 | 55
ubuntu-22.04 | true | true | true | true | true | 81 | 102 | 109
