# Maximize available disk space for build tasks

If the available disk space on Github runners is too little for your build job, this action might be for you.
If not: please go on, there's nothing to see here.

This table shows the amount of free space you receive when using the action with the various options.

OS | Android SDKs removed | .NET SDKs removed | Haskell removed | GB freed | GB free
---|:--------------------:|:-----------------:|:---------------:|---------:|-------:
ubuntu-18.04 |  |  |  | 7 | 37
ubuntu-18.04 |  |  | true | 7 | 37
ubuntu-18.04 |  | true |  | 10 | 40
ubuntu-18.04 |  | true | true | 10 | 40
ubuntu-18.04 | true |  |  | 20 | 50
ubuntu-18.04 | true |  | true | 20 | 50
ubuntu-18.04 | true | true |  | 23 | 53
ubuntu-18.04 | true | true | true | 23 | 53
ubuntu-20.04 |  |  |  | 7 | 37
ubuntu-20.04 |  |  | true | 7 | 37
ubuntu-20.04 |  | true |  | 10 | 40
ubuntu-20.04 |  | true | true | 10 | 40
ubuntu-20.04 | true |  |  | 18 | 48
ubuntu-20.04 | true |  | true | 18 | 48
ubuntu-20.04 | true | true |  | 21 | 51
ubuntu-20.04 | true | true | true | 21 | 51
ubuntu-22.04 |  |  |  | 6 | 42
ubuntu-22.04 |  |  | true | 6 | 42
ubuntu-22.04 |  | true |  | 7 | 43
ubuntu-22.04 |  | true | true | 7 | 43
ubuntu-22.04 | true |  |  | 18 | 54
ubuntu-22.04 | true |  | true | 18 | 54
ubuntu-22.04 | true | true |  | 19 | 55
ubuntu-22.04 | true | true | true | 19 | 55
