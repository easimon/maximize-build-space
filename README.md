# Maximize available disk space for build tasks

If the available disk space on Github runners is too little for your build job, this action might be for you.
If not: please go on, there's nothing to see here.

This table shows the amount of free space you receive when using the action with the various options.

OS | Android SDKs removed | .NET SDKs removed | Haskell removed | CodeQL Removed | Cached Docker Images Removed | GB freed | GB free
---|:--------------------:|:-----------------:|:---------------:|:--------------:|:----------------------------:|---------:|-------:
ubuntu-20.04 |  |  |  |  |  | 7 | 30
ubuntu-20.04 |  |  |  |  | true | 12 | 35
ubuntu-20.04 |  |  |  | true |  | 12 | 35
ubuntu-20.04 |  |  |  | true | true | 17 | 40
ubuntu-20.04 |  |  | true |  |  | 7 | 30
ubuntu-20.04 |  |  | true |  | true | 12 | 35
ubuntu-20.04 |  |  | true | true |  | 12 | 35
ubuntu-20.04 |  |  | true | true | true | 17 | 40
ubuntu-20.04 |  | true |  |  |  | 8 | 31
ubuntu-20.04 |  | true |  |  | true | 14 | 37
ubuntu-20.04 |  | true |  | true |  | 14 | 37
ubuntu-20.04 |  | true |  | true | true | 19 | 42
ubuntu-20.04 |  | true | true |  |  | 8 | 31
ubuntu-20.04 |  | true | true |  | true | 14 | 37
ubuntu-20.04 |  | true | true | true |  | 14 | 37
ubuntu-20.04 |  | true | true | true | true | 19 | 42
ubuntu-20.04 | true |  |  |  |  | 18 | 41
ubuntu-20.04 | true |  |  |  | true | 24 | 47
ubuntu-20.04 | true |  |  | true |  | 24 | 47
ubuntu-20.04 | true |  |  | true | true | 29 | 52
ubuntu-20.04 | true |  | true |  |  | 18 | 41
ubuntu-20.04 | true |  | true |  | true | 24 | 47
ubuntu-20.04 | true |  | true | true |  | 24 | 47
ubuntu-20.04 | true |  | true | true | true | 29 | 52
ubuntu-20.04 | true | true |  |  |  | 20 | 43
ubuntu-20.04 | true | true |  |  | true | 26 | 49
ubuntu-20.04 | true | true |  | true |  | 25 | 48
ubuntu-20.04 | true | true |  | true | true | 31 | 54
ubuntu-20.04 | true | true | true |  |  | 20 | 43
ubuntu-20.04 | true | true | true |  | true | 26 | 49
ubuntu-20.04 | true | true | true | true |  | 25 | 48
ubuntu-20.04 | true | true | true | true | true | 31 | 54
ubuntu-22.04 |  |  |  |  |  | 7 | 32
ubuntu-22.04 |  |  |  |  | true | 12 | 37
ubuntu-22.04 |  |  |  | true |  | 13 | 38
ubuntu-22.04 |  |  |  | true | true | 17 | 42
ubuntu-22.04 |  |  | true |  |  | 7 | 32
ubuntu-22.04 |  |  | true |  | true | 12 | 37
ubuntu-22.04 |  |  | true | true |  | 13 | 38
ubuntu-22.04 |  |  | true | true | true | 17 | 42
ubuntu-22.04 |  | true |  |  |  | 9 | 34
ubuntu-22.04 |  | true |  |  | true | 14 | 39
ubuntu-22.04 |  | true |  | true |  | 14 | 39
ubuntu-22.04 |  | true |  | true | true | 19 | 44
ubuntu-22.04 |  | true | true |  |  | 9 | 34
ubuntu-22.04 |  | true | true |  | true | 14 | 39
ubuntu-22.04 |  | true | true | true |  | 14 | 39
ubuntu-22.04 |  | true | true | true | true | 19 | 44
ubuntu-22.04 | true |  |  |  |  | 19 | 44
ubuntu-22.04 | true |  |  |  | true | 24 | 49
ubuntu-22.04 | true |  |  | true |  | 24 | 49
ubuntu-22.04 | true |  |  | true | true | 29 | 54
ubuntu-22.04 | true |  | true |  |  | 19 | 44
ubuntu-22.04 | true |  | true |  | true | 24 | 49
ubuntu-22.04 | true |  | true | true |  | 24 | 49
ubuntu-22.04 | true |  | true | true | true | 29 | 54
ubuntu-22.04 | true | true |  |  |  | 21 | 46
ubuntu-22.04 | true | true |  |  | true | 25 | 50
ubuntu-22.04 | true | true |  | true |  | 26 | 51
ubuntu-22.04 | true | true |  | true | true | 31 | 56
ubuntu-22.04 | true | true | true |  |  | 21 | 46
ubuntu-22.04 | true | true | true |  | true | 25 | 50
ubuntu-22.04 | true | true | true | true |  | 26 | 51
ubuntu-22.04 | true | true | true | true | true | 31 | 56
