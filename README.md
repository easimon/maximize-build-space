# Maximize available disk space for build tasks

If the available disk space on Github runners is too little for your build job, this action might be for you.
If not: please go on, there's nothing to see here.

This table shows the amount of free space you receive when using the action with the various options.

OS | Android SDKs removed | .NET SDKs removed | Haskell removed | CodeQL Removed | Cached Docker Images Removed | GB freed | GB free | Elapsed Time (seconds) |
---|:--------------------:|:-----------------:|:---------------:|:--------------:|:----------------------------:|:--------:|:-------:|:----------------------:|
ubuntu-20.04 |  |  |  |  |  | 7 | 26 | 3
ubuntu-20.04 |  |  |  |  | true | 13 | 32 | 30
ubuntu-20.04 |  |  |  | true |  | 15 | 34 | 3
ubuntu-20.04 |  |  |  | true | true | 21 | 40 | 25
ubuntu-20.04 |  |  | true |  |  | 7 | 26 | 2
ubuntu-20.04 |  |  | true |  | true | 13 | 32 | 27
ubuntu-20.04 |  |  | true | true |  | 15 | 34 | 4
ubuntu-20.04 |  |  | true | true | true | 21 | 40 | 39
ubuntu-20.04 |  | true |  |  |  | 9 | 28 | 5
ubuntu-20.04 |  | true |  |  | true | 14 | 33 | 13
ubuntu-20.04 |  | true |  | true |  | 17 | 36 | 8
ubuntu-20.04 |  | true |  | true | true | 23 | 42 | 36
ubuntu-20.04 |  | true | true |  |  | 9 | 28 | 6
ubuntu-20.04 |  | true | true |  | true | 14 | 33 | 31
ubuntu-20.04 |  | true | true | true |  | 17 | 36 | 8
ubuntu-20.04 |  | true | true | true | true | 23 | 42 | 34
ubuntu-20.04 | true |  |  |  |  | 19 | 38 | 45
ubuntu-20.04 | true |  |  |  | true | 25 | 44 | 74
ubuntu-20.04 | true |  |  | true |  | 27 | 46 | 48
ubuntu-20.04 | true |  |  | true | true | 33 | 52 | 74
ubuntu-20.04 | true |  | true |  |  | 19 | 38 | 15
ubuntu-20.04 | true |  | true |  | true | 25 | 44 | 33
ubuntu-20.04 | true |  | true | true |  | 27 | 46 | 61
ubuntu-20.04 | true |  | true | true | true | 33 | 52 | 86
ubuntu-20.04 | true | true |  |  |  | 21 | 40 | 51
ubuntu-20.04 | true | true |  |  | true | 26 | 45 | 70
ubuntu-20.04 | true | true |  | true |  | 29 | 48 | 62
ubuntu-20.04 | true | true |  | true | true | 34 | 53 | 72
ubuntu-20.04 | true | true | true |  |  | 21 | 40 | 56
ubuntu-20.04 | true | true | true |  | true | 26 | 45 | 82
ubuntu-20.04 | true | true | true | true |  | 29 | 48 | 51
ubuntu-20.04 | true | true | true | true | true | 34 | 53 | 39
ubuntu-22.04 |  |  |  |  |  | 7 | 29 | 2
ubuntu-22.04 |  |  |  |  | true | 12 | 34 | 24
ubuntu-22.04 |  |  |  | true |  | 15 | 37 | 3
ubuntu-22.04 |  |  |  | true | true | 20 | 42 | 9
ubuntu-22.04 |  |  | true |  |  | 7 | 29 | 2
ubuntu-22.04 |  |  | true |  | true | 12 | 34 | 18
ubuntu-22.04 |  |  | true | true |  | 15 | 37 | 3
ubuntu-22.04 |  |  | true | true | true | 20 | 42 | 26
ubuntu-22.04 |  | true |  |  |  | 9 | 31 | 3
ubuntu-22.04 |  | true |  |  | true | 13 | 35 | 29
ubuntu-22.04 |  | true |  | true |  | 17 | 39 | 5
ubuntu-22.04 |  | true |  | true | true | 21 | 43 | 31
ubuntu-22.04 |  | true | true |  |  | 9 | 31 | 4
ubuntu-22.04 |  | true | true |  | true | 13 | 35 | 27
ubuntu-22.04 |  | true | true | true |  | 17 | 39 | 5
ubuntu-22.04 |  | true | true | true | true | 21 | 43 | 62
ubuntu-22.04 | true |  |  |  |  | 19 | 41 | 96
ubuntu-22.04 | true |  |  |  | true | 23 | 45 | 95
ubuntu-22.04 | true |  |  | true |  | 27 | 49 | 101
ubuntu-22.04 | true |  |  | true | true | 31 | 53 | 78
ubuntu-22.04 | true |  | true |  |  | 19 | 41 | 80
ubuntu-22.04 | true |  | true |  | true | 23 | 45 | 111
ubuntu-22.04 | true |  | true | true |  | 27 | 49 | 124
ubuntu-22.04 | true |  | true | true | true | 31 | 53 | 18
ubuntu-22.04 | true | true |  |  |  | 21 | 43 | 114
ubuntu-22.04 | true | true |  |  | true | 25 | 47 | 91
ubuntu-22.04 | true | true |  | true |  | 29 | 51 | 124
ubuntu-22.04 | true | true |  | true | true | 33 | 55 | 111
ubuntu-22.04 | true | true | true |  |  | 21 | 43 | 81
ubuntu-22.04 | true | true | true |  | true | 25 | 47 | 115
ubuntu-22.04 | true | true | true | true |  | 29 | 51 | 109
ubuntu-22.04 | true | true | true | true | true | 33 | 55 | 128
