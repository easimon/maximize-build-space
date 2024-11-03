# Maximize available disk space for build tasks

If the available disk space on Github runners is too little for your build job, this action might be for you.
If not: please go on, there's nothing to see here.

This table shows the amount of free space you receive when using the action with the various options.

OS | Android SDKs removed | .NET SDKs removed | Haskell removed | CodeQL Removed | Cached Docker Images Removed | GB freed | GB free | Elapsed Time (seconds) |
---|:--------------------:|:-----------------:|:---------------:|:--------------:|:----------------------------:|:--------:|:-------:|:----------------------:|
ubuntu-20.04 |  |  |  |  |  | 63 | 83 | 3
ubuntu-20.04 |  |  |  |  | true | 66 | 86 | 8
ubuntu-20.04 |  |  |  | true |  | 68 | 88 | 4
ubuntu-20.04 |  |  |  | true | true | 71 | 91 | 45
ubuntu-20.04 |  |  | true |  |  | 63 | 83 | 3
ubuntu-20.04 |  |  | true |  | true | 66 | 86 | 61
ubuntu-20.04 |  |  | true | true |  | 68 | 88 | 4
ubuntu-20.04 |  |  | true | true | true | 71 | 91 | 68
ubuntu-20.04 |  | true |  |  |  | 64 | 84 | 5
ubuntu-20.04 |  | true |  |  | true | 68 | 88 | 67
ubuntu-20.04 |  | true |  | true |  | 69 | 89 | 5
ubuntu-20.04 |  | true |  | true | true | 72 | 92 | 9
ubuntu-20.04 |  | true | true |  |  | 64 | 84 | 4
ubuntu-20.04 |  | true | true |  | true | 68 | 88 | 88
ubuntu-20.04 |  | true | true | true |  | 69 | 89 | 6
ubuntu-20.04 |  | true | true | true | true | 72 | 92 | 8
ubuntu-20.04 | true |  |  |  |  | 70 | 90 | 12
ubuntu-20.04 | true |  |  |  | true | 73 | 93 | 24
ubuntu-20.04 | true |  |  | true |  | 75 | 95 | 137
ubuntu-20.04 | true |  |  | true | true | 78 | 98 | 54
ubuntu-20.04 | true |  | true |  |  | 70 | 90 | 76
ubuntu-20.04 | true |  | true |  | true | 73 | 93 | 174
ubuntu-20.04 | true |  | true | true |  | 75 | 95 | 17
ubuntu-20.04 | true |  | true | true | true | 78 | 98 | 25
ubuntu-20.04 | true | true |  |  |  | 72 | 92 | 14
ubuntu-20.04 | true | true |  |  | true | 75 | 95 | 73
ubuntu-20.04 | true | true |  | true |  | 77 | 97 | 62
ubuntu-20.04 | true | true |  | true | true | 80 | 100 | 20
ubuntu-20.04 | true | true | true |  |  | 72 | 92 | 64
ubuntu-20.04 | true | true | true |  | true | 75 | 95 | 154
ubuntu-20.04 | true | true | true | true |  | 77 | 97 | 14
ubuntu-20.04 | true | true | true | true | true | 80 | 100 | 113
ubuntu-22.04 |  |  |  |  |  | 63 | 84 | 2
ubuntu-22.04 |  |  |  |  | true | 66 | 87 | 6
ubuntu-22.04 |  |  |  | true |  | 68 | 89 | 4
ubuntu-22.04 |  |  |  | true | true | 71 | 92 | 7
ubuntu-22.04 |  |  | true |  |  | 63 | 84 | 2
ubuntu-22.04 |  |  | true |  | true | 66 | 87 | 40
ubuntu-22.04 |  |  | true | true |  | 68 | 89 | 3
ubuntu-22.04 |  |  | true | true | true | 71 | 92 | 8
ubuntu-22.04 |  | true |  |  |  | 64 | 85 | 3
ubuntu-22.04 |  | true |  |  | true | 67 | 88 | 7
ubuntu-22.04 |  | true |  | true |  | 69 | 90 | 5
ubuntu-22.04 |  | true |  | true | true | 72 | 93 | 25
ubuntu-22.04 |  | true | true |  |  | 64 | 85 | 4
ubuntu-22.04 |  | true | true |  | true | 67 | 88 | 6
ubuntu-22.04 |  | true | true | true |  | 69 | 90 | 5
ubuntu-22.04 |  | true | true | true | true | 72 | 93 | 11
ubuntu-22.04 | true |  |  |  |  | 70 | 91 | 13
ubuntu-22.04 | true |  |  |  | true | 73 | 94 | 113
ubuntu-22.04 | true |  |  | true |  | 75 | 96 | 17
ubuntu-22.04 | true |  |  | true | true | 78 | 99 | 41
ubuntu-22.04 | true |  | true |  |  | 70 | 91 | 15
ubuntu-22.04 | true |  | true |  | true | 73 | 94 | 20
ubuntu-22.04 | true |  | true | true |  | 75 | 96 | 103
ubuntu-22.04 | true |  | true | true | true | 78 | 99 | 26
ubuntu-22.04 | true | true |  |  |  | 72 | 93 | 12
ubuntu-22.04 | true | true |  |  | true | 75 | 96 | 21
ubuntu-22.04 | true | true |  | true |  | 77 | 98 | 12
ubuntu-22.04 | true | true |  | true | true | 80 | 101 | 23
ubuntu-22.04 | true | true | true |  |  | 72 | 93 | 17
ubuntu-22.04 | true | true | true |  | true | 75 | 96 | 17
ubuntu-22.04 | true | true | true | true |  | 77 | 98 | 16
ubuntu-22.04 | true | true | true | true | true | 80 | 101 | 17
