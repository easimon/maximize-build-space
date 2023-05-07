# Maximize available disk space for build tasks

If the available disk space on Github runners is too little for your build job, this action might be for you.
If not: please go on, there's nothing to see here.

This table shows the amount of free space you receive when using the action with the various options.

OS | Android SDKs removed | .NET SDKs removed | Haskell removed | CodeQL Removed | Cached Docker Images Removed | GB freed | GB free
---|:--------------------:|:-----------------:|:---------------:|:--------------:|:----------------------------:|---------:|-------:
ubuntu-20.04 |  |  |  |  |  | 7 | 35
ubuntu-20.04 |  |  |  |  | true | 11 | 39
ubuntu-20.04 |  |  |  | true |  | 12 | 40
ubuntu-20.04 |  |  |  | true | true | 16 | 44
ubuntu-20.04 |  |  | true |  |  | 7 | 35
ubuntu-20.04 |  |  | true |  | true | 11 | 39
ubuntu-20.04 |  |  | true | true |  | 12 | 40
ubuntu-20.04 |  |  | true | true | true | 16 | 44
ubuntu-20.04 |  | true |  |  |  | 9 | 37
ubuntu-20.04 |  | true |  |  | true | 13 | 41
ubuntu-20.04 |  | true |  | true |  | 14 | 42
ubuntu-20.04 |  | true |  | true | true | 18 | 46
ubuntu-20.04 |  | true | true |  |  | 9 | 37
ubuntu-20.04 |  | true | true |  | true | 13 | 41
ubuntu-20.04 |  | true | true | true |  | 14 | 42
ubuntu-20.04 |  | true | true | true | true | 18 | 46
ubuntu-20.04 | true |  |  |  |  | 18 | 46
ubuntu-20.04 | true |  |  |  | true | 22 | 50
ubuntu-20.04 | true |  |  | true |  | 24 | 52
ubuntu-20.04 | true |  |  | true | true | 27 | 55
ubuntu-20.04 | true |  | true |  |  | 18 | 46
ubuntu-20.04 | true |  | true |  | true | 22 | 50
ubuntu-20.04 | true |  | true | true |  | 24 | 52
ubuntu-20.04 | true |  | true | true | true | 27 | 55
ubuntu-20.04 | true | true |  |  |  | 21 | 49
ubuntu-20.04 | true | true |  |  | true | 24 | 52
ubuntu-20.04 | true | true |  | true |  | 26 | 54
ubuntu-20.04 | true | true |  | true | true | 30 | 58
ubuntu-20.04 | true | true | true |  |  | 21 | 49
ubuntu-20.04 | true | true | true |  | true | 24 | 52
ubuntu-20.04 | true | true | true | true |  | 26 | 54
ubuntu-20.04 | true | true | true | true | true | 30 | 58
ubuntu-22.04 |  |  |  |  |  | 7 | 38
ubuntu-22.04 |  |  |  |  | true | 10 | 41
ubuntu-22.04 |  |  |  | true |  | 13 | 44
ubuntu-22.04 |  |  |  | true | true | 15 | 46
ubuntu-22.04 |  |  | true |  |  | 7 | 38
ubuntu-22.04 |  |  | true |  | true | 10 | 41
ubuntu-22.04 |  |  | true | true |  | 13 | 44
ubuntu-22.04 |  |  | true | true | true | 15 | 46
ubuntu-22.04 |  | true |  |  |  | 9 | 40
ubuntu-22.04 |  | true |  |  | true | 11 | 42
ubuntu-22.04 |  | true |  | true |  | 14 | 45
ubuntu-22.04 |  | true |  | true | true | 17 | 48
ubuntu-22.04 |  | true | true |  |  | 9 | 40
ubuntu-22.04 |  | true | true |  | true | 11 | 42
ubuntu-22.04 |  | true | true | true |  | 14 | 45
ubuntu-22.04 |  | true | true | true | true | 17 | 48
ubuntu-22.04 | true |  |  |  |  | 19 | 50
ubuntu-22.04 | true |  |  |  | true | 22 | 53
ubuntu-22.04 | true |  |  | true |  | 24 | 55
ubuntu-22.04 | true |  |  | true | true | 27 | 58
ubuntu-22.04 | true |  | true |  |  | 19 | 50
ubuntu-22.04 | true |  | true |  | true | 22 | 53
ubuntu-22.04 | true |  | true | true |  | 24 | 55
ubuntu-22.04 | true |  | true | true | true | 27 | 58
ubuntu-22.04 | true | true |  |  |  | 20 | 51
ubuntu-22.04 | true | true |  |  | true | 23 | 54
ubuntu-22.04 | true | true |  | true |  | 25 | 56
ubuntu-22.04 | true | true |  | true | true | 28 | 59
ubuntu-22.04 | true | true | true |  |  | 20 | 51
ubuntu-22.04 | true | true | true |  | true | 23 | 54
ubuntu-22.04 | true | true | true | true |  | 25 | 56
ubuntu-22.04 | true | true | true | true | true | 28 | 59
