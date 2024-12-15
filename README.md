# Maximize available disk space for build tasks

If the available disk space on Github runners is too little for your build job, this action might be for you.
If not: please go on, there's nothing to see here.

This table shows the amount of free space you receive when using the action with the various options.

OS | Android SDKs removed | .NET SDKs removed | Haskell removed | CodeQL Removed | Cached Docker Images Removed | GB freed | GB free | Elapsed Time (seconds) |
---|:--------------------:|:-----------------:|:---------------:|:--------------:|:----------------------------:|:--------:|:-------:|:----------------------:|
ubuntu-20.04 |  |  |  |  |  | 62 | 83 | 2
ubuntu-20.04 |  |  |  |  | true | 65 | 86 | 26
ubuntu-20.04 |  |  |  | true |  | 67 | 88 | 4
ubuntu-20.04 |  |  |  | true | true | 70 | 91 | 8
ubuntu-20.04 |  |  | true |  |  | 62 | 83 | 3
ubuntu-20.04 |  |  | true |  | true | 65 | 86 | 23
ubuntu-20.04 |  |  | true | true |  | 67 | 88 | 4
ubuntu-20.04 |  |  | true | true | true | 70 | 91 | 6
ubuntu-20.04 |  | true |  |  |  | 64 | 85 | 5
ubuntu-20.04 |  | true |  |  | true | 66 | 87 | 43
ubuntu-20.04 |  | true |  | true |  | 69 | 90 | 5
ubuntu-20.04 |  | true |  | true | true | 71 | 92 | 41
ubuntu-20.04 |  | true | true |  |  | 64 | 85 | 4
ubuntu-20.04 |  | true | true |  | true | 66 | 87 | 8
ubuntu-20.04 |  | true | true | true |  | 69 | 90 | 4
ubuntu-20.04 |  | true | true | true | true | 71 | 92 | 19
ubuntu-20.04 | true |  |  |  |  | 70 | 91 | 18
ubuntu-20.04 | true |  |  |  | true | 72 | 93 | 121
ubuntu-20.04 | true |  |  | true |  | 75 | 96 | 65
ubuntu-20.04 | true |  |  | true | true | 77 | 98 | 19
ubuntu-20.04 | true |  | true |  |  | 70 | 91 | 12
ubuntu-20.04 | true |  | true |  | true | 72 | 93 | 21
ubuntu-20.04 | true |  | true | true |  | 75 | 96 | 15
ubuntu-20.04 | true |  | true | true | true | 77 | 98 | 55
ubuntu-20.04 | true | true |  |  |  | 71 | 92 | 15
ubuntu-20.04 | true | true |  |  | true | 74 | 95 | 109
ubuntu-20.04 | true | true |  | true |  | 76 | 97 | 18
ubuntu-20.04 | true | true |  | true | true | 79 | 100 | 84
ubuntu-20.04 | true | true | true |  |  | 71 | 92 | 217
ubuntu-20.04 | true | true | true |  | true | 74 | 95 | 123
ubuntu-20.04 | true | true | true | true |  | 76 | 97 | 115
ubuntu-20.04 | true | true | true | true | true | 79 | 100 | 34
ubuntu-22.04 |  |  |  |  |  | 62 | 84 | 2
ubuntu-22.04 |  |  |  |  | true | 65 | 87 | 7
ubuntu-22.04 |  |  |  | true |  | 67 | 89 | 3
ubuntu-22.04 |  |  |  | true | true | 70 | 92 | 6
ubuntu-22.04 |  |  | true |  |  | 62 | 84 | 2
ubuntu-22.04 |  |  | true |  | true | 65 | 87 | 5
ubuntu-22.04 |  |  | true | true |  | 67 | 89 | 4
ubuntu-22.04 |  |  | true | true | true | 70 | 92 | 8
ubuntu-22.04 |  | true |  |  |  | 64 | 86 | 4
ubuntu-22.04 |  | true |  |  | true | 66 | 88 | 32
ubuntu-22.04 |  | true |  | true |  | 69 | 91 | 4
ubuntu-22.04 |  | true |  | true | true | 71 | 93 | 7
ubuntu-22.04 |  | true | true |  |  | 64 | 86 | 6
ubuntu-22.04 |  | true | true |  | true | 66 | 88 | 7
ubuntu-22.04 |  | true | true | true |  | 69 | 91 | 4
ubuntu-22.04 |  | true | true | true | true | 71 | 93 | 8
ubuntu-22.04 | true |  |  |  |  | 70 | 92 | 14
ubuntu-22.04 | true |  |  |  | true | 72 | 94 | 15
ubuntu-22.04 | true |  |  | true |  | 75 | 97 | 14
ubuntu-22.04 | true |  |  | true | true | 77 | 99 | 18
ubuntu-22.04 | true |  | true |  |  | 70 | 92 | 78
ubuntu-22.04 | true |  | true |  | true | 72 | 94 | 19
ubuntu-22.04 | true |  | true | true |  | 75 | 97 | 68
ubuntu-22.04 | true |  | true | true | true | 77 | 99 | 88
ubuntu-22.04 | true | true |  |  |  | 71 | 93 | 18
ubuntu-22.04 | true | true |  |  | true | 74 | 96 | 20
ubuntu-22.04 | true | true |  | true |  | 76 | 98 | 19
ubuntu-22.04 | true | true |  | true | true | 79 | 101 | 82
ubuntu-22.04 | true | true | true |  |  | 71 | 93 | 12
ubuntu-22.04 | true | true | true |  | true | 74 | 96 | 72
ubuntu-22.04 | true | true | true | true |  | 76 | 98 | 20
ubuntu-22.04 | true | true | true | true | true | 79 | 101 | 34
