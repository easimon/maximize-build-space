# Maximize available disk space for build tasks

If the available disk space on Github runners is too little for your build job, this action might be for you.
If not: please go on, there's nothing to see here.

This table shows the amount of free space you receive when using the action with the various options.

OS | Android SDKs removed | .NET SDKs removed | Haskell removed | CodeQL Removed | Cached Docker Images Removed | GB freed | GB free | Elapsed Time (seconds) |
---|:--------------------:|:-----------------:|:---------------:|:--------------:|:----------------------------:|:--------:|:-------:|:----------------------:|
ubuntu-20.04 |  |  |  |  |  | 7 | 26 | 2
ubuntu-20.04 |  |  |  |  | true | 12 | 31 | 51
ubuntu-20.04 |  |  |  | true |  | 15 | 34 | 4
ubuntu-20.04 |  |  |  | true | true | 20 | 39 | 42
ubuntu-20.04 |  |  | true |  |  | 7 | 26 | 3
ubuntu-20.04 |  |  | true |  | true | 13 | 32 | 28
ubuntu-20.04 |  |  | true | true |  | 15 | 34 | 4
ubuntu-20.04 |  |  | true | true | true | 20 | 39 | 29
ubuntu-20.04 |  | true |  |  |  | 9 | 28 | 6
ubuntu-20.04 |  | true |  |  | true | 14 | 33 | 45
ubuntu-20.04 |  | true |  | true |  | 17 | 36 | 5
ubuntu-20.04 |  | true |  | true | true | 23 | 42 | 53
ubuntu-20.04 |  | true | true |  |  | 10 | 29 | 5
ubuntu-20.04 |  | true | true |  | true | 15 | 34 | 30
ubuntu-20.04 |  | true | true | true |  | 17 | 36 | 4
ubuntu-20.04 |  | true | true | true | true | 23 | 42 | 34
ubuntu-20.04 | true |  |  |  |  | 19 | 38 | 60
ubuntu-20.04 | true |  |  |  | true | 24 | 43 | 51
ubuntu-20.04 | true |  |  | true |  | 27 | 46 | 70
ubuntu-20.04 | true |  |  | true | true | 33 | 52 | 19
ubuntu-20.04 | true |  | true |  |  | 19 | 38 | 58
ubuntu-20.04 | true |  | true |  | true | 24 | 43 | 103
ubuntu-20.04 | true |  | true | true |  | 27 | 46 | 60
ubuntu-20.04 | true |  | true | true | true | 33 | 52 | 101
ubuntu-20.04 | true | true |  |  |  | 21 | 40 | 47
ubuntu-20.04 | true | true |  |  | true | 26 | 45 | 20
ubuntu-20.04 | true | true |  | true |  | 29 | 48 | 27
ubuntu-20.04 | true | true |  | true | true | 35 | 54 | 24
ubuntu-20.04 | true | true | true |  |  | 21 | 40 | 79
ubuntu-20.04 | true | true | true |  | true | 26 | 45 | 117
ubuntu-20.04 | true | true | true | true |  | 29 | 48 | 79
ubuntu-20.04 | true | true | true | true | true | 34 | 53 | 50
ubuntu-22.04 |  |  |  |  |  | 7 | 29 | 2
ubuntu-22.04 |  |  |  |  | true | 11 | 33 | 8
ubuntu-22.04 |  |  |  | true |  | 15 | 37 | 4
ubuntu-22.04 |  |  |  | true | true | 20 | 42 | 8
ubuntu-22.04 |  |  | true |  |  | 7 | 29 | 3
ubuntu-22.04 |  |  | true |  | true | 12 | 34 | 7
ubuntu-22.04 |  |  | true | true |  | 15 | 37 | 4
ubuntu-22.04 |  |  | true | true | true | 20 | 42 | 28
ubuntu-22.04 |  | true |  |  |  | 10 | 32 | 3
ubuntu-22.04 |  | true |  |  | true | 14 | 36 | 21
ubuntu-22.04 |  | true |  | true |  | 18 | 40 | 5
ubuntu-22.04 |  | true |  | true | true | 22 | 44 | 30
ubuntu-22.04 |  | true | true |  |  | 9 | 31 | 6
ubuntu-22.04 |  | true | true |  | true | 14 | 36 | 36
ubuntu-22.04 |  | true | true | true |  | 18 | 40 | 4
ubuntu-22.04 |  | true | true | true | true | 22 | 44 | 34
ubuntu-22.04 | true |  |  |  |  | 19 | 41 | 8
ubuntu-22.04 | true |  |  |  | true | 23 | 45 | 18
ubuntu-22.04 | true |  |  | true |  | 27 | 49 | 79
ubuntu-22.04 | true |  |  | true | true | 32 | 54 | 82
ubuntu-22.04 | true |  | true |  |  | 19 | 41 | 82
ubuntu-22.04 | true |  | true |  | true | 24 | 46 | 121
ubuntu-22.04 | true |  | true | true |  | 27 | 49 | 10
ubuntu-22.04 | true |  | true | true | true | 31 | 53 | 30
ubuntu-22.04 | true | true |  |  |  | 21 | 43 | 12
ubuntu-22.04 | true | true |  |  | true | 26 | 48 | 93
ubuntu-22.04 | true | true |  | true |  | 29 | 51 | 99
ubuntu-22.04 | true | true |  | true | true | 34 | 56 | 32
ubuntu-22.04 | true | true | true |  |  | 21 | 43 | 91
ubuntu-22.04 | true | true | true |  | true | 26 | 48 | 25
ubuntu-22.04 | true | true | true | true |  | 29 | 51 | 85
ubuntu-22.04 | true | true | true | true | true | 33 | 55 | 19
