# Maximize available disk space for build tasks

If the available disk space on Github runners is too little for your build job, this action might be for you.
If not: please go on, there's nothing to see here.

This table shows the amount of free space you receive when using the action with the various options.

OS | Android SDKs removed | .NET SDKs removed | Haskell removed | CodeQL Removed | Cached Docker Images Removed | GB freed | GB free | Elapsed Time (seconds) |
---|:--------------------:|:-----------------:|:---------------:|:--------------:|:----------------------------:|:--------:|:-------:|:----------------------:|
ubuntu-20.04 |  |  |  |  |  | 53 | 76 | 1
ubuntu-20.04 |  |  |  |  | true | 58 | 81 | 27
ubuntu-20.04 |  |  |  | true |  | 57 | 80 | 3
ubuntu-20.04 |  |  |  | true | true | 63 | 86 | 8
ubuntu-20.04 |  |  | true |  |  | 53 | 76 | 2
ubuntu-20.04 |  |  | true |  | true | 58 | 81 | 7
ubuntu-20.04 |  |  | true | true |  | 57 | 80 | 2
ubuntu-20.04 |  |  | true | true | true | 63 | 86 | 42
ubuntu-20.04 |  | true |  |  |  | 55 | 78 | 6
ubuntu-20.04 |  | true |  |  | true | 61 | 84 | 7
ubuntu-20.04 |  | true |  | true |  | 60 | 83 | 5
ubuntu-20.04 |  | true |  | true | true | 65 | 88 | 9
ubuntu-20.04 |  | true | true |  |  | 55 | 78 | 3
ubuntu-20.04 |  | true | true |  | true | 61 | 84 | 40
ubuntu-20.04 |  | true | true | true |  | 60 | 83 | 3
ubuntu-20.04 |  | true | true | true | true | 65 | 88 | 30
ubuntu-20.04 | true |  |  |  |  | 65 | 88 | 50
ubuntu-20.04 | true |  |  |  | true | 70 | 93 | 66
ubuntu-20.04 | true |  |  | true |  | 69 | 92 | 43
ubuntu-20.04 | true |  |  | true | true | 75 | 98 | 26
ubuntu-20.04 | true |  | true |  |  | 65 | 88 | 46
ubuntu-20.04 | true |  | true |  | true | 70 | 93 | 37
ubuntu-20.04 | true |  | true | true |  | 69 | 92 | 10
ubuntu-20.04 | true |  | true | true | true | 75 | 98 | 56
ubuntu-20.04 | true | true |  |  |  | 67 | 90 | 10
ubuntu-20.04 | true | true |  |  | true | 72 | 95 | 88
ubuntu-20.04 | true | true |  | true |  | 72 | 95 | 46
ubuntu-20.04 | true | true |  | true | true | 77 | 100 | 19
ubuntu-20.04 | true | true | true |  |  | 67 | 90 | 55
ubuntu-20.04 | true | true | true |  | true | 72 | 95 | 51
ubuntu-20.04 | true | true | true | true |  | 72 | 95 | 11
ubuntu-20.04 | true | true | true | true | true | 77 | 100 | 15
ubuntu-22.04 |  |  |  |  |  | 52 | 77 | 2
ubuntu-22.04 |  |  |  |  | true | 57 | 82 | 18
ubuntu-22.04 |  |  |  | true |  | 57 | 82 | 5
ubuntu-22.04 |  |  |  | true | true | 62 | 87 | 12
ubuntu-22.04 |  |  | true |  |  | 52 | 77 | 1
ubuntu-22.04 |  |  | true |  | true | 57 | 82 | 21
ubuntu-22.04 |  |  | true | true |  | 57 | 82 | 4
ubuntu-22.04 |  |  | true | true | true | 62 | 87 | 9
ubuntu-22.04 |  | true |  |  |  | 55 | 80 | 6
ubuntu-22.04 |  | true |  |  | true | 60 | 85 | 23
ubuntu-22.04 |  | true |  | true |  | 60 | 85 | 4
ubuntu-22.04 |  | true |  | true | true | 64 | 89 | 18
ubuntu-22.04 |  | true | true |  |  | 55 | 80 | 5
ubuntu-22.04 |  | true | true |  | true | 60 | 85 | 79
ubuntu-22.04 |  | true | true | true |  | 60 | 85 | 4
ubuntu-22.04 |  | true | true | true | true | 64 | 89 | 11
ubuntu-22.04 | true |  |  |  |  | 64 | 89 | 15
ubuntu-22.04 | true |  |  |  | true | 69 | 94 | 105
ubuntu-22.04 | true |  |  | true |  | 69 | 94 | 16
ubuntu-22.04 | true |  |  | true | true | 73 | 98 | 114
ubuntu-22.04 | true |  | true |  |  | 64 | 89 | 17
ubuntu-22.04 | true |  | true |  | true | 69 | 94 | 98
ubuntu-22.04 | true |  | true | true |  | 69 | 94 | 18
ubuntu-22.04 | true |  | true | true | true | 73 | 98 | 19
ubuntu-22.04 | true | true |  |  |  | 67 | 92 | 13
ubuntu-22.04 | true | true |  |  | true | 71 | 96 | 20
ubuntu-22.04 | true | true |  | true |  | 72 | 97 | 16
ubuntu-22.04 | true | true |  | true | true | 76 | 101 | 106
ubuntu-22.04 | true | true | true |  |  | 67 | 92 | 16
ubuntu-22.04 | true | true | true |  | true | 71 | 96 | 25
ubuntu-22.04 | true | true | true | true |  | 72 | 97 | 93
ubuntu-22.04 | true | true | true | true | true | 76 | 101 | 99
