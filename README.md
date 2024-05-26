# Maximize available disk space for build tasks

If the available disk space on Github runners is too little for your build job, this action might be for you.
If not: please go on, there's nothing to see here.

This table shows the amount of free space you receive when using the action with the various options.

OS | Android SDKs removed | .NET SDKs removed | Haskell removed | CodeQL Removed | Cached Docker Images Removed | GB freed | GB free | Elapsed Time (seconds) |
---|:--------------------:|:-----------------:|:---------------:|:--------------:|:----------------------------:|:--------:|:-------:|:----------------------:|
ubuntu-20.04 |  |  |  |  |  | 63 | 83 | 2
ubuntu-20.04 |  |  |  |  | true | 66 | 86 | 41
ubuntu-20.04 |  |  |  | true |  | 68 | 88 | 3
ubuntu-20.04 |  |  |  | true | true | 71 | 91 | 57
ubuntu-20.04 |  |  | true |  |  | 63 | 83 | 2
ubuntu-20.04 |  |  | true |  | true | 66 | 86 | 45
ubuntu-20.04 |  |  | true | true |  | 68 | 88 | 3
ubuntu-20.04 |  |  | true | true | true | 71 | 91 | 7
ubuntu-20.04 |  | true |  |  |  | 64 | 84 | 3
ubuntu-20.04 |  | true |  |  | true | 67 | 87 | 32
ubuntu-20.04 |  | true |  | true |  | 69 | 89 | 7
ubuntu-20.04 |  | true |  | true | true | 72 | 92 | 49
ubuntu-20.04 |  | true | true |  |  | 64 | 84 | 2
ubuntu-20.04 |  | true | true |  | true | 67 | 87 | 40
ubuntu-20.04 |  | true | true | true |  | 69 | 89 | 5
ubuntu-20.04 |  | true | true | true | true | 72 | 92 | 10
ubuntu-20.04 | true |  |  |  |  | 71 | 91 | 10
ubuntu-20.04 | true |  |  |  | true | 75 | 95 | 78
ubuntu-20.04 | true |  |  | true |  | 76 | 96 | 79
ubuntu-20.04 | true |  |  | true | true | 79 | 99 | 112
ubuntu-20.04 | true |  | true |  |  | 71 | 91 | 8
ubuntu-20.04 | true |  | true |  | true | 75 | 95 | 135
ubuntu-20.04 | true |  | true | true |  | 76 | 96 | 7
ubuntu-20.04 | true |  | true | true | true | 79 | 99 | 86
ubuntu-20.04 | true | true |  |  |  | 73 | 93 | 10
ubuntu-20.04 | true | true |  |  | true | 76 | 96 | 15
ubuntu-20.04 | true | true |  | true |  | 78 | 98 | 45
ubuntu-20.04 | true | true |  | true | true | 81 | 101 | 12
ubuntu-20.04 | true | true | true |  |  | 73 | 93 | 65
ubuntu-20.04 | true | true | true |  | true | 76 | 96 | 15
ubuntu-20.04 | true | true | true | true |  | 78 | 98 | 8
ubuntu-20.04 | true | true | true | true | true | 81 | 101 | 44
ubuntu-22.04 |  |  |  |  |  | 63 | 84 | 2
ubuntu-22.04 |  |  |  |  | true | 66 | 87 | 7
ubuntu-22.04 |  |  |  | true |  | 68 | 89 | 4
ubuntu-22.04 |  |  |  | true | true | 71 | 92 | 30
ubuntu-22.04 |  |  | true |  |  | 63 | 84 | 2
ubuntu-22.04 |  |  | true |  | true | 66 | 87 | 31
ubuntu-22.04 |  |  | true | true |  | 68 | 89 | 4
ubuntu-22.04 |  |  | true | true | true | 71 | 92 | 8
ubuntu-22.04 |  | true |  |  |  | 65 | 86 | 3
ubuntu-22.04 |  | true |  |  | true | 68 | 89 | 30
ubuntu-22.04 |  | true |  | true |  | 69 | 90 | 5
ubuntu-22.04 |  | true |  | true | true | 73 | 94 | 44
ubuntu-22.04 |  | true | true |  |  | 65 | 86 | 4
ubuntu-22.04 |  | true | true |  | true | 68 | 89 | 62
ubuntu-22.04 |  | true | true | true |  | 69 | 90 | 5
ubuntu-22.04 |  | true | true | true | true | 73 | 94 | 27
ubuntu-22.04 | true |  |  |  |  | 72 | 93 | 9
ubuntu-22.04 | true |  |  |  | true | 75 | 96 | 100
ubuntu-22.04 | true |  |  | true |  | 77 | 98 | 14
ubuntu-22.04 | true |  |  | true | true | 80 | 101 | 15
ubuntu-22.04 | true |  | true |  |  | 72 | 93 | 10
ubuntu-22.04 | true |  | true |  | true | 75 | 96 | 96
ubuntu-22.04 | true |  | true | true |  | 77 | 98 | 59
ubuntu-22.04 | true |  | true | true | true | 80 | 101 | 70
ubuntu-22.04 | true | true |  |  |  | 73 | 94 | 53
ubuntu-22.04 | true | true |  |  | true | 76 | 97 | 18
ubuntu-22.04 | true | true |  | true |  | 78 | 99 | 13
ubuntu-22.04 | true | true |  | true | true | 81 | 102 | 22
ubuntu-22.04 | true | true | true |  |  | 73 | 94 | 58
ubuntu-22.04 | true | true | true |  | true | 76 | 97 | 87
ubuntu-22.04 | true | true | true | true |  | 78 | 99 | 69
ubuntu-22.04 | true | true | true | true | true | 81 | 102 | 16
