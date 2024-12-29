# Maximize available disk space for build tasks

If the available disk space on Github runners is too little for your build job, this action might be for you.
If not: please go on, there's nothing to see here.

This table shows the amount of free space you receive when using the action with the various options.

OS | Android SDKs removed | .NET SDKs removed | Haskell removed | CodeQL Removed | Cached Docker Images Removed | GB freed | GB free | Elapsed Time (seconds) |
---|:--------------------:|:-----------------:|:---------------:|:--------------:|:----------------------------:|:--------:|:-------:|:----------------------:|
ubuntu-20.04 |  |  |  |  |  | 62 | 83 | 2
ubuntu-20.04 |  |  |  |  | true | 65 | 86 | 39
ubuntu-20.04 |  |  |  | true |  | 67 | 88 | 5
ubuntu-20.04 |  |  |  | true | true | 70 | 91 | 9
ubuntu-20.04 |  |  | true |  |  | 62 | 83 | 2
ubuntu-20.04 |  |  | true |  | true | 65 | 86 | 64
ubuntu-20.04 |  |  | true | true |  | 67 | 88 | 3
ubuntu-20.04 |  |  | true | true | true | 70 | 91 | 9
ubuntu-20.04 |  | true |  |  |  | 64 | 85 | 4
ubuntu-20.04 |  | true |  |  | true | 66 | 87 | 9
ubuntu-20.04 |  | true |  | true |  | 69 | 90 | 5
ubuntu-20.04 |  | true |  | true | true | 71 | 92 | 9
ubuntu-20.04 |  | true | true |  |  | 64 | 85 | 5
ubuntu-20.04 |  | true | true |  | true | 66 | 87 | 51
ubuntu-20.04 |  | true | true | true |  | 69 | 90 | 6
ubuntu-20.04 |  | true | true | true | true | 71 | 92 | 35
ubuntu-20.04 | true |  |  |  |  | 70 | 91 | 15
ubuntu-20.04 | true |  |  |  | true | 72 | 93 | 180
ubuntu-20.04 | true |  |  | true |  | 75 | 96 | 15
ubuntu-20.04 | true |  |  | true | true | 77 | 98 | 136
ubuntu-20.04 | true |  | true |  |  | 70 | 91 | 84
ubuntu-20.04 | true |  | true |  | true | 72 | 93 | 84
ubuntu-20.04 | true |  | true | true |  | 75 | 96 | 68
ubuntu-20.04 | true |  | true | true | true | 77 | 98 | 20
ubuntu-20.04 | true | true |  |  |  | 71 | 92 | 14
ubuntu-20.04 | true | true |  |  | true | 74 | 95 | 20
ubuntu-20.04 | true | true |  | true |  | 76 | 97 | 17
ubuntu-20.04 | true | true |  | true | true | 79 | 100 | 132
ubuntu-20.04 | true | true | true |  |  | 71 | 92 | 12
ubuntu-20.04 | true | true | true |  | true | 74 | 95 | 170
ubuntu-20.04 | true | true | true | true |  | 76 | 97 | 18
ubuntu-20.04 | true | true | true | true | true | 79 | 100 | 19
ubuntu-22.04 |  |  |  |  |  | 62 | 84 | 2
ubuntu-22.04 |  |  |  |  | true | 65 | 87 | 7
ubuntu-22.04 |  |  |  | true |  | 67 | 89 | 4
ubuntu-22.04 |  |  |  | true | true | 70 | 92 | 6
ubuntu-22.04 |  |  | true |  |  | 62 | 84 | 1
ubuntu-22.04 |  |  | true |  | true | 65 | 87 | 13
ubuntu-22.04 |  |  | true | true |  | 67 | 89 | 3
ubuntu-22.04 |  |  | true | true | true | 70 | 92 | 18
ubuntu-22.04 |  | true |  |  |  | 64 | 86 | 3
ubuntu-22.04 |  | true |  |  | true | 66 | 88 | 7
ubuntu-22.04 |  | true |  | true |  | 69 | 91 | 4
ubuntu-22.04 |  | true |  | true | true | 71 | 93 | 7
ubuntu-22.04 |  | true | true |  |  | 64 | 86 | 4
ubuntu-22.04 |  | true | true |  | true | 66 | 88 | 5
ubuntu-22.04 |  | true | true | true |  | 69 | 91 | 5
ubuntu-22.04 |  | true | true | true | true | 71 | 93 | 22
ubuntu-22.04 | true |  |  |  |  | 70 | 92 | 95
ubuntu-22.04 | true |  |  |  | true | 72 | 94 | 62
ubuntu-22.04 | true |  |  | true |  | 75 | 97 | 102
ubuntu-22.04 | true |  |  | true | true | 77 | 99 | 19
ubuntu-22.04 | true |  | true |  |  | 70 | 92 | 18
ubuntu-22.04 | true |  | true |  | true | 72 | 94 | 20
ubuntu-22.04 | true |  | true | true |  | 75 | 97 | 14
ubuntu-22.04 | true |  | true | true | true | 77 | 99 | 15
ubuntu-22.04 | true | true |  |  |  | 71 | 93 | 14
ubuntu-22.04 | true | true |  |  | true | 74 | 96 | 26
ubuntu-22.04 | true | true |  | true |  | 76 | 98 | 99
ubuntu-22.04 | true | true |  | true | true | 79 | 101 | 22
ubuntu-22.04 | true | true | true |  |  | 71 | 93 | 101
ubuntu-22.04 | true | true | true |  | true | 74 | 96 | 67
ubuntu-22.04 | true | true | true | true |  | 76 | 98 | 20
ubuntu-22.04 | true | true | true | true | true | 79 | 101 | 25
