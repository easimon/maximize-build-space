# Maximize available disk space for build tasks

If the available disk space on Github runners is too little for your build job, this action might be for you.
If not: please go on, there's nothing to see here.

This table shows the amount of free space you receive when using the action with the various options.

OS | Android SDKs removed | .NET SDKs removed | Haskell removed | CodeQL Removed | Cached Docker Images Removed | GB freed | GB free | Elapsed Time (seconds) |
---|:--------------------:|:-----------------:|:---------------:|:--------------:|:----------------------------:|:--------:|:-------:|:----------------------:|
ubuntu-20.04 |  |  |  |  |  | 63 | 82 | 1
ubuntu-20.04 |  |  |  |  | true | 66 | 85 | 25
ubuntu-20.04 |  |  |  | true |  | 68 | 87 | 3
ubuntu-20.04 |  |  |  | true | true | 71 | 90 | 34
ubuntu-20.04 |  |  | true |  |  | 63 | 82 | 2
ubuntu-20.04 |  |  | true |  | true | 66 | 85 | 25
ubuntu-20.04 |  |  | true | true |  | 68 | 87 | 4
ubuntu-20.04 |  |  | true | true | true | 71 | 90 | 19
ubuntu-20.04 |  | true |  |  |  | 64 | 83 | 4
ubuntu-20.04 |  | true |  |  | true | 67 | 86 | 6
ubuntu-20.04 |  | true |  | true |  | 69 | 88 | 4
ubuntu-20.04 |  | true |  | true | true | 72 | 91 | 28
ubuntu-20.04 |  | true | true |  |  | 64 | 83 | 2
ubuntu-20.04 |  | true | true |  | true | 67 | 86 | 37
ubuntu-20.04 |  | true | true | true |  | 69 | 88 | 6
ubuntu-20.04 |  | true | true | true | true | 72 | 91 | 6
ubuntu-20.04 | true |  |  |  |  | 71 | 90 | 41
ubuntu-20.04 | true |  |  |  | true | 75 | 94 | 54
ubuntu-20.04 | true |  |  | true |  | 76 | 95 | 9
ubuntu-20.04 | true |  |  | true | true | 79 | 98 | 33
ubuntu-20.04 | true |  | true |  |  | 71 | 90 | 42
ubuntu-20.04 | true |  | true |  | true | 75 | 94 | 12
ubuntu-20.04 | true |  | true | true |  | 76 | 95 | 11
ubuntu-20.04 | true |  | true | true | true | 79 | 98 | 44
ubuntu-20.04 | true | true |  |  |  | 73 | 92 | 48
ubuntu-20.04 | true | true |  |  | true | 76 | 95 | 53
ubuntu-20.04 | true | true |  | true |  | 78 | 97 | 42
ubuntu-20.04 | true | true |  | true | true | 81 | 100 | 70
ubuntu-20.04 | true | true | true |  |  | 73 | 92 | 41
ubuntu-20.04 | true | true | true |  | true | 76 | 95 | 49
ubuntu-20.04 | true | true | true | true |  | 78 | 97 | 9
ubuntu-20.04 | true | true | true | true | true | 81 | 100 | 60
ubuntu-22.04 |  |  |  |  |  | 62 | 82 | 2
ubuntu-22.04 |  |  |  |  | true | 66 | 86 | 6
ubuntu-22.04 |  |  |  | true |  | 67 | 87 | 3
ubuntu-22.04 |  |  |  | true | true | 70 | 90 | 8
ubuntu-22.04 |  |  | true |  |  | 62 | 82 | 2
ubuntu-22.04 |  |  | true |  | true | 66 | 86 | 7
ubuntu-22.04 |  |  | true | true |  | 67 | 87 | 3
ubuntu-22.04 |  |  | true | true | true | 70 | 90 | 28
ubuntu-22.04 |  | true |  |  |  | 64 | 84 | 5
ubuntu-22.04 |  | true |  |  | true | 67 | 87 | 20
ubuntu-22.04 |  | true |  | true |  | 69 | 89 | 5
ubuntu-22.04 |  | true |  | true | true | 72 | 92 | 28
ubuntu-22.04 |  | true | true |  |  | 64 | 84 | 4
ubuntu-22.04 |  | true | true |  | true | 67 | 87 | 37
ubuntu-22.04 |  | true | true | true |  | 69 | 89 | 5
ubuntu-22.04 |  | true | true | true | true | 72 | 92 | 9
ubuntu-22.04 | true |  |  |  |  | 71 | 91 | 63
ubuntu-22.04 | true |  |  |  | true | 74 | 94 | 106
ubuntu-22.04 | true |  |  | true |  | 76 | 96 | 15
ubuntu-22.04 | true |  |  | true | true | 79 | 99 | 19
ubuntu-22.04 | true |  | true |  |  | 71 | 91 | 11
ubuntu-22.04 | true |  | true |  | true | 74 | 94 | 89
ubuntu-22.04 | true |  | true | true |  | 76 | 96 | 74
ubuntu-22.04 | true |  | true | true | true | 79 | 99 | 93
ubuntu-22.04 | true | true |  |  |  | 73 | 93 | 9
ubuntu-22.04 | true | true |  |  | true | 76 | 96 | 96
ubuntu-22.04 | true | true |  | true |  | 77 | 97 | 71
ubuntu-22.04 | true | true |  | true | true | 81 | 101 | 16
ubuntu-22.04 | true | true | true |  |  | 73 | 93 | 11
ubuntu-22.04 | true | true | true |  | true | 76 | 96 | 90
ubuntu-22.04 | true | true | true | true |  | 77 | 97 | 15
ubuntu-22.04 | true | true | true | true | true | 81 | 101 | 37
