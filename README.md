# Maximize available disk space for build tasks

If the available disk space on Github runners is too little for your build job, this action might be for you.
If not: please go on, there's nothing to see here.

This table shows the amount of free space you receive when using the action with the various options.

OS | Android SDKs removed | .NET SDKs removed | Haskell removed | CodeQL Removed | Cached Docker Images Removed | GB freed | GB free | Elapsed Time (seconds) |
---|:--------------------:|:-----------------:|:---------------:|:--------------:|:----------------------------:|:--------:|:-------:|:----------------------:|
ubuntu-20.04 |  |  |  |  |  | 7 | 26 | 2
ubuntu-20.04 |  |  |  |  | true | 13 | 32 | 32
ubuntu-20.04 |  |  |  | true |  | 15 | 34 | 3
ubuntu-20.04 |  |  |  | true | true | 21 | 40 | 26
ubuntu-20.04 |  |  | true |  |  | 7 | 26 | 2
ubuntu-20.04 |  |  | true |  | true | 13 | 32 | 37
ubuntu-20.04 |  |  | true | true |  | 15 | 34 | 4
ubuntu-20.04 |  |  | true | true | true | 21 | 40 | 26
ubuntu-20.04 |  | true |  |  |  | 9 | 28 | 3
ubuntu-20.04 |  | true |  |  | true | 14 | 33 | 25
ubuntu-20.04 |  | true |  | true |  | 17 | 36 | 3
ubuntu-20.04 |  | true |  | true | true | 23 | 42 | 33
ubuntu-20.04 |  | true | true |  |  | 9 | 28 | 6
ubuntu-20.04 |  | true | true |  | true | 14 | 33 | 25
ubuntu-20.04 |  | true | true | true |  | 17 | 36 | 4
ubuntu-20.04 |  | true | true | true | true | 23 | 42 | 40
ubuntu-20.04 | true |  |  |  |  | 19 | 38 | 12
ubuntu-20.04 | true |  |  |  | true | 25 | 44 | 43
ubuntu-20.04 | true |  |  | true |  | 27 | 46 | 63
ubuntu-20.04 | true |  |  | true | true | 33 | 52 | 34
ubuntu-20.04 | true |  | true |  |  | 19 | 38 | 58
ubuntu-20.04 | true |  | true |  | true | 25 | 44 | 84
ubuntu-20.04 | true |  | true | true |  | 27 | 46 | 78
ubuntu-20.04 | true |  | true | true | true | 33 | 52 | 84
ubuntu-20.04 | true | true |  |  |  | 21 | 40 | 56
ubuntu-20.04 | true | true |  |  | true | 26 | 45 | 86
ubuntu-20.04 | true | true |  | true |  | 29 | 48 | 12
ubuntu-20.04 | true | true |  | true | true | 34 | 53 | 80
ubuntu-20.04 | true | true | true |  |  | 21 | 40 | 81
ubuntu-20.04 | true | true | true |  | true | 26 | 45 | 90
ubuntu-20.04 | true | true | true | true |  | 29 | 48 | 17
ubuntu-20.04 | true | true | true | true | true | 34 | 53 | 98
ubuntu-22.04 |  |  |  |  |  | 7 | 29 | 2
ubuntu-22.04 |  |  |  |  | true | 12 | 34 | 30
ubuntu-22.04 |  |  |  | true |  | 15 | 37 | 3
ubuntu-22.04 |  |  |  | true | true | 20 | 42 | 25
ubuntu-22.04 |  |  | true |  |  | 7 | 29 | 2
ubuntu-22.04 |  |  | true |  | true | 12 | 34 | 20
ubuntu-22.04 |  |  | true | true |  | 15 | 37 | 3
ubuntu-22.04 |  |  | true | true | true | 20 | 42 | 19
ubuntu-22.04 |  | true |  |  |  | 9 | 31 | 4
ubuntu-22.04 |  | true |  |  | true | 13 | 35 | 25
ubuntu-22.04 |  | true |  | true |  | 17 | 39 | 6
ubuntu-22.04 |  | true |  | true | true | 21 | 43 | 31
ubuntu-22.04 |  | true | true |  |  | 9 | 31 | 3
ubuntu-22.04 |  | true | true |  | true | 13 | 35 | 8
ubuntu-22.04 |  | true | true | true |  | 17 | 39 | 4
ubuntu-22.04 |  | true | true | true | true | 21 | 43 | 38
ubuntu-22.04 | true |  |  |  |  | 19 | 41 | 99
ubuntu-22.04 | true |  |  |  | true | 23 | 45 | 99
ubuntu-22.04 | true |  |  | true |  | 27 | 49 | 109
ubuntu-22.04 | true |  |  | true | true | 31 | 53 | 122
ubuntu-22.04 | true |  | true |  |  | 19 | 41 | 91
ubuntu-22.04 | true |  | true |  | true | 23 | 45 | 141
ubuntu-22.04 | true |  | true | true |  | 27 | 49 | 92
ubuntu-22.04 | true |  | true | true | true | 31 | 53 | 109
ubuntu-22.04 | true | true |  |  |  | 21 | 43 | 20
ubuntu-22.04 | true | true |  |  | true | 25 | 47 | 124
ubuntu-22.04 | true | true |  | true |  | 29 | 51 | 108
ubuntu-22.04 | true | true |  | true | true | 33 | 55 | 143
ubuntu-22.04 | true | true | true |  |  | 21 | 43 | 85
ubuntu-22.04 | true | true | true |  | true | 25 | 47 | 138
ubuntu-22.04 | true | true | true | true |  | 29 | 51 | 97
ubuntu-22.04 | true | true | true | true | true | 33 | 55 | 122
