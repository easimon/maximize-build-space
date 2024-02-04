# Maximize available disk space for build tasks

If the available disk space on Github runners is too little for your build job, this action might be for you.
If not: please go on, there's nothing to see here.

This table shows the amount of free space you receive when using the action with the various options.

OS | Android SDKs removed | .NET SDKs removed | Haskell removed | CodeQL Removed | Cached Docker Images Removed | GB freed | GB free | Elapsed Time (seconds) |
---|:--------------------:|:-----------------:|:---------------:|:--------------:|:----------------------------:|:--------:|:-------:|:----------------------:|
ubuntu-20.04 |  |  |  |  |  | 63 | 82 | 2
ubuntu-20.04 |  |  |  |  | true | 66 | 85 | 16
ubuntu-20.04 |  |  |  | true |  | 68 | 87 | 3
ubuntu-20.04 |  |  |  | true | true | 71 | 90 | 17
ubuntu-20.04 |  |  | true |  |  | 63 | 82 | 4
ubuntu-20.04 |  |  | true |  | true | 66 | 85 | 20
ubuntu-20.04 |  |  | true | true |  | 68 | 87 | 3
ubuntu-20.04 |  |  | true | true | true | 71 | 90 | 18
ubuntu-20.04 |  | true |  |  |  | 64 | 83 | 3
ubuntu-20.04 |  | true |  |  | true | 67 | 86 | 14
ubuntu-20.04 |  | true |  | true |  | 69 | 88 | 5
ubuntu-20.04 |  | true |  | true | true | 72 | 91 | 8
ubuntu-20.04 |  | true | true |  |  | 64 | 83 | 4
ubuntu-20.04 |  | true | true |  | true | 67 | 86 | 6
ubuntu-20.04 |  | true | true | true |  | 69 | 88 | 4
ubuntu-20.04 |  | true | true | true | true | 72 | 91 | 7
ubuntu-20.04 | true |  |  |  |  | 71 | 90 | 30
ubuntu-20.04 | true |  |  |  | true | 75 | 94 | 13
ubuntu-20.04 | true |  |  | true |  | 76 | 95 | 31
ubuntu-20.04 | true |  |  | true | true | 79 | 98 | 42
ubuntu-20.04 | true |  | true |  |  | 71 | 90 | 8
ubuntu-20.04 | true |  | true |  | true | 75 | 94 | 18
ubuntu-20.04 | true |  | true | true |  | 76 | 95 | 35
ubuntu-20.04 | true |  | true | true | true | 79 | 98 | 41
ubuntu-20.04 | true | true |  |  |  | 73 | 92 | 43
ubuntu-20.04 | true | true |  |  | true | 76 | 95 | 71
ubuntu-20.04 | true | true |  | true |  | 78 | 97 | 29
ubuntu-20.04 | true | true |  | true | true | 81 | 100 | 12
ubuntu-20.04 | true | true | true |  |  | 73 | 92 | 7
ubuntu-20.04 | true | true | true |  | true | 76 | 95 | 51
ubuntu-20.04 | true | true | true | true |  | 78 | 97 | 35
ubuntu-20.04 | true | true | true | true | true | 81 | 100 | 49
ubuntu-22.04 |  |  |  |  |  | 62 | 83 | 1
ubuntu-22.04 |  |  |  |  | true | 65 | 86 | 26
ubuntu-22.04 |  |  |  | true |  | 67 | 88 | 4
ubuntu-22.04 |  |  |  | true | true | 70 | 91 | 21
ubuntu-22.04 |  |  | true |  |  | 62 | 83 | 2
ubuntu-22.04 |  |  | true |  | true | 66 | 86 | 31
ubuntu-22.04 |  |  | true | true |  | 67 | 88 | 4
ubuntu-22.04 |  |  | true | true | true | 70 | 91 | 24
ubuntu-22.04 |  | true |  |  |  | 64 | 85 | 4
ubuntu-22.04 |  | true |  |  | true | 67 | 88 | 23
ubuntu-22.04 |  | true |  | true |  | 69 | 89 | 7
ubuntu-22.04 |  | true |  | true | true | 72 | 93 | 8
ubuntu-22.04 |  | true | true |  |  | 64 | 85 | 3
ubuntu-22.04 |  | true | true |  | true | 67 | 88 | 30
ubuntu-22.04 |  | true | true | true |  | 68 | 89 | 4
ubuntu-22.04 |  | true | true | true | true | 72 | 93 | 9
ubuntu-22.04 | true |  |  |  |  | 71 | 92 | 13
ubuntu-22.04 | true |  |  |  | true | 74 | 95 | 15
ubuntu-22.04 | true |  |  | true |  | 76 | 97 | 51
ubuntu-22.04 | true |  |  | true | true | 79 | 100 | 77
ubuntu-22.04 | true |  | true |  |  | 71 | 92 | 31
ubuntu-22.04 | true |  | true |  | true | 74 | 95 | 17
ubuntu-22.04 | true |  | true | true |  | 76 | 97 | 49
ubuntu-22.04 | true |  | true | true | true | 79 | 100 | 24
ubuntu-22.04 | true | true |  |  |  | 72 | 93 | 52
ubuntu-22.04 | true | true |  |  | true | 75 | 96 | 15
ubuntu-22.04 | true | true |  | true |  | 77 | 98 | 48
ubuntu-22.04 | true | true |  | true | true | 80 | 101 | 58
ubuntu-22.04 | true | true | true |  |  | 72 | 93 | 38
ubuntu-22.04 | true | true | true |  | true | 75 | 96 | 75
ubuntu-22.04 | true | true | true | true |  | 77 | 98 | 55
ubuntu-22.04 | true | true | true | true | true | 80 | 101 | 69
