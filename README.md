# Maximize available disk space for build tasks

If the available disk space on Github runners is too little for your build job, this action might be for you.
If not: please go on, there's nothing to see here.

This table shows the amount of free space you receive when using the action with the various options.

OS | Android SDKs removed | .NET SDKs removed | Haskell removed | CodeQL Removed | Cached Docker Images Removed | GB freed | GB free | Elapsed Time (seconds) |
---|:--------------------:|:-----------------:|:---------------:|:--------------:|:----------------------------:|:--------:|:-------:|:----------------------:|
ubuntu-20.04 |  |  |  |  |  | 62 | 80 | 3
ubuntu-20.04 |  |  |  |  | true | 66 | 84 | 41
ubuntu-20.04 |  |  |  | true |  | 67 | 85 | 5
ubuntu-20.04 |  |  |  | true | true | 70 | 88 | 58
ubuntu-20.04 |  |  | true |  |  | 62 | 80 | 2
ubuntu-20.04 |  |  | true |  | true | 66 | 84 | 50
ubuntu-20.04 |  |  | true | true |  | 67 | 85 | 4
ubuntu-20.04 |  |  | true | true | true | 70 | 88 | 10
ubuntu-20.04 |  | true |  |  |  | 64 | 82 | 4
ubuntu-20.04 |  | true |  |  | true | 67 | 85 | 8
ubuntu-20.04 |  | true |  | true |  | 69 | 87 | 6
ubuntu-20.04 |  | true |  | true | true | 72 | 90 | 56
ubuntu-20.04 |  | true | true |  |  | 64 | 82 | 5
ubuntu-20.04 |  | true | true |  | true | 67 | 85 | 56
ubuntu-20.04 |  | true | true | true |  | 69 | 87 | 5
ubuntu-20.04 |  | true | true | true | true | 72 | 90 | 9
ubuntu-20.04 | true |  |  |  |  | 73 | 91 | 11
ubuntu-20.04 | true |  |  |  | true | 76 | 94 | 198
ubuntu-20.04 | true |  |  | true |  | 78 | 96 | 14
ubuntu-20.04 | true |  |  | true | true | 81 | 99 | 102
ubuntu-20.04 | true |  | true |  |  | 73 | 91 | 71
ubuntu-20.04 | true |  | true |  | true | 76 | 94 | 18
ubuntu-20.04 | true |  | true | true |  | 78 | 96 | 56
ubuntu-20.04 | true |  | true | true | true | 81 | 99 | 116
ubuntu-20.04 | true | true |  |  |  | 75 | 93 | 103
ubuntu-20.04 | true | true |  |  | true | 78 | 96 | 68
ubuntu-20.04 | true | true |  | true |  | 80 | 98 | 11
ubuntu-20.04 | true | true |  | true | true | 83 | 101 | 101
ubuntu-20.04 | true | true | true |  |  | 75 | 93 | 80
ubuntu-20.04 | true | true | true |  | true | 78 | 96 | 18
ubuntu-20.04 | true | true | true | true |  | 80 | 98 | 12
ubuntu-20.04 | true | true | true | true | true | 83 | 101 | 148
ubuntu-22.04 |  |  |  |  |  | 63 | 82 | 2
ubuntu-22.04 |  |  |  |  | true | 66 | 85 | 7
ubuntu-22.04 |  |  |  | true |  | 68 | 87 | 3
ubuntu-22.04 |  |  |  | true | true | 71 | 90 | 8
ubuntu-22.04 |  |  | true |  |  | 63 | 82 | 2
ubuntu-22.04 |  |  | true |  | true | 66 | 85 | 46
ubuntu-22.04 |  |  | true | true |  | 68 | 87 | 3
ubuntu-22.04 |  |  | true | true | true | 71 | 90 | 30
ubuntu-22.04 |  | true |  |  |  | 64 | 83 | 3
ubuntu-22.04 |  | true |  |  | true | 67 | 86 | 55
ubuntu-22.04 |  | true |  | true |  | 69 | 88 | 4
ubuntu-22.04 |  | true |  | true | true | 72 | 91 | 10
ubuntu-22.04 |  | true | true |  |  | 64 | 83 | 5
ubuntu-22.04 |  | true | true |  | true | 67 | 86 | 37
ubuntu-22.04 |  | true | true | true |  | 69 | 88 | 4
ubuntu-22.04 |  | true | true | true | true | 72 | 91 | 50
ubuntu-22.04 | true |  |  |  |  | 74 | 93 | 10
ubuntu-22.04 | true |  |  |  | true | 77 | 96 | 20
ubuntu-22.04 | true |  |  | true |  | 78 | 97 | 15
ubuntu-22.04 | true |  |  | true | true | 82 | 101 | 18
ubuntu-22.04 | true |  | true |  |  | 74 | 93 | 11
ubuntu-22.04 | true |  | true |  | true | 77 | 96 | 21
ubuntu-22.04 | true |  | true | true |  | 78 | 97 | 89
ubuntu-22.04 | true |  | true | true | true | 82 | 101 | 102
ubuntu-22.04 | true | true |  |  |  | 75 | 94 | 12
ubuntu-22.04 | true | true |  |  | true | 78 | 97 | 96
ubuntu-22.04 | true | true |  | true |  | 80 | 99 | 73
ubuntu-22.04 | true | true |  | true | true | 83 | 102 | 19
ubuntu-22.04 | true | true | true |  |  | 75 | 94 | 84
ubuntu-22.04 | true | true | true |  | true | 78 | 97 | 154
ubuntu-22.04 | true | true | true | true |  | 80 | 99 | 12
ubuntu-22.04 | true | true | true | true | true | 83 | 102 | 118
