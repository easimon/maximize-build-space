# Maximize available disk space for build tasks

If the available disk space on Github runners is too little for your build job, this action might be for you.
If not: please go on, there's nothing to see here.

This table shows the amount of free space you receive when using the action with the various options.

OS | Android SDKs removed | .NET SDKs removed | Haskell removed | CodeQL Removed | Cached Docker Images Removed | GB freed | GB free | Elapsed Time (seconds) |
---|:--------------------:|:-----------------:|:---------------:|:--------------:|:----------------------------:|:--------:|:-------:|:----------------------:|
ubuntu-20.04 |  |  |  |  |  | 7 | 28 | 2
ubuntu-20.04 |  |  |  |  | true | 13 | 34 | 41
ubuntu-20.04 |  |  |  | true |  | 11 | 32 | 4
ubuntu-20.04 |  |  |  | true | true | 17 | 38 | 39
ubuntu-20.04 |  |  | true |  |  | 7 | 28 | 2
ubuntu-20.04 |  |  | true |  | true | 13 | 34 | 43
ubuntu-20.04 |  |  | true | true |  | 11 | 32 | 4
ubuntu-20.04 |  |  | true | true | true | 17 | 38 | 41
ubuntu-20.04 |  | true |  |  |  | 9 | 30 | 4
ubuntu-20.04 |  | true |  |  | true | 16 | 37 | 11
ubuntu-20.04 |  | true |  | true |  | 13 | 34 | 4
ubuntu-20.04 |  | true |  | true | true | 19 | 40 | 42
ubuntu-20.04 |  | true | true |  |  | 9 | 30 | 3
ubuntu-20.04 |  | true | true |  | true | 16 | 37 | 45
ubuntu-20.04 |  | true | true | true |  | 13 | 34 | 4
ubuntu-20.04 |  | true | true | true | true | 19 | 40 | 51
ubuntu-20.04 | true |  |  |  |  | 21 | 42 | 94
ubuntu-20.04 | true |  |  |  | true | 27 | 48 | 135
ubuntu-20.04 | true |  |  | true |  | 24 | 45 | 20
ubuntu-20.04 | true |  |  | true | true | 31 | 52 | 27
ubuntu-20.04 | true |  | true |  |  | 21 | 42 | 89
ubuntu-20.04 | true |  | true |  | true | 27 | 48 | 31
ubuntu-20.04 | true |  | true | true |  | 24 | 45 | 84
ubuntu-20.04 | true |  | true | true | true | 31 | 52 | 142
ubuntu-20.04 | true | true |  |  |  | 23 | 44 | 87
ubuntu-20.04 | true | true |  |  | true | 30 | 51 | 22
ubuntu-20.04 | true | true |  | true |  | 27 | 48 | 14
ubuntu-20.04 | true | true |  | true | true | 33 | 54 | 62
ubuntu-20.04 | true | true | true |  |  | 23 | 44 | 10
ubuntu-20.04 | true | true | true |  | true | 30 | 51 | 127
ubuntu-20.04 | true | true | true | true |  | 27 | 48 | 76
ubuntu-20.04 | true | true | true | true | true | 33 | 54 | 111
ubuntu-22.04 |  |  |  |  |  | 7 | 30 | 2
ubuntu-22.04 |  |  |  |  | true | 13 | 36 | 28
ubuntu-22.04 |  |  |  | true |  | 10 | 33 | 4
ubuntu-22.04 |  |  |  | true | true | 16 | 39 | 29
ubuntu-22.04 |  |  | true |  |  | 7 | 30 | 2
ubuntu-22.04 |  |  | true |  | true | 13 | 36 | 29
ubuntu-22.04 |  |  | true | true |  | 10 | 33 | 4
ubuntu-22.04 |  |  | true | true | true | 16 | 39 | 31
ubuntu-22.04 |  | true |  |  |  | 9 | 32 | 3
ubuntu-22.04 |  | true |  |  | true | 15 | 38 | 42
ubuntu-22.04 |  | true |  | true |  | 13 | 36 | 9
ubuntu-22.04 |  | true |  | true | true | 18 | 41 | 18
ubuntu-22.04 |  | true | true |  |  | 9 | 32 | 7
ubuntu-22.04 |  | true | true |  | true | 15 | 38 | 15
ubuntu-22.04 |  | true | true | true |  | 13 | 36 | 8
ubuntu-22.04 |  | true | true | true | true | 18 | 41 | 33
ubuntu-22.04 | true |  |  |  |  | 21 | 44 | 56
ubuntu-22.04 | true |  |  |  | true | 27 | 50 | 21
ubuntu-22.04 | true |  |  | true |  | 24 | 47 | 64
ubuntu-22.04 | true |  |  | true | true | 30 | 53 | 64
ubuntu-22.04 | true |  | true |  |  | 21 | 44 | 56
ubuntu-22.04 | true |  | true |  | true | 27 | 50 | 23
ubuntu-22.04 | true |  | true | true |  | 24 | 47 | 59
ubuntu-22.04 | true |  | true | true | true | 30 | 53 | 62
ubuntu-22.04 | true | true |  |  |  | 23 | 46 | 50
ubuntu-22.04 | true | true |  |  | true | 29 | 52 | 18
ubuntu-22.04 | true | true |  | true |  | 27 | 50 | 65
ubuntu-22.04 | true | true |  | true | true | 32 | 55 | 108
ubuntu-22.04 | true | true | true |  |  | 23 | 46 | 20
ubuntu-22.04 | true | true | true |  | true | 29 | 52 | 117
ubuntu-22.04 | true | true | true | true |  | 27 | 50 | 11
ubuntu-22.04 | true | true | true | true | true | 32 | 55 | 44
