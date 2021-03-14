# Maximize available disk space for build tasks

If the available disk space on Github runners is too little for your build job, this action might be for you.
If not: please go on, there's nothing to see here.

This table shows the amount of free space you receive when using the action with the various options.

OS | Android SDKs removed | .NET SDKs removed | Haskell removed | Space freed | Space free
---|----------------------|-------------------|-----------------|-------------|-----------
ubuntu-18.04 |  |  |  | 7 | 29
ubuntu-18.04 |  |  | true | 9 | 31
ubuntu-18.04 |  | true |  | 29 | 51
ubuntu-18.04 |  | true | true | 31 | 53
ubuntu-18.04 | true |  |  | 17 | 39
ubuntu-18.04 | true |  | true | 18 | 40
ubuntu-18.04 | true | true |  | 39 | 61
ubuntu-18.04 | true | true | true | 40 | 62
ubuntu-20.04 |  |  |  | 7 | 26
ubuntu-20.04 |  |  | true | 9 | 28
ubuntu-20.04 |  | true |  | 29 | 48
ubuntu-20.04 |  | true | true | 31 | 50
ubuntu-20.04 | true |  |  | 18 | 37
ubuntu-20.04 | true |  | true | 20 | 39
ubuntu-20.04 | true | true |  | 40 | 59
ubuntu-20.04 | true | true | true | 42 | 61
