# FindSurface-iOS

**Curv*Surf* FindSurface™ library package for iOS (Swift)**

## Overview

**FindSurface-iOS** is a Swift package of FindSurface™ library, of which interface is modified to allow you to use its functionalities.

> **NOTE**: `FindSurfaceFramework` (including `FindSurface-iOS`) provides its functionality for non-commercial purposes within Apple iPhone/iPad devices. It is internally limited to process input point clouds of **500k points or less**. For commercial uses or use cases that require more than 500k points, please contact to support@curvsurf.com.


### What's new in the package compared to the old framework?

Thanks to Swift Package Manager, you no longer have to specify the framework path. Just simply add the package to your project. The package exposes a wrapper class of FindSurface context, which gives you a clue on how to invoke the FindSurface APIs. Feel free to use it or to customize it for your own needs.

As mentioned above, the framework enclosed in the package now have a limitation on the number of input point clouds.


## Samples

The followings are sample project repositories to help you get started to make your application with the package (more samples are to be added in the future):

- [BasicDemo (Swift)](https://github.com/CurvSurf/FindSurface-BasicDemo-iOS)

- [GUIDemo (Swift)](https://github.com/CurvSurf/FindSurface-GUIDemo-iOS)

- [ARDemo (Swift, SceneKit)](https://github.com/CurvSurf/FindSurface-SceneKit-ARDemo-iOS)


## How to install

### Adding this package as a Dependency

You can import this package by adding the following line to the dependencies in your `Package.swift` file:

````
dependencies: [
    ...
    .package(utl: "https://github.com/CurvSurf/FindSurface-iOS", from: "1.0.3")
],
targets: [
    .target(name: "<target>", dependencies: [
        ...
        "FindSurface-iOS"
    ]),
    ...
]
````

Then, add `import FindSurface_iOS` (note that it is not hyphenated, but underscored in the middle of the words.)

### Using the XCFramework without the wrapper

This package is a wrapper containing the iOS version (including the simulator) of the FindSurface XCFramework. You can also refer to the source code of this package to use the framework directly. In that case, import `FindSurfaceFramework` instead.


## About License

You may use the source code of this package freely under MIT license, as the license file stated, except for `FindSurfaceFramework`, which is the core of the package.

About the framework, refer to the following statement:

````
Copyright (c) 2024 CurvSurf, Inc. All rights reserved.

The framework `FindSurface-iphoneOS.xcframework` and `FindSurfaceFramework.framework`'s 
ownership is solely on CurvSurf, Inc. and anyone can use it for non-commercial purposes. 
Contact to support@curvsurf.com for commercial use of the library.
````

