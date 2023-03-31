# Maximize available disk space for build tasks

If the available disk space on Github runners is too little for your build job, this action might be for you.
If not: please go on, there's nothing to see here.

This table shows the amount of free space you receive when using the action with the various options.

OS | Android SDKs removed | .NET SDKs removed | Haskell removed | CodeQL Removed | Cached Docker Images Removed | GB freed | GB free
---|:--------------------:|:-----------------:|:---------------:|:--------------:|:----------------------------:|---------:|-------:
ubuntu-18.04 |  |  |  |  |  | 7 | 35
ubuntu-18.04 |  |  |  |  | true | 11 | 39
ubuntu-18.04 |  |  |  | true |  | 12 | 40
ubuntu-18.04 |  |  |  | true | true | 16 | 44
ubuntu-18.04 |  |  | true |  |  | 7 | 35
ubuntu-18.04 |  |  | true |  | true | 11 | 39
ubuntu-18.04 |  |  | true | true |  | 12 | 40
ubuntu-18.04 |  |  | true | true | true | 16 | 44
ubuntu-18.04 |  | true |  |  |  | 8 | 36
ubuntu-18.04 |  | true |  |  | true | 12 | 40
ubuntu-18.04 |  | true |  | true |  | 14 | 42
ubuntu-18.04 |  | true |  | true | true | 17 | 45
ubuntu-18.04 |  | true | true |  |  | 8 | 36
ubuntu-18.04 |  | true | true |  | true | 12 | 40
ubuntu-18.04 |  | true | true | true |  | 14 | 42
ubuntu-18.04 |  | true | true | true | true | 17 | 45
ubuntu-18.04 | true |  |  |  |  | 20 | 48
ubuntu-18.04 | true |  |  |  | true | 24 | 52
ubuntu-18.04 | true |  |  | true |  | 26 | 54
ubuntu-18.04 | true |  |  | true | true | 29 | 57
ubuntu-18.04 | true |  | true |  |  | 20 | 48
ubuntu-18.04 | true |  | true |  | true | 24 | 52
ubuntu-18.04 | true |  | true | true |  | 26 | 54
ubuntu-18.04 | true |  | true | true | true | 29 | 57
ubuntu-18.04 | true | true |  |  |  | 22 | 50
ubuntu-18.04 | true | true |  |  | true | 26 | 54
ubuntu-18.04 | true | true |  | true |  | 27 | 55
ubuntu-18.04 | true | true |  | true | true | 31 | 59
ubuntu-18.04 | true | true | true |  |  | 22 | 50
ubuntu-18.04 | true | true | true |  | true | 26 | 54
ubuntu-18.04 | true | true | true | true |  | 27 | 55
ubuntu-18.04 | true | true | true | true | true | 31 | 59
ubuntu-20.04 |  |  |  |  |  | 7 | 33
ubuntu-20.04 |  |  |  |  | true | 11 | 37
ubuntu-20.04 |  |  |  | true |  | 12 | 38
ubuntu-20.04 |  |  |  | true | true | 16 | 42
ubuntu-20.04 |  |  | true |  |  | 7 | 33
ubuntu-20.04 |  |  | true |  | true | 11 | 37
ubuntu-20.04 |  |  | true | true |  | 12 | 38
ubuntu-20.04 |  |  | true | true | true | 16 | 42
ubuntu-20.04 |  | true |  |  |  | 9 | 35
ubuntu-20.04 |  | true |  |  | true | 13 | 39
ubuntu-20.04 |  | true |  | true |  | 15 | 41
ubuntu-20.04 |  | true |  | true | true | 18 | 44
ubuntu-20.04 |  | true | true |  |  | 9 | 35
ubuntu-20.04 |  | true | true |  | true | 13 | 39
ubuntu-20.04 |  | true | true | true |  | 15 | 41
ubuntu-20.04 |  | true | true | true | true | 18 | 44
ubuntu-20.04 | true |  |  |  |  | 19 | 45
ubuntu-20.04 | true |  |  |  | true | 22 | 48
ubuntu-20.04 | true |  |  | true |  | 24 | 50
ubuntu-20.04 | true |  |  | true | true | 28 | 54
ubuntu-20.04 | true |  | true |  |  | 19 | 45
ubuntu-20.04 | true |  | true |  | true | 22 | 48
ubuntu-20.04 | true |  | true | true |  | 24 | 50
ubuntu-20.04 | true |  | true | true | true | 28 | 54
ubuntu-20.04 | true | true |  |  |  | 21 | 47
ubuntu-20.04 | true | true |  |  | true | 25 | 51
ubuntu-20.04 | true | true |  | true |  | 26 | 52
ubuntu-20.04 | true | true |  | true | true | 30 | 56
ubuntu-20.04 | true | true | true |  |  | 21 | 47
ubuntu-20.04 | true | true | true |  | true | 25 | 51
ubuntu-20.04 | true | true | true | true |  | 26 | 52
ubuntu-20.04 | true | true | true | true | true | 30 | 56
ubuntu-22.04 |  |  |  |  |  | 7 | 37
ubuntu-22.04 |  |  |  |  | true | 10 | 40
ubuntu-22.04 |  |  |  | true |  | 12 | 42
ubuntu-22.04 |  |  |  | true | true | 15 | 45
ubuntu-22.04 |  |  | true |  |  | 7 | 37
ubuntu-22.04 |  |  | true |  | true | 10 | 40
ubuntu-22.04 |  |  | true | true |  | 12 | 42
ubuntu-22.04 |  |  | true | true | true | 15 | 45
ubuntu-22.04 |  | true |  |  |  | 8 | 38
ubuntu-22.04 |  | true |  |  | true | 11 | 41
ubuntu-22.04 |  | true |  | true |  | 13 | 43
ubuntu-22.04 |  | true |  | true | true | 16 | 46
ubuntu-22.04 |  | true | true |  |  | 8 | 38
ubuntu-22.04 |  | true | true |  | true | 11 | 41
ubuntu-22.04 |  | true | true | true |  | 13 | 43
ubuntu-22.04 |  | true | true | true | true | 16 | 46
ubuntu-22.04 | true |  |  |  |  | 18 | 48
ubuntu-22.04 | true |  |  |  | true | 21 | 51
ubuntu-22.04 | true |  |  | true |  | 24 | 54
ubuntu-22.04 | true |  |  | true | true | 26 | 56
ubuntu-22.04 | true |  | true |  |  | 18 | 48
ubuntu-22.04 | true |  | true |  | true | 21 | 51
ubuntu-22.04 | true |  | true | true |  | 24 | 54
ubuntu-22.04 | true |  | true | true | true | 26 | 56
ubuntu-22.04 | true | true |  |  |  | 20 | 50
ubuntu-22.04 | true | true |  |  | true | 22 | 52
ubuntu-22.04 | true | true |  | true |  | 25 | 55
ubuntu-22.04 | true | true |  | true | true | 28 | 58
ubuntu-22.04 | true | true | true |  |  | 20 | 50
ubuntu-22.04 | true | true | true |  | true | 22 | 52
ubuntu-22.04 | true | true | true | true |  | 25 | 55
ubuntu-22.04 | true | true | true | true | true | 28 | 58
