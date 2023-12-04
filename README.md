# Maximize available disk space for build tasks

If the available disk space on Github runners is too little for your build job, this action might be for you.
If not: please go on, there's nothing to see here.

This table shows the amount of free space you receive when using the action with the various options.

OS | Android SDKs removed | .NET SDKs removed | Haskell removed | CodeQL Removed | Cached Docker Images Removed | GB freed | GB free | Elapsed Time (seconds) |
---|:--------------------:|:-----------------:|:---------------:|:--------------:|:----------------------------:|:--------:|:-------:|:----------------------:|
ubuntu-20.04 |  |  |  |  |  | 53 | 76 | 2
ubuntu-20.04 |  |  |  |  | true | 58 | 81 | 41
ubuntu-20.04 |  |  |  | true |  | 57 | 80 | 2
ubuntu-20.04 |  |  |  | true | true | 63 | 86 | 32
ubuntu-20.04 |  |  | true |  |  | 53 | 76 | 2
ubuntu-20.04 |  |  | true |  | true | 58 | 81 | 30
ubuntu-20.04 |  |  | true | true |  | 57 | 80 | 3
ubuntu-20.04 |  |  | true | true | true | 63 | 86 | 28
ubuntu-20.04 |  | true |  |  |  | 55 | 78 | 5
ubuntu-20.04 |  | true |  |  | true | 61 | 84 | 23
ubuntu-20.04 |  | true |  | true |  | 60 | 83 | 4
ubuntu-20.04 |  | true |  | true | true | 65 | 88 | 31
ubuntu-20.04 |  | true | true |  |  | 55 | 78 | 5
ubuntu-20.04 |  | true | true |  | true | 61 | 84 | 10
ubuntu-20.04 |  | true | true | true |  | 60 | 83 | 6
ubuntu-20.04 |  | true | true | true | true | 65 | 88 | 10
ubuntu-20.04 | true |  |  |  |  | 65 | 88 | 53
ubuntu-20.04 | true |  |  |  | true | 70 | 93 | 75
ubuntu-20.04 | true |  |  | true |  | 69 | 92 | 9
ubuntu-20.04 | true |  |  | true | true | 75 | 98 | 46
ubuntu-20.04 | true |  | true |  |  | 65 | 88 | 43
ubuntu-20.04 | true |  | true |  | true | 70 | 93 | 78
ubuntu-20.04 | true |  | true | true |  | 69 | 92 | 11
ubuntu-20.04 | true |  | true | true | true | 75 | 98 | 57
ubuntu-20.04 | true | true |  |  |  | 67 | 90 | 10
ubuntu-20.04 | true | true |  |  | true | 72 | 95 | 64
ubuntu-20.04 | true | true |  | true |  | 72 | 95 | 11
ubuntu-20.04 | true | true |  | true | true | 77 | 100 | 17
ubuntu-20.04 | true | true | true |  |  | 67 | 90 | 10
ubuntu-20.04 | true | true | true |  | true | 72 | 95 | 70
ubuntu-20.04 | true | true | true | true |  | 72 | 95 | 58
ubuntu-20.04 | true | true | true | true | true | 77 | 100 | 103
ubuntu-22.04 |  |  |  |  |  | 52 | 77 | 2
ubuntu-22.04 |  |  |  |  | true | 57 | 82 | 8
ubuntu-22.04 |  |  |  | true |  | 57 | 82 | 4
ubuntu-22.04 |  |  |  | true | true | 62 | 87 | 10
ubuntu-22.04 |  |  | true |  |  | 52 | 77 | 2
ubuntu-22.04 |  |  | true |  | true | 57 | 82 | 19
ubuntu-22.04 |  |  | true | true |  | 57 | 82 | 4
ubuntu-22.04 |  |  | true | true | true | 62 | 87 | 10
ubuntu-22.04 |  | true |  |  |  | 55 | 80 | 4
ubuntu-22.04 |  | true |  |  | true | 60 | 85 | 10
ubuntu-22.04 |  | true |  | true |  | 60 | 85 | 3
ubuntu-22.04 |  | true |  | true | true | 64 | 89 | 12
ubuntu-22.04 |  | true | true |  |  | 55 | 80 | 6
ubuntu-22.04 |  | true | true |  | true | 60 | 85 | 9
ubuntu-22.04 |  | true | true | true |  | 60 | 85 | 4
ubuntu-22.04 |  | true | true | true | true | 64 | 89 | 31
ubuntu-22.04 | true |  |  |  |  | 64 | 89 | 16
ubuntu-22.04 | true |  |  |  | true | 69 | 94 | 25
ubuntu-22.04 | true |  |  | true |  | 69 | 94 | 15
ubuntu-22.04 | true |  |  | true | true | 73 | 98 | 23
ubuntu-22.04 | true |  | true |  |  | 64 | 89 | 13
ubuntu-22.04 | true |  | true |  | true | 69 | 94 | 17
ubuntu-22.04 | true |  | true | true |  | 69 | 94 | 15
ubuntu-22.04 | true |  | true | true | true | 73 | 98 | 20
ubuntu-22.04 | true | true |  |  |  | 67 | 92 | 14
ubuntu-22.04 | true | true |  |  | true | 71 | 96 | 122
ubuntu-22.04 | true | true |  | true |  | 72 | 97 | 16
ubuntu-22.04 | true | true |  | true | true | 76 | 101 | 22
ubuntu-22.04 | true | true | true |  |  | 67 | 92 | 16
ubuntu-22.04 | true | true | true |  | true | 71 | 96 | 20
ubuntu-22.04 | true | true | true | true |  | 72 | 97 | 74
ubuntu-22.04 | true | true | true | true | true | 76 | 101 | 22
