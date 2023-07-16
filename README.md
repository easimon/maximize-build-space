# Maximize available disk space for build tasks

If the available disk space on Github runners is too little for your build job, this action might be for you.
If not: please go on, there's nothing to see here.

This table shows the amount of free space you receive when using the action with the various options.

OS | Android SDKs removed | .NET SDKs removed | Haskell removed | CodeQL Removed | Cached Docker Images Removed | GB freed | GB free
---|:--------------------:|:-----------------:|:---------------:|:--------------:|:----------------------------:|---------:|-------:
ubuntu-20.04 |  |  |  |  |  | 7 | 29
ubuntu-20.04 |  |  |  |  | true | 12 | 34
ubuntu-20.04 |  |  |  | true |  | 14 | 35
ubuntu-20.04 |  |  |  | true | true | 19 | 41
ubuntu-20.04 |  |  | true |  |  | 7 | 29
ubuntu-20.04 |  |  | true |  | true | 12 | 34
ubuntu-20.04 |  |  | true | true |  | 14 | 36
ubuntu-20.04 |  |  | true | true | true | 19 | 41
ubuntu-20.04 |  | true |  |  |  | 9 | 31
ubuntu-20.04 |  | true |  |  | true | 15 | 36
ubuntu-20.04 |  | true |  | true |  | 15 | 37
ubuntu-20.04 |  | true |  | true | true | 21 | 43
ubuntu-20.04 |  | true | true |  |  | 9 | 31
ubuntu-20.04 |  | true | true |  | true | 14 | 36
ubuntu-20.04 |  | true | true | true |  | 16 | 37
ubuntu-20.04 |  | true | true | true | true | 21 | 43
ubuntu-20.04 | true |  |  |  |  | 19 | 40
ubuntu-20.04 | true |  |  |  | true | 25 | 46
ubuntu-20.04 | true |  |  | true |  | 26 | 48
ubuntu-20.04 | true |  |  | true | true | 31 | 53
ubuntu-20.04 | true |  | true |  |  | 19 | 41
ubuntu-20.04 | true |  | true |  | true | 24 | 46
ubuntu-20.04 | true |  | true | true |  | 26 | 48
ubuntu-20.04 | true |  | true | true | true | 31 | 52
ubuntu-20.04 | true | true |  |  |  | 21 | 43
ubuntu-20.04 | true | true |  |  | true | 27 | 48
ubuntu-20.04 | true | true |  | true |  | 27 | 49
ubuntu-20.04 | true | true |  | true | true | 33 | 55
ubuntu-20.04 | true | true | true |  |  | 21 | 44
ubuntu-20.04 | true | true | true |  | true | 26 | 48
ubuntu-20.04 | true | true | true | true |  | 27 | 49
ubuntu-20.04 | true | true | true | true | true | 33 | 55
ubuntu-22.04 |  |  |  |  |  | 7 | 32
ubuntu-22.04 |  |  |  |  | true | 11 | 36
ubuntu-22.04 |  |  |  | true |  | 13 | 38
ubuntu-22.04 |  |  |  | true | true | 18 | 43
ubuntu-22.04 |  |  | true |  |  | 7 | 32
ubuntu-22.04 |  |  | true |  | true | 11 | 36
ubuntu-22.04 |  |  | true | true |  | 13 | 38
ubuntu-22.04 |  |  | true | true | true | 18 | 42
ubuntu-22.04 |  | true |  |  |  | 8 | 33
ubuntu-22.04 |  | true |  |  | true | 13 | 38
ubuntu-22.04 |  | true |  | true |  | 15 | 40
ubuntu-22.04 |  | true |  | true | true | 20 | 45
ubuntu-22.04 |  | true | true |  |  | 8 | 33
ubuntu-22.04 |  | true | true |  | true | 13 | 38
ubuntu-22.04 |  | true | true | true |  | 15 | 40
ubuntu-22.04 |  | true | true | true | true | 20 | 45
ubuntu-22.04 | true |  |  |  |  | 19 | 44
ubuntu-22.04 | true |  |  |  | true | 23 | 48
ubuntu-22.04 | true |  |  | true |  | 25 | 50
ubuntu-22.04 | true |  |  | true | true | 30 | 55
ubuntu-22.04 | true |  | true |  |  | 19 | 44
ubuntu-22.04 | true |  | true |  | true | 23 | 48
ubuntu-22.04 | true |  | true | true |  | 25 | 50
ubuntu-22.04 | true |  | true | true | true | 30 | 55
ubuntu-22.04 | true | true |  |  |  | 20 | 45
ubuntu-22.04 | true | true |  |  | true | 25 | 50
ubuntu-22.04 | true | true |  | true |  | 27 | 52
ubuntu-22.04 | true | true |  | true | true | 32 | 56
ubuntu-22.04 | true | true | true |  |  | 21 | 45
ubuntu-22.04 | true | true | true |  | true | 25 | 50
ubuntu-22.04 | true | true | true | true |  | 27 | 52
ubuntu-22.04 | true | true | true | true | true | 32 | 57
