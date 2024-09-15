# Maximize available disk space for build tasks

If the available disk space on Github runners is too little for your build job, this action might be for you.
If not: please go on, there's nothing to see here.

This table shows the amount of free space you receive when using the action with the various options.

OS | Android SDKs removed | .NET SDKs removed | Haskell removed | CodeQL Removed | Cached Docker Images Removed | GB freed | GB free | Elapsed Time (seconds) |
---|:--------------------:|:-----------------:|:---------------:|:--------------:|:----------------------------:|:--------:|:-------:|:----------------------:|
ubuntu-20.04 |  |  |  |  |  | 63 | 84 | 2
ubuntu-20.04 |  |  |  |  | true | 66 | 87 | 21
ubuntu-20.04 |  |  |  | true |  | 68 | 89 | 4
ubuntu-20.04 |  |  |  | true | true | 71 | 92 | 22
ubuntu-20.04 |  |  | true |  |  | 63 | 84 | 3
ubuntu-20.04 |  |  | true |  | true | 66 | 87 | 22
ubuntu-20.04 |  |  | true | true |  | 68 | 89 | 4
ubuntu-20.04 |  |  | true | true | true | 71 | 92 | 9
ubuntu-20.04 |  | true |  |  |  | 64 | 85 | 3
ubuntu-20.04 |  | true |  |  | true | 67 | 88 | 9
ubuntu-20.04 |  | true |  | true |  | 69 | 90 | 5
ubuntu-20.04 |  | true |  | true | true | 72 | 93 | 11
ubuntu-20.04 |  | true | true |  |  | 64 | 85 | 5
ubuntu-20.04 |  | true | true |  | true | 67 | 88 | 7
ubuntu-20.04 |  | true | true | true |  | 69 | 90 | 6
ubuntu-20.04 |  | true | true | true | true | 72 | 93 | 24
ubuntu-20.04 | true |  |  |  |  | 70 | 91 | 63
ubuntu-20.04 | true |  |  |  | true | 73 | 94 | 98
ubuntu-20.04 | true |  |  | true |  | 75 | 96 | 15
ubuntu-20.04 | true |  |  | true | true | 78 | 99 | 26
ubuntu-20.04 | true |  | true |  |  | 70 | 91 | 66
ubuntu-20.04 | true |  | true |  | true | 73 | 94 | 78
ubuntu-20.04 | true |  | true | true |  | 75 | 96 | 75
ubuntu-20.04 | true |  | true | true | true | 78 | 99 | 224
ubuntu-20.04 | true | true |  |  |  | 72 | 93 | 87
ubuntu-20.04 | true | true |  |  | true | 75 | 96 | 74
ubuntu-20.04 | true | true |  | true |  | 76 | 97 | 14
ubuntu-20.04 | true | true |  | true | true | 80 | 101 | 18
ubuntu-20.04 | true | true | true |  |  | 72 | 93 | 57
ubuntu-20.04 | true | true | true |  | true | 75 | 96 | 88
ubuntu-20.04 | true | true | true | true |  | 76 | 97 | 80
ubuntu-20.04 | true | true | true | true | true | 80 | 101 | 102
ubuntu-22.04 |  |  |  |  |  | 63 | 85 | 2
ubuntu-22.04 |  |  |  |  | true | 66 | 88 | 29
ubuntu-22.04 |  |  |  | true |  | 68 | 90 | 4
ubuntu-22.04 |  |  |  | true | true | 71 | 93 | 8
ubuntu-22.04 |  |  | true |  |  | 63 | 85 | 2
ubuntu-22.04 |  |  | true |  | true | 66 | 88 | 6
ubuntu-22.04 |  |  | true | true |  | 68 | 90 | 3
ubuntu-22.04 |  |  | true | true | true | 71 | 93 | 10
ubuntu-22.04 |  | true |  |  |  | 64 | 86 | 3
ubuntu-22.04 |  | true |  |  | true | 67 | 89 | 9
ubuntu-22.04 |  | true |  | true |  | 69 | 91 | 5
ubuntu-22.04 |  | true |  | true | true | 72 | 94 | 8
ubuntu-22.04 |  | true | true |  |  | 64 | 86 | 3
ubuntu-22.04 |  | true | true |  | true | 67 | 89 | 8
ubuntu-22.04 |  | true | true | true |  | 69 | 91 | 5
ubuntu-22.04 |  | true | true | true | true | 72 | 94 | 9
ubuntu-22.04 | true |  |  |  |  | 70 | 92 | 58
ubuntu-22.04 | true |  |  |  | true | 73 | 95 | 19
ubuntu-22.04 | true |  |  | true |  | 75 | 97 | 14
ubuntu-22.04 | true |  |  | true | true | 78 | 100 | 28
ubuntu-22.04 | true |  | true |  |  | 70 | 92 | 12
ubuntu-22.04 | true |  | true |  | true | 73 | 95 | 109
ubuntu-22.04 | true |  | true | true |  | 75 | 97 | 70
ubuntu-22.04 | true |  | true | true | true | 78 | 100 | 100
ubuntu-22.04 | true | true |  |  |  | 72 | 94 | 15
ubuntu-22.04 | true | true |  |  | true | 75 | 97 | 15
ubuntu-22.04 | true | true |  | true |  | 77 | 99 | 71
ubuntu-22.04 | true | true |  | true | true | 80 | 102 | 21
ubuntu-22.04 | true | true | true |  |  | 72 | 94 | 62
ubuntu-22.04 | true | true | true |  | true | 75 | 97 | 21
ubuntu-22.04 | true | true | true | true |  | 77 | 99 | 71
ubuntu-22.04 | true | true | true | true | true | 80 | 102 | 17
