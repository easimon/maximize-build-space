# Maximize available disk space for build tasks

If the available disk space on Github runners is too little for your build job, this action might be for you.
If not: please go on, there's nothing to see here.

This table shows the amount of free space you receive when using the action with the various options.

OS | Android SDKs removed | .NET SDKs removed | Haskell removed | CodeQL Removed | Cached Docker Images Removed | GB freed | GB free | Elapsed Time (seconds) |
---|:--------------------:|:-----------------:|:---------------:|:--------------:|:----------------------------:|:--------:|:-------:|:----------------------:|
ubuntu-20.04 |  |  |  |  |  | 63 | 84 | 2
ubuntu-20.04 |  |  |  |  | true | 66 | 87 | 24
ubuntu-20.04 |  |  |  | true |  | 68 | 89 | 4
ubuntu-20.04 |  |  |  | true | true | 71 | 92 | 38
ubuntu-20.04 |  |  | true |  |  | 63 | 84 | 2
ubuntu-20.04 |  |  | true |  | true | 66 | 87 | 25
ubuntu-20.04 |  |  | true | true |  | 68 | 89 | 4
ubuntu-20.04 |  |  | true | true | true | 71 | 92 | 8
ubuntu-20.04 |  | true |  |  |  | 64 | 85 | 5
ubuntu-20.04 |  | true |  |  | true | 67 | 88 | 11
ubuntu-20.04 |  | true |  | true |  | 69 | 90 | 5
ubuntu-20.04 |  | true |  | true | true | 72 | 93 | 42
ubuntu-20.04 |  | true | true |  |  | 64 | 85 | 5
ubuntu-20.04 |  | true | true |  | true | 67 | 88 | 23
ubuntu-20.04 |  | true | true | true |  | 69 | 90 | 6
ubuntu-20.04 |  | true | true | true | true | 72 | 93 | 32
ubuntu-20.04 | true |  |  |  |  | 70 | 91 | 57
ubuntu-20.04 | true |  |  |  | true | 73 | 94 | 166
ubuntu-20.04 | true |  |  | true |  | 75 | 96 | 14
ubuntu-20.04 | true |  |  | true | true | 78 | 99 | 102
ubuntu-20.04 | true |  | true |  |  | 70 | 91 | 14
ubuntu-20.04 | true |  | true |  | true | 73 | 94 | 107
ubuntu-20.04 | true |  | true | true |  | 75 | 96 | 13
ubuntu-20.04 | true |  | true | true | true | 78 | 99 | 20
ubuntu-20.04 | true | true |  |  |  | 72 | 93 | 163
ubuntu-20.04 | true | true |  |  | true | 75 | 96 | 99
ubuntu-20.04 | true | true |  | true |  | 77 | 98 | 77
ubuntu-20.04 | true | true |  | true | true | 80 | 101 | 119
ubuntu-20.04 | true | true | true |  |  | 72 | 93 | 15
ubuntu-20.04 | true | true | true |  | true | 75 | 96 | 16
ubuntu-20.04 | true | true | true | true |  | 77 | 98 | 63
ubuntu-20.04 | true | true | true | true | true | 80 | 101 | 19
ubuntu-22.04 |  |  |  |  |  | 63 | 85 | 2
ubuntu-22.04 |  |  |  |  | true | 66 | 88 | 8
ubuntu-22.04 |  |  |  | true |  | 68 | 90 | 4
ubuntu-22.04 |  |  |  | true | true | 71 | 93 | 35
ubuntu-22.04 |  |  | true |  |  | 63 | 85 | 2
ubuntu-22.04 |  |  | true |  | true | 66 | 88 | 6
ubuntu-22.04 |  |  | true | true |  | 68 | 90 | 4
ubuntu-22.04 |  |  | true | true | true | 71 | 93 | 8
ubuntu-22.04 |  | true |  |  |  | 64 | 86 | 5
ubuntu-22.04 |  | true |  |  | true | 68 | 90 | 7
ubuntu-22.04 |  | true |  | true |  | 69 | 91 | 4
ubuntu-22.04 |  | true |  | true | true | 72 | 94 | 8
ubuntu-22.04 |  | true | true |  |  | 64 | 86 | 3
ubuntu-22.04 |  | true | true |  | true | 68 | 90 | 27
ubuntu-22.04 |  | true | true | true |  | 69 | 91 | 5
ubuntu-22.04 |  | true | true | true | true | 72 | 94 | 33
ubuntu-22.04 | true |  |  |  |  | 70 | 92 | 19
ubuntu-22.04 | true |  |  |  | true | 73 | 95 | 95
ubuntu-22.04 | true |  |  | true |  | 75 | 97 | 15
ubuntu-22.04 | true |  |  | true | true | 78 | 100 | 21
ubuntu-22.04 | true |  | true |  |  | 70 | 92 | 72
ubuntu-22.04 | true |  | true |  | true | 73 | 95 | 18
ubuntu-22.04 | true |  | true | true |  | 75 | 97 | 16
ubuntu-22.04 | true |  | true | true | true | 78 | 100 | 134
ubuntu-22.04 | true | true |  |  |  | 72 | 94 | 16
ubuntu-22.04 | true | true |  |  | true | 75 | 97 | 19
ubuntu-22.04 | true | true |  | true |  | 77 | 99 | 17
ubuntu-22.04 | true | true |  | true | true | 80 | 102 | 62
ubuntu-22.04 | true | true | true |  |  | 72 | 94 | 17
ubuntu-22.04 | true | true | true |  | true | 75 | 97 | 36
ubuntu-22.04 | true | true | true | true |  | 77 | 99 | 13
ubuntu-22.04 | true | true | true | true | true | 80 | 102 | 18
