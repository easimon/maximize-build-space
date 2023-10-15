# Maximize available disk space for build tasks

If the available disk space on Github runners is too little for your build job, this action might be for you.
If not: please go on, there's nothing to see here.

This table shows the amount of free space you receive when using the action with the various options.

OS | Android SDKs removed | .NET SDKs removed | Haskell removed | CodeQL Removed | Cached Docker Images Removed | GB freed | GB free | Elapsed Time (seconds) |
---|:--------------------:|:-----------------:|:---------------:|:--------------:|:----------------------------:|:--------:|:-------:|:----------------------:|
ubuntu-20.04 |  |  |  |  |  | 7 | 26 | 2
ubuntu-20.04 |  |  |  |  | true | 14 | 33 | 17
ubuntu-20.04 |  |  |  | true |  | 11 | 30 | 4
ubuntu-20.04 |  |  |  | true | true | 18 | 37 | 39
ubuntu-20.04 |  |  | true |  |  | 7 | 26 | 3
ubuntu-20.04 |  |  | true |  | true | 14 | 33 | 40
ubuntu-20.04 |  |  | true | true |  | 11 | 30 | 5
ubuntu-20.04 |  |  | true | true | true | 18 | 37 | 45
ubuntu-20.04 |  | true |  |  |  | 10 | 29 | 6
ubuntu-20.04 |  | true |  |  | true | 16 | 35 | 9
ubuntu-20.04 |  | true |  | true |  | 13 | 32 | 6
ubuntu-20.04 |  | true |  | true | true | 20 | 39 | 12
ubuntu-20.04 |  | true | true |  |  | 10 | 29 | 5
ubuntu-20.04 |  | true | true |  | true | 16 | 35 | 12
ubuntu-20.04 |  | true | true | true |  | 13 | 32 | 4
ubuntu-20.04 |  | true | true | true | true | 20 | 39 | 35
ubuntu-20.04 | true |  |  |  |  | 21 | 40 | 12
ubuntu-20.04 | true |  |  |  | true | 28 | 47 | 96
ubuntu-20.04 | true |  |  | true |  | 25 | 44 | 67
ubuntu-20.04 | true |  |  | true | true | 32 | 51 | 103
ubuntu-20.04 | true |  | true |  |  | 21 | 40 | 14
ubuntu-20.04 | true |  | true |  | true | 28 | 47 | 43
ubuntu-20.04 | true |  | true | true |  | 25 | 44 | 69
ubuntu-20.04 | true |  | true | true | true | 32 | 51 | 107
ubuntu-20.04 | true | true |  |  |  | 23 | 42 | 13
ubuntu-20.04 | true | true |  |  | true | 30 | 49 | 27
ubuntu-20.04 | true | true |  | true |  | 27 | 46 | 68
ubuntu-20.04 | true | true |  | true | true | 34 | 53 | 101
ubuntu-20.04 | true | true | true |  |  | 23 | 42 | 64
ubuntu-20.04 | true | true | true |  | true | 30 | 49 | 22
ubuntu-20.04 | true | true | true | true |  | 27 | 46 | 81
ubuntu-20.04 | true | true | true | true | true | 34 | 53 | 115
ubuntu-22.04 |  |  |  |  |  | 7 | 25 | 2
ubuntu-22.04 |  |  |  |  | true | 13 | 31 | 32
ubuntu-22.04 |  |  |  | true |  | 15 | 33 | 4
ubuntu-22.04 |  |  |  | true | true | 21 | 39 | 31
ubuntu-22.04 |  |  | true |  |  | 7 | 25 | 2
ubuntu-22.04 |  |  | true |  | true | 13 | 31 | 32
ubuntu-22.04 |  |  | true | true |  | 15 | 33 | 5
ubuntu-22.04 |  |  | true | true | true | 21 | 39 | 28
ubuntu-22.04 |  | true |  |  |  | 9 | 27 | 3
ubuntu-22.04 |  | true |  |  | true | 15 | 33 | 35
ubuntu-22.04 |  | true |  | true |  | 17 | 35 | 5
ubuntu-22.04 |  | true |  | true | true | 23 | 41 | 27
ubuntu-22.04 |  | true | true |  |  | 9 | 27 | 4
ubuntu-22.04 |  | true | true |  | true | 15 | 33 | 27
ubuntu-22.04 |  | true | true | true |  | 17 | 35 | 6
ubuntu-22.04 |  | true | true | true | true | 23 | 41 | 32
ubuntu-22.04 | true |  |  |  |  | 21 | 39 | 15
ubuntu-22.04 | true |  |  |  | true | 27 | 45 | 70
ubuntu-22.04 | true |  |  | true |  | 29 | 47 | 72
ubuntu-22.04 | true |  |  | true | true | 35 | 53 | 73
ubuntu-22.04 | true |  | true |  |  | 21 | 39 | 74
ubuntu-22.04 | true |  | true |  | true | 27 | 45 | 101
ubuntu-22.04 | true |  | true | true |  | 29 | 47 | 17
ubuntu-22.04 | true |  | true | true | true | 35 | 53 | 81
ubuntu-22.04 | true | true |  |  |  | 23 | 41 | 59
ubuntu-22.04 | true | true |  |  | true | 29 | 47 | 22
ubuntu-22.04 | true | true |  | true |  | 31 | 49 | 66
ubuntu-22.04 | true | true |  | true | true | 37 | 55 | 22
ubuntu-22.04 | true | true | true |  |  | 23 | 41 | 81
ubuntu-22.04 | true | true | true |  | true | 29 | 47 | 96
ubuntu-22.04 | true | true | true | true |  | 31 | 49 | 66
ubuntu-22.04 | true | true | true | true | true | 37 | 55 | 109
