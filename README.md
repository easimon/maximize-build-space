# Maximize available disk space for build tasks

If the available disk space on Github runners is too little for your build job, this action might be for you.
If not: please go on, there's nothing to see here.

This table shows the amount of free space you receive when using the action with the various options.

OS | Android SDKs removed | .NET SDKs removed | Haskell removed | CodeQL Removed | Cached Docker Images Removed | GB freed | GB free | Elapsed Time (seconds) |
---|:--------------------:|:-----------------:|:---------------:|:--------------:|:----------------------------:|:--------:|:-------:|:----------------------:|
ubuntu-20.04 |  |  |  |  |  | 63 | 84 | 2
ubuntu-20.04 |  |  |  |  | true | 66 | 87 | 7
ubuntu-20.04 |  |  |  | true |  | 68 | 89 | 4
ubuntu-20.04 |  |  |  | true | true | 71 | 92 | 7
ubuntu-20.04 |  |  | true |  |  | 63 | 84 | 3
ubuntu-20.04 |  |  | true |  | true | 66 | 87 | 32
ubuntu-20.04 |  |  | true | true |  | 68 | 89 | 4
ubuntu-20.04 |  |  | true | true | true | 71 | 92 | 9
ubuntu-20.04 |  | true |  |  |  | 64 | 85 | 4
ubuntu-20.04 |  | true |  |  | true | 67 | 88 | 7
ubuntu-20.04 |  | true |  | true |  | 69 | 90 | 6
ubuntu-20.04 |  | true |  | true | true | 72 | 93 | 23
ubuntu-20.04 |  | true | true |  |  | 64 | 85 | 4
ubuntu-20.04 |  | true | true |  | true | 67 | 88 | 9
ubuntu-20.04 |  | true | true | true |  | 69 | 90 | 6
ubuntu-20.04 |  | true | true | true | true | 72 | 93 | 37
ubuntu-20.04 | true |  |  |  |  | 70 | 91 | 17
ubuntu-20.04 | true |  |  |  | true | 73 | 94 | 23
ubuntu-20.04 | true |  |  | true |  | 75 | 96 | 65
ubuntu-20.04 | true |  |  | true | true | 78 | 99 | 134
ubuntu-20.04 | true |  | true |  |  | 70 | 91 | 12
ubuntu-20.04 | true |  | true |  | true | 73 | 94 | 111
ubuntu-20.04 | true |  | true | true |  | 75 | 96 | 16
ubuntu-20.04 | true |  | true | true | true | 78 | 99 | 121
ubuntu-20.04 | true | true |  |  |  | 72 | 93 | 14
ubuntu-20.04 | true | true |  |  | true | 75 | 96 | 126
ubuntu-20.04 | true | true |  | true |  | 77 | 98 | 137
ubuntu-20.04 | true | true |  | true | true | 80 | 101 | 171
ubuntu-20.04 | true | true | true |  |  | 72 | 93 | 96
ubuntu-20.04 | true | true | true |  | true | 75 | 96 | 114
ubuntu-20.04 | true | true | true | true |  | 77 | 98 | 18
ubuntu-20.04 | true | true | true | true | true | 80 | 101 | 35
ubuntu-22.04 |  |  |  |  |  | 63 | 85 | 1
ubuntu-22.04 |  |  |  |  | true | 66 | 88 | 42
ubuntu-22.04 |  |  |  | true |  | 68 | 90 | 3
ubuntu-22.04 |  |  |  | true | true | 71 | 93 | 7
ubuntu-22.04 |  |  | true |  |  | 63 | 85 | 2
ubuntu-22.04 |  |  | true |  | true | 66 | 88 | 7
ubuntu-22.04 |  |  | true | true |  | 68 | 90 | 4
ubuntu-22.04 |  |  | true | true | true | 71 | 93 | 9
ubuntu-22.04 |  | true |  |  |  | 64 | 86 | 4
ubuntu-22.04 |  | true |  |  | true | 68 | 90 | 7
ubuntu-22.04 |  | true |  | true |  | 69 | 91 | 6
ubuntu-22.04 |  | true |  | true | true | 72 | 94 | 10
ubuntu-22.04 |  | true | true |  |  | 64 | 86 | 5
ubuntu-22.04 |  | true | true |  | true | 68 | 90 | 6
ubuntu-22.04 |  | true | true | true |  | 69 | 91 | 4
ubuntu-22.04 |  | true | true | true | true | 72 | 94 | 10
ubuntu-22.04 | true |  |  |  |  | 70 | 92 | 14
ubuntu-22.04 | true |  |  |  | true | 74 | 96 | 18
ubuntu-22.04 | true |  |  | true |  | 75 | 97 | 76
ubuntu-22.04 | true |  |  | true | true | 78 | 100 | 103
ubuntu-22.04 | true |  | true |  |  | 70 | 92 | 58
ubuntu-22.04 | true |  | true |  | true | 74 | 96 | 96
ubuntu-22.04 | true |  | true | true |  | 75 | 97 | 15
ubuntu-22.04 | true |  | true | true | true | 78 | 100 | 67
ubuntu-22.04 | true | true |  |  |  | 72 | 94 | 64
ubuntu-22.04 | true | true |  |  | true | 75 | 97 | 15
ubuntu-22.04 | true | true |  | true |  | 77 | 99 | 71
ubuntu-22.04 | true | true |  | true | true | 80 | 102 | 23
ubuntu-22.04 | true | true | true |  |  | 72 | 94 | 14
ubuntu-22.04 | true | true | true |  | true | 75 | 97 | 19
ubuntu-22.04 | true | true | true | true |  | 77 | 99 | 15
ubuntu-22.04 | true | true | true | true | true | 80 | 102 | 25
