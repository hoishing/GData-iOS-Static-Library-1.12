# GData iOS Static Library

![objc] ![mit]

> iOS static library of Google Data APIs Objective-C Client Library

🔗 [source code]

It can be used in both simulator and devices. Tested with Xcode 4.1.1 on Mac OS X 10.7.1

[mit]: https://img.shields.io/github/license/hoishing/GData-iOS-Static-Library-1.12
[objc]: https://img.shields.io/badge/lang-objective--c-blue
[source code]: https://github.com/hoishing/GData-iOS-Static-Library-1.12

## How to use

1. Add all files (header files and the .a binary image) into your Xcode project
2. In your target -> Build Settings, set `/usr/include/libxml2` in Header Search Paths
3. In your target -> Build Phases -> Link Binary With Libraries, add `libxml2.dylib`
4. To use the `gdata` classes, just add the following line in your header file: `#import "GData.h"`
5. Done

## Questions?

Open a [github issue] or ping me on [Twitter ![twitter-icon]][Twitter]

[github issue]: https://github.com/hoishing/GData-iOS-Static-Library-1.12/issues
[Twitter]: https://twitter.com/intent/tweet?text=https://github.com/hoishing/GData-iOS-Static-Library-1.12/%20%0D@hoishing
[twitter-icon]: https://api.iconify.design/logos/twitter.svg?width=20
