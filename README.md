# Maximize available disk space for build tasks

If the available disk space on Github runners is too little for your build job, this action might be for you.
If not: please go on, there's nothing to see here.

This table shows the amount of free space you receive when using the action with the various options.

OS | Android SDKs removed | .NET SDKs removed | Haskell removed | GB freed | GB free
---|:--------------------:|:-----------------:|:---------------:|---------:|-------:
ubuntu-18.04 |  |  |  | 7 | 30
ubuntu-18.04 |  |  | true | 9 | 32
ubuntu-18.04 |  | true |  | 31 | 54
ubuntu-18.04 |  | true | true | 33 | 56
ubuntu-18.04 | true |  |  | 17 | 40
ubuntu-18.04 | true |  | true | 19 | 42
ubuntu-18.04 | true | true |  | 41 | 64
ubuntu-18.04 | true | true | true | 42 | 65
ubuntu-20.04 |  |  |  | 7 | 26
ubuntu-20.04 |  |  | true | 9 | 28
ubuntu-20.04 |  | true |  | 30 | 49
ubuntu-20.04 |  | true | true | 32 | 51
ubuntu-20.04 | true |  |  | 18 | 37
ubuntu-20.04 | true |  | true | 20 | 39
ubuntu-20.04 | true | true |  | 41 | 60
ubuntu-20.04 | true | true | true | 43 | 62
