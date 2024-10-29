# FindSurfaceFramework for iOS

**Curv*Surf* FindSurface™**

## Overview

This library is the implementation of the **FindSurface** library for **iOS (Objective-C/Swift).**



## Samples

These are the samples to help you get started to make your application with the framework (more samples are to be added in the future):

- [BasicDemo (Swift)](https://github.com/CurvSurf/FindSurface-BasicDemo-iOS)

- [GUIDemo (Swift)](https://github.com/CurvSurf/FindSurface-GUIDemo-iOS)

- [ARDemo (Swift, SceneKit)](https://github.com/CurvSurf/FindSurface-SceneKit-ARDemo-iOS)

## F.A.Qs

### Q. How do I import this framework to my project?

refer to [this document](How-to-import-FindSurface-Framework-to-your-project.md).



### Q. Does this framework work on Mac OS?

No. It doesn't. The framework is currently compatible only for iOS 14.5+.



### Q. My app failed to build for SwiftUI preview (iOS simulator) while it succeeded to build and run on my iOS device. What's the problem?

Since the framework module has been built only for `arm64`, your app could not find the module for `x86_64-apple-ios-simulator`, which is used by the SwiftUI preview (iOS simulator).

## ---

(c) Copyright 2021 CurvSurf, Inc. All rights reserved.

This library's ownership is solely on CurvSurf, Inc. and anyone can use it for non-commercial purposes. Contact to support@curvsurf.com for commercial use of the library.

