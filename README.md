# Maximize available disk space for build tasks

If the available disk space on Github runners is too little for your build job, this action might be for you.
If not: please go on, there's nothing to see here.

This table shows the amount of free space you receive when using the action with the various options.

OS | Android SDKs removed | .NET SDKs removed | Haskell removed | CodeQL Removed | Cached Docker Images Removed | GB freed | GB free | Elapsed Time (seconds) |
---|:--------------------:|:-----------------:|:---------------:|:--------------:|:----------------------------:|:--------:|:-------:|:----------------------:|
ubuntu-20.04 |  |  |  |  |  | 7 | 26 | 2
ubuntu-20.04 |  |  |  |  | true | 13 | 32 | 53
ubuntu-20.04 |  |  |  | true |  | 16 | 34 | 4
ubuntu-20.04 |  |  |  | true | true | 21 | 40 | 42
ubuntu-20.04 |  |  | true |  |  | 7 | 26 | 2
ubuntu-20.04 |  |  | true |  | true | 12 | 31 | 40
ubuntu-20.04 |  |  | true | true |  | 15 | 34 | 3
ubuntu-20.04 |  |  | true | true | true | 21 | 40 | 51
ubuntu-20.04 |  | true |  |  |  | 9 | 28 | 3
ubuntu-20.04 |  | true |  |  | true | 14 | 33 | 13
ubuntu-20.04 |  | true |  | true |  | 17 | 36 | 7
ubuntu-20.04 |  | true |  | true | true | 23 | 42 | 63
ubuntu-20.04 |  | true | true |  |  | 9 | 28 | 7
ubuntu-20.04 |  | true | true |  | true | 15 | 33 | 38
ubuntu-20.04 |  | true | true | true |  | 17 | 36 | 7
ubuntu-20.04 |  | true | true | true | true | 22 | 41 | 10
ubuntu-20.04 | true |  |  |  |  | 19 | 38 | 11
ubuntu-20.04 | true |  |  |  | true | 24 | 43 | 125
ubuntu-20.04 | true |  |  | true |  | 27 | 45 | 12
ubuntu-20.04 | true |  |  | true | true | 32 | 51 | 129
ubuntu-20.04 | true |  | true |  |  | 19 | 38 | 9
ubuntu-20.04 | true |  | true |  | true | 24 | 43 | 43
ubuntu-20.04 | true |  | true | true |  | 27 | 46 | 67
ubuntu-20.04 | true |  | true | true | true | 33 | 52 | 56
ubuntu-20.04 | true | true |  |  |  | 21 | 40 | 15
ubuntu-20.04 | true | true |  |  | true | 26 | 45 | 134
ubuntu-20.04 | true | true |  | true |  | 29 | 48 | 83
ubuntu-20.04 | true | true |  | true | true | 35 | 54 | 85
ubuntu-20.04 | true | true | true |  |  | 21 | 39 | 67
ubuntu-20.04 | true | true | true |  | true | 27 | 46 | 130
ubuntu-20.04 | true | true | true | true |  | 29 | 48 | 69
ubuntu-20.04 | true | true | true | true | true | 35 | 54 | 103
ubuntu-22.04 |  |  |  |  |  | 7 | 29 | 1
ubuntu-22.04 |  |  |  |  | true | 11 | 33 | 27
ubuntu-22.04 |  |  |  | true |  | 15 | 37 | 2
ubuntu-22.04 |  |  |  | true | true | 20 | 41 | 25
ubuntu-22.04 |  |  | true |  |  | 7 | 28 | 2
ubuntu-22.04 |  |  | true |  | true | 12 | 33 | 8
ubuntu-22.04 |  |  | true | true |  | 15 | 36 | 3
ubuntu-22.04 |  |  | true | true | true | 19 | 41 | 24
ubuntu-22.04 |  | true |  |  |  | 9 | 31 | 2
ubuntu-22.04 |  | true |  |  | true | 13 | 35 | 26
ubuntu-22.04 |  | true |  | true |  | 17 | 38 | 6
ubuntu-22.04 |  | true |  | true | true | 22 | 43 | 27
ubuntu-22.04 |  | true | true |  |  | 9 | 31 | 4
ubuntu-22.04 |  | true | true |  | true | 13 | 35 | 12
ubuntu-22.04 |  | true | true | true |  | 17 | 38 | 5
ubuntu-22.04 |  | true | true | true | true | 22 | 43 | 28
ubuntu-22.04 | true |  |  |  |  | 19 | 41 | 11
ubuntu-22.04 | true |  |  |  | true | 23 | 45 | 114
ubuntu-22.04 | true |  |  | true |  | 27 | 49 | 63
ubuntu-22.04 | true |  |  | true | true | 31 | 53 | 89
ubuntu-22.04 | true |  | true |  |  | 19 | 40 | 78
ubuntu-22.04 | true |  | true |  | true | 23 | 45 | 99
ubuntu-22.04 | true |  | true | true |  | 27 | 48 | 9
ubuntu-22.04 | true |  | true | true | true | 31 | 53 | 69
ubuntu-22.04 | true | true |  |  |  | 21 | 43 | 80
ubuntu-22.04 | true | true |  |  | true | 25 | 46 | 22
ubuntu-22.04 | true | true |  | true |  | 29 | 50 | 75
ubuntu-22.04 | true | true |  | true | true | 33 | 55 | 104
ubuntu-22.04 | true | true | true |  |  | 21 | 43 | 13
ubuntu-22.04 | true | true | true |  | true | 26 | 47 | 75
ubuntu-22.04 | true | true | true | true |  | 29 | 51 | 88
ubuntu-22.04 | true | true | true | true | true | 34 | 55 | 70
