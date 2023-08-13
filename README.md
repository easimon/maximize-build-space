# Maximize available disk space for build tasks

If the available disk space on Github runners is too little for your build job, this action might be for you.
If not: please go on, there's nothing to see here.

This table shows the amount of free space you receive when using the action with the various options.

OS | Android SDKs removed | .NET SDKs removed | Haskell removed | CodeQL Removed | Cached Docker Images Removed | GB freed | GB free | Elapsed Time (seconds) |
---|:--------------------:|:-----------------:|:---------------:|:--------------:|:----------------------------:|:--------:|:-------:|:----------------------:|
ubuntu-20.04 |  |  |  |  |  | 7 | 28 | 2
ubuntu-20.04 |  |  |  |  | true | 12 | 33 | 11
ubuntu-20.04 |  |  |  | true |  | 15 | 35 | 4
ubuntu-20.04 |  |  |  | true | true | 21 | 41 | 20
ubuntu-20.04 |  |  | true |  |  | 7 | 28 | 2
ubuntu-20.04 |  |  | true |  | true | 13 | 33 | 26
ubuntu-20.04 |  |  | true | true |  | 15 | 36 | 4
ubuntu-20.04 |  |  | true | true | true | 20 | 41 | 28
ubuntu-20.04 |  | true |  |  |  | 9 | 29 | 6
ubuntu-20.04 |  | true |  |  | true | 14 | 35 | 18
ubuntu-20.04 |  | true |  | true |  | 17 | 38 | 6
ubuntu-20.04 |  | true |  | true | true | 23 | 43 | 26
ubuntu-20.04 |  | true | true |  |  | 9 | 30 | 6
ubuntu-20.04 |  | true | true |  | true | 14 | 35 | 25
ubuntu-20.04 |  | true | true | true |  | 17 | 38 | 6
ubuntu-20.04 |  | true | true | true | true | 22 | 43 | 36
ubuntu-20.04 | true |  |  |  |  | 19 | 40 | 10
ubuntu-20.04 | true |  |  |  | true | 24 | 45 | 90
ubuntu-20.04 | true |  |  | true |  | 27 | 48 | 56
ubuntu-20.04 | true |  |  | true | true | 32 | 53 | 71
ubuntu-20.04 | true |  | true |  |  | 19 | 39 | 20
ubuntu-20.04 | true |  | true |  | true | 25 | 45 | 37
ubuntu-20.04 | true |  | true | true |  | 27 | 48 | 69
ubuntu-20.04 | true |  | true | true | true | 33 | 53 | 73
ubuntu-20.04 | true | true |  |  |  | 20 | 41 | 12
ubuntu-20.04 | true | true |  |  | true | 26 | 47 | 93
ubuntu-20.04 | true | true |  | true |  | 29 | 50 | 13
ubuntu-20.04 | true | true |  | true | true | 34 | 55 | 48
ubuntu-20.04 | true | true | true |  |  | 20 | 41 | 55
ubuntu-20.04 | true | true | true |  | true | 26 | 47 | 69
ubuntu-20.04 | true | true | true | true |  | 29 | 50 | 77
ubuntu-20.04 | true | true | true | true | true | 34 | 54 | 100
ubuntu-22.04 |  |  |  |  |  | 7 | 31 | 2
ubuntu-22.04 |  |  |  |  | true | 11 | 35 | 16
ubuntu-22.04 |  |  |  | true |  | 15 | 39 | 5
ubuntu-22.04 |  |  |  | true | true | 19 | 43 | 9
ubuntu-22.04 |  |  | true |  |  | 7 | 31 | 2
ubuntu-22.04 |  |  | true |  | true | 11 | 35 | 7
ubuntu-22.04 |  |  | true | true |  | 15 | 38 | 3
ubuntu-22.04 |  |  | true | true | true | 20 | 43 | 14
ubuntu-22.04 |  | true |  |  |  | 8 | 32 | 5
ubuntu-22.04 |  | true |  |  | true | 13 | 36 | 10
ubuntu-22.04 |  | true |  | true |  | 17 | 40 | 9
ubuntu-22.04 |  | true |  | true | true | 22 | 45 | 29
ubuntu-22.04 |  | true | true |  |  | 9 | 32 | 5
ubuntu-22.04 |  | true | true |  | true | 13 | 36 | 26
ubuntu-22.04 |  | true | true | true |  | 17 | 40 | 5
ubuntu-22.04 |  | true | true | true | true | 22 | 45 | 26
ubuntu-22.04 | true |  |  |  |  | 19 | 42 | 82
ubuntu-22.04 | true |  |  |  | true | 24 | 47 | 19
ubuntu-22.04 | true |  |  | true |  | 27 | 50 | 15
ubuntu-22.04 | true |  |  | true | true | 32 | 55 | 33
ubuntu-22.04 | true |  | true |  |  | 19 | 43 | 72
ubuntu-22.04 | true |  | true |  | true | 24 | 47 | 77
ubuntu-22.04 | true |  | true | true |  | 27 | 51 | 14
ubuntu-22.04 | true |  | true | true | true | 31 | 55 | 89
ubuntu-22.04 | true | true |  |  |  | 21 | 44 | 13
ubuntu-22.04 | true | true |  |  | true | 25 | 49 | 85
ubuntu-22.04 | true | true |  | true |  | 28 | 52 | 74
ubuntu-22.04 | true | true |  | true | true | 33 | 57 | 88
ubuntu-22.04 | true | true | true |  |  | 20 | 44 | 65
ubuntu-22.04 | true | true | true |  | true | 25 | 48 | 85
ubuntu-22.04 | true | true | true | true |  | 29 | 52 | 72
ubuntu-22.04 | true | true | true | true | true | 33 | 56 | 117
