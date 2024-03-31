# Maximize available disk space for build tasks

If the available disk space on Github runners is too little for your build job, this action might be for you.
If not: please go on, there's nothing to see here.

This table shows the amount of free space you receive when using the action with the various options.

OS | Android SDKs removed | .NET SDKs removed | Haskell removed | CodeQL Removed | Cached Docker Images Removed | GB freed | GB free | Elapsed Time (seconds) |
---|:--------------------:|:-----------------:|:---------------:|:--------------:|:----------------------------:|:--------:|:-------:|:----------------------:|
ubuntu-20.04 |  |  |  |  |  | 63 | 83 | 2
ubuntu-20.04 |  |  |  |  | true | 66 | 86 | 8
ubuntu-20.04 |  |  |  | true |  | 68 | 88 | 8
ubuntu-20.04 |  |  |  | true | true | 71 | 91 | 14
ubuntu-20.04 |  |  | true |  |  | 63 | 83 | 2
ubuntu-20.04 |  |  | true |  | true | 66 | 86 | 22
ubuntu-20.04 |  |  | true | true |  | 68 | 88 | 2
ubuntu-20.04 |  |  | true | true | true | 71 | 91 | 8
ubuntu-20.04 |  | true |  |  |  | 64 | 84 | 4
ubuntu-20.04 |  | true |  |  | true | 68 | 88 | 24
ubuntu-20.04 |  | true |  | true |  | 69 | 89 | 3
ubuntu-20.04 |  | true |  | true | true | 72 | 92 | 22
ubuntu-20.04 |  | true | true |  |  | 64 | 84 | 4
ubuntu-20.04 |  | true | true |  | true | 68 | 88 | 23
ubuntu-20.04 |  | true | true | true |  | 69 | 89 | 6
ubuntu-20.04 |  | true | true | true | true | 72 | 92 | 31
ubuntu-20.04 | true |  |  |  |  | 72 | 92 | 56
ubuntu-20.04 | true |  |  |  | true | 75 | 95 | 79
ubuntu-20.04 | true |  |  | true |  | 76 | 96 | 63
ubuntu-20.04 | true |  |  | true | true | 80 | 100 | 75
ubuntu-20.04 | true |  | true |  |  | 72 | 92 | 59
ubuntu-20.04 | true |  | true |  | true | 75 | 95 | 85
ubuntu-20.04 | true |  | true | true |  | 76 | 96 | 53
ubuntu-20.04 | true |  | true | true | true | 80 | 100 | 193
ubuntu-20.04 | true | true |  |  |  | 73 | 93 | 59
ubuntu-20.04 | true | true |  |  | true | 76 | 96 | 72
ubuntu-20.04 | true | true |  | true |  | 78 | 98 | 11
ubuntu-20.04 | true | true |  | true | true | 81 | 101 | 12
ubuntu-20.04 | true | true | true |  |  | 73 | 93 | 98
ubuntu-20.04 | true | true | true |  | true | 76 | 96 | 76
ubuntu-20.04 | true | true | true | true |  | 78 | 98 | 69
ubuntu-20.04 | true | true | true | true | true | 81 | 101 | 73
ubuntu-22.04 |  |  |  |  |  | 62 | 83 | 4
ubuntu-22.04 |  |  |  |  | true | 66 | 87 | 6
ubuntu-22.04 |  |  |  | true |  | 67 | 88 | 3
ubuntu-22.04 |  |  |  | true | true | 70 | 91 | 28
ubuntu-22.04 |  |  | true |  |  | 62 | 83 | 2
ubuntu-22.04 |  |  | true |  | true | 66 | 87 | 6
ubuntu-22.04 |  |  | true | true |  | 67 | 88 | 4
ubuntu-22.04 |  |  | true | true | true | 70 | 91 | 29
ubuntu-22.04 |  | true |  |  |  | 64 | 85 | 5
ubuntu-22.04 |  | true |  |  | true | 67 | 88 | 6
ubuntu-22.04 |  | true |  | true |  | 69 | 90 | 5
ubuntu-22.04 |  | true |  | true | true | 72 | 93 | 48
ubuntu-22.04 |  | true | true |  |  | 64 | 85 | 4
ubuntu-22.04 |  | true | true |  | true | 67 | 88 | 33
ubuntu-22.04 |  | true | true | true |  | 69 | 90 | 5
ubuntu-22.04 |  | true | true | true | true | 72 | 93 | 41
ubuntu-22.04 | true |  |  |  |  | 71 | 92 | 58
ubuntu-22.04 | true |  |  |  | true | 74 | 95 | 16
ubuntu-22.04 | true |  |  | true |  | 76 | 97 | 60
ubuntu-22.04 | true |  |  | true | true | 79 | 100 | 16
ubuntu-22.04 | true |  | true |  |  | 71 | 92 | 40
ubuntu-22.04 | true |  | true |  | true | 74 | 95 | 78
ubuntu-22.04 | true |  | true | true |  | 76 | 97 | 18
ubuntu-22.04 | true |  | true | true | true | 79 | 100 | 17
ubuntu-22.04 | true | true |  |  |  | 73 | 94 | 10
ubuntu-22.04 | true | true |  |  | true | 76 | 97 | 67
ubuntu-22.04 | true | true |  | true |  | 77 | 98 | 46
ubuntu-22.04 | true | true |  | true | true | 81 | 102 | 80
ubuntu-22.04 | true | true | true |  |  | 73 | 94 | 44
ubuntu-22.04 | true | true | true |  | true | 76 | 97 | 69
ubuntu-22.04 | true | true | true | true |  | 77 | 98 | 15
ubuntu-22.04 | true | true | true | true | true | 81 | 102 | 84
