# Maximize available disk space for build tasks

If the available disk space on Github runners is too little for your build job, this action might be for you.
If not: please go on, there's nothing to see here.

This table shows the amount of free space you receive when using the action with the various options.

OS | Android SDKs removed | .NET SDKs removed | Haskell removed | CodeQL Removed | Cached Docker Images Removed | GB freed | GB free
---|:--------------------:|:-----------------:|:---------------:|:--------------:|:----------------------------:|---------:|-------:
ubuntu-20.04 |  |  |  |  |  | 7 | 29
ubuntu-20.04 |  |  |  |  | true | 13 | 35
ubuntu-20.04 |  |  |  | true |  | 12 | 34
ubuntu-20.04 |  |  |  | true | true | 18 | 40
ubuntu-20.04 |  |  | true |  |  | 7 | 29
ubuntu-20.04 |  |  | true |  | true | 13 | 35
ubuntu-20.04 |  |  | true | true |  | 12 | 34
ubuntu-20.04 |  |  | true | true | true | 18 | 40
ubuntu-20.04 |  | true |  |  |  | 10 | 32
ubuntu-20.04 |  | true |  |  | true | 15 | 37
ubuntu-20.04 |  | true |  | true |  | 15 | 37
ubuntu-20.04 |  | true |  | true | true | 21 | 43
ubuntu-20.04 |  | true | true |  |  | 10 | 32
ubuntu-20.04 |  | true | true |  | true | 15 | 37
ubuntu-20.04 |  | true | true | true |  | 15 | 37
ubuntu-20.04 |  | true | true | true | true | 21 | 43
ubuntu-20.04 | true |  |  |  |  | 19 | 41
ubuntu-20.04 | true |  |  |  | true | 24 | 46
ubuntu-20.04 | true |  |  | true |  | 24 | 46
ubuntu-20.04 | true |  |  | true | true | 30 | 52
ubuntu-20.04 | true |  | true |  |  | 19 | 41
ubuntu-20.04 | true |  | true |  | true | 24 | 46
ubuntu-20.04 | true |  | true | true |  | 24 | 46
ubuntu-20.04 | true |  | true | true | true | 30 | 52
ubuntu-20.04 | true | true |  |  |  | 22 | 44
ubuntu-20.04 | true | true |  |  | true | 27 | 49
ubuntu-20.04 | true | true |  | true |  | 27 | 49
ubuntu-20.04 | true | true |  | true | true | 32 | 54
ubuntu-20.04 | true | true | true |  |  | 22 | 44
ubuntu-20.04 | true | true | true |  | true | 27 | 49
ubuntu-20.04 | true | true | true | true |  | 27 | 49
ubuntu-20.04 | true | true | true | true | true | 32 | 54
ubuntu-22.04 |  |  |  |  |  | 7 | 33
ubuntu-22.04 |  |  |  |  | true | 12 | 38
ubuntu-22.04 |  |  |  | true |  | 12 | 38
ubuntu-22.04 |  |  |  | true | true | 17 | 43
ubuntu-22.04 |  |  | true |  |  | 7 | 33
ubuntu-22.04 |  |  | true |  | true | 12 | 38
ubuntu-22.04 |  |  | true | true |  | 12 | 38
ubuntu-22.04 |  |  | true | true | true | 17 | 43
ubuntu-22.04 |  | true |  |  |  | 9 | 35
ubuntu-22.04 |  | true |  |  | true | 13 | 39
ubuntu-22.04 |  | true |  | true |  | 14 | 40
ubuntu-22.04 |  | true |  | true | true | 18 | 44
ubuntu-22.04 |  | true | true |  |  | 9 | 35
ubuntu-22.04 |  | true | true |  | true | 13 | 39
ubuntu-22.04 |  | true | true | true |  | 14 | 40
ubuntu-22.04 |  | true | true | true | true | 18 | 44
ubuntu-22.04 | true |  |  |  |  | 19 | 45
ubuntu-22.04 | true |  |  |  | true | 23 | 49
ubuntu-22.04 | true |  |  | true |  | 24 | 50
ubuntu-22.04 | true |  |  | true | true | 29 | 55
ubuntu-22.04 | true |  | true |  |  | 19 | 45
ubuntu-22.04 | true |  | true |  | true | 23 | 49
ubuntu-22.04 | true |  | true | true |  | 24 | 50
ubuntu-22.04 | true |  | true | true | true | 29 | 55
ubuntu-22.04 | true | true |  |  |  | 21 | 47
ubuntu-22.04 | true | true |  |  | true | 25 | 51
ubuntu-22.04 | true | true |  | true |  | 26 | 52
ubuntu-22.04 | true | true |  | true | true | 30 | 56
ubuntu-22.04 | true | true | true |  |  | 21 | 47
ubuntu-22.04 | true | true | true |  | true | 25 | 51
ubuntu-22.04 | true | true | true | true |  | 26 | 52
ubuntu-22.04 | true | true | true | true | true | 30 | 56
