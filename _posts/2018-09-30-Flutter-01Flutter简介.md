---
layout: post
title: Flutter 简介
categories: [Flutter, ]
description: Flutter 是谷歌的移动UI框架，可以快速在 iOS 和 Android 上构建高质量的原生用户界面。
keywords: Flutter, 
---

Flutter 是谷歌的移动UI框架，可以快速在 iOS 和 Android 上构建高质量的原生用户界面。

![](/images/posts/flutter/2018-09-30-00.jpeg)
### Flutter 特性

#### 一、快速开发
Flutter 提供了一个 热重载功能，在开发的时候，修改了代码，界面会立即更新，可以帮助你快速的开发和测试。flutter 的热重载功能，可以达到毫秒级，并且不会丢失状态。

#### 二、富有表现力，漂亮的用户界面
Flutter 提供了丰富的 UI 组件, 内置了 Material Design 和 Cupertino（ iOS 风格）widget 、并且有丰富的 motion API、 可以实现平滑而自然的滑动效果。

#### 三、现代的，响应式框架
使用 Flutter 的现代、响应式框架，和一系列基础 widget，可以轻松构建您的用户界面。并且还可以使用功能强大且灵活的 API（针对2D、动画、手势、效果等）实现复杂的 UI。

#### 四、访问本地功能和SDK
Flutter 可以复用现有的 Java、 Kotlin、 Swift 或 ObjC 代码，还可以访问 iOS 和 Android 上的原生系统功能和系统SDK。所以使用 Flutter 可以和这些语言混合开发。

#### 五、统一的应用开发体验
Flutter 拥有丰富的工具和库 ，你可以轻松的实现你的移动应用程序，并且可以同时在 iOS 和 Android 上运行。

#### 六、流畅的原生性能
由于 Flutter 的机制是生成 原生应用，和使用 WebView 、Hybrid 、React Native 等方式都不一样，这些方式调用原生能力中间都有 jsBridge 作为桥梁。但是 Flutter 是直接生成原生应用程序，所以可以实现流畅的原生效果。

#### 七、Flutter 目前的缺点
目前的缺点是，打出来应用程序包，相对其他来说（包括原生）会有点大，但是对于目前的网络环境，基本可以忽略。由于 Flutter 使用的是 Dart 语言，并且提供特别多的 widget，所以学习门槛有点高。
![](/images/posts/flutter/2018-09-30-01.png)

### Dart介绍
Dart 是谷歌开发的计算机编程语言，2011年10月份发布。它被用于 web、服务器、移动应用和物联网等领域的开发。
Dart 是面向对象的、类定义的、单继承的语言。它的语法类似 C 语言，可以转译为 JavaScript ，支持接口(interfaces)、混入(mixins)、抽象类(abstract classes)、具体化泛型(reified generics)、可选类型(optional typing)和sound type system

- Dart 是 AOT（Ahead Of Time）编译的，编译成快速、可预测的本地代码，使Flutter几乎都可以使用Dart编写；
- Dart 也可以 JIT（Just In Time）编译，开发周期快；
- Dart 可以更轻松地创建以60fps运行的流畅动画和转场；
- Dart 使 Flutter 不需要单独的声明式布局语言；
- Dart 容易学习，具有静态和动态语言用户都熟悉的特性。

### 官网
英文官网： [https://flutter.io/](https://flutter.io/)


中文官网： [https://flutterchina.club/](https://flutterchina.club/)
