# Maximize available disk space for build tasks

If the available disk space on Github runners is too little for your build job, this action might be for you.
If not: please go on, there's nothing to see here.

This table shows the amount of free space you receive when using the action with the various options.

OS | Android SDKs removed | .NET SDKs removed | Haskell removed | CodeQL Removed | Cached Docker Images Removed | GB freed | GB free
---|:--------------------:|:-----------------:|:---------------:|:--------------:|:----------------------------:|---------:|-------:
ubuntu-20.04 |  |  |  |  |  | 7 | 34
ubuntu-20.04 |  |  |  |  | true | 11 | 38
ubuntu-20.04 |  |  |  | true |  | 13 | 40
ubuntu-20.04 |  |  |  | true | true | 16 | 43
ubuntu-20.04 |  |  | true |  |  | 7 | 34
ubuntu-20.04 |  |  | true |  | true | 11 | 38
ubuntu-20.04 |  |  | true | true |  | 13 | 40
ubuntu-20.04 |  |  | true | true | true | 16 | 43
ubuntu-20.04 |  | true |  |  |  | 10 | 37
ubuntu-20.04 |  | true |  |  | true | 13 | 40
ubuntu-20.04 |  | true |  | true |  | 15 | 42
ubuntu-20.04 |  | true |  | true | true | 19 | 46
ubuntu-20.04 |  | true | true |  |  | 10 | 37
ubuntu-20.04 |  | true | true |  | true | 13 | 40
ubuntu-20.04 |  | true | true | true |  | 15 | 42
ubuntu-20.04 |  | true | true | true | true | 19 | 46
ubuntu-20.04 | true |  |  |  |  | 19 | 46
ubuntu-20.04 | true |  |  |  | true | 23 | 50
ubuntu-20.04 | true |  |  | true |  | 24 | 51
ubuntu-20.04 | true |  |  | true | true | 28 | 55
ubuntu-20.04 | true |  | true |  |  | 19 | 46
ubuntu-20.04 | true |  | true |  | true | 23 | 50
ubuntu-20.04 | true |  | true | true |  | 24 | 51
ubuntu-20.04 | true |  | true | true | true | 28 | 55
ubuntu-20.04 | true | true |  |  |  | 21 | 48
ubuntu-20.04 | true | true |  |  | true | 25 | 52
ubuntu-20.04 | true | true |  | true |  | 26 | 53
ubuntu-20.04 | true | true |  | true | true | 30 | 57
ubuntu-20.04 | true | true | true |  |  | 21 | 48
ubuntu-20.04 | true | true | true |  | true | 25 | 52
ubuntu-20.04 | true | true | true | true |  | 26 | 53
ubuntu-20.04 | true | true | true | true | true | 30 | 57
ubuntu-22.04 |  |  |  |  |  | 7 | 38
ubuntu-22.04 |  |  |  |  | true | 10 | 41
ubuntu-22.04 |  |  |  | true |  | 12 | 43
ubuntu-22.04 |  |  |  | true | true | 15 | 46
ubuntu-22.04 |  |  | true |  |  | 7 | 38
ubuntu-22.04 |  |  | true |  | true | 10 | 41
ubuntu-22.04 |  |  | true | true |  | 12 | 43
ubuntu-22.04 |  |  | true | true | true | 15 | 46
ubuntu-22.04 |  | true |  |  |  | 8 | 39
ubuntu-22.04 |  | true |  |  | true | 11 | 42
ubuntu-22.04 |  | true |  | true |  | 13 | 44
ubuntu-22.04 |  | true |  | true | true | 16 | 47
ubuntu-22.04 |  | true | true |  |  | 8 | 39
ubuntu-22.04 |  | true | true |  | true | 11 | 42
ubuntu-22.04 |  | true | true | true |  | 13 | 44
ubuntu-22.04 |  | true | true | true | true | 16 | 47
ubuntu-22.04 | true |  |  |  |  | 18 | 49
ubuntu-22.04 | true |  |  |  | true | 21 | 52
ubuntu-22.04 | true |  |  | true |  | 24 | 55
ubuntu-22.04 | true |  |  | true | true | 26 | 57
ubuntu-22.04 | true |  | true |  |  | 18 | 49
ubuntu-22.04 | true |  | true |  | true | 21 | 52
ubuntu-22.04 | true |  | true | true |  | 24 | 55
ubuntu-22.04 | true |  | true | true | true | 26 | 57
ubuntu-22.04 | true | true |  |  |  | 20 | 51
ubuntu-22.04 | true | true |  |  | true | 23 | 54
ubuntu-22.04 | true | true |  | true |  | 25 | 56
ubuntu-22.04 | true | true |  | true | true | 28 | 59
ubuntu-22.04 | true | true | true |  |  | 20 | 51
ubuntu-22.04 | true | true | true |  | true | 23 | 54
ubuntu-22.04 | true | true | true | true |  | 25 | 56
ubuntu-22.04 | true | true | true | true | true | 28 | 59
