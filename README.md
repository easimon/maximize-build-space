# Maximize available disk space for build tasks

If the available disk space on Github runners is too little for your build job, this action might be for you.
If not: please go on, there's nothing to see here.

This table shows the amount of free space you receive when using the action with the various options.

OS | Android SDKs removed | .NET SDKs removed | Haskell removed | CodeQL Removed | Cached Docker Images Removed | GB freed | GB free | Elapsed Time (seconds) |
---|:--------------------:|:-----------------:|:---------------:|:--------------:|:----------------------------:|:--------:|:-------:|:----------------------:|
ubuntu-20.04 |  |  |  |  |  | 52 | 75 | 2
ubuntu-20.04 |  |  |  |  | true | 59 | 82 | 25
ubuntu-20.04 |  |  |  | true |  | 56 | 79 | 2
ubuntu-20.04 |  |  |  | true | true | 62 | 85 | 10
ubuntu-20.04 |  |  | true |  |  | 52 | 75 | 2
ubuntu-20.04 |  |  | true |  | true | 59 | 82 | 39
ubuntu-20.04 |  |  | true | true |  | 56 | 79 | 3
ubuntu-20.04 |  |  | true | true | true | 62 | 85 | 35
ubuntu-20.04 |  | true |  |  |  | 55 | 78 | 6
ubuntu-20.04 |  | true |  |  | true | 62 | 85 | 45
ubuntu-20.04 |  | true |  | true |  | 59 | 82 | 9
ubuntu-20.04 |  | true |  | true | true | 65 | 88 | 10
ubuntu-20.04 |  | true | true |  |  | 55 | 78 | 6
ubuntu-20.04 |  | true | true |  | true | 62 | 85 | 11
ubuntu-20.04 |  | true | true | true |  | 59 | 82 | 7
ubuntu-20.04 |  | true | true | true | true | 65 | 88 | 34
ubuntu-20.04 | true |  |  |  |  | 64 | 87 | 52
ubuntu-20.04 | true |  |  |  | true | 71 | 94 | 14
ubuntu-20.04 | true |  |  | true |  | 68 | 91 | 69
ubuntu-20.04 | true |  |  | true | true | 74 | 97 | 40
ubuntu-20.04 | true |  | true |  |  | 64 | 87 | 13
ubuntu-20.04 | true |  | true |  | true | 71 | 94 | 19
ubuntu-20.04 | true |  | true | true |  | 68 | 91 | 8
ubuntu-20.04 | true |  | true | true | true | 74 | 97 | 106
ubuntu-20.04 | true | true |  |  |  | 67 | 90 | 9
ubuntu-20.04 | true | true |  |  | true | 73 | 96 | 16
ubuntu-20.04 | true | true |  | true |  | 70 | 93 | 10
ubuntu-20.04 | true | true |  | true | true | 77 | 100 | 15
ubuntu-20.04 | true | true | true |  |  | 67 | 90 | 9
ubuntu-20.04 | true | true | true |  | true | 73 | 96 | 102
ubuntu-20.04 | true | true | true | true |  | 70 | 93 | 71
ubuntu-20.04 | true | true | true | true | true | 77 | 100 | 19
ubuntu-22.04 |  |  |  |  |  | 52 | 77 | 2
ubuntu-22.04 |  |  |  |  | true | 58 | 83 | 10
ubuntu-22.04 |  |  |  | true |  | 56 | 81 | 3
ubuntu-22.04 |  |  |  | true | true | 61 | 86 | 29
ubuntu-22.04 |  |  | true |  |  | 52 | 77 | 2
ubuntu-22.04 |  |  | true |  | true | 58 | 83 | 12
ubuntu-22.04 |  |  | true | true |  | 56 | 81 | 4
ubuntu-22.04 |  |  | true | true | true | 61 | 86 | 30
ubuntu-22.04 |  | true |  |  |  | 55 | 80 | 5
ubuntu-22.04 |  | true |  |  | true | 60 | 85 | 35
ubuntu-22.04 |  | true |  | true |  | 58 | 83 | 4
ubuntu-22.04 |  | true |  | true | true | 64 | 89 | 36
ubuntu-22.04 |  | true | true |  |  | 55 | 80 | 4
ubuntu-22.04 |  | true | true |  | true | 60 | 85 | 12
ubuntu-22.04 |  | true | true | true |  | 58 | 83 | 4
ubuntu-22.04 |  | true | true | true | true | 64 | 89 | 14
ubuntu-22.04 | true |  |  |  |  | 64 | 89 | 25
ubuntu-22.04 | true |  |  |  | true | 70 | 95 | 26
ubuntu-22.04 | true |  |  | true |  | 68 | 93 | 15
ubuntu-22.04 | true |  |  | true | true | 73 | 98 | 23
ubuntu-22.04 | true |  | true |  |  | 64 | 89 | 14
ubuntu-22.04 | true |  | true |  | true | 70 | 95 | 22
ubuntu-22.04 | true |  | true | true |  | 68 | 93 | 14
ubuntu-22.04 | true |  | true | true | true | 73 | 98 | 24
ubuntu-22.04 | true | true |  |  |  | 67 | 92 | 29
ubuntu-22.04 | true | true |  |  | true | 72 | 97 | 28
ubuntu-22.04 | true | true |  | true |  | 70 | 95 | 24
ubuntu-22.04 | true | true |  | true | true | 76 | 101 | 31
ubuntu-22.04 | true | true | true |  |  | 67 | 92 | 13
ubuntu-22.04 | true | true | true |  | true | 72 | 97 | 39
ubuntu-22.04 | true | true | true | true |  | 70 | 95 | 91
ubuntu-22.04 | true | true | true | true | true | 76 | 101 | 111
