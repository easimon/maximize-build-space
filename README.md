# Maximize available disk space for build tasks

If the available disk space on Github runners is too little for your build job, this action might be for you.
If not: please go on, there's nothing to see here.

This table shows the amount of free space you receive when using the action with the various options.

OS | Android SDKs removed | .NET SDKs removed | Haskell removed | CodeQL Removed | Cached Docker Images Removed | GB freed | GB free | Elapsed Time (seconds) |
---|:--------------------:|:-----------------:|:---------------:|:--------------:|:----------------------------:|:--------:|:-------:|:----------------------:|
ubuntu-20.04 |  |  |  |  |  | 62 | 83 | 2
ubuntu-20.04 |  |  |  |  | true | 65 | 86 | 19
ubuntu-20.04 |  |  |  | true |  | 67 | 88 | 3
ubuntu-20.04 |  |  |  | true | true | 70 | 91 | 18
ubuntu-20.04 |  |  | true |  |  | 62 | 83 | 5
ubuntu-20.04 |  |  | true |  | true | 65 | 86 | 25
ubuntu-20.04 |  |  | true | true |  | 67 | 88 | 7
ubuntu-20.04 |  |  | true | true | true | 70 | 91 | 16
ubuntu-20.04 |  | true |  |  |  | 64 | 85 | 2
ubuntu-20.04 |  | true |  |  | true | 67 | 88 | 19
ubuntu-20.04 |  | true |  | true |  | 69 | 90 | 8
ubuntu-20.04 |  | true |  | true | true | 72 | 93 | 7
ubuntu-20.04 |  | true | true |  |  | 64 | 85 | 5
ubuntu-20.04 |  | true | true |  | true | 67 | 88 | 25
ubuntu-20.04 |  | true | true | true |  | 69 | 90 | 4
ubuntu-20.04 |  | true | true | true | true | 72 | 93 | 7
ubuntu-20.04 | true |  |  |  |  | 71 | 92 | 12
ubuntu-20.04 | true |  |  |  | true | 74 | 95 | 18
ubuntu-20.04 | true |  |  | true |  | 76 | 97 | 60
ubuntu-20.04 | true |  |  | true | true | 79 | 100 | 68
ubuntu-20.04 | true |  | true |  |  | 71 | 92 | 38
ubuntu-20.04 | true |  | true |  | true | 74 | 95 | 68
ubuntu-20.04 | true |  | true | true |  | 76 | 97 | 13
ubuntu-20.04 | true |  | true | true | true | 79 | 100 | 47
ubuntu-20.04 | true | true |  |  |  | 72 | 93 | 52
ubuntu-20.04 | true | true |  |  | true | 75 | 96 | 11
ubuntu-20.04 | true | true |  | true |  | 77 | 98 | 50
ubuntu-20.04 | true | true |  | true | true | 80 | 101 | 12
ubuntu-20.04 | true | true | true |  |  | 72 | 93 | 8
ubuntu-20.04 | true | true | true |  | true | 75 | 96 | 60
ubuntu-20.04 | true | true | true | true |  | 77 | 98 | 48
ubuntu-20.04 | true | true | true | true | true | 80 | 101 | 14
ubuntu-22.04 |  |  |  |  |  | 63 | 84 | 2
ubuntu-22.04 |  |  |  |  | true | 66 | 87 | 28
ubuntu-22.04 |  |  |  | true |  | 67 | 88 | 4
ubuntu-22.04 |  |  |  | true | true | 71 | 92 | 38
ubuntu-22.04 |  |  | true |  |  | 63 | 84 | 4
ubuntu-22.04 |  |  | true |  | true | 66 | 87 | 7
ubuntu-22.04 |  |  | true | true |  | 67 | 88 | 5
ubuntu-22.04 |  |  | true | true | true | 71 | 92 | 9
ubuntu-22.04 |  | true |  |  |  | 64 | 85 | 5
ubuntu-22.04 |  | true |  |  | true | 67 | 88 | 7
ubuntu-22.04 |  | true |  | true |  | 69 | 90 | 6
ubuntu-22.04 |  | true |  | true | true | 72 | 93 | 9
ubuntu-22.04 |  | true | true |  |  | 64 | 85 | 3
ubuntu-22.04 |  | true | true |  | true | 67 | 88 | 25
ubuntu-22.04 |  | true | true | true |  | 69 | 90 | 4
ubuntu-22.04 |  | true | true | true | true | 72 | 93 | 8
ubuntu-22.04 | true |  |  |  |  | 71 | 92 | 50
ubuntu-22.04 | true |  |  |  | true | 74 | 95 | 82
ubuntu-22.04 | true |  |  | true |  | 76 | 97 | 62
ubuntu-22.04 | true |  |  | true | true | 79 | 100 | 17
ubuntu-22.04 | true |  | true |  |  | 71 | 92 | 12
ubuntu-22.04 | true |  | true |  | true | 74 | 95 | 15
ubuntu-22.04 | true |  | true | true |  | 76 | 97 | 52
ubuntu-22.04 | true |  | true | true | true | 79 | 100 | 18
ubuntu-22.04 | true | true |  |  |  | 73 | 94 | 10
ubuntu-22.04 | true | true |  |  | true | 76 | 97 | 15
ubuntu-22.04 | true | true |  | true |  | 78 | 99 | 12
ubuntu-22.04 | true | true |  | true | true | 81 | 102 | 71
ubuntu-22.04 | true | true | true |  |  | 73 | 94 | 48
ubuntu-22.04 | true | true | true |  | true | 76 | 97 | 66
ubuntu-22.04 | true | true | true | true |  | 78 | 99 | 124
ubuntu-22.04 | true | true | true | true | true | 81 | 102 | 94
