# Maximize available disk space for build tasks

If the available disk space on Github runners is too little for your build job, this action might be for you.
If not: please go on, there's nothing to see here.

This table shows the amount of free space you receive when using the action with the various options.

OS | Android SDKs removed | .NET SDKs removed | Haskell removed | CodeQL Removed | Cached Docker Images Removed | GB freed | GB free | Elapsed Time (seconds) |
---|:--------------------:|:-----------------:|:---------------:|:--------------:|:----------------------------:|:--------:|:-------:|:----------------------:|
ubuntu-20.04 |  |  |  |  |  | 53 | 82 | 2
ubuntu-20.04 |  |  |  |  | true | 56 | 85 | 14
ubuntu-20.04 |  |  |  | true |  | 58 | 87 | 3
ubuntu-20.04 |  |  |  | true | true | 61 | 90 | 13
ubuntu-20.04 |  |  | true |  |  | 53 | 82 | 4
ubuntu-20.04 |  |  | true |  | true | 56 | 85 | 19
ubuntu-20.04 |  |  | true | true |  | 58 | 87 | 3
ubuntu-20.04 |  |  | true | true | true | 61 | 90 | 15
ubuntu-20.04 |  | true |  |  |  | 54 | 83 | 6
ubuntu-20.04 |  | true |  |  | true | 58 | 87 | 15
ubuntu-20.04 |  | true |  | true |  | 59 | 88 | 4
ubuntu-20.04 |  | true |  | true | true | 62 | 91 | 16
ubuntu-20.04 |  | true | true |  |  | 54 | 83 | 4
ubuntu-20.04 |  | true | true |  | true | 58 | 87 | 16
ubuntu-20.04 |  | true | true | true |  | 59 | 88 | 4
ubuntu-20.04 |  | true | true | true | true | 62 | 91 | 20
ubuntu-20.04 | true |  |  |  |  | 61 | 90 | 40
ubuntu-20.04 | true |  |  |  | true | 65 | 94 | 62
ubuntu-20.04 | true |  |  | true |  | 66 | 95 | 50
ubuntu-20.04 | true |  |  | true | true | 69 | 98 | 54
ubuntu-20.04 | true |  | true |  |  | 61 | 90 | 43
ubuntu-20.04 | true |  | true |  | true | 65 | 94 | 41
ubuntu-20.04 | true |  | true | true |  | 66 | 95 | 61
ubuntu-20.04 | true |  | true | true | true | 69 | 98 | 57
ubuntu-20.04 | true | true |  |  |  | 63 | 92 | 43
ubuntu-20.04 | true | true |  |  | true | 66 | 95 | 67
ubuntu-20.04 | true | true |  | true |  | 68 | 97 | 44
ubuntu-20.04 | true | true |  | true | true | 71 | 100 | 61
ubuntu-20.04 | true | true | true |  |  | 63 | 92 | 42
ubuntu-20.04 | true | true | true |  | true | 66 | 95 | 56
ubuntu-20.04 | true | true | true | true |  | 68 | 97 | 51
ubuntu-20.04 | true | true | true | true | true | 71 | 100 | 19
ubuntu-22.04 |  |  |  |  |  | 53 | 83 | 2
ubuntu-22.04 |  |  |  |  | true | 56 | 86 | 23
ubuntu-22.04 |  |  |  | true |  | 57 | 87 | 4
ubuntu-22.04 |  |  |  | true | true | 60 | 90 | 18
ubuntu-22.04 |  |  | true |  |  | 53 | 83 | 2
ubuntu-22.04 |  |  | true |  | true | 56 | 86 | 6
ubuntu-22.04 |  |  | true | true |  | 57 | 87 | 4
ubuntu-22.04 |  |  | true | true | true | 60 | 90 | 20
ubuntu-22.04 |  | true |  |  |  | 54 | 84 | 5
ubuntu-22.04 |  | true |  |  | true | 57 | 87 | 14
ubuntu-22.04 |  | true |  | true |  | 59 | 89 | 4
ubuntu-22.04 |  | true |  | true | true | 62 | 92 | 9
ubuntu-22.04 |  | true | true |  |  | 54 | 84 | 4
ubuntu-22.04 |  | true | true |  | true | 57 | 87 | 9
ubuntu-22.04 |  | true | true | true |  | 59 | 89 | 6
ubuntu-22.04 |  | true | true | true | true | 62 | 92 | 26
ubuntu-22.04 | true |  |  |  |  | 61 | 91 | 12
ubuntu-22.04 | true |  |  |  | true | 64 | 94 | 13
ubuntu-22.04 | true |  |  | true |  | 66 | 96 | 61
ubuntu-22.04 | true |  |  | true | true | 69 | 99 | 82
ubuntu-22.04 | true |  | true |  |  | 61 | 91 | 10
ubuntu-22.04 | true |  | true |  | true | 64 | 94 | 75
ubuntu-22.04 | true |  | true | true |  | 66 | 96 | 54
ubuntu-22.04 | true |  | true | true | true | 69 | 99 | 18
ubuntu-22.04 | true | true |  |  |  | 63 | 93 | 58
ubuntu-22.04 | true | true |  |  | true | 66 | 96 | 18
ubuntu-22.04 | true | true |  | true |  | 67 | 97 | 60
ubuntu-22.04 | true | true |  | true | true | 71 | 101 | 19
ubuntu-22.04 | true | true | true |  |  | 63 | 93 | 49
ubuntu-22.04 | true | true | true |  | true | 66 | 96 | 28
ubuntu-22.04 | true | true | true | true |  | 67 | 97 | 74
ubuntu-22.04 | true | true | true | true | true | 71 | 101 | 21
