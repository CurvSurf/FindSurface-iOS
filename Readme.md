# FindSurfaceFramework

**Curv*Surf* FindSurface™**

## Overview

This library is the implementation of the FindSurface library for iOS (Objective-C/Swift).



## F.A.Qs

### Q. How do I import this framework to my project?

refer to [this document](How-to-import-FindSurface-Framework-to-your-project.md).



### Q. Does this framework work on Mac OS?

No. It doesn't. The framework is currently compatible only for iOS 14.5+.



### Q. My app failed to build for SwiftUI preview (iOS simulator) while it succeeded to build and run on my iOS device. What's the problem?

Since the framework module has been built only for `arm64`, you app could not find the module for `x86_64-apple-ios-simulator`, which is used by the SwiftUI preview (iOS simulator).

