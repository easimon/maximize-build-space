# Maximize available disk space for build tasks

If the available disk space on Github runners is too little for your build job, this action might be for you.
If not: please go on, there's nothing to see here.

This table shows the amount of free space you receive when using the action with the various options.

OS | Android SDKs removed | .NET SDKs removed | Haskell removed | CodeQL Removed | Cached Docker Images Removed | GB freed | GB free | Elapsed Time (seconds) |
---|:--------------------:|:-----------------:|:---------------:|:--------------:|:----------------------------:|:--------:|:-------:|:----------------------:|
ubuntu-20.04 |  |  |  |  |  | 63 | 83 | 2
ubuntu-20.04 |  |  |  |  | true | 66 | 86 | 54
ubuntu-20.04 |  |  |  | true |  | 68 | 88 | 4
ubuntu-20.04 |  |  |  | true | true | 71 | 91 | 58
ubuntu-20.04 |  |  | true |  |  | 63 | 83 | 7
ubuntu-20.04 |  |  | true |  | true | 66 | 86 | 49
ubuntu-20.04 |  |  | true | true |  | 68 | 88 | 3
ubuntu-20.04 |  |  | true | true | true | 71 | 91 | 27
ubuntu-20.04 |  | true |  |  |  | 64 | 84 | 5
ubuntu-20.04 |  | true |  |  | true | 68 | 88 | 88
ubuntu-20.04 |  | true |  | true |  | 69 | 89 | 5
ubuntu-20.04 |  | true |  | true | true | 72 | 92 | 60
ubuntu-20.04 |  | true | true |  |  | 64 | 84 | 5
ubuntu-20.04 |  | true | true |  | true | 68 | 88 | 37
ubuntu-20.04 |  | true | true | true |  | 69 | 89 | 6
ubuntu-20.04 |  | true | true | true | true | 72 | 92 | 64
ubuntu-20.04 | true |  |  |  |  | 70 | 90 | 15
ubuntu-20.04 | true |  |  |  | true | 73 | 93 | 288
ubuntu-20.04 | true |  |  | true |  | 75 | 95 | 18
ubuntu-20.04 | true |  |  | true | true | 78 | 98 | 313
ubuntu-20.04 | true |  | true |  |  | 70 | 90 | 132
ubuntu-20.04 | true |  | true |  | true | 73 | 93 | 19
ubuntu-20.04 | true |  | true | true |  | 75 | 95 | 70
ubuntu-20.04 | true |  | true | true | true | 78 | 98 | 119
ubuntu-20.04 | true | true |  |  |  | 72 | 92 | 15
ubuntu-20.04 | true | true |  |  | true | 75 | 95 | 102
ubuntu-20.04 | true | true |  | true |  | 77 | 97 | 15
ubuntu-20.04 | true | true |  | true | true | 80 | 100 | 216
ubuntu-20.04 | true | true | true |  |  | 72 | 92 | 13
ubuntu-20.04 | true | true | true |  | true | 75 | 95 | 107
ubuntu-20.04 | true | true | true | true |  | 77 | 97 | 61
ubuntu-20.04 | true | true | true | true | true | 80 | 100 | 19
ubuntu-22.04 |  |  |  |  |  | 63 | 84 | 2
ubuntu-22.04 |  |  |  |  | true | 66 | 87 | 7
ubuntu-22.04 |  |  |  | true |  | 68 | 89 | 4
ubuntu-22.04 |  |  |  | true | true | 71 | 92 | 8
ubuntu-22.04 |  |  | true |  |  | 63 | 84 | 2
ubuntu-22.04 |  |  | true |  | true | 66 | 87 | 8
ubuntu-22.04 |  |  | true | true |  | 68 | 89 | 4
ubuntu-22.04 |  |  | true | true | true | 71 | 92 | 6
ubuntu-22.04 |  | true |  |  |  | 64 | 85 | 3
ubuntu-22.04 |  | true |  |  | true | 67 | 88 | 35
ubuntu-22.04 |  | true |  | true |  | 69 | 90 | 5
ubuntu-22.04 |  | true |  | true | true | 72 | 93 | 8
ubuntu-22.04 |  | true | true |  |  | 64 | 85 | 4
ubuntu-22.04 |  | true | true |  | true | 67 | 88 | 34
ubuntu-22.04 |  | true | true | true |  | 69 | 90 | 5
ubuntu-22.04 |  | true | true | true | true | 72 | 93 | 44
ubuntu-22.04 | true |  |  |  |  | 70 | 91 | 10
ubuntu-22.04 | true |  |  |  | true | 73 | 94 | 153
ubuntu-22.04 | true |  |  | true |  | 75 | 96 | 16
ubuntu-22.04 | true |  |  | true | true | 78 | 99 | 21
ubuntu-22.04 | true |  | true |  |  | 70 | 91 | 11
ubuntu-22.04 | true |  | true |  | true | 73 | 94 | 132
ubuntu-22.04 | true |  | true | true |  | 75 | 96 | 78
ubuntu-22.04 | true |  | true | true | true | 78 | 99 | 18
ubuntu-22.04 | true | true |  |  |  | 72 | 93 | 67
ubuntu-22.04 | true | true |  |  | true | 75 | 96 | 27
ubuntu-22.04 | true | true |  | true |  | 77 | 98 | 13
ubuntu-22.04 | true | true |  | true | true | 80 | 101 | 22
ubuntu-22.04 | true | true | true |  |  | 72 | 93 | 80
ubuntu-22.04 | true | true | true |  | true | 75 | 96 | 133
ubuntu-22.04 | true | true | true | true |  | 77 | 98 | 15
ubuntu-22.04 | true | true | true | true | true | 80 | 101 | 21
