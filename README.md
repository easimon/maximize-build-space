# Maximize available disk space for build tasks

If the available disk space on Github runners is too little for your build job, this action might be for you.
If not: please go on, there's nothing to see here.

This table shows the amount of free space you receive when using the action with the various options.

OS | Android SDKs removed | .NET SDKs removed | Haskell removed | CodeQL Removed | Cached Docker Images Removed | GB freed | GB free | Elapsed Time (seconds) |
---|:--------------------:|:-----------------:|:---------------:|:--------------:|:----------------------------:|:--------:|:-------:|:----------------------:|
ubuntu-20.04 |  |  |  |  |  | 53 | 83 | 1
ubuntu-20.04 |  |  |  |  | true | 56 | 86 | 15
ubuntu-20.04 |  |  |  | true |  | 57 | 87 | 4
ubuntu-20.04 |  |  |  | true | true | 60 | 90 | 18
ubuntu-20.04 |  |  | true |  |  | 53 | 83 | 2
ubuntu-20.04 |  |  | true |  | true | 56 | 86 | 16
ubuntu-20.04 |  |  | true | true |  | 57 | 87 | 3
ubuntu-20.04 |  |  | true | true | true | 60 | 90 | 5
ubuntu-20.04 |  | true |  |  |  | 54 | 84 | 4
ubuntu-20.04 |  | true |  |  | true | 57 | 87 | 15
ubuntu-20.04 |  | true |  | true |  | 59 | 89 | 4
ubuntu-20.04 |  | true |  | true | true | 62 | 92 | 22
ubuntu-20.04 |  | true | true |  |  | 54 | 84 | 5
ubuntu-20.04 |  | true | true |  | true | 57 | 87 | 6
ubuntu-20.04 |  | true | true | true |  | 59 | 89 | 5
ubuntu-20.04 |  | true | true | true | true | 62 | 92 | 22
ubuntu-20.04 | true |  |  |  |  | 61 | 91 | 8
ubuntu-20.04 | true |  |  |  | true | 64 | 94 | 53
ubuntu-20.04 | true |  |  | true |  | 66 | 96 | 49
ubuntu-20.04 | true |  |  | true | true | 69 | 99 | 54
ubuntu-20.04 | true |  | true |  |  | 61 | 91 | 44
ubuntu-20.04 | true |  | true |  | true | 64 | 94 | 8
ubuntu-20.04 | true |  | true | true |  | 66 | 96 | 38
ubuntu-20.04 | true |  | true | true | true | 69 | 99 | 69
ubuntu-20.04 | true | true |  |  |  | 63 | 93 | 51
ubuntu-20.04 | true | true |  |  | true | 66 | 96 | 13
ubuntu-20.04 | true | true |  | true |  | 67 | 97 | 49
ubuntu-20.04 | true | true |  | true | true | 71 | 101 | 52
ubuntu-20.04 | true | true | true |  |  | 63 | 93 | 8
ubuntu-20.04 | true | true | true |  | true | 66 | 96 | 22
ubuntu-20.04 | true | true | true | true |  | 67 | 97 | 48
ubuntu-20.04 | true | true | true | true | true | 71 | 101 | 17
ubuntu-22.04 |  |  |  |  |  | 52 | 83 | 1
ubuntu-22.04 |  |  |  |  | true | 55 | 86 | 6
ubuntu-22.04 |  |  |  | true |  | 57 | 88 | 4
ubuntu-22.04 |  |  |  | true | true | 60 | 91 | 20
ubuntu-22.04 |  |  | true |  |  | 52 | 83 | 2
ubuntu-22.04 |  |  | true |  | true | 55 | 86 | 16
ubuntu-22.04 |  |  | true | true |  | 57 | 88 | 4
ubuntu-22.04 |  |  | true | true | true | 60 | 91 | 8
ubuntu-22.04 |  | true |  |  |  | 54 | 85 | 4
ubuntu-22.04 |  | true |  |  | true | 57 | 88 | 7
ubuntu-22.04 |  | true |  | true |  | 59 | 90 | 5
ubuntu-22.04 |  | true |  | true | true | 62 | 93 | 8
ubuntu-22.04 |  | true | true |  |  | 54 | 85 | 4
ubuntu-22.04 |  | true | true |  | true | 57 | 88 | 21
ubuntu-22.04 |  | true | true | true |  | 59 | 90 | 5
ubuntu-22.04 |  | true | true | true | true | 62 | 93 | 18
ubuntu-22.04 | true |  |  |  |  | 61 | 92 | 63
ubuntu-22.04 | true |  |  |  | true | 64 | 95 | 19
ubuntu-22.04 | true |  |  | true |  | 66 | 97 | 13
ubuntu-22.04 | true |  |  | true | true | 69 | 100 | 65
ubuntu-22.04 | true |  | true |  |  | 61 | 92 | 47
ubuntu-22.04 | true |  | true |  | true | 64 | 95 | 13
ubuntu-22.04 | true |  | true | true |  | 66 | 97 | 56
ubuntu-22.04 | true |  | true | true | true | 69 | 100 | 22
ubuntu-22.04 | true | true |  |  |  | 62 | 93 | 12
ubuntu-22.04 | true | true |  |  | true | 65 | 96 | 75
ubuntu-22.04 | true | true |  | true |  | 67 | 98 | 65
ubuntu-22.04 | true | true |  | true | true | 70 | 101 | 17
ubuntu-22.04 | true | true | true |  |  | 62 | 93 | 46
ubuntu-22.04 | true | true | true |  | true | 65 | 96 | 14
ubuntu-22.04 | true | true | true | true |  | 67 | 98 | 63
ubuntu-22.04 | true | true | true | true | true | 70 | 101 | 61
