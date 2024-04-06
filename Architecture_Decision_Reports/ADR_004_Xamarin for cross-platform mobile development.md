# Title: Use Xamarin for cross-platform mobile development

## Status

APPROVED

## Context

We are developing a mobile application that needs to run on both Android and iOS devices. We want to minimize the development time and cost, while ensuring a high-quality user experience and performance.

## Decision

* We decided to use Xamarin, an open-source framework from Microsoft that allows building cross-platform apps using a single C# and .NET codebase. 
* Xamarin extends the .NET development platform with libraries used specifically for building apps for Android, iOS, watchOS, macOS, Tizen and Windows.


## Consequences

Using Xamarin has the following benefits:

* Code sharing: We can share more than 90% of code across major platforms, which leads to faster mobile application development and easier maintenance1.
* Native performance and UI: Xamarin uses platform-specific UI controls and leverages native hardware acceleration, which ensures a smooth and responsive user interface and optimal performance2.
* Support and ecosystem: Xamarin is backed by Microsoft and has a large and active community of developers. It also integrates well with other Microsoft products and services, such as Visual Studio, Azure, and App Center4. Xamarin provides comprehensive documentation, tutorials, samples, forums, and blogs to help us with our development process5.

Using Xamarin also has some drawbacks:

* Larger app size: Xamarin apps tend to have larger file sizes than native apps, because they include the Mono runtime and some additional libraries6. This can affect the app download time and storage space on the device.
* Learning curve: Although Xamarin uses C# and .NET, which are familiar to us, we still need to learn some platform-specific concepts and APIs to build effective cross-platform apps. We also need to use different IDEs depending on the platform: Visual Studio for Windows and Visual Studio for Mac or Rider for macOS.

[Home Page](../README.md) | [ADR Home Page](../Architecture_Decision_Reports)