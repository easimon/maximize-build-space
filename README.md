# Maximize available disk space for build tasks

If the available disk space on Github runners is too little for your build job, this action might be for you.
If not: please go on, there's nothing to see here.

This table shows the amount of free space you receive when using the action with the various options.

OS | Android SDKs removed | .NET SDKs removed | Haskell removed | GB freed | GB free
---|:--------------------:|:-----------------:|:---------------:|---------:|-------:
ubuntu-18.04 |  |  |  | 7 | 29
ubuntu-18.04 |  |  | true | 9 | 31
ubuntu-18.04 |  | true |  | 31 | 53
ubuntu-18.04 |  | true | true | 33 | 55
ubuntu-18.04 | true |  |  | 17 | 39
ubuntu-18.04 | true |  | true | 19 | 41
ubuntu-18.04 | true | true |  | 41 | 63
ubuntu-18.04 | true | true | true | 42 | 64
ubuntu-20.04 |  |  |  | 7 | 24
ubuntu-20.04 |  |  | true | 9 | 26
ubuntu-20.04 |  | true |  | 31 | 48
ubuntu-20.04 |  | true | true | 33 | 50
ubuntu-20.04 | true |  |  | 18 | 35
ubuntu-20.04 | true |  | true | 20 | 37
ubuntu-20.04 | true | true |  | 42 | 59
ubuntu-20.04 | true | true | true | 44 | 61
