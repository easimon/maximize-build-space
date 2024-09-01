# Maximize available disk space for build tasks

If the available disk space on Github runners is too little for your build job, this action might be for you.
If not: please go on, there's nothing to see here.

This table shows the amount of free space you receive when using the action with the various options.

OS | Android SDKs removed | .NET SDKs removed | Haskell removed | CodeQL Removed | Cached Docker Images Removed | GB freed | GB free | Elapsed Time (seconds) |
---|:--------------------:|:-----------------:|:---------------:|:--------------:|:----------------------------:|:--------:|:-------:|:----------------------:|
ubuntu-20.04 |  |  |  |  |  | 63 | 84 | 3
ubuntu-20.04 |  |  |  |  | true | 66 | 87 | 6
ubuntu-20.04 |  |  |  | true |  | 68 | 89 | 4
ubuntu-20.04 |  |  |  | true | true | 71 | 92 | 22
ubuntu-20.04 |  |  | true |  |  | 63 | 84 | 3
ubuntu-20.04 |  |  | true |  | true | 66 | 87 | 22
ubuntu-20.04 |  |  | true | true |  | 68 | 89 | 4
ubuntu-20.04 |  |  | true | true | true | 71 | 92 | 26
ubuntu-20.04 |  | true |  |  |  | 64 | 85 | 4
ubuntu-20.04 |  | true |  |  | true | 67 | 88 | 10
ubuntu-20.04 |  | true |  | true |  | 69 | 90 | 5
ubuntu-20.04 |  | true |  | true | true | 72 | 93 | 23
ubuntu-20.04 |  | true | true |  |  | 64 | 85 | 3
ubuntu-20.04 |  | true | true |  | true | 67 | 88 | 24
ubuntu-20.04 |  | true | true | true |  | 69 | 90 | 5
ubuntu-20.04 |  | true | true | true | true | 72 | 93 | 25
ubuntu-20.04 | true |  |  |  |  | 70 | 91 | 69
ubuntu-20.04 | true |  |  |  | true | 73 | 94 | 16
ubuntu-20.04 | true |  |  | true |  | 75 | 96 | 15
ubuntu-20.04 | true |  |  | true | true | 78 | 99 | 15
ubuntu-20.04 | true |  | true |  |  | 70 | 91 | 67
ubuntu-20.04 | true |  | true |  | true | 73 | 94 | 89
ubuntu-20.04 | true |  | true | true |  | 75 | 96 | 15
ubuntu-20.04 | true |  | true | true | true | 78 | 99 | 31
ubuntu-20.04 | true | true |  |  |  | 72 | 93 | 73
ubuntu-20.04 | true | true |  |  | true | 75 | 96 | 80
ubuntu-20.04 | true | true |  | true |  | 77 | 98 | 51
ubuntu-20.04 | true | true |  | true | true | 80 | 101 | 78
ubuntu-20.04 | true | true | true |  |  | 72 | 93 | 13
ubuntu-20.04 | true | true | true |  | true | 75 | 96 | 22
ubuntu-20.04 | true | true | true | true |  | 77 | 98 | 17
ubuntu-20.04 | true | true | true | true | true | 80 | 101 | 101
ubuntu-22.04 |  |  |  |  |  | 63 | 85 | 1
ubuntu-22.04 |  |  |  |  | true | 66 | 88 | 38
ubuntu-22.04 |  |  |  | true |  | 68 | 90 | 4
ubuntu-22.04 |  |  |  | true | true | 71 | 93 | 8
ubuntu-22.04 |  |  | true |  |  | 63 | 85 | 2
ubuntu-22.04 |  |  | true |  | true | 66 | 88 | 8
ubuntu-22.04 |  |  | true | true |  | 68 | 90 | 4
ubuntu-22.04 |  |  | true | true | true | 71 | 93 | 8
ubuntu-22.04 |  | true |  |  |  | 64 | 86 | 4
ubuntu-22.04 |  | true |  |  | true | 68 | 90 | 46
ubuntu-22.04 |  | true |  | true |  | 69 | 91 | 5
ubuntu-22.04 |  | true |  | true | true | 72 | 94 | 12
ubuntu-22.04 |  | true | true |  |  | 64 | 86 | 3
ubuntu-22.04 |  | true | true |  | true | 68 | 90 | 8
ubuntu-22.04 |  | true | true | true |  | 69 | 91 | 5
ubuntu-22.04 |  | true | true | true | true | 72 | 94 | 9
ubuntu-22.04 | true |  |  |  |  | 70 | 92 | 45
ubuntu-22.04 | true |  |  |  | true | 73 | 95 | 62
ubuntu-22.04 | true |  |  | true |  | 75 | 97 | 51
ubuntu-22.04 | true |  |  | true | true | 78 | 100 | 85
ubuntu-22.04 | true |  | true |  |  | 70 | 92 | 36
ubuntu-22.04 | true |  | true |  | true | 73 | 95 | 28
ubuntu-22.04 | true |  | true | true |  | 75 | 97 | 45
ubuntu-22.04 | true |  | true | true | true | 78 | 100 | 66
ubuntu-22.04 | true | true |  |  |  | 72 | 94 | 13
ubuntu-22.04 | true | true |  |  | true | 75 | 97 | 91
ubuntu-22.04 | true | true |  | true |  | 77 | 99 | 51
ubuntu-22.04 | true | true |  | true | true | 80 | 102 | 17
ubuntu-22.04 | true | true | true |  |  | 72 | 94 | 14
ubuntu-22.04 | true | true | true |  | true | 75 | 97 | 66
ubuntu-22.04 | true | true | true | true |  | 77 | 99 | 56
ubuntu-22.04 | true | true | true | true | true | 80 | 102 | 21
