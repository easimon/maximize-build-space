# Maximize available disk space for build tasks

If the available disk space on Github runners is too little for your build job, this action might be for you.
If not: please go on, there's nothing to see here.

This table shows the amount of free space you receive when using the action with the various options.

OS | Android SDKs removed | .NET SDKs removed | Haskell removed | CodeQL Removed | Cached Docker Images Removed | GB freed | GB free | Elapsed Time (seconds) |
---|:--------------------:|:-----------------:|:---------------:|:--------------:|:----------------------------:|:--------:|:-------:|:----------------------:|
ubuntu-20.04 |  |  |  |  |  | 7 | 26 | 2
ubuntu-20.04 |  |  |  |  | true | 13 | 32 | 27
ubuntu-20.04 |  |  |  | true |  | 15 | 34 | 3
ubuntu-20.04 |  |  |  | true | true | 21 | 40 | 27
ubuntu-20.04 |  |  | true |  |  | 7 | 26 | 2
ubuntu-20.04 |  |  | true |  | true | 12 | 32 | 22
ubuntu-20.04 |  |  | true | true |  | 15 | 34 | 4
ubuntu-20.04 |  |  | true | true | true | 21 | 40 | 24
ubuntu-20.04 |  | true |  |  |  | 9 | 28 | 3
ubuntu-20.04 |  | true |  |  | true | 14 | 33 | 38
ubuntu-20.04 |  | true |  | true |  | 17 | 36 | 5
ubuntu-20.04 |  | true |  | true | true | 22 | 42 | 40
ubuntu-20.04 |  | true | true |  |  | 9 | 28 | 6
ubuntu-20.04 |  | true | true |  | true | 14 | 33 | 26
ubuntu-20.04 |  | true | true | true |  | 17 | 36 | 8
ubuntu-20.04 |  | true | true | true | true | 23 | 42 | 24
ubuntu-20.04 | true |  |  |  |  | 19 | 38 | 41
ubuntu-20.04 | true |  |  |  | true | 25 | 44 | 65
ubuntu-20.04 | true |  |  | true |  | 27 | 46 | 46
ubuntu-20.04 | true |  |  | true | true | 33 | 52 | 43
ubuntu-20.04 | true |  | true |  |  | 19 | 38 | 51
ubuntu-20.04 | true |  | true |  | true | 25 | 44 | 82
ubuntu-20.04 | true |  | true | true |  | 27 | 47 | 46
ubuntu-20.04 | true |  | true | true | true | 33 | 52 | 27
ubuntu-20.04 | true | true |  |  |  | 21 | 40 | 61
ubuntu-20.04 | true | true |  |  | true | 26 | 45 | 87
ubuntu-20.04 | true | true |  | true |  | 29 | 48 | 16
ubuntu-20.04 | true | true |  | true | true | 34 | 53 | 78
ubuntu-20.04 | true | true | true |  |  | 21 | 40 | 13
ubuntu-20.04 | true | true | true |  | true | 26 | 45 | 82
ubuntu-20.04 | true | true | true | true |  | 29 | 48 | 11
ubuntu-20.04 | true | true | true | true | true | 34 | 53 | 32
ubuntu-22.04 |  |  |  |  |  | 8 | 30 | 2
ubuntu-22.04 |  |  |  |  | true | 12 | 34 | 30
ubuntu-22.04 |  |  |  | true |  | 15 | 37 | 3
ubuntu-22.04 |  |  |  | true | true | 20 | 42 | 8
ubuntu-22.04 |  |  | true |  |  | 8 | 30 | 2
ubuntu-22.04 |  |  | true |  | true | 12 | 34 | 11
ubuntu-22.04 |  |  | true | true |  | 15 | 37 | 4
ubuntu-22.04 |  |  | true | true | true | 20 | 42 | 27
ubuntu-22.04 |  | true |  |  |  | 9 | 31 | 3
ubuntu-22.04 |  | true |  |  | true | 13 | 35 | 27
ubuntu-22.04 |  | true |  | true |  | 17 | 39 | 4
ubuntu-22.04 |  | true |  | true | true | 21 | 43 | 23
ubuntu-22.04 |  | true | true |  |  | 9 | 31 | 4
ubuntu-22.04 |  | true | true |  | true | 13 | 35 | 33
ubuntu-22.04 |  | true | true | true |  | 17 | 39 | 3
ubuntu-22.04 |  | true | true | true | true | 21 | 43 | 9
ubuntu-22.04 | true |  |  |  |  | 19 | 41 | 13
ubuntu-22.04 | true |  |  |  | true | 23 | 45 | 99
ubuntu-22.04 | true |  |  | true |  | 27 | 49 | 13
ubuntu-22.04 | true |  |  | true | true | 31 | 53 | 30
ubuntu-22.04 | true |  | true |  |  | 19 | 41 | 80
ubuntu-22.04 | true |  | true |  | true | 23 | 45 | 96
ubuntu-22.04 | true |  | true | true |  | 27 | 49 | 97
ubuntu-22.04 | true |  | true | true | true | 32 | 54 | 35
ubuntu-22.04 | true | true |  |  |  | 21 | 43 | 18
ubuntu-22.04 | true | true |  |  | true | 26 | 48 | 92
ubuntu-22.04 | true | true |  | true |  | 29 | 51 | 96
ubuntu-22.04 | true | true |  | true | true | 33 | 55 | 114
ubuntu-22.04 | true | true | true |  |  | 21 | 43 | 103
ubuntu-22.04 | true | true | true |  | true | 26 | 48 | 31
ubuntu-22.04 | true | true | true | true |  | 29 | 51 | 14
ubuntu-22.04 | true | true | true | true | true | 34 | 56 | 22
