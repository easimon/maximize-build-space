# Maximize available disk space for build tasks

If the available disk space on Github runners is too little for your build job, this action might be for you.
If not: please go on, there's nothing to see here.

This table shows the amount of free space you receive when using the action with the various options.

OS | Android SDKs removed | .NET SDKs removed | Haskell removed | GB freed | GB free
---|:--------------------:|:-----------------:|:---------------:|---------:|-------:
ubuntu-18.04 |  |  |  | 7 | 39
ubuntu-18.04 |  |  | true | 7 | 39
ubuntu-18.04 |  | true |  | 9 | 41
ubuntu-18.04 |  | true | true | 9 | 41
ubuntu-18.04 | true |  |  | 20 | 52
ubuntu-18.04 | true |  | true | 20 | 52
ubuntu-18.04 | true | true |  | 23 | 55
ubuntu-18.04 | true | true | true | 23 | 55
ubuntu-20.04 |  |  |  | 7 | 36
ubuntu-20.04 |  |  | true | 7 | 36
ubuntu-20.04 |  | true |  | 10 | 39
ubuntu-20.04 |  | true | true | 10 | 39
ubuntu-20.04 | true |  |  | 18 | 47
ubuntu-20.04 | true |  | true | 18 | 47
ubuntu-20.04 | true | true |  | 21 | 50
ubuntu-20.04 | true | true | true | 21 | 50
ubuntu-22.04 |  |  |  | 6 | 40
ubuntu-22.04 |  |  | true | 6 | 40
ubuntu-22.04 |  | true |  | 7 | 41
ubuntu-22.04 |  | true | true | 7 | 41
ubuntu-22.04 | true |  |  | 18 | 52
ubuntu-22.04 | true |  | true | 18 | 52
ubuntu-22.04 | true | true |  | 19 | 53
ubuntu-22.04 | true | true | true | 19 | 53
