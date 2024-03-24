# Maximize available disk space for build tasks

If the available disk space on Github runners is too little for your build job, this action might be for you.
If not: please go on, there's nothing to see here.

This table shows the amount of free space you receive when using the action with the various options.

OS | Android SDKs removed | .NET SDKs removed | Haskell removed | CodeQL Removed | Cached Docker Images Removed | GB freed | GB free | Elapsed Time (seconds) |
---|:--------------------:|:-----------------:|:---------------:|:--------------:|:----------------------------:|:--------:|:-------:|:----------------------:|
ubuntu-20.04 |  |  |  |  |  | 62 | 82 | 5
ubuntu-20.04 |  |  |  |  | true | 65 | 85 | 6
ubuntu-20.04 |  |  |  | true |  | 67 | 87 | 2
ubuntu-20.04 |  |  |  | true | true | 70 | 90 | 6
ubuntu-20.04 |  |  | true |  |  | 62 | 82 | 2
ubuntu-20.04 |  |  | true |  | true | 66 | 86 | 6
ubuntu-20.04 |  |  | true | true |  | 67 | 87 | 3
ubuntu-20.04 |  |  | true | true | true | 70 | 90 | 48
ubuntu-20.04 |  | true |  |  |  | 64 | 84 | 4
ubuntu-20.04 |  | true |  |  | true | 67 | 87 | 7
ubuntu-20.04 |  | true |  | true |  | 69 | 89 | 4
ubuntu-20.04 |  | true |  | true | true | 72 | 92 | 6
ubuntu-20.04 |  | true | true |  |  | 64 | 84 | 3
ubuntu-20.04 |  | true | true |  | true | 67 | 87 | 54
ubuntu-20.04 |  | true | true | true |  | 69 | 89 | 4
ubuntu-20.04 |  | true | true | true | true | 72 | 92 | 31
ubuntu-20.04 | true |  |  |  |  | 71 | 91 | 51
ubuntu-20.04 | true |  |  |  | true | 74 | 94 | 109
ubuntu-20.04 | true |  |  | true |  | 76 | 96 | 48
ubuntu-20.04 | true |  |  | true | true | 79 | 99 | 95
ubuntu-20.04 | true |  | true |  |  | 71 | 91 | 40
ubuntu-20.04 | true |  | true |  | true | 74 | 94 | 42
ubuntu-20.04 | true |  | true | true |  | 76 | 96 | 7
ubuntu-20.04 | true |  | true | true | true | 79 | 99 | 95
ubuntu-20.04 | true | true |  |  |  | 73 | 93 | 45
ubuntu-20.04 | true | true |  |  | true | 76 | 96 | 122
ubuntu-20.04 | true | true |  | true |  | 77 | 97 | 13
ubuntu-20.04 | true | true |  | true | true | 81 | 101 | 33
ubuntu-20.04 | true | true | true |  |  | 73 | 93 | 7
ubuntu-20.04 | true | true | true |  | true | 76 | 96 | 10
ubuntu-20.04 | true | true | true | true |  | 77 | 97 | 10
ubuntu-20.04 | true | true | true | true | true | 81 | 101 | 17
ubuntu-22.04 |  |  |  |  |  | 62 | 83 | 2
ubuntu-22.04 |  |  |  |  | true | 65 | 86 | 6
ubuntu-22.04 |  |  |  | true |  | 67 | 88 | 4
ubuntu-22.04 |  |  |  | true | true | 70 | 91 | 9
ubuntu-22.04 |  |  | true |  |  | 62 | 83 | 2
ubuntu-22.04 |  |  | true |  | true | 65 | 86 | 7
ubuntu-22.04 |  |  | true | true |  | 67 | 88 | 3
ubuntu-22.04 |  |  | true | true | true | 70 | 91 | 8
ubuntu-22.04 |  | true |  |  |  | 64 | 85 | 5
ubuntu-22.04 |  | true |  |  | true | 67 | 88 | 8
ubuntu-22.04 |  | true |  | true |  | 69 | 90 | 5
ubuntu-22.04 |  | true |  | true | true | 72 | 93 | 70
ubuntu-22.04 |  | true | true |  |  | 64 | 85 | 4
ubuntu-22.04 |  | true | true |  | true | 67 | 88 | 36
ubuntu-22.04 |  | true | true | true |  | 69 | 90 | 4
ubuntu-22.04 |  | true | true | true | true | 72 | 93 | 9
ubuntu-22.04 | true |  |  |  |  | 71 | 92 | 59
ubuntu-22.04 | true |  |  |  | true | 74 | 95 | 68
ubuntu-22.04 | true |  |  | true |  | 76 | 97 | 15
ubuntu-22.04 | true |  |  | true | true | 79 | 100 | 108
ubuntu-22.04 | true |  | true |  |  | 71 | 92 | 15
ubuntu-22.04 | true |  | true |  | true | 74 | 95 | 99
ubuntu-22.04 | true |  | true | true |  | 76 | 97 | 13
ubuntu-22.04 | true |  | true | true | true | 79 | 100 | 107
ubuntu-22.04 | true | true |  |  |  | 72 | 93 | 11
ubuntu-22.04 | true | true |  |  | true | 76 | 97 | 109
ubuntu-22.04 | true | true |  | true |  | 77 | 98 | 63
ubuntu-22.04 | true | true |  | true | true | 80 | 101 | 16
ubuntu-22.04 | true | true | true |  |  | 73 | 94 | 69
ubuntu-22.04 | true | true | true |  | true | 76 | 97 | 21
ubuntu-22.04 | true | true | true | true |  | 77 | 98 | 15
ubuntu-22.04 | true | true | true | true | true | 81 | 102 | 63
