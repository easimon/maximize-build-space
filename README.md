# Maximize available disk space for build tasks

If the available disk space on Github runners is too little for your build job, this action might be for you.
If not: please go on, there's nothing to see here.

This table shows the amount of free space you receive when using the action with the various options.

OS | Android SDKs removed | .NET SDKs removed | Haskell removed | CodeQL Removed | Cached Docker Images Removed | GB freed | GB free
---|:--------------------:|:-----------------:|:---------------:|:--------------:|:----------------------------:|---------:|-------:
ubuntu-20.04 |  |  |  |  |  | 7 | 31
ubuntu-20.04 |  |  |  |  | true | 11 | 35
ubuntu-20.04 |  |  |  | true |  | 12 | 36
ubuntu-20.04 |  |  |  | true | true | 16 | 40
ubuntu-20.04 |  |  | true |  |  | 7 | 31
ubuntu-20.04 |  |  | true |  | true | 11 | 35
ubuntu-20.04 |  |  | true | true |  | 12 | 36
ubuntu-20.04 |  |  | true | true | true | 16 | 40
ubuntu-20.04 |  | true |  |  |  | 9 | 33
ubuntu-20.04 |  | true |  |  | true | 14 | 38
ubuntu-20.04 |  | true |  | true |  | 14 | 38
ubuntu-20.04 |  | true |  | true | true | 19 | 43
ubuntu-20.04 |  | true | true |  |  | 9 | 33
ubuntu-20.04 |  | true | true |  | true | 14 | 38
ubuntu-20.04 |  | true | true | true |  | 15 | 39
ubuntu-20.04 |  | true | true | true | true | 19 | 43
ubuntu-20.04 | true |  |  |  |  | 18 | 42
ubuntu-20.04 | true |  |  |  | true | 23 | 47
ubuntu-20.04 | true |  |  | true |  | 23 | 47
ubuntu-20.04 | true |  |  | true | true | 28 | 52
ubuntu-20.04 | true |  | true |  |  | 18 | 42
ubuntu-20.04 | true |  | true |  | true | 23 | 47
ubuntu-20.04 | true |  | true | true |  | 23 | 47
ubuntu-20.04 | true |  | true | true | true | 28 | 52
ubuntu-20.04 | true | true |  |  |  | 21 | 45
ubuntu-20.04 | true | true |  |  | true | 25 | 49
ubuntu-20.04 | true | true |  | true |  | 26 | 50
ubuntu-20.04 | true | true |  | true | true | 31 | 55
ubuntu-20.04 | true | true | true |  |  | 21 | 45
ubuntu-20.04 | true | true | true |  | true | 25 | 49
ubuntu-20.04 | true | true | true | true |  | 26 | 50
ubuntu-20.04 | true | true | true | true | true | 31 | 55
ubuntu-22.04 |  |  |  |  |  | 7 | 34
ubuntu-22.04 |  |  |  |  | true | 11 | 38
ubuntu-22.04 |  |  |  | true |  | 13 | 40
ubuntu-22.04 |  |  |  | true | true | 16 | 43
ubuntu-22.04 |  |  | true |  |  | 7 | 34
ubuntu-22.04 |  |  | true |  | true | 11 | 38
ubuntu-22.04 |  |  | true | true |  | 13 | 40
ubuntu-22.04 |  |  | true | true | true | 16 | 43
ubuntu-22.04 |  | true |  |  |  | 9 | 36
ubuntu-22.04 |  | true |  |  | true | 13 | 40
ubuntu-22.04 |  | true |  | true |  | 14 | 41
ubuntu-22.04 |  | true |  | true | true | 18 | 45
ubuntu-22.04 |  | true | true |  |  | 9 | 36
ubuntu-22.04 |  | true | true |  | true | 13 | 40
ubuntu-22.04 |  | true | true | true |  | 14 | 41
ubuntu-22.04 |  | true | true | true | true | 18 | 45
ubuntu-22.04 | true |  |  |  |  | 19 | 46
ubuntu-22.04 | true |  |  |  | true | 23 | 50
ubuntu-22.04 | true |  |  | true |  | 24 | 51
ubuntu-22.04 | true |  |  | true | true | 28 | 55
ubuntu-22.04 | true |  | true |  |  | 19 | 46
ubuntu-22.04 | true |  | true |  | true | 23 | 50
ubuntu-22.04 | true |  | true | true |  | 24 | 51
ubuntu-22.04 | true |  | true | true | true | 28 | 55
ubuntu-22.04 | true | true |  |  |  | 21 | 48
ubuntu-22.04 | true | true |  |  | true | 24 | 51
ubuntu-22.04 | true | true |  | true |  | 26 | 53
ubuntu-22.04 | true | true |  | true | true | 29 | 56
ubuntu-22.04 | true | true | true |  |  | 21 | 48
ubuntu-22.04 | true | true | true |  | true | 24 | 51
ubuntu-22.04 | true | true | true | true |  | 26 | 53
ubuntu-22.04 | true | true | true | true | true | 29 | 56
