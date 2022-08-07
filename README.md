# Maximize available disk space for build tasks

If the available disk space on Github runners is too little for your build job, this action might be for you.
If not: please go on, there's nothing to see here.

This table shows the amount of free space you receive when using the action with the various options.

OS | Android SDKs removed | .NET SDKs removed | Haskell removed | GB freed | GB free
---|:--------------------:|:-----------------:|:---------------:|---------:|-------:
ubuntu-18.04 |  |  |  | 7 | 40
ubuntu-18.04 |  |  | true | 7 | 40
ubuntu-18.04 |  | true |  | 9 | 42
ubuntu-18.04 |  | true | true | 9 | 42
ubuntu-18.04 | true |  |  | 20 | 53
ubuntu-18.04 | true |  | true | 20 | 53
ubuntu-18.04 | true | true |  | 23 | 56
ubuntu-18.04 | true | true | true | 23 | 56
ubuntu-20.04 |  |  |  | 7 | 40
ubuntu-20.04 |  |  | true | 7 | 40
ubuntu-20.04 |  | true |  | 10 | 43
ubuntu-20.04 |  | true | true | 10 | 43
ubuntu-20.04 | true |  |  | 18 | 51
ubuntu-20.04 | true |  | true | 18 | 51
ubuntu-20.04 | true | true |  | 21 | 54
ubuntu-20.04 | true | true | true | 21 | 54
ubuntu-22.04 |  |  |  | 7 | 49
ubuntu-22.04 |  |  | true | 7 | 49
ubuntu-22.04 |  | true |  | 7 | 49
ubuntu-22.04 |  | true | true | 7 | 49
ubuntu-22.04 | true |  |  | 18 | 60
ubuntu-22.04 | true |  | true | 18 | 60
ubuntu-22.04 | true | true |  | 18 | 60
ubuntu-22.04 | true | true | true | 18 | 60
