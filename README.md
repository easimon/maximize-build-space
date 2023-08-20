# Maximize available disk space for build tasks

If the available disk space on Github runners is too little for your build job, this action might be for you.
If not: please go on, there's nothing to see here.

This table shows the amount of free space you receive when using the action with the various options.

OS | Android SDKs removed | .NET SDKs removed | Haskell removed | CodeQL Removed | Cached Docker Images Removed | GB freed | GB free | Elapsed Time (seconds) |
---|:--------------------:|:-----------------:|:---------------:|:--------------:|:----------------------------:|:--------:|:-------:|:----------------------:|
ubuntu-20.04 |  |  |  |  |  | 7 | 27 | 3
ubuntu-20.04 |  |  |  |  | true | 13 | 32 | 12
ubuntu-20.04 |  |  |  | true |  | 15 | 35 | 3
ubuntu-20.04 |  |  |  | true | true | 20 | 40 | 36
ubuntu-20.04 |  |  | true |  |  | 7 | 27 | 5
ubuntu-20.04 |  |  | true |  | true | 13 | 33 | 21
ubuntu-20.04 |  |  | true | true |  | 15 | 35 | 4
ubuntu-20.04 |  |  | true | true | true | 21 | 40 | 25
ubuntu-20.04 |  | true |  |  |  | 9 | 29 | 5
ubuntu-20.04 |  | true |  |  | true | 14 | 34 | 9
ubuntu-20.04 |  | true |  | true |  | 17 | 36 | 4
ubuntu-20.04 |  | true |  | true | true | 22 | 42 | 10
ubuntu-20.04 |  | true | true |  |  | 9 | 29 | 6
ubuntu-20.04 |  | true | true |  | true | 14 | 34 | 29
ubuntu-20.04 |  | true | true | true |  | 16 | 36 | 6
ubuntu-20.04 |  | true | true | true | true | 22 | 42 | 33
ubuntu-20.04 | true |  |  |  |  | 19 | 39 | 63
ubuntu-20.04 | true |  |  |  | true | 24 | 44 | 19
ubuntu-20.04 | true |  |  | true |  | 27 | 47 | 11
ubuntu-20.04 | true |  |  | true | true | 33 | 52 | 68
ubuntu-20.04 | true |  | true |  |  | 19 | 38 | 75
ubuntu-20.04 | true |  | true |  | true | 24 | 44 | 41
ubuntu-20.04 | true |  | true | true |  | 27 | 47 | 13
ubuntu-20.04 | true |  | true | true | true | 33 | 52 | 98
ubuntu-20.04 | true | true |  |  |  | 21 | 41 | 51
ubuntu-20.04 | true | true |  |  | true | 26 | 46 | 34
ubuntu-20.04 | true | true |  | true |  | 29 | 49 | 53
ubuntu-20.04 | true | true |  | true | true | 35 | 54 | 15
ubuntu-20.04 | true | true | true |  |  | 21 | 40 | 63
ubuntu-20.04 | true | true | true |  | true | 27 | 46 | 102
ubuntu-20.04 | true | true | true | true |  | 28 | 48 | 18
ubuntu-20.04 | true | true | true | true | true | 34 | 54 | 93
ubuntu-22.04 |  |  |  |  |  | 7 | 30 | 2
ubuntu-22.04 |  |  |  |  | true | 12 | 35 | 23
ubuntu-22.04 |  |  |  | true |  | 15 | 37 | 3
ubuntu-22.04 |  |  |  | true | true | 20 | 43 | 8
ubuntu-22.04 |  |  | true |  |  | 7 | 29 | 2
ubuntu-22.04 |  |  | true |  | true | 12 | 34 | 22
ubuntu-22.04 |  |  | true | true |  | 16 | 38 | 4
ubuntu-22.04 |  |  | true | true | true | 20 | 43 | 8
ubuntu-22.04 |  | true |  |  |  | 9 | 31 | 3
ubuntu-22.04 |  | true |  |  | true | 14 | 36 | 16
ubuntu-22.04 |  | true |  | true |  | 17 | 39 | 7
ubuntu-22.04 |  | true |  | true | true | 22 | 44 | 29
ubuntu-22.04 |  | true | true |  |  | 9 | 32 | 4
ubuntu-22.04 |  | true | true |  | true | 14 | 36 | 33
ubuntu-22.04 |  | true | true | true |  | 17 | 39 | 6
ubuntu-22.04 |  | true | true | true | true | 22 | 44 | 40
ubuntu-22.04 | true |  |  |  |  | 19 | 41 | 49
ubuntu-22.04 | true |  |  |  | true | 24 | 46 | 13
ubuntu-22.04 | true |  |  | true |  | 27 | 49 | 79
ubuntu-22.04 | true |  |  | true | true | 32 | 54 | 96
ubuntu-22.04 | true |  | true |  |  | 19 | 41 | 71
ubuntu-22.04 | true |  | true |  | true | 23 | 45 | 222
ubuntu-22.04 | true |  | true | true |  | 27 | 49 | 70
ubuntu-22.04 | true |  | true | true | true | 32 | 54 | 94
ubuntu-22.04 | true | true |  |  |  | 21 | 43 | 55
ubuntu-22.04 | true | true |  |  | true | 26 | 48 | 27
ubuntu-22.04 | true | true |  | true |  | 29 | 52 | 63
ubuntu-22.04 | true | true |  | true | true | 34 | 56 | 92
ubuntu-22.04 | true | true | true |  |  | 21 | 43 | 85
ubuntu-22.04 | true | true | true |  | true | 26 | 48 | 17
ubuntu-22.04 | true | true | true | true |  | 29 | 51 | 11
ubuntu-22.04 | true | true | true | true | true | 34 | 56 | 82
