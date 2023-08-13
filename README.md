# Maximize available disk space for build tasks

If the available disk space on Github runners is too little for your build job, this action might be for you.
If not: please go on, there's nothing to see here.

This table shows the amount of free space you receive when using the action with the various options.

OS | Android SDKs removed | .NET SDKs removed | Haskell removed | CodeQL Removed | Cached Docker Images Removed | GB freed | GB free | Elapsed Time (seconds) |
---|:--------------------:|:-----------------:|:---------------:|:--------------:|:----------------------------:|:--------:|:-------:|:----------------------:|
ubuntu-20.04 |  |  |  |  |  | 7 | 28 | 2
ubuntu-20.04 |  |  |  |  | true | 12 | 33 | 29
ubuntu-20.04 |  |  |  | true |  | 15 | 36 | 4
ubuntu-20.04 |  |  |  | true | true | 21 | 41 | 28
ubuntu-20.04 |  |  | true |  |  | 7 | 28 | 3
ubuntu-20.04 |  |  | true |  | true | 12 | 33 | 30
ubuntu-20.04 |  |  | true | true |  | 15 | 36 | 3
ubuntu-20.04 |  |  | true | true | true | 21 | 41 | 32
ubuntu-20.04 |  | true |  |  |  | 9 | 29 | 4
ubuntu-20.04 |  | true |  |  | true | 14 | 35 | 14
ubuntu-20.04 |  | true |  | true |  | 17 | 38 | 5
ubuntu-20.04 |  | true |  | true | true | 23 | 43 | 30
ubuntu-20.04 |  | true | true |  |  | 9 | 30 | 8
ubuntu-20.04 |  | true | true |  | true | 15 | 35 | 27
ubuntu-20.04 |  | true | true | true |  | 17 | 38 | 5
ubuntu-20.04 |  | true | true | true | true | 23 | 43 | 30
ubuntu-20.04 | true |  |  |  |  | 19 | 40 | 49
ubuntu-20.04 | true |  |  |  | true | 24 | 45 | 37
ubuntu-20.04 | true |  |  | true |  | 27 | 47 | 10
ubuntu-20.04 | true |  |  | true | true | 33 | 53 | 92
ubuntu-20.04 | true |  | true |  |  | 19 | 40 | 59
ubuntu-20.04 | true |  | true |  | true | 24 | 45 | 29
ubuntu-20.04 | true |  | true | true |  | 27 | 48 | 60
ubuntu-20.04 | true |  | true | true | true | 32 | 53 | 99
ubuntu-20.04 | true | true |  |  |  | 21 | 41 | 60
ubuntu-20.04 | true | true |  |  | true | 26 | 47 | 98
ubuntu-20.04 | true | true |  | true |  | 29 | 49 | 11
ubuntu-20.04 | true | true |  | true | true | 34 | 55 | 91
ubuntu-20.04 | true | true | true |  |  | 21 | 41 | 72
ubuntu-20.04 | true | true | true |  | true | 26 | 47 | 117
ubuntu-20.04 | true | true | true | true |  | 29 | 49 | 73
ubuntu-20.04 | true | true | true | true | true | 34 | 55 | 96
ubuntu-22.04 |  |  |  |  |  | 7 | 31 | 1
ubuntu-22.04 |  |  |  |  | true | 11 | 35 | 8
ubuntu-22.04 |  |  |  | true |  | 15 | 39 | 3
ubuntu-22.04 |  |  |  | true | true | 20 | 43 | 20
ubuntu-22.04 |  |  | true |  |  | 7 | 30 | 2
ubuntu-22.04 |  |  | true |  | true | 11 | 35 | 8
ubuntu-22.04 |  |  | true | true |  | 15 | 38 | 3
ubuntu-22.04 |  |  | true | true | true | 19 | 43 | 22
ubuntu-22.04 |  | true |  |  |  | 8 | 32 | 3
ubuntu-22.04 |  | true |  |  | true | 13 | 37 | 9
ubuntu-22.04 |  | true |  | true |  | 17 | 41 | 7
ubuntu-22.04 |  | true |  | true | true | 21 | 45 | 23
ubuntu-22.04 |  | true | true |  |  | 9 | 32 | 6
ubuntu-22.04 |  | true | true |  | true | 13 | 37 | 24
ubuntu-22.04 |  | true | true | true |  | 17 | 40 | 5
ubuntu-22.04 |  | true | true | true | true | 21 | 45 | 22
ubuntu-22.04 | true |  |  |  |  | 19 | 42 | 60
ubuntu-22.04 | true |  |  |  | true | 23 | 47 | 26
ubuntu-22.04 | true |  |  | true |  | 27 | 50 | 11
ubuntu-22.04 | true |  |  | true | true | 31 | 55 | 23
ubuntu-22.04 | true |  | true |  |  | 19 | 43 | 13
ubuntu-22.04 | true |  | true |  | true | 23 | 47 | 77
ubuntu-22.04 | true |  | true | true |  | 27 | 50 | 16
ubuntu-22.04 | true |  | true | true | true | 32 | 55 | 32
ubuntu-22.04 | true | true |  |  |  | 20 | 44 | 55
ubuntu-22.04 | true | true |  |  | true | 25 | 49 | 31
ubuntu-22.04 | true | true |  | true |  | 28 | 52 | 68
ubuntu-22.04 | true | true |  | true | true | 33 | 57 | 114
ubuntu-22.04 | true | true | true |  |  | 21 | 44 | 62
ubuntu-22.04 | true | true | true |  | true | 25 | 49 | 21
ubuntu-22.04 | true | true | true | true |  | 28 | 52 | 77
ubuntu-22.04 | true | true | true | true | true | 33 | 57 | 87
