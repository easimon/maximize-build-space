# Maximize available disk space for build tasks

If the available disk space on Github runners is too little for your build job, this action might be for you.
If not: please go on, there's nothing to see here.

This table shows the amount of free space you receive when using the action with the various options.

OS | Android SDKs removed | .NET SDKs removed | Haskell removed | CodeQL Removed | Cached Docker Images Removed | GB freed | GB free | Elapsed Time (seconds) |
---|:--------------------:|:-----------------:|:---------------:|:--------------:|:----------------------------:|:--------:|:-------:|:----------------------:|
ubuntu-20.04 |  |  |  |  |  | 7 | 24 | 3
ubuntu-20.04 |  |  |  |  | true | 13 | 30 | 91
ubuntu-20.04 |  |  |  | true |  | 15 | 32 | 4
ubuntu-20.04 |  |  |  | true | true | 22 | 39 | 56
ubuntu-20.04 |  |  | true |  |  | 7 | 24 | 2
ubuntu-20.04 |  |  | true |  | true | 14 | 31 | 53
ubuntu-20.04 |  |  | true | true |  | 15 | 32 | 3
ubuntu-20.04 |  |  | true | true | true | 22 | 39 | 31
ubuntu-20.04 |  | true |  |  |  | 10 | 27 | 6
ubuntu-20.04 |  | true |  |  | true | 16 | 33 | 60
ubuntu-20.04 |  | true |  | true |  | 18 | 35 | 6
ubuntu-20.04 |  | true |  | true | true | 23 | 40 | 41
ubuntu-20.04 |  | true | true |  |  | 10 | 27 | 5
ubuntu-20.04 |  | true | true |  | true | 16 | 33 | 32
ubuntu-20.04 |  | true | true | true |  | 18 | 35 | 3
ubuntu-20.04 |  | true | true | true | true | 24 | 41 | 44
ubuntu-20.04 | true |  |  |  |  | 21 | 38 | 61
ubuntu-20.04 | true |  |  |  | true | 27 | 44 | 64
ubuntu-20.04 | true |  |  | true |  | 29 | 46 | 12
ubuntu-20.04 | true |  |  | true | true | 36 | 53 | 42
ubuntu-20.04 | true |  | true |  |  | 21 | 38 | 81
ubuntu-20.04 | true |  | true |  | true | 27 | 44 | 23
ubuntu-20.04 | true |  | true | true |  | 29 | 46 | 93
ubuntu-20.04 | true |  | true | true | true | 36 | 53 | 133
ubuntu-20.04 | true | true |  |  |  | 23 | 40 | 78
ubuntu-20.04 | true | true |  |  | true | 29 | 46 | 22
ubuntu-20.04 | true | true |  | true |  | 31 | 48 | 95
ubuntu-20.04 | true | true |  | true | true | 38 | 55 | 18
ubuntu-20.04 | true | true | true |  |  | 23 | 40 | 19
ubuntu-20.04 | true | true | true |  | true | 29 | 46 | 133
ubuntu-20.04 | true | true | true | true |  | 31 | 48 | 11
ubuntu-20.04 | true | true | true | true | true | 38 | 55 | 123
ubuntu-22.04 |  |  |  |  |  | 7 | 27 | 1
ubuntu-22.04 |  |  |  |  | true | 12 | 32 | 14
ubuntu-22.04 |  |  |  | true |  | 15 | 35 | 4
ubuntu-22.04 |  |  |  | true | true | 20 | 40 | 10
ubuntu-22.04 |  |  | true |  |  | 7 | 27 | 2
ubuntu-22.04 |  |  | true |  | true | 12 | 32 | 34
ubuntu-22.04 |  |  | true | true |  | 15 | 35 | 5
ubuntu-22.04 |  |  | true | true | true | 20 | 40 | 30
ubuntu-22.04 |  | true |  |  |  | 9 | 29 | 4
ubuntu-22.04 |  | true |  |  | true | 14 | 34 | 49
ubuntu-22.04 |  | true |  | true |  | 17 | 37 | 14
ubuntu-22.04 |  | true |  | true | true | 23 | 43 | 11
ubuntu-22.04 |  | true | true |  |  | 9 | 29 | 9
ubuntu-22.04 |  | true | true |  | true | 14 | 34 | 46
ubuntu-22.04 |  | true | true | true |  | 17 | 37 | 4
ubuntu-22.04 |  | true | true | true | true | 23 | 43 | 9
ubuntu-22.04 | true |  |  |  |  | 21 | 41 | 80
ubuntu-22.04 | true |  |  |  | true | 26 | 46 | 17
ubuntu-22.04 | true |  |  | true |  | 29 | 49 | 12
ubuntu-22.04 | true |  |  | true | true | 34 | 54 | 65
ubuntu-22.04 | true |  | true |  |  | 21 | 41 | 59
ubuntu-22.04 | true |  | true |  | true | 26 | 46 | 84
ubuntu-22.04 | true |  | true | true |  | 29 | 49 | 12
ubuntu-22.04 | true |  | true | true | true | 34 | 54 | 90
ubuntu-22.04 | true | true |  |  |  | 23 | 43 | 109
ubuntu-22.04 | true | true |  |  | true | 28 | 48 | 115
ubuntu-22.04 | true | true |  | true |  | 31 | 51 | 11
ubuntu-22.04 | true | true |  | true | true | 36 | 56 | 38
ubuntu-22.04 | true | true | true |  |  | 23 | 43 | 17
ubuntu-22.04 | true | true | true |  | true | 28 | 48 | 17
ubuntu-22.04 | true | true | true | true |  | 31 | 51 | 72
ubuntu-22.04 | true | true | true | true | true | 36 | 56 | 32
