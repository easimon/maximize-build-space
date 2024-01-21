# Maximize available disk space for build tasks

If the available disk space on Github runners is too little for your build job, this action might be for you.
If not: please go on, there's nothing to see here.

This table shows the amount of free space you receive when using the action with the various options.

OS | Android SDKs removed | .NET SDKs removed | Haskell removed | CodeQL Removed | Cached Docker Images Removed | GB freed | GB free | Elapsed Time (seconds) |
---|:--------------------:|:-----------------:|:---------------:|:--------------:|:----------------------------:|:--------:|:-------:|:----------------------:|
ubuntu-20.04 |  |  |  |  |  | 53 | 82 | 7
ubuntu-20.04 |  |  |  |  | true | 56 | 85 | 19
ubuntu-20.04 |  |  |  | true |  | 58 | 87 | 3
ubuntu-20.04 |  |  |  | true | true | 61 | 90 | 19
ubuntu-20.04 |  |  | true |  |  | 53 | 82 | 2
ubuntu-20.04 |  |  | true |  | true | 56 | 85 | 5
ubuntu-20.04 |  |  | true | true |  | 58 | 87 | 3
ubuntu-20.04 |  |  | true | true | true | 61 | 90 | 14
ubuntu-20.04 |  | true |  |  |  | 54 | 83 | 4
ubuntu-20.04 |  | true |  |  | true | 58 | 87 | 15
ubuntu-20.04 |  | true |  | true |  | 59 | 88 | 5
ubuntu-20.04 |  | true |  | true | true | 62 | 91 | 16
ubuntu-20.04 |  | true | true |  |  | 54 | 83 | 3
ubuntu-20.04 |  | true | true |  | true | 58 | 87 | 16
ubuntu-20.04 |  | true | true | true |  | 59 | 88 | 5
ubuntu-20.04 |  | true | true | true | true | 62 | 91 | 22
ubuntu-20.04 | true |  |  |  |  | 62 | 91 | 50
ubuntu-20.04 | true |  |  |  | true | 65 | 94 | 30
ubuntu-20.04 | true |  |  | true |  | 66 | 95 | 70
ubuntu-20.04 | true |  |  | true | true | 69 | 98 | 49
ubuntu-20.04 | true |  | true |  |  | 62 | 91 | 38
ubuntu-20.04 | true |  | true |  | true | 65 | 94 | 19
ubuntu-20.04 | true |  | true | true |  | 66 | 95 | 8
ubuntu-20.04 | true |  | true | true | true | 69 | 98 | 103
ubuntu-20.04 | true | true |  |  |  | 63 | 92 | 53
ubuntu-20.04 | true | true |  |  | true | 66 | 95 | 23
ubuntu-20.04 | true | true |  | true |  | 68 | 97 | 42
ubuntu-20.04 | true | true |  | true | true | 71 | 100 | 55
ubuntu-20.04 | true | true | true |  |  | 63 | 92 | 49
ubuntu-20.04 | true | true | true |  | true | 66 | 95 | 58
ubuntu-20.04 | true | true | true | true |  | 68 | 97 | 41
ubuntu-20.04 | true | true | true | true | true | 71 | 100 | 52
ubuntu-22.04 |  |  |  |  |  | 53 | 83 | 2
ubuntu-22.04 |  |  |  |  | true | 56 | 86 | 20
ubuntu-22.04 |  |  |  | true |  | 57 | 87 | 4
ubuntu-22.04 |  |  |  | true | true | 60 | 90 | 12
ubuntu-22.04 |  |  | true |  |  | 53 | 83 | 2
ubuntu-22.04 |  |  | true |  | true | 56 | 86 | 7
ubuntu-22.04 |  |  | true | true |  | 57 | 87 | 4
ubuntu-22.04 |  |  | true | true | true | 60 | 90 | 18
ubuntu-22.04 |  | true |  |  |  | 54 | 84 | 5
ubuntu-22.04 |  | true |  |  | true | 57 | 87 | 8
ubuntu-22.04 |  | true |  | true |  | 59 | 89 | 5
ubuntu-22.04 |  | true |  | true | true | 62 | 92 | 17
ubuntu-22.04 |  | true | true |  |  | 54 | 84 | 10
ubuntu-22.04 |  | true | true |  | true | 57 | 87 | 17
ubuntu-22.04 |  | true | true | true |  | 59 | 89 | 4
ubuntu-22.04 |  | true | true | true | true | 62 | 92 | 10
ubuntu-22.04 | true |  |  |  |  | 61 | 91 | 37
ubuntu-22.04 | true |  |  |  | true | 64 | 94 | 16
ubuntu-22.04 | true |  |  | true |  | 66 | 96 | 50
ubuntu-22.04 | true |  |  | true | true | 69 | 99 | 63
ubuntu-22.04 | true |  | true |  |  | 61 | 91 | 48
ubuntu-22.04 | true |  | true |  | true | 64 | 94 | 21
ubuntu-22.04 | true |  | true | true |  | 66 | 96 | 45
ubuntu-22.04 | true |  | true | true | true | 69 | 99 | 65
ubuntu-22.04 | true | true |  |  |  | 63 | 93 | 15
ubuntu-22.04 | true | true |  |  | true | 66 | 96 | 66
ubuntu-22.04 | true | true |  | true |  | 67 | 97 | 54
ubuntu-22.04 | true | true |  | true | true | 71 | 101 | 18
ubuntu-22.04 | true | true | true |  |  | 63 | 93 | 59
ubuntu-22.04 | true | true | true |  | true | 66 | 96 | 72
ubuntu-22.04 | true | true | true | true |  | 67 | 97 | 65
ubuntu-22.04 | true | true | true | true | true | 71 | 101 | 83
