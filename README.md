# Maximize available disk space for build tasks

If the available disk space on Github runners is too little for your build job, this action might be for you.
If not: please go on, there's nothing to see here.

This table shows the amount of free space you receive when using the action with the various options.

OS | Android SDKs removed | .NET SDKs removed | Haskell removed | CodeQL Removed | Cached Docker Images Removed | GB freed | GB free | Elapsed Time (seconds) |
---|:--------------------:|:-----------------:|:---------------:|:--------------:|:----------------------------:|:--------:|:-------:|:----------------------:|
ubuntu-20.04 |  |  |  |  |  | 63 | 83 | 2
ubuntu-20.04 |  |  |  |  | true | 66 | 86 | 69
ubuntu-20.04 |  |  |  | true |  | 68 | 88 | 3
ubuntu-20.04 |  |  |  | true | true | 71 | 91 | 41
ubuntu-20.04 |  |  | true |  |  | 63 | 83 | 2
ubuntu-20.04 |  |  | true |  | true | 66 | 86 | 43
ubuntu-20.04 |  |  | true | true |  | 68 | 88 | 3
ubuntu-20.04 |  |  | true | true | true | 71 | 91 | 29
ubuntu-20.04 |  | true |  |  |  | 64 | 84 | 2
ubuntu-20.04 |  | true |  |  | true | 67 | 87 | 7
ubuntu-20.04 |  | true |  | true |  | 69 | 89 | 4
ubuntu-20.04 |  | true |  | true | true | 72 | 92 | 65
ubuntu-20.04 |  | true | true |  |  | 64 | 84 | 3
ubuntu-20.04 |  | true | true |  | true | 67 | 87 | 28
ubuntu-20.04 |  | true | true | true |  | 69 | 89 | 4
ubuntu-20.04 |  | true | true | true | true | 72 | 92 | 48
ubuntu-20.04 | true |  |  |  |  | 71 | 91 | 63
ubuntu-20.04 | true |  |  |  | true | 75 | 95 | 12
ubuntu-20.04 | true |  |  | true |  | 76 | 96 | 7
ubuntu-20.04 | true |  |  | true | true | 80 | 100 | 51
ubuntu-20.04 | true |  | true |  |  | 71 | 91 | 8
ubuntu-20.04 | true |  | true |  | true | 75 | 95 | 12
ubuntu-20.04 | true |  | true | true |  | 76 | 96 | 46
ubuntu-20.04 | true |  | true | true | true | 80 | 100 | 109
ubuntu-20.04 | true | true |  |  |  | 73 | 93 | 60
ubuntu-20.04 | true | true |  |  | true | 76 | 96 | 100
ubuntu-20.04 | true | true |  | true |  | 78 | 98 | 8
ubuntu-20.04 | true | true |  | true | true | 81 | 101 | 47
ubuntu-20.04 | true | true | true |  |  | 73 | 93 | 9
ubuntu-20.04 | true | true | true |  | true | 76 | 96 | 117
ubuntu-20.04 | true | true | true | true |  | 78 | 98 | 9
ubuntu-20.04 | true | true | true | true | true | 81 | 101 | 109
ubuntu-22.04 |  |  |  |  |  | 63 | 84 | 2
ubuntu-22.04 |  |  |  |  | true | 66 | 87 | 38
ubuntu-22.04 |  |  |  | true |  | 68 | 89 | 3
ubuntu-22.04 |  |  |  | true | true | 71 | 92 | 9
ubuntu-22.04 |  |  | true |  |  | 63 | 84 | 2
ubuntu-22.04 |  |  | true |  | true | 66 | 87 | 29
ubuntu-22.04 |  |  | true | true |  | 68 | 89 | 4
ubuntu-22.04 |  |  | true | true | true | 71 | 92 | 34
ubuntu-22.04 |  | true |  |  |  | 64 | 85 | 4
ubuntu-22.04 |  | true |  |  | true | 68 | 89 | 8
ubuntu-22.04 |  | true |  | true |  | 69 | 90 | 6
ubuntu-22.04 |  | true |  | true | true | 73 | 94 | 9
ubuntu-22.04 |  | true | true |  |  | 64 | 85 | 4
ubuntu-22.04 |  | true | true |  | true | 68 | 89 | 7
ubuntu-22.04 |  | true | true | true |  | 69 | 90 | 4
ubuntu-22.04 |  | true | true | true | true | 73 | 94 | 38
ubuntu-22.04 | true |  |  |  |  | 72 | 93 | 45
ubuntu-22.04 | true |  |  |  | true | 75 | 96 | 100
ubuntu-22.04 | true |  |  | true |  | 77 | 98 | 11
ubuntu-22.04 | true |  |  | true | true | 80 | 101 | 15
ubuntu-22.04 | true |  | true |  |  | 72 | 93 | 10
ubuntu-22.04 | true |  | true |  | true | 75 | 96 | 96
ubuntu-22.04 | true |  | true | true |  | 77 | 98 | 55
ubuntu-22.04 | true |  | true | true | true | 80 | 101 | 91
ubuntu-22.04 | true | true |  |  |  | 73 | 94 | 12
ubuntu-22.04 | true | true |  |  | true | 76 | 97 | 80
ubuntu-22.04 | true | true |  | true |  | 78 | 99 | 14
ubuntu-22.04 | true | true |  | true | true | 81 | 102 | 82
ubuntu-22.04 | true | true | true |  |  | 73 | 94 | 12
ubuntu-22.04 | true | true | true |  | true | 76 | 97 | 13
ubuntu-22.04 | true | true | true | true |  | 78 | 99 | 14
ubuntu-22.04 | true | true | true | true | true | 81 | 102 | 17
