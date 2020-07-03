---
title: List of state management approaches
description: A list of different approaches to managing state.
prev:
  title: Simple app state management
  path: /docs/development/data-and-backend/state-mgmt/simple
---

State management is a complex topic.
If you feel that some of your questions haven't been answered,
or that the approach described on these pages
is not viable for your use cases, you are probably right.

Learn more at the following links,
many of which have been contributed by the Flutter community:

## General overview

* [This very section], for those of you who arrived
  directly to this _Options_ page and missed the previous pages
* [Build reactive mobile apps with Flutter],
  a video from Google I/O 2018, and an [accompanying article]
* [Flutter Architecture Samples], by Brian Egan

## setState

* [Adding interactivity to your Flutter app], a Flutter tutorial
* [Basic state management in Google Flutter], by Agung Surya

## InheritedWidget &amp; InheritedModel

* [InheritedWidget docs]
* [Managing Flutter Application State With InheritedWidgets],
  by Hans Muller
* [Inheriting Widgets], by Mehmet Fidanboylu
* [Using Flutter Inherited Widgets Effectively], by Eric Windmill
* [Widget - State - Context - InheritedWidget], by Didier Bolelens

## Provider &amp; Scoped Model

* [Provider package]
* [Scoped Model package]
* [Simple app state management], the previous page in this section
* [You might not need Redux: The Flutter edition], by Ryan Edge
* [Managing state with the scoped model pattern in Dart's Flutter framework],
  a video by Tensor Programming
* [Flutter: Inherited Widget and Scoped Model Explained, part 1],
  a video by MTechViral
* [Flutter state management&mdash;scoped model]
* [Making sense of all those Flutter Providers]

## Redux

* [Animation Management with Redux and Flutter],
  a video from DartConf 2018 [Accompanying article on Medium]
* [Flutter Redux package]
* [Introduction to Redux in Flutter], by Xavi Rigau
* [Flutter + Redux&mdash;How to make a shopping list app],
  by Paulina Szklarska on Hackernoon
* [Building a TODO application (CRUD) in Flutter with Redux&mdash;Part 1],
  a video by Tensor Programming
* [Flutter Redux Thunk, an example], by Jack Wong
* [Building a (large) Flutter app with Redux], by Hillel Coren
* [Fish-Redux - An assembled flutter application framework based on Redux],
  by Alibaba
* [Async Redux - Redux without boilerplate. Allows for both sync and async reducers],
  by Marcelo Glasberg
* [Flutter meets Redux: The Redux way of managing Flutter applications state], by Amir Ghezelbash

## BLoC / Rx

* [Architect your Flutter project using BLoC pattern],
  by Sagar Suri
* [BloC Library], by Felix Angelov
* [Reactive Programming - Streams - BLoC - Practical Use Cases],
  by Didier Boelens

## MobX

* [MobX.dart, Hassle free state-management for your Dart and Flutter apps]
* [Getting started with MobX.dart]
* [Flutter: State Management with Mobx], a video by Paul Halliday


[Adding interactivity to your Flutter app]: /docs/development/ui/interactive
[accompanying article]: {{site.flutter-medium}}/build-reactive-mobile-apps-in-flutter-companion-article-13950959e381
[Accompanying article on Medium]: {{site.flutter-medium}}/animation-management-with-flutter-and-flux-redux-94729e6585fa
[Animation Management with Redux and Flutter]: https://www.youtube.com/watch?v=9ZkLtr0Fbgk
[Architect your Flutter project using BLoC pattern]: {{site.medium}}/flutterpub/architecting-your-flutter-project-bd04e144a8f1
[Async Redux - Redux without boilerplate. Allows for both sync and async reducers]: {{site.pub}}/packages/async_redux/
[Basic state management in Google Flutter]: {{site.medium}}/@agungsurya/basic-state-management-in-google-flutter-6ee73608f96d
[Flutter meets Redux: The Redux way of managing Flutter applications state]: https://medium.com/@thisisamir98/flutter-meets-redux-the-redux-way-of-managing-flutter-applications-state-f60ef693b509
[BloC Library]: https://felangel.github.io/bloc
[Build reactive mobile apps with Flutter]: https://www.youtube.com/watch?v=RS36gBEp8OI&feature=youtu.be
[Building a (large) Flutter app with Redux]: https://hillelcoren.com/2018/06/01/building-a-large-flutter-app-with-redux/
[Building a TODO application (CRUD) in Flutter with Redux&mdash;Part 1]: https://www.youtube.com/watch?v=Wj216eSBBWs
[Fish-Redux - An assembled flutter application framework based on Redux]: {{site.github}}/alibaba/fish-redux/
[Flutter Architecture Samples]: https://fluttersamples.com/
[Flutter: Inherited Widget and Scoped Model Explained, part 1]: https://www.youtube.com/watch?v=j-27MZwRbFw
[Flutter: State Management with Mobx]: https://www.youtube.com/watch?v=p-MUBLOEkCs
[Flutter Redux package]: {{site.pub-pkg}}/flutter_redux
[Flutter Redux Thunk, an example]: {{site.medium}}/flutterpub/flutter-redux-thunk-27c2f2b80a3b
[Flutter + Redux&mdash;How to make a shopping list app]: https://hackernoon.com/flutter-redux-how-to-make-shopping-list-app-1cd315e79b65
[Flutter state management&mdash;scoped model]: https://www.youtube.com/watch?v=Oql5bU-Uvso
[Getting started with MobX.dart]: https://mobx.netlify.com/getting-started
[InheritedWidget docs]: {{site.api}}/flutter/widgets/InheritedWidget-class.html
[Inheriting Widgets]: {{site.medium}}/@mehmetf_71205/inheriting-widgets-b7ac56dbbeb1
[Introduction to Redux in Flutter]: https://blog.novoda.com/introduction-to-redux-in-flutter/
[Making sense of all those Flutter Providers]: {{site.medium}}/flutter-community/making-sense-all-of-those-flutter-providers-e842e18f45dd
[Managing Flutter Application State With InheritedWidgets]: {{site.flutter-medium}}/managing-flutter-application-state-with-inheritedwidgets-1140452befe1
[Managing state with the scoped model pattern in Dart's Flutter framework]: https://www.youtube.com/watch?v=-MCeWP3rgI0
[MobX.dart, Hassle free state-management for your Dart and Flutter apps]: {{site.github}}/mobxjs/mobx.dart
[Provider package]: {{site.pub-pkg}}/provider
[Reactive Programming - Streams - BLoC - Practical Use Cases]: https://www.didierboelens.com/2018/12/reactive-programming---streams---bloc---practical-use-cases
[Scoped Model package]: {{site.pub-pkg}}/scoped_model
[Simple app state management]: /docs/development/data-and-backend/state-mgmt/simple
[This very section]: /docs/development/data-and-backend/state-mgmt/intro
[Using Flutter Inherited Widgets Effectively]: https://ericwindmill.com/articles/inherited_widget/
[Widget - State - Context - InheritedWidget]: https://www.didierboelens.com/2018/06/widget---state---context---inheritedwidget/
[You might not need Redux: The Flutter edition]: https://proandroiddev.com/you-might-not-need-redux-the-flutter-edition-9c11eba006d7
