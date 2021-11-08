<!-- 
This README describes the package. If you publish this package to pub.dev,
this README's contents appear on the landing page for your package.

For information about how to write a good package README, see the guide for
[writing package pages](https://dart.dev/guides/libraries/writing-package-pages). 

For general information about developing packages, see the Dart guide for
[creating packages](https://dart.dev/guides/libraries/create-library-packages)
and the Flutter guide for
[developing packages and plugins](https://flutter.dev/developing-packages). 
-->

A Flutter package that will help you to display a long text in a small space.

## How to use it
```dart
TextDisplay(
  text: Text(
    "Mollit aute cupidatat ullamco sit dolor id non proident veniam enim ad dolore amet culpa.",
    softWrap: false,
    overflow: TextOverflow.visible,
  ),
  waitDuration: Duration(seconds: 3),
  animationDuration: Duration(seconds: 5),
),
```
