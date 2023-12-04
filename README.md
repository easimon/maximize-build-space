# Maximize available disk space for build tasks

If the available disk space on Github runners is too little for your build job, this action might be for you.
If not: please go on, there's nothing to see here.

This table shows the amount of free space you receive when using the action with the various options.

OS | Android SDKs removed | .NET SDKs removed | Haskell removed | CodeQL Removed | Cached Docker Images Removed | GB freed | GB free | Elapsed Time (seconds) |
---|:--------------------:|:-----------------:|:---------------:|:--------------:|:----------------------------:|:--------:|:-------:|:----------------------:|
ubuntu-20.04 |  |  |  |  |  | 53 | 76 | 2
ubuntu-20.04 |  |  |  |  | true | 58 | 81 | 35
ubuntu-20.04 |  |  |  | true |  | 57 | 80 | 3
ubuntu-20.04 |  |  |  | true | true | 63 | 86 | 7
ubuntu-20.04 |  |  | true |  |  | 53 | 76 | 2
ubuntu-20.04 |  |  | true |  | true | 58 | 81 | 7
ubuntu-20.04 |  |  | true | true |  | 57 | 80 | 3
ubuntu-20.04 |  |  | true | true | true | 63 | 86 | 23
ubuntu-20.04 |  | true |  |  |  | 55 | 78 | 3
ubuntu-20.04 |  | true |  |  | true | 61 | 84 | 20
ubuntu-20.04 |  | true |  | true |  | 60 | 83 | 4
ubuntu-20.04 |  | true |  | true | true | 65 | 88 | 20
ubuntu-20.04 |  | true | true |  |  | 55 | 78 | 6
ubuntu-20.04 |  | true | true |  | true | 61 | 84 | 36
ubuntu-20.04 |  | true | true | true |  | 60 | 83 | 3
ubuntu-20.04 |  | true | true | true | true | 65 | 88 | 13
ubuntu-20.04 | true |  |  |  |  | 65 | 88 | 9
ubuntu-20.04 | true |  |  |  | true | 70 | 93 | 26
ubuntu-20.04 | true |  |  | true |  | 69 | 92 | 10
ubuntu-20.04 | true |  |  | true | true | 75 | 98 | 15
ubuntu-20.04 | true |  | true |  |  | 65 | 88 | 63
ubuntu-20.04 | true |  | true |  | true | 70 | 93 | 80
ubuntu-20.04 | true |  | true | true |  | 69 | 92 | 54
ubuntu-20.04 | true |  | true | true | true | 75 | 98 | 78
ubuntu-20.04 | true | true |  |  |  | 67 | 90 | 13
ubuntu-20.04 | true | true |  |  | true | 72 | 95 | 51
ubuntu-20.04 | true | true |  | true |  | 72 | 95 | 12
ubuntu-20.04 | true | true |  | true | true | 77 | 100 | 14
ubuntu-20.04 | true | true | true |  |  | 67 | 90 | 9
ubuntu-20.04 | true | true | true |  | true | 72 | 95 | 66
ubuntu-20.04 | true | true | true | true |  | 72 | 95 | 90
ubuntu-20.04 | true | true | true | true | true | 77 | 100 | 14
ubuntu-22.04 |  |  |  |  |  | 52 | 77 | 1
ubuntu-22.04 |  |  |  |  | true | 57 | 82 | 8
ubuntu-22.04 |  |  |  | true |  | 57 | 82 | 4
ubuntu-22.04 |  |  |  | true | true | 62 | 87 | 23
ubuntu-22.04 |  |  | true |  |  | 52 | 77 | 2
ubuntu-22.04 |  |  | true |  | true | 57 | 82 | 8
ubuntu-22.04 |  |  | true | true |  | 57 | 82 | 4
ubuntu-22.04 |  |  | true | true | true | 62 | 87 | 22
ubuntu-22.04 |  | true |  |  |  | 55 | 80 | 6
ubuntu-22.04 |  | true |  |  | true | 60 | 85 | 8
ubuntu-22.04 |  | true |  | true |  | 60 | 85 | 4
ubuntu-22.04 |  | true |  | true | true | 64 | 89 | 19
ubuntu-22.04 |  | true | true |  |  | 55 | 80 | 6
ubuntu-22.04 |  | true | true |  | true | 60 | 85 | 22
ubuntu-22.04 |  | true | true | true |  | 60 | 85 | 3
ubuntu-22.04 |  | true | true | true | true | 64 | 89 | 13
ubuntu-22.04 | true |  |  |  |  | 64 | 89 | 13
ubuntu-22.04 | true |  |  |  | true | 69 | 94 | 19
ubuntu-22.04 | true |  |  | true |  | 69 | 94 | 15
ubuntu-22.04 | true |  |  | true | true | 73 | 98 | 106
ubuntu-22.04 | true |  | true |  |  | 64 | 89 | 14
ubuntu-22.04 | true |  | true |  | true | 69 | 94 | 94
ubuntu-22.04 | true |  | true | true |  | 69 | 94 | 69
ubuntu-22.04 | true |  | true | true | true | 73 | 98 | 100
ubuntu-22.04 | true | true |  |  |  | 67 | 92 | 56
ubuntu-22.04 | true | true |  |  | true | 71 | 96 | 20
ubuntu-22.04 | true | true |  | true |  | 72 | 97 | 88
ubuntu-22.04 | true | true |  | true | true | 76 | 101 | 25
ubuntu-22.04 | true | true | true |  |  | 67 | 92 | 76
ubuntu-22.04 | true | true | true |  | true | 71 | 96 | 26
ubuntu-22.04 | true | true | true | true |  | 72 | 97 | 16
ubuntu-22.04 | true | true | true | true | true | 76 | 101 | 23
