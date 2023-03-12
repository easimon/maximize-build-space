# Maximize available disk space for build tasks

If the available disk space on Github runners is too little for your build job, this action might be for you.
If not: please go on, there's nothing to see here.

This table shows the amount of free space you receive when using the action with the various options.

OS | Android SDKs removed | .NET SDKs removed | Haskell removed | GB freed | GB free
---|:--------------------:|:-----------------:|:---------------:|---------:|-------:
ubuntu-18.04 |  |  |  | 7 | 34
ubuntu-18.04 |  |  | true | 7 | 34
ubuntu-18.04 |  | true |  | 9 | 36
ubuntu-18.04 |  | true | true | 9 | 36
ubuntu-18.04 | true |  |  | 21 | 48
ubuntu-18.04 | true |  | true | 21 | 48
ubuntu-18.04 | true | true |  | 22 | 49
ubuntu-18.04 | true | true | true | 22 | 49
ubuntu-20.04 |  |  |  | 7 | 33
ubuntu-20.04 |  |  | true | 7 | 33
ubuntu-20.04 |  | true |  | 9 | 35
ubuntu-20.04 |  | true | true | 9 | 35
ubuntu-20.04 | true |  |  | 19 | 45
ubuntu-20.04 | true |  | true | 19 | 45
ubuntu-20.04 | true | true |  | 21 | 47
ubuntu-20.04 | true | true | true | 21 | 47
ubuntu-22.04 |  |  |  | 7 | 36
ubuntu-22.04 |  |  | true | 7 | 36
ubuntu-22.04 |  | true |  | 9 | 38
ubuntu-22.04 |  | true | true | 9 | 38
ubuntu-22.04 | true |  |  | 19 | 48
ubuntu-22.04 | true |  | true | 19 | 48
ubuntu-22.04 | true | true |  | 20 | 49
ubuntu-22.04 | true | true | true | 20 | 49
