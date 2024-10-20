# Maximize available disk space for build tasks

If the available disk space on Github runners is too little for your build job, this action might be for you.
If not: please go on, there's nothing to see here.

This table shows the amount of free space you receive when using the action with the various options.

OS | Android SDKs removed | .NET SDKs removed | Haskell removed | CodeQL Removed | Cached Docker Images Removed | GB freed | GB free | Elapsed Time (seconds) |
---|:--------------------:|:-----------------:|:---------------:|:--------------:|:----------------------------:|:--------:|:-------:|:----------------------:|
ubuntu-20.04 |  |  |  |  |  | 63 | 83 | 3
ubuntu-20.04 |  |  |  |  | true | 66 | 86 | 48
ubuntu-20.04 |  |  |  | true |  | 68 | 88 | 4
ubuntu-20.04 |  |  |  | true | true | 71 | 91 | 51
ubuntu-20.04 |  |  | true |  |  | 63 | 83 | 2
ubuntu-20.04 |  |  | true |  | true | 66 | 86 | 56
ubuntu-20.04 |  |  | true | true |  | 68 | 88 | 4
ubuntu-20.04 |  |  | true | true | true | 71 | 91 | 35
ubuntu-20.04 |  | true |  |  |  | 64 | 84 | 4
ubuntu-20.04 |  | true |  |  | true | 68 | 88 | 10
ubuntu-20.04 |  | true |  | true |  | 69 | 89 | 6
ubuntu-20.04 |  | true |  | true | true | 72 | 92 | 48
ubuntu-20.04 |  | true | true |  |  | 64 | 84 | 4
ubuntu-20.04 |  | true | true |  | true | 68 | 88 | 39
ubuntu-20.04 |  | true | true | true |  | 69 | 89 | 5
ubuntu-20.04 |  | true | true | true | true | 72 | 92 | 9
ubuntu-20.04 | true |  |  |  |  | 70 | 90 | 84
ubuntu-20.04 | true |  |  |  | true | 73 | 93 | 50
ubuntu-20.04 | true |  |  | true |  | 75 | 95 | 66
ubuntu-20.04 | true |  |  | true | true | 78 | 98 | 93
ubuntu-20.04 | true |  | true |  |  | 70 | 90 | 11
ubuntu-20.04 | true |  | true |  | true | 73 | 93 | 64
ubuntu-20.04 | true |  | true | true |  | 75 | 95 | 59
ubuntu-20.04 | true |  | true | true | true | 78 | 98 | 112
ubuntu-20.04 | true | true |  |  |  | 72 | 92 | 17
ubuntu-20.04 | true | true |  |  | true | 75 | 95 | 21
ubuntu-20.04 | true | true |  | true |  | 77 | 97 | 71
ubuntu-20.04 | true | true |  | true | true | 80 | 100 | 105
ubuntu-20.04 | true | true | true |  |  | 72 | 92 | 13
ubuntu-20.04 | true | true | true |  | true | 75 | 95 | 64
ubuntu-20.04 | true | true | true | true |  | 77 | 97 | 61
ubuntu-20.04 | true | true | true | true | true | 80 | 100 | 76
ubuntu-22.04 |  |  |  |  |  | 63 | 84 | 2
ubuntu-22.04 |  |  |  |  | true | 66 | 87 | 6
ubuntu-22.04 |  |  |  | true |  | 68 | 89 | 4
ubuntu-22.04 |  |  |  | true | true | 71 | 92 | 7
ubuntu-22.04 |  |  | true |  |  | 63 | 84 | 2
ubuntu-22.04 |  |  | true |  | true | 66 | 87 | 8
ubuntu-22.04 |  |  | true | true |  | 68 | 89 | 4
ubuntu-22.04 |  |  | true | true | true | 71 | 92 | 8
ubuntu-22.04 |  | true |  |  |  | 64 | 85 | 5
ubuntu-22.04 |  | true |  |  | true | 67 | 88 | 37
ubuntu-22.04 |  | true |  | true |  | 69 | 90 | 5
ubuntu-22.04 |  | true |  | true | true | 72 | 93 | 25
ubuntu-22.04 |  | true | true |  |  | 64 | 85 | 4
ubuntu-22.04 |  | true | true |  | true | 67 | 88 | 33
ubuntu-22.04 |  | true | true | true |  | 69 | 90 | 6
ubuntu-22.04 |  | true | true | true | true | 72 | 93 | 20
ubuntu-22.04 | true |  |  |  |  | 70 | 91 | 17
ubuntu-22.04 | true |  |  |  | true | 73 | 94 | 123
ubuntu-22.04 | true |  |  | true |  | 75 | 96 | 67
ubuntu-22.04 | true |  |  | true | true | 78 | 99 | 90
ubuntu-22.04 | true |  | true |  |  | 70 | 91 | 81
ubuntu-22.04 | true |  | true |  | true | 73 | 94 | 27
ubuntu-22.04 | true |  | true | true |  | 75 | 96 | 14
ubuntu-22.04 | true |  | true | true | true | 78 | 99 | 74
ubuntu-22.04 | true | true |  |  |  | 72 | 93 | 97
ubuntu-22.04 | true | true |  |  | true | 75 | 96 | 91
ubuntu-22.04 | true | true |  | true |  | 77 | 98 | 82
ubuntu-22.04 | true | true |  | true | true | 80 | 101 | 19
ubuntu-22.04 | true | true | true |  |  | 72 | 93 | 60
ubuntu-22.04 | true | true | true |  | true | 75 | 96 | 42
ubuntu-22.04 | true | true | true | true |  | 77 | 98 | 20
ubuntu-22.04 | true | true | true | true | true | 80 | 101 | 17
