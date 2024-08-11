# Maximize available disk space for build tasks

If the available disk space on Github runners is too little for your build job, this action might be for you.
If not: please go on, there's nothing to see here.

This table shows the amount of free space you receive when using the action with the various options.

OS | Android SDKs removed | .NET SDKs removed | Haskell removed | CodeQL Removed | Cached Docker Images Removed | GB freed | GB free | Elapsed Time (seconds) |
---|:--------------------:|:-----------------:|:---------------:|:--------------:|:----------------------------:|:--------:|:-------:|:----------------------:|
ubuntu-20.04 |  |  |  |  |  | 62 | 80 | 2
ubuntu-20.04 |  |  |  |  | true | 66 | 84 | 36
ubuntu-20.04 |  |  |  | true |  | 67 | 85 | 5
ubuntu-20.04 |  |  |  | true | true | 70 | 88 | 49
ubuntu-20.04 |  |  | true |  |  | 62 | 80 | 2
ubuntu-20.04 |  |  | true |  | true | 66 | 84 | 61
ubuntu-20.04 |  |  | true | true |  | 67 | 85 | 4
ubuntu-20.04 |  |  | true | true | true | 70 | 88 | 48
ubuntu-20.04 |  | true |  |  |  | 64 | 82 | 4
ubuntu-20.04 |  | true |  |  | true | 67 | 85 | 61
ubuntu-20.04 |  | true |  | true |  | 69 | 87 | 6
ubuntu-20.04 |  | true |  | true | true | 72 | 90 | 37
ubuntu-20.04 |  | true | true |  |  | 64 | 82 | 5
ubuntu-20.04 |  | true | true |  | true | 67 | 85 | 55
ubuntu-20.04 |  | true | true | true |  | 69 | 87 | 6
ubuntu-20.04 |  | true | true | true | true | 72 | 90 | 9
ubuntu-20.04 | true |  |  |  |  | 73 | 91 | 46
ubuntu-20.04 | true |  |  |  | true | 76 | 94 | 16
ubuntu-20.04 | true |  |  | true |  | 78 | 96 | 75
ubuntu-20.04 | true |  |  | true | true | 81 | 99 | 86
ubuntu-20.04 | true |  | true |  |  | 73 | 91 | 57
ubuntu-20.04 | true |  | true |  | true | 76 | 94 | 112
ubuntu-20.04 | true |  | true | true |  | 78 | 96 | 71
ubuntu-20.04 | true |  | true | true | true | 81 | 99 | 173
ubuntu-20.04 | true | true |  |  |  | 75 | 93 | 14
ubuntu-20.04 | true | true |  |  | true | 78 | 96 | 143
ubuntu-20.04 | true | true |  | true |  | 80 | 98 | 15
ubuntu-20.04 | true | true |  | true | true | 83 | 101 | 114
ubuntu-20.04 | true | true | true |  |  | 75 | 93 | 14
ubuntu-20.04 | true | true | true |  | true | 78 | 96 | 16
ubuntu-20.04 | true | true | true | true |  | 80 | 98 | 16
ubuntu-20.04 | true | true | true | true | true | 83 | 101 | 61
ubuntu-22.04 |  |  |  |  |  | 63 | 82 | 2
ubuntu-22.04 |  |  |  |  | true | 66 | 85 | 8
ubuntu-22.04 |  |  |  | true |  | 68 | 87 | 4
ubuntu-22.04 |  |  |  | true | true | 71 | 90 | 8
ubuntu-22.04 |  |  | true |  |  | 63 | 82 | 2
ubuntu-22.04 |  |  | true |  | true | 66 | 85 | 34
ubuntu-22.04 |  |  | true | true |  | 68 | 87 | 4
ubuntu-22.04 |  |  | true | true | true | 71 | 90 | 8
ubuntu-22.04 |  | true |  |  |  | 64 | 83 | 4
ubuntu-22.04 |  | true |  |  | true | 67 | 86 | 33
ubuntu-22.04 |  | true |  | true |  | 69 | 88 | 4
ubuntu-22.04 |  | true |  | true | true | 72 | 91 | 26
ubuntu-22.04 |  | true | true |  |  | 64 | 83 | 4
ubuntu-22.04 |  | true | true |  | true | 67 | 86 | 7
ubuntu-22.04 |  | true | true | true |  | 69 | 88 | 6
ubuntu-22.04 |  | true | true | true | true | 72 | 91 | 8
ubuntu-22.04 | true |  |  |  |  | 74 | 93 | 44
ubuntu-22.04 | true |  |  |  | true | 77 | 96 | 90
ubuntu-22.04 | true |  |  | true |  | 78 | 97 | 12
ubuntu-22.04 | true |  |  | true | true | 82 | 101 | 18
ubuntu-22.04 | true |  | true |  |  | 74 | 93 | 50
ubuntu-22.04 | true |  | true |  | true | 77 | 96 | 16
ubuntu-22.04 | true |  | true | true |  | 78 | 97 | 44
ubuntu-22.04 | true |  | true | true | true | 82 | 101 | 60
ubuntu-22.04 | true | true |  |  |  | 75 | 94 | 12
ubuntu-22.04 | true | true |  |  | true | 78 | 97 | 89
ubuntu-22.04 | true | true |  | true |  | 80 | 99 | 11
ubuntu-22.04 | true | true |  | true | true | 83 | 102 | 17
ubuntu-22.04 | true | true | true |  |  | 75 | 94 | 49
ubuntu-22.04 | true | true | true |  | true | 78 | 97 | 89
ubuntu-22.04 | true | true | true | true |  | 80 | 99 | 51
ubuntu-22.04 | true | true | true | true | true | 83 | 102 | 103
