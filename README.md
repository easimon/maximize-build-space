# Maximize available disk space for build tasks

If the available disk space on Github runners is too little for your build job, this action might be for you.
If not: please go on, there's nothing to see here.

This table shows the amount of free space you receive when using the action with the various options.

OS | Android SDKs removed | .NET SDKs removed | Haskell removed | CodeQL Removed | Cached Docker Images Removed | GB freed | GB free | Elapsed Time (seconds) |
---|:--------------------:|:-----------------:|:---------------:|:--------------:|:----------------------------:|:--------:|:-------:|:----------------------:|
ubuntu-20.04 |  |  |  |  |  | 53 | 75 | 2
ubuntu-20.04 |  |  |  |  | true | 14 | 36 | 12
ubuntu-20.04 |  |  |  | true |  | 11 | 33 | 3
ubuntu-20.04 |  |  |  | true | true | 17 | 39 | 18
ubuntu-20.04 |  |  | true |  |  | 7 | 29 | 2
ubuntu-20.04 |  |  | true |  | true | 14 | 36 | 12
ubuntu-20.04 |  |  | true | true |  | 11 | 33 | 5
ubuntu-20.04 |  |  | true | true | true | 63 | 85 | 9
ubuntu-20.04 |  | true |  |  |  | 9 | 31 | 6
ubuntu-20.04 |  | true |  |  | true | 61 | 83 | 8
ubuntu-20.04 |  | true |  | true |  | 13 | 35 | 5
ubuntu-20.04 |  | true |  | true | true | 65 | 87 | 33
ubuntu-20.04 |  | true | true |  |  | 55 | 77 | 8
ubuntu-20.04 |  | true | true |  | true | 16 | 38 | 55
ubuntu-20.04 |  | true | true | true |  | 13 | 35 | 9
ubuntu-20.04 |  | true | true | true | true | 65 | 87 | 34
ubuntu-20.04 | true |  |  |  |  | 21 | 43 | 69
ubuntu-20.04 | true |  |  |  | true | 73 | 95 | 18
ubuntu-20.04 | true |  |  | true |  | 70 | 92 | 65
ubuntu-20.04 | true |  |  | true | true | 77 | 99 | 35
ubuntu-20.04 | true |  | true |  |  | 21 | 43 | 14
ubuntu-20.04 | true |  | true |  | true | 28 | 50 | 94
ubuntu-20.04 | true |  | true | true |  | 25 | 47 | 16
ubuntu-20.04 | true |  | true | true | true | 31 | 53 | 90
ubuntu-20.04 | true | true |  |  |  | 23 | 45 | 66
ubuntu-20.04 | true | true |  |  | true | 30 | 52 | 28
ubuntu-20.04 | true | true |  | true |  | 72 | 94 | 16
ubuntu-20.04 | true | true |  | true | true | 79 | 101 | 15
ubuntu-20.04 | true | true | true |  |  | 23 | 45 | 12
ubuntu-20.04 | true | true | true |  | true | 30 | 52 | 111
ubuntu-20.04 | true | true | true | true |  | 72 | 94 | 10
ubuntu-20.04 | true | true | true | true | true | 79 | 101 | 44
ubuntu-22.04 |  |  |  |  |  | 52 | 76 | 2
ubuntu-22.04 |  |  |  |  | true | 12 | 36 | 12
ubuntu-22.04 |  |  |  | true |  | 56 | 80 | 4
ubuntu-22.04 |  |  |  | true | true | 61 | 85 | 12
ubuntu-22.04 |  |  | true |  |  | 52 | 76 | 2
ubuntu-22.04 |  |  | true |  | true | 58 | 82 | 42
ubuntu-22.04 |  |  | true | true |  | 10 | 34 | 3
ubuntu-22.04 |  |  | true | true | true | 16 | 40 | 26
ubuntu-22.04 |  | true |  |  |  | 54 | 78 | 5
ubuntu-22.04 |  | true |  |  | true | 14 | 38 | 27
ubuntu-22.04 |  | true |  | true |  | 12 | 36 | 4
ubuntu-22.04 |  | true |  | true | true | 18 | 42 | 14
ubuntu-22.04 |  | true | true |  |  | 9 | 33 | 3
ubuntu-22.04 |  | true | true |  | true | 14 | 38 | 33
ubuntu-22.04 |  | true | true | true |  | 58 | 82 | 4
ubuntu-22.04 |  | true | true | true | true | 18 | 42 | 9
ubuntu-22.04 | true |  |  |  |  | 66 | 90 | 14
ubuntu-22.04 | true |  |  |  | true | 26 | 50 | 98
ubuntu-22.04 | true |  |  | true |  | 24 | 48 | 50
ubuntu-22.04 | true |  |  | true | true | 30 | 54 | 42
ubuntu-22.04 | true |  | true |  |  | 66 | 90 | 13
ubuntu-22.04 | true |  | true |  | true | 26 | 50 | 20
ubuntu-22.04 | true |  | true | true |  | 70 | 94 | 14
ubuntu-22.04 | true |  | true | true | true | 30 | 54 | 26
ubuntu-22.04 | true | true |  |  |  | 68 | 92 | 52
ubuntu-22.04 | true | true |  |  | true | 28 | 52 | 52
ubuntu-22.04 | true | true |  | true |  | 72 | 96 | 14
ubuntu-22.04 | true | true |  | true | true | 78 | 102 | 24
ubuntu-22.04 | true | true | true |  |  | 23 | 47 | 12
ubuntu-22.04 | true | true | true |  | true | 74 | 98 | 21
ubuntu-22.04 | true | true | true | true |  | 26 | 50 | 50
ubuntu-22.04 | true | true | true | true | true | 78 | 102 | 20
