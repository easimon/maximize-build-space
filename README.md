# Maximize available disk space for build tasks

If the available disk space on Github runners is too little for your build job, this action might be for you.
If not: please go on, there's nothing to see here.

This table shows the amount of free space you receive when using the action with the various options.

OS | Android SDKs removed | .NET SDKs removed | Haskell removed | CodeQL Removed | Cached Docker Images Removed | GB freed | GB free | Elapsed Time (seconds) |
---|:--------------------:|:-----------------:|:---------------:|:--------------:|:----------------------------:|:--------:|:-------:|:----------------------:|
ubuntu-20.04 |  |  |  |  |  | 62 | 82 | 2
ubuntu-20.04 |  |  |  |  | true | 65 | 85 | 8
ubuntu-20.04 |  |  |  | true |  | 67 | 87 | 3
ubuntu-20.04 |  |  |  | true | true | 70 | 90 | 46
ubuntu-20.04 |  |  | true |  |  | 62 | 82 | 2
ubuntu-20.04 |  |  | true |  | true | 65 | 85 | 32
ubuntu-20.04 |  |  | true | true |  | 67 | 87 | 3
ubuntu-20.04 |  |  | true | true | true | 70 | 90 | 28
ubuntu-20.04 |  | true |  |  |  | 64 | 84 | 4
ubuntu-20.04 |  | true |  |  | true | 67 | 87 | 27
ubuntu-20.04 |  | true |  | true |  | 69 | 89 | 5
ubuntu-20.04 |  | true |  | true | true | 72 | 92 | 9
ubuntu-20.04 |  | true | true |  |  | 64 | 84 | 4
ubuntu-20.04 |  | true | true |  | true | 67 | 87 | 7
ubuntu-20.04 |  | true | true | true |  | 69 | 89 | 4
ubuntu-20.04 |  | true | true | true | true | 72 | 92 | 25
ubuntu-20.04 | true |  |  |  |  | 71 | 91 | 7
ubuntu-20.04 | true |  |  |  | true | 74 | 94 | 78
ubuntu-20.04 | true |  |  | true |  | 76 | 96 | 48
ubuntu-20.04 | true |  |  | true | true | 79 | 99 | 97
ubuntu-20.04 | true |  | true |  |  | 71 | 91 | 49
ubuntu-20.04 | true |  | true |  | true | 74 | 94 | 15
ubuntu-20.04 | true |  | true | true |  | 76 | 96 | 50
ubuntu-20.04 | true |  | true | true | true | 79 | 99 | 99
ubuntu-20.04 | true | true |  |  |  | 72 | 92 | 9
ubuntu-20.04 | true | true |  |  | true | 76 | 96 | 12
ubuntu-20.04 | true | true |  | true |  | 77 | 97 | 52
ubuntu-20.04 | true | true |  | true | true | 80 | 100 | 91
ubuntu-20.04 | true | true | true |  |  | 72 | 92 | 66
ubuntu-20.04 | true | true | true |  | true | 76 | 96 | 32
ubuntu-20.04 | true | true | true | true |  | 77 | 97 | 38
ubuntu-20.04 | true | true | true | true | true | 80 | 100 | 87
ubuntu-22.04 |  |  |  |  |  | 62 | 83 | 2
ubuntu-22.04 |  |  |  |  | true | 65 | 86 | 8
ubuntu-22.04 |  |  |  | true |  | 67 | 88 | 4
ubuntu-22.04 |  |  |  | true | true | 70 | 91 | 8
ubuntu-22.04 |  |  | true |  |  | 62 | 83 | 2
ubuntu-22.04 |  |  | true |  | true | 65 | 86 | 37
ubuntu-22.04 |  |  | true | true |  | 67 | 88 | 4
ubuntu-22.04 |  |  | true | true | true | 70 | 91 | 42
ubuntu-22.04 |  | true |  |  |  | 64 | 85 | 4
ubuntu-22.04 |  | true |  |  | true | 67 | 88 | 7
ubuntu-22.04 |  | true |  | true |  | 69 | 90 | 4
ubuntu-22.04 |  | true |  | true | true | 72 | 93 | 8
ubuntu-22.04 |  | true | true |  |  | 64 | 85 | 4
ubuntu-22.04 |  | true | true |  | true | 67 | 88 | 39
ubuntu-22.04 |  | true | true | true |  | 69 | 90 | 4
ubuntu-22.04 |  | true | true | true | true | 72 | 93 | 7
ubuntu-22.04 | true |  |  |  |  | 71 | 92 | 60
ubuntu-22.04 | true |  |  |  | true | 74 | 95 | 19
ubuntu-22.04 | true |  |  | true |  | 76 | 97 | 63
ubuntu-22.04 | true |  |  | true | true | 79 | 100 | 19
ubuntu-22.04 | true |  | true |  |  | 71 | 92 | 8
ubuntu-22.04 | true |  | true |  | true | 74 | 95 | 101
ubuntu-22.04 | true |  | true | true |  | 76 | 97 | 55
ubuntu-22.04 | true |  | true | true | true | 79 | 100 | 88
ubuntu-22.04 | true | true |  |  |  | 73 | 94 | 62
ubuntu-22.04 | true | true |  |  | true | 76 | 97 | 16
ubuntu-22.04 | true | true |  | true |  | 77 | 98 | 63
ubuntu-22.04 | true | true |  | true | true | 80 | 101 | 16
ubuntu-22.04 | true | true | true |  |  | 73 | 94 | 54
ubuntu-22.04 | true | true | true |  | true | 76 | 97 | 14
ubuntu-22.04 | true | true | true | true |  | 77 | 98 | 11
ubuntu-22.04 | true | true | true | true | true | 80 | 101 | 16
