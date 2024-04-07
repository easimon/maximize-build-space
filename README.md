# Maximize available disk space for build tasks

If the available disk space on Github runners is too little for your build job, this action might be for you.
If not: please go on, there's nothing to see here.

This table shows the amount of free space you receive when using the action with the various options.

OS | Android SDKs removed | .NET SDKs removed | Haskell removed | CodeQL Removed | Cached Docker Images Removed | GB freed | GB free | Elapsed Time (seconds) |
---|:--------------------:|:-----------------:|:---------------:|:--------------:|:----------------------------:|:--------:|:-------:|:----------------------:|
ubuntu-20.04 |  |  |  |  |  | 62 | 83 | 2
ubuntu-20.04 |  |  |  |  | true | 65 | 86 | 6
ubuntu-20.04 |  |  |  | true |  | 67 | 88 | 4
ubuntu-20.04 |  |  |  | true | true | 70 | 91 | 52
ubuntu-20.04 |  |  | true |  |  | 62 | 83 | 1
ubuntu-20.04 |  |  | true |  | true | 65 | 86 | 36
ubuntu-20.04 |  |  | true | true |  | 67 | 88 | 5
ubuntu-20.04 |  |  | true | true | true | 70 | 91 | 7
ubuntu-20.04 |  | true |  |  |  | 64 | 85 | 4
ubuntu-20.04 |  | true |  |  | true | 67 | 88 | 7
ubuntu-20.04 |  | true |  | true |  | 69 | 90 | 3
ubuntu-20.04 |  | true |  | true | true | 72 | 93 | 146
ubuntu-20.04 |  | true | true |  |  | 64 | 85 | 4
ubuntu-20.04 |  | true | true |  | true | 67 | 88 | 7
ubuntu-20.04 |  | true | true | true |  | 69 | 90 | 4
ubuntu-20.04 |  | true | true | true | true | 72 | 93 | 40
ubuntu-20.04 | true |  |  |  |  | 72 | 92 | 10
ubuntu-20.04 | true |  |  |  | true | 74 | 95 | 16
ubuntu-20.04 | true |  |  | true |  | 76 | 97 | 57
ubuntu-20.04 | true |  |  | true | true | 79 | 100 | 72
ubuntu-20.04 | true |  | true |  |  | 71 | 92 | 8
ubuntu-20.04 | true |  | true |  | true | 74 | 95 | 107
ubuntu-20.04 | true |  | true | true |  | 76 | 97 | 70
ubuntu-20.04 | true |  | true | true | true | 79 | 100 | 99
ubuntu-20.04 | true | true |  |  |  | 72 | 93 | 180
ubuntu-20.04 | true | true |  |  | true | 76 | 97 | 107
ubuntu-20.04 | true | true |  | true |  | 77 | 98 | 98
ubuntu-20.04 | true | true |  | true | true | 80 | 101 | 83
ubuntu-20.04 | true | true | true |  |  | 72 | 93 | 9
ubuntu-20.04 | true | true | true |  | true | 76 | 97 | 16
ubuntu-20.04 | true | true | true | true |  | 77 | 98 | 8
ubuntu-20.04 | true | true | true | true | true | 80 | 101 | 122
ubuntu-22.04 |  |  |  |  |  | 63 | 84 | 2
ubuntu-22.04 |  |  |  |  | true | 66 | 87 | 33
ubuntu-22.04 |  |  |  | true |  | 67 | 88 | 3
ubuntu-22.04 |  |  |  | true | true | 71 | 92 | 6
ubuntu-22.04 |  |  | true |  |  | 63 | 84 | 2
ubuntu-22.04 |  |  | true |  | true | 66 | 87 | 7
ubuntu-22.04 |  |  | true | true |  | 67 | 88 | 3
ubuntu-22.04 |  |  | true | true | true | 70 | 91 | 8
ubuntu-22.04 |  | true |  |  |  | 64 | 85 | 5
ubuntu-22.04 |  | true |  |  | true | 67 | 88 | 26
ubuntu-22.04 |  | true |  | true |  | 69 | 90 | 4
ubuntu-22.04 |  | true |  | true | true | 72 | 93 | 8
ubuntu-22.04 |  | true | true |  |  | 64 | 85 | 3
ubuntu-22.04 |  | true | true |  | true | 67 | 88 | 41
ubuntu-22.04 |  | true | true | true |  | 69 | 90 | 4
ubuntu-22.04 |  | true | true | true | true | 72 | 93 | 10
ubuntu-22.04 | true |  |  |  |  | 71 | 92 | 15
ubuntu-22.04 | true |  |  |  | true | 74 | 95 | 14
ubuntu-22.04 | true |  |  | true |  | 76 | 97 | 12
ubuntu-22.04 | true |  |  | true | true | 79 | 100 | 16
ubuntu-22.04 | true |  | true |  |  | 71 | 92 | 46
ubuntu-22.04 | true |  | true |  | true | 74 | 95 | 15
ubuntu-22.04 | true |  | true | true |  | 76 | 97 | 12
ubuntu-22.04 | true |  | true | true | true | 79 | 100 | 15
ubuntu-22.04 | true | true |  |  |  | 73 | 94 | 56
ubuntu-22.04 | true | true |  |  | true | 76 | 97 | 14
ubuntu-22.04 | true | true |  | true |  | 78 | 99 | 12
ubuntu-22.04 | true | true |  | true | true | 81 | 102 | 67
ubuntu-22.04 | true | true | true |  |  | 73 | 94 | 10
ubuntu-22.04 | true | true | true |  | true | 76 | 97 | 85
ubuntu-22.04 | true | true | true | true |  | 78 | 99 | 51
ubuntu-22.04 | true | true | true | true | true | 81 | 102 | 14
