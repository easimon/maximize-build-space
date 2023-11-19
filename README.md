# Maximize available disk space for build tasks

If the available disk space on Github runners is too little for your build job, this action might be for you.
If not: please go on, there's nothing to see here.

This table shows the amount of free space you receive when using the action with the various options.

OS | Android SDKs removed | .NET SDKs removed | Haskell removed | CodeQL Removed | Cached Docker Images Removed | GB freed | GB free | Elapsed Time (seconds) |
---|:--------------------:|:-----------------:|:---------------:|:--------------:|:----------------------------:|:--------:|:-------:|:----------------------:|
ubuntu-20.04 |  |  |  |  |  | 53 | 75 | 2
ubuntu-20.04 |  |  |  |  | true | 59 | 81 | 34
ubuntu-20.04 |  |  |  | true |  | 56 | 78 | 3
ubuntu-20.04 |  |  |  | true | true | 63 | 85 | 13
ubuntu-20.04 |  |  | true |  |  | 53 | 75 | 2
ubuntu-20.04 |  |  | true |  | true | 59 | 81 | 9
ubuntu-20.04 |  |  | true | true |  | 56 | 78 | 3
ubuntu-20.04 |  |  | true | true | true | 63 | 85 | 8
ubuntu-20.04 |  | true |  |  |  | 55 | 77 | 3
ubuntu-20.04 |  | true |  |  | true | 61 | 83 | 42
ubuntu-20.04 |  | true |  | true |  | 59 | 82 | 3
ubuntu-20.04 |  | true |  | true | true | 65 | 87 | 44
ubuntu-20.04 |  | true | true |  |  | 55 | 78 | 6
ubuntu-20.04 |  | true | true |  | true | 62 | 85 | 41
ubuntu-20.04 |  | true | true | true |  | 59 | 82 | 5
ubuntu-20.04 |  | true | true | true | true | 65 | 87 | 10
ubuntu-20.04 | true |  |  |  |  | 67 | 89 | 42
ubuntu-20.04 | true |  |  |  | true | 73 | 95 | 84
ubuntu-20.04 | true |  |  | true |  | 70 | 92 | 56
ubuntu-20.04 | true |  |  | true | true | 77 | 99 | 88
ubuntu-20.04 | true |  | true |  |  | 67 | 89 | 48
ubuntu-20.04 | true |  | true |  | true | 73 | 95 | 95
ubuntu-20.04 | true |  | true | true |  | 70 | 92 | 10
ubuntu-20.04 | true |  | true | true | true | 77 | 99 | 96
ubuntu-20.04 | true | true |  |  |  | 67 | 90 | 66
ubuntu-20.04 | true | true |  |  | true | 75 | 97 | 22
ubuntu-20.04 | true | true |  | true |  | 72 | 94 | 40
ubuntu-20.04 | true | true |  | true | true | 79 | 101 | 49
ubuntu-20.04 | true | true | true |  |  | 69 | 91 | 57
ubuntu-20.04 | true | true | true |  | true | 73 | 96 | 41
ubuntu-20.04 | true | true | true | true |  | 72 | 94 | 51
ubuntu-20.04 | true | true | true | true | true | 77 | 100 | 92
ubuntu-22.04 |  |  |  |  |  | 52 | 76 | 2
ubuntu-22.04 |  |  |  |  | true | 58 | 82 | 32
ubuntu-22.04 |  |  |  | true |  | 56 | 80 | 4
ubuntu-22.04 |  |  |  | true | true | 61 | 85 | 12
ubuntu-22.04 |  |  | true |  |  | 52 | 77 | 2
ubuntu-22.04 |  |  | true |  | true | 58 | 82 | 14
ubuntu-22.04 |  |  | true | true |  | 56 | 80 | 3
ubuntu-22.04 |  |  | true | true | true | 61 | 85 | 12
ubuntu-22.04 |  | true |  |  |  | 55 | 80 | 12
ubuntu-22.04 |  | true |  |  | true | 60 | 84 | 51
ubuntu-22.04 |  | true |  | true |  | 58 | 82 | 10
ubuntu-22.04 |  | true |  | true | true | 64 | 88 | 55
ubuntu-22.04 |  | true | true |  |  | 54 | 78 | 4
ubuntu-22.04 |  | true | true |  | true | 60 | 84 | 13
ubuntu-22.04 |  | true | true | true |  | 58 | 82 | 8
ubuntu-22.04 |  | true | true | true | true | 64 | 88 | 55
ubuntu-22.04 | true |  |  |  |  | 66 | 90 | 12
ubuntu-22.04 | true |  |  |  | true | 70 | 95 | 90
ubuntu-22.04 | true |  |  | true |  | 70 | 94 | 51
ubuntu-22.04 | true |  |  | true | true | 73 | 98 | 95
ubuntu-22.04 | true |  | true |  |  | 66 | 90 | 51
ubuntu-22.04 | true |  | true |  | true | 72 | 96 | 97
ubuntu-22.04 | true |  | true | true |  | 70 | 94 | 51
ubuntu-22.04 | true |  | true | true | true | 75 | 99 | 83
ubuntu-22.04 | true | true |  |  |  | 68 | 92 | 54
ubuntu-22.04 | true | true |  |  | true | 74 | 98 | 88
ubuntu-22.04 | true | true |  | true |  | 72 | 96 | 18
ubuntu-22.04 | true | true |  | true | true | 78 | 102 | 74
ubuntu-22.04 | true | true | true |  |  | 68 | 92 | 57
ubuntu-22.04 | true | true | true |  | true | 74 | 98 | 95
ubuntu-22.04 | true | true | true | true |  | 72 | 96 | 65
ubuntu-22.04 | true | true | true | true | true | 78 | 102 | 98
