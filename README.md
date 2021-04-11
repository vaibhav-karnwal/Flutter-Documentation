# Flutter-Documentation

## Ways to create Mobile Apps
* Native Frameworks
* Hybrid Apps
* Developing Mobile Apps using Web Apps

### In Native Apps
In case of Native Apps we use native tools as
* for developing Android device we use Java and Kotlin.
* for developing Ios we use objective C and Swift.
* Native Frameworks is used by Google and Apple thats why they gets updated with new features in regular intervals.

### Disadvantage of Native Frameworks
* When we develope native application, we have to create two seperate application for both platforms.
* Which means we have to made two code base for each platforms, which requires a lot of time and resources.
* It also cost a lot of money.

### In Web Apps
* Html, Css and Javascript used to build responsive websites for android and Ios Display.

### Hybrid Apps
* In case of Hybrid Application, we can made or build it using one or more Code Base.
* Xamarin, Cordava, Ionic, ReactNative are some frameworks used in building of Hybrid Apps but in case of Advanced features they are not compatible. So, we use flutter which have a lot of features that is lacking in other frameworks.

## About Flutter

Flutter is Google's SDK for crafting beautiful, fast user experiences for
mobile, web, and desktop from a single codebase. Flutter works with existing
code and is used by developers and organizations around the world. It is free
and open source.
We think Flutter will help you create beautiful, fast apps, with a productive,
extensible and open development model.
* It is a Single Code Base(Dart) which means we only have to write our app once for multiple devices.


### Why Use Flutter?

* Only i code base.
* Good layout methodology borrowed from responsive web
* Very smooth and quick experience when running apps
* Works well with Firebase as a backend.
* Uses Dart, Which is a really easy language to pick up
* Uses Material Design out of the box.

### How Flutter Different ?

* Flutter used Dart as a language so we basically develope flutter using Dart
* Dart is strongly typed object oriented language developed by Google
* Dart has very fast development cycle because it supports JIT(Just in Time) Compilation which is a kind of compilation that results in faster compilation of code during application developement that is whenever we make any changes to our code, we can able to reload our application in our device very fastly in no time. It is called as a Heart reload of the Application.
* When app is ready to launch in market Dart supports AOT(Ahead of Time) Compilation.
* In this type of compilation while runnin application on device, it is much much faster , so for end user it provides seemless user experience.
* So we can say for developers, JIT helps in faster app development and after development for app users, AOT provides faster application execution.
* So as flutter uses Dart so it made flutter different from other frameworks and helps in faster development.
* Flutter provides similar user experience compared to Native Apps like Android and IOS.
* Maintaing code for user is very very easy due to having single code base property.

## Flutter Downloading Procedure

* Go to https://flutter.dev/get-started/ [Install Flutter](https://flutter.dev/get-started/)
* Then Click on Window/Mac/IOS 
* Then scroll a little down and You will see a new release flutter_windows-stable.zip SDK.
* Click on it and downloading will Start

For announcements about new releases and breaking changes, follow the
[flutter-announce@googlegroups.com](https://groups.google.com/forum/#!forum/flutter-announce)
mailing list or see the
[breaking changes](https://flutter.dev/docs/release/breaking-changes) page.

### Beautiful user experiences

We want to enable designers to deliver their full creative vision without being
forced to water it down due to limitations of the underlying framework.
Flutter's [layered architecture] gives you control over every pixel on the
screen and its powerful compositing capabilities let you overlay and animate
graphics, video, text, and controls without limitation. Flutter includes a full
[set of widgets][widget catalog] that deliver pixel-perfect experiences on both
iOS and Android.

![Reflectly hero image][Reflectly hero image]

### Fast results

Flutter is fast. It's powered by the same hardware-accelerated 2D graphics
library that underpins Chrome and Android: [Skia]. We architected Flutter to
support glitch-free, jank-free graphics at the native speed of your device.
Flutter code is powered by the world-class [Dart platform], which enables
compilation to 32-bit and 64-bit ARM machine code for iOS and Android, as well
as JavaScript for the web and Intel x64 for desktop devices.

### Productive development

Flutter offers stateful hot reload, allowing you to make changes to your code
and see the results instantly without restarting your app or losing its state.

[![Hot reload animation][]][Hot reload]

### Extensible and open model

Flutter works with any development tool (or none at all) but includes editor
plug-ins for both [Visual Studio Code] and [IntelliJ / Android Studio]. Flutter
provides [thousands of packages][Flutter packages] to speed your development,
regardless of your target platform. And accessing other native code is easy,
with support for both [FFI] and [platform-specific APIs][platform channels].


## Lets Start

As you know App is build by using lots of widgets or we can say .... widget are the backbone of flutter App. Here we use Widget as a child, root, siblings... Its a tree of widgets.

### MaterialApp Widget

Material App is a pre-defined class used in the flutter. It contains widgets that are used for the material design of an application. It contains title as a first parameter and second it contains home widget which helps it to use again the material widget.


### Home Property

 <img src="https://github.com/vaibhav-karnwal/Flutter-Documentation/blob/main/img/home.png" alt="home" width="450" height="250"/>

This home property shows what is gona be on the home screen. So, we can give as a paramenter, a calling function or a simple string using Text Widget.


Flutter is a fully open-source project, and we welcome contributions.
Information on how to get started can be found at our
[contributor guide](CONTRIBUTING.md).



[Flutter logo]: https://raw.githubusercontent.com/flutter/website/master/src/_assets/image/flutter-lockup-bg.jpg
[flutter.dev]: https://flutter.dev
[Build Status - Cirrus]: https://api.cirrus-ci.com/github/flutter/flutter.svg
[Build status]: https://cirrus-ci.com/github/flutter/flutter/master
[Discord instructions]: https://github.com/flutter/flutter/wiki/Chat
[Discord badge]: https://img.shields.io/discord/608014603317936148
[Twitter handle]: https://img.shields.io/twitter/follow/flutterdev.svg?style=social&label=Follow
[Twitter badge]: https://twitter.com/intent/follow?screen_name=flutterdev
[layered architecture]: https://flutter.dev/docs/resources/inside-flutter
[widget catalog]: https://flutter.dev/widgets/
[Reflectly hero image]: https://github.com/flutter/website/blob/master/src/images/homepage/reflectly-hero-600px.png
[Skia]: https://skia.org/
[Dart platform]: https://dart.dev/
[Dart platform diagram]: https://github.com/flutter/website/blob/master/src/images/homepage/dart-diagram-small.png
[Hot reload animation]: https://raw.githubusercontent.com/flutter/website/master/src/_assets/image/tools/android-studio/hot-reload.gif
[Hot reload]: https://flutter.dev/docs/development/tools/hot-reload
[Visual Studio Code]: https://marketplace.visualstudio.com/items?itemName=Dart-Code.flutter
[IntelliJ / Android Studio]: https://plugins.jetbrains.com/plugin/9212-flutter
[Flutter packages]: https://pub.dev/flutter
[FFI]: https://flutter.dev/docs/development/platform-integration/c-interop
[platform channels]: https://flutter.dev/docs/development/platform-integration/platform-channels
[interop example]: https://github.com/flutter/flutter/tree/master/examples/platform_channel
