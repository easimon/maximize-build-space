# Maximize available disk space for build tasks

If the available disk space on Github runners is too little for your build job, this action might be for you.
If not: please go on, there's nothing to see here.

This table shows the amount of free space you receive when using the action with the various options.

OS | Android SDKs removed | .NET SDKs removed | Haskell removed | CodeQL Removed | Cached Docker Images Removed | GB freed | GB free | Elapsed Time (seconds) |
---|:--------------------:|:-----------------:|:---------------:|:--------------:|:----------------------------:|:--------:|:-------:|:----------------------:|
ubuntu-20.04 |  |  |  |  |  | 53 | 76 | 2
ubuntu-20.04 |  |  |  |  | true | 58 | 81 | 40
ubuntu-20.04 |  |  |  | true |  | 57 | 80 | 3
ubuntu-20.04 |  |  |  | true | true | 63 | 86 | 20
ubuntu-20.04 |  |  | true |  |  | 53 | 76 | 2
ubuntu-20.04 |  |  | true |  | true | 58 | 81 | 42
ubuntu-20.04 |  |  | true | true |  | 57 | 80 | 3
ubuntu-20.04 |  |  | true | true | true | 63 | 86 | 21
ubuntu-20.04 |  | true |  |  |  | 55 | 78 | 4
ubuntu-20.04 |  | true |  |  | true | 61 | 84 | 32
ubuntu-20.04 |  | true |  | true |  | 60 | 83 | 5
ubuntu-20.04 |  | true |  | true | true | 65 | 88 | 30
ubuntu-20.04 |  | true | true |  |  | 55 | 78 | 3
ubuntu-20.04 |  | true | true |  | true | 61 | 84 | 40
ubuntu-20.04 |  | true | true | true |  | 60 | 83 | 5
ubuntu-20.04 |  | true | true | true | true | 65 | 88 | 11
ubuntu-20.04 | true |  |  |  |  | 65 | 88 | 60
ubuntu-20.04 | true |  |  |  | true | 70 | 93 | 147
ubuntu-20.04 | true |  |  | true |  | 69 | 92 | 43
ubuntu-20.04 | true |  |  | true | true | 75 | 98 | 18
ubuntu-20.04 | true |  | true |  |  | 65 | 88 | 11
ubuntu-20.04 | true |  | true |  | true | 70 | 93 | 84
ubuntu-20.04 | true |  | true | true |  | 69 | 92 | 37
ubuntu-20.04 | true |  | true | true | true | 75 | 98 | 73
ubuntu-20.04 | true | true |  |  |  | 67 | 90 | 50
ubuntu-20.04 | true | true |  |  | true | 72 | 95 | 59
ubuntu-20.04 | true | true |  | true |  | 72 | 95 | 12
ubuntu-20.04 | true | true |  | true | true | 77 | 100 | 70
ubuntu-20.04 | true | true | true |  |  | 67 | 90 | 48
ubuntu-20.04 | true | true | true |  | true | 72 | 95 | 79
ubuntu-20.04 | true | true | true | true |  | 72 | 95 | 11
ubuntu-20.04 | true | true | true | true | true | 77 | 100 | 34
ubuntu-22.04 |  |  |  |  |  | 52 | 77 | 2
ubuntu-22.04 |  |  |  |  | true | 57 | 82 | 20
ubuntu-22.04 |  |  |  | true |  | 57 | 82 | 4
ubuntu-22.04 |  |  |  | true | true | 62 | 87 | 8
ubuntu-22.04 |  |  | true |  |  | 52 | 77 | 2
ubuntu-22.04 |  |  | true |  | true | 57 | 82 | 19
ubuntu-22.04 |  |  | true | true |  | 57 | 82 | 4
ubuntu-22.04 |  |  | true | true | true | 62 | 87 | 10
ubuntu-22.04 |  | true |  |  |  | 55 | 80 | 4
ubuntu-22.04 |  | true |  |  | true | 60 | 85 | 25
ubuntu-22.04 |  | true |  | true |  | 60 | 85 | 4
ubuntu-22.04 |  | true |  | true | true | 64 | 89 | 13
ubuntu-22.04 |  | true | true |  |  | 55 | 80 | 5
ubuntu-22.04 |  | true | true |  | true | 60 | 85 | 22
ubuntu-22.04 |  | true | true | true |  | 60 | 85 | 3
ubuntu-22.04 |  | true | true | true | true | 64 | 89 | 10
ubuntu-22.04 | true |  |  |  |  | 64 | 89 | 16
ubuntu-22.04 | true |  |  |  | true | 69 | 94 | 111
ubuntu-22.04 | true |  |  | true |  | 69 | 94 | 13
ubuntu-22.04 | true |  |  | true | true | 73 | 98 | 92
ubuntu-22.04 | true |  | true |  |  | 64 | 89 | 71
ubuntu-22.04 | true |  | true |  | true | 69 | 94 | 33
ubuntu-22.04 | true |  | true | true |  | 69 | 94 | 77
ubuntu-22.04 | true |  | true | true | true | 73 | 98 | 73
ubuntu-22.04 | true | true |  |  |  | 67 | 92 | 14
ubuntu-22.04 | true | true |  |  | true | 71 | 96 | 71
ubuntu-22.04 | true | true |  | true |  | 72 | 97 | 14
ubuntu-22.04 | true | true |  | true | true | 76 | 101 | 24
ubuntu-22.04 | true | true | true |  |  | 67 | 92 | 76
ubuntu-22.04 | true | true | true |  | true | 71 | 96 | 82
ubuntu-22.04 | true | true | true | true |  | 72 | 97 | 17
ubuntu-22.04 | true | true | true | true | true | 76 | 101 | 27
