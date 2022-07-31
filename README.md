# Maximize available disk space for build tasks

If the available disk space on Github runners is too little for your build job, this action might be for you.
If not: please go on, there's nothing to see here.

This table shows the amount of free space you receive when using the action with the various options.

OS | Android SDKs removed | .NET SDKs removed | Haskell removed | GB freed | GB free
---|:--------------------:|:-----------------:|:---------------:|---------:|-------:
ubuntu-18.04 |  |  |  | 7 | 38
ubuntu-18.04 |  |  | true | 7 | 38
ubuntu-18.04 |  | true |  | 9 | 40
ubuntu-18.04 |  | true | true | 9 | 40
ubuntu-18.04 | true |  |  | 22 | 53
ubuntu-18.04 | true |  | true | 22 | 53
ubuntu-18.04 | true | true |  | 25 | 56
ubuntu-18.04 | true | true | true | 25 | 56
ubuntu-20.04 |  |  |  | 7 | 38
ubuntu-20.04 |  |  | true | 7 | 38
ubuntu-20.04 |  | true |  | 9 | 40
ubuntu-20.04 |  | true | true | 9 | 40
ubuntu-20.04 | true |  |  | 20 | 51
ubuntu-20.04 | true |  | true | 20 | 51
ubuntu-20.04 | true | true |  | 23 | 54
ubuntu-20.04 | true | true | true | 23 | 54
ubuntu-22.04 |  |  |  | 6 | 46
ubuntu-22.04 |  |  | true | 6 | 46
ubuntu-22.04 |  | true |  | 7 | 47
ubuntu-22.04 |  | true | true | 7 | 47
ubuntu-22.04 | true |  |  | 20 | 60
ubuntu-22.04 | true |  | true | 20 | 60
ubuntu-22.04 | true | true |  | 20 | 60
ubuntu-22.04 | true | true | true | 20 | 60
