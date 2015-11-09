# Awesome Android [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of awesome Android [libraries](#libraries) and [resources](#resources). For general Java libraries have a look at [awesome-java](https://github.com/akullpp/awesome-java).

这是一个很酷的 Android [库](#libraries) 和 [资源](#resources) 的策划列表。关于一般的 Java 库可以看 [awesome-java](https://github.com/akullpp/awesome-java).

- [Libraries](#libraries)
    - [Charts](#charts)
    - [Dependency Injection](#dependency-injection)
    - [Game Development](#game-development)
    - [GUI](#gui)
        - [ActionBar](#actionbar)
        - [Navigation](#navigation)
        - [Animations](#animations)
        - [Images](#images)
        - [Inputs](#inputs)
        - [Loading images](#loading-images)
    - [JSON](#json)
    - [Crash monitoring](#crash-monitoring)
    - [Networking](#networking)
    - [Notifications](#notifications)
    - [Database](#database)
        - [ORM](#orm)
    - [REST](#rest)
    - [Testing](#testing)
    - [Tracking](#tracking)
    - [Utility](#utility)
    - [Wireless](#wireless)
    - [Other](#other)
- [Resources](#resources)
    - [More lists of libraries](#more-lists-of-libraries)
- [Development Alternatives](#development-alternatives)
    - [C#](#c)
    - [HTML, CSS and Javascript](#html-css-and-javascript)
    - [Lua](#lua)
    - [Scala](#scala)
    - [Groovy](#groovy)
    - [Kotlin](#kotlin)
- [Performance](#performance)
- [Other Awesome Lists](#other-awesome-lists)
- [Contributing](#contributing)

- [库](#libraries)
    - [图表库](#charts)
    - [依赖注入框架](#dependency-injection)
    - [游戏开发库](#game-development)
    - [GUI](#gui)
        - [ActionBar](#actionbar)
        - [导航](#navigation)
        - [动画](#animations)
        - [图片库](#images)
        - [输入处理](#inputs)
        - [图片加载](#loading-images)
    - [JSON](#json)
    - [崩溃监控](#crash-monitoring)
    - [网络](#networking)
    - [通知](#notifications)
    - [数据库](#database)
        - [对象关系映射（ORM）](#orm)
    - [REST](#rest)
    - [测试](#testing)
    - [跟踪](#tracking)
    - [工具](#utility)
    - [无线](#wireless)
    - [其他](#other)
- [资源](#resources)
    - [其他库列表](#more-lists-of-libraries)
- [其他开发方式](#development-alternatives)
    - [C#](#c)
    - [HTML, CSS and Javascript](#html-css-and-javascript)
    - [Lua](#lua)
    - [Scala](#scala)
    - [Groovy](#groovy)
    - [Kotlin](#kotlin)
- [性能](#performance)
- [其他 Awesome Lists](#other-awesome-lists)
- [贡献](#contributing)

## Libraries
## 库

### Charts
### 图表库

- [AChartEngine](http://code.google.com/p/achartengine/) - Charting Engine.
- [AChartEngine](http://code.google.com/p/achartengine/) - 一个图表引擎。 
- [EazeGraph](https://github.com/blackfizz/EazeGraph) - Chart and graph library.
- [EazeGraph](https://github.com/blackfizz/EazeGraph) - 图表和图形库。
- [WilliamChart](https://github.com/diogobernardino/WilliamChart) - Chart library with good motion capabilities.
- [WilliamChart](https://github.com/diogobernardino/WilliamChart) - 具有很好？？？能力的图表库。
- [HelloCharts](https://github.com/lecho/hellocharts-android) - Chart and graph library with support for scaling, scrolling and animations.
- [HelloCharts](https://github.com/lecho/hellocharts-android) - 支持缩放、滚动和动画的图表和图形库。
- [MPAndroidChart](https://github.com/PhilJay/MPAndroidChart) - An Android chart and graph library supporting scaling and dragging by gesture.
- [MPAndroidChart](https://github.com/PhilJay/MPAndroidChart) - 一个支持缩放和手势拖拽的 Android 图表和图形库。

### Dependency Injection
### 依赖注入框架

- [RoboGuice](https://github.com/roboguice/roboguice) - Dependency injection framework for Android.
- [RoboGuice](https://github.com/roboguice/roboguice) - Android 上的依赖注入框架。
- [Dagger](https://github.com/square/Dagger) - Dependency injection framework for Java and Android.
- [Dagger](https://github.com/square/Dagger) - 支持 Java 和 Android 的依赖注入框架。
- [Butter Knife](http://jakewharton.github.io/butterknife) - View "injection" library for Android.
- [Butter Knife](http://jakewharton.github.io/butterknife) - Android 视图对象（View）“注入”库。
- [AndroidAnnotations](https://github.com/excilys/androidannotations) - Java annotations with dependency injection at compile time.
- [AndroidAnnotations](https://github.com/excilys/androidannotations) - 利用编译时依赖注入实现的 Java 注解？？？。

### Game Development
### 游戏开发

- [AndEngine](http://www.andengine.org/) - Free, Fun and Fast Android 2D OpenGL Game Engine.
- [AndEngine](http://www.andengine.org/) - 免费、有趣并且快速的 Android 2D OpenGL 游戏引擎。
- [Libgdx](https://libgdx.badlogicgames.com/) - Cross-platform game engine and SDK. [Open Source](https://github.com/libGDX/libGDX)
- [Libgdx](https://libgdx.badlogicgames.com/) - 跨平台游戏引擎和 SDK。 [源码](https://github.com/libGDX/libGDX)
- [Vuforia](https://www.vuforia.com) - Augmented Reality library.
- [Vuforia](https://www.vuforia.com) - 增强现实库。
- [Unity](http://unity3d.com/unity/multiplatform/mobile) - Cross-platform game creation system.
- [Unity](http://unity3d.com/unity/multiplatform/mobile) - 跨平台游戏创作系统 （GCS）。
- [Rajawali](https://github.com/Rajawali/Rajawali) - Android OpenGL ES 2.0/3.0 Engine
- [Rajawali](https://github.com/Rajawali/Rajawali) - Android OpenGL ES 2.0/3.0 引擎。

### GUI
### 图形用户界面 （GUI）

- [Pull to refresh](https://developer.android.com/reference/android/support/v4/widget/SwipeRefreshLayout.html) - A swipe refresh layout is available in the v4 support library.
- [Pull to refresh](https://developer.android.com/reference/android/support/v4/widget/SwipeRefreshLayout.html) - 在 v4 Support Library 中可用的一个滑动刷新布局。
- [Cardslib](https://github.com/gabrielemariotti/cardslib) - Android Library to build a UI Card.
- [Cardslib](https://github.com/gabrielemariotti/cardslib) - 用来制作一个 UI 卡片的 Android 库。
- [AndroidStaggeredGrid](https://github.com/etsy/AndroidStaggeredGrid) - Grid view which supports multiple columns with rows of varying sizes.
- [AndroidStaggeredGrid](https://github.com/etsy/AndroidStaggeredGrid) - 一个网格视图类，支持多列，并且每列中行的高度可以不同。
- [AQuery](https://code.google.com/p/android-query/) - Android-Query (AQuery) is a light-weight library for doing asynchronous tasks and manipulating UI elements in Android.
- [AQuery](https://code.google.com/p/android-query/) - Android-Query (AQuery) 是一个用来实现异步任务和操作 UI 元素的轻量库。
- [Flow](https://github.com/square/flow) - Library that helps with describing an app as a collection of moderately independent screens.
- [Flow](https://github.com/square/flow) - 
- [Crouton](https://github.com/keyboardsurfer/Crouton) - Context sensitive notifications for Android
- [Crouton](https://github.com/keyboardsurfer/Crouton) - 提供 Android 上的上下文敏感的通知功能。
- [DragSortListView](https://github.com/bauerca/drag-sort-listview) - Extension of the Android ListView that enables drag-and-drop reordering (No longer maintained).
- [DragSortListView](https://github.com/bauerca/drag-sort-listview) - Android ListView 的一个扩展， 实现了通过拖拽将元素重新排序的功能（已经不再维护）。
- [MaterialProgressBar](https://github.com/DreaminginCodeZH/MaterialProgressBar) - Material design ProgressBar with consistent appearance.
- [MaterialProgressBar](https://github.com/DreaminginCodeZH/MaterialProgressBar) - 具有一致外观的材料设计（Material Design）的 ProgressBar。
- [AndroidFillableLoaders](https://github.com/JorgeCastilloPrz/AndroidFillableLoaders) - Fillable progress view working with SVG paths. Nice option too for creating interesting app logos.
- [AndroidFillableLoaders](https://github.com/JorgeCastilloPrz/AndroidFillableLoaders) - .

#### ActionBar
#### 活动栏
- [ActionBarSherlock](http://actionbarsherlock.com) - ActionBar for older Android versions.
- [ActionBarSherlock](http://actionbarsherlock.com) - 针对旧版本的 ActionBar。
- [FadingActionBar](https://github.com/ManuelPeinado/FadingActionBar) - Fading action bar effect that can be seen in the new Play Music app.
- [FadingActionBar](https://github.com/ManuelPeinado/FadingActionBar) -  ？？ 活动栏效果， 在新版 Play Music 应用中可以看到。

#### Navigation
#### 导航
- [SlidingMenu](https://github.com/jfeinstein10/SlidingMenu) - Library to create applications with slide-in menus.
- [SlidingMenu](https://github.com/jfeinstein10/SlidingMenu) - 用来制作滑入式菜单应用的库。
- [SlidingTutorial](https://github.com/Cleveroad/slidingtutorial-android) - Simple library that helps to create awesome sliding android app tutorials.
- [SlidingTutorial](https://github.com/Cleveroad/slidingtutorial-android) - 一个用来帮助制作很酷的滑动式 Android 应用帮助教程的简易库。
- [PagerSlidingTabStrip](https://github.com/astuetz/PagerSlidingTabStrip) - An interactive indicator to navigate between the different pages of a ViewPager.
- [PagerSlidingTabStrip](https://github.com/astuetz/PagerSlidingTabStrip) - 一个用来在 ViewPager 的不同页面之间导航的交互式指示器。
- [Page View indicator](https://github.com/JakeWharton/Android-ViewPagerIndicator) - Support for horizontally scrolling ViewPager.
- [Page View indicator](https://github.com/JakeWharton/Android-ViewPagerIndicator) - 支持ViewPager的水平滚动。
- [MaterialDrawer](https://github.com/mikepenz/MaterialDrawer) - Simple take on a material design navigation drawer.
- [MaterialDrawer](https://github.com/mikepenz/MaterialDrawer) - 轻松实现材料设计的导航抽屉（navigation drawer）.

#### Animations
- [NineOldAndroids](https://github.com/JakeWharton/NineOldAndroids) - Library for using the Honeycomb animation API on all versions of the platform back to 1.0.
- [NineOldAndroids](https://github.com/JakeWharton/NineOldAndroids) - Library for using the Honeycomb animation API on all versions of the platform back to 1.0.
- [Rebound](https://github.com/facebook/rebound) - Rebound is a java library that models spring dynamics.
- [Rebound](https://github.com/facebook/rebound) - Rebound 是一个 Java 库，实现了弹跳动力建模。
- [Android View Animations](https://github.com/daimajia/AndroidViewAnimations) - Cute view animation collection.
- [Android View Animations](https://github.com/daimajia/AndroidViewAnimations) - 漂亮的视图动画集合。
- [Android-Transition](https://github.com/kaichunlin/android-transition) - Allows the easy creation of view transitions that react to user inputs.
- [Android-Transition](https://github.com/kaichunlin/android-transition) - 这个库允许你轻松地实现响应用于输入的视图切换功能。
- [Android-View-Actions](https://github.com/dtx12/AndroidAnimationsActions) - Makes creating complex animations for views easy.
- [Android-View-Actions](https://github.com/dtx12/AndroidAnimationsActions) - 这个库让制作复杂的视图动画变得容易。

#### Images
#### 图片处理

- [android-crop](https://github.com/jdamcd/android-crop) - Library project for cropping images.

- [CircularImageView](https://github.com/Pkmmte/CircularImageView) - Custom view for circular images while maintaining the best draw performance.

- [Android-Image-Filter](https://github.com/ragnraok/android-image-filter) - Library project for applying image filters easily.

#### Inputs

- [FloatingLabel](https://github.com/hardik-trivedi/FloatingLabel) - FloatingLabel Allows you to create a blow kind of EditText. *Doesn't have Gradle or Maven Support.*
- [MaterialEditText](https://github.com/rengwuxian/MaterialEditText) - Supporting Floating Labels, Single Line Ellipsis, Max/Min Characters, Helper Text and Error Text with Custom Colors.
- [Emojicon](https://github.com/rockerhieu/emojicon) - Adds emoticons to your app

#### Loading Images

- [Picasso](https://github.com/square/picasso) - A powerful image downloading and caching library for Android.
- [Universal Image Loader](https://github.com/nostra13/Android-Universal-Image-Loader) - Asynchronous, out of the box loading and caching of images.
- [Glide](https://github.com/bumptech/glide) - An image loading and caching library for Android focused on smooth scrolling,Recommended by google.
- [Fresco](https://github.com/facebook/fresco) - An Android library for managing images and the memory they use.

### JSON

- [Gson](https://code.google.com/p/google-gson/) - Gson is a Java library used for serializing and deserializing Java objects from and into JSON.
- [Jackson JSON Processor](http://jackson.codehaus.org) - High-performance JSON processor.

### Crash monitoring

- [Crashlytics](https://crashlytics.com) - Easy crash reporting solution.
- [HockeyApp](http://hockeyapp.net) - Distribution, Crash Reports, Feedback and Analytics
- [Splunk MINT](https://mint.splunk.com/) - Monitoring, Crash Reports, Real tima data, Statistic.
- [Bugsnag](https://bugsnag.com/) - Cross platform error monitoring.

### Networking

- [Ion](https://github.com/koush/ion) - Good networking library for android.
- [OkHttp](https://github.com/square/okhttp) - An HTTP+SPDY client for Android and Java applications.
- [Asynchronous Http Client](https://github.com/loopj/android-async-http) - An Asynchronous HTTP Library.
- [RoboSpice](https://github.com/stephanenicolas/robospice) - Library that makes writing asynchronous network requests easy.
- [IceNet](https://github.com/anton19/IceNet) - Fast, Simple and Easy Networking for Android
- [Android Volley](http://developer.android.com/training/volley/index.html) - Official Android HTTP library that makes networking for easier and faster.
- [IceSoap](https://github.com/AlexGilleran/IceSoap) - Easy, asynchronous, annotation-based SOAP for Android.
- [node-android](https://github.com/InstantWebP2P/node-android) - Run Node.js on Android.

### Notifications
- [android-remote-notifications](https://github.com/kaiwinter/android-remote-notifications) - Pulls notifications from a remote JSON file and shows them in your app.

### Database
- [Cupboard](https://bitbucket.org/qbusict/cupboard) - Access the sqlite easily via direct database access or through the ContentProvider framework.
- [DbInspector](https://github.com/infinum/android_dbinspector) - Provides a simple way to view the contents of the in-app database for debugging purposes.
- [Realm](https://github.com/realm/realm-java) - The alternative to SQLite and ORMs: Simple, modern and fast! Object oriented API and multi platform support.
- [RestorableSQLiteDatabase](https://github.com/yaa110/RestorableSQLiteDatabase) - A wrapper to replicate android's SQLiteDatabase with restoring capability.

#### ORM

- [GreeDAO](http://greendao-orm.com) - Light & fast ORM solution.
- [ORMLite](http://ormlite.com/sqlite_java_android_orm.shtml) - Lightweight ORM Java package for JDBC and Android.
- [ActiveAndroid](http://www.activeandroid.com) - Active record style ORM.
- [Sugar ORM](http://satyan.github.io/sugar/) - Insanely easy way to work with Android Databases.
- [DBFlow](https://github.com/Raizlabs/DBFlow) - Fast and powerful ORM with compile-time annotation processing.

### REST

- [Retrofit](http://square.github.io/retrofit/) - Retrofit turns your REST API into a Java interface.

### Testing

- [Robotium](https://code.google.com/p/robotium/) - Test automation framework for black-box UI tests.
- [Roboletric](http://robolectric.org/) - Unit test framework to run tests inside the JVM on your workstation, not in the emulator.
- [AssertJ Android](https://github.com/square/assertj-android) - AssertJ assertions geared towards Android.

### Tracking

- [MobileAppTracking](http://mobileapptracking.com/) - Tracking your marketing campaigns across multiple ad networks.
- [Mixpanel](https://mixpanel.com/) - Analytics platform to analyze the users.

### Utility

- [EventBus](http://greenrobot.github.io/EventBus/) - EventBus is a library that simplifies communication between different parts of your application.
- [Otto](https://github.com/square/otto) - Event Bus for Android.
- [Weak handler](https://github.com/badoo/android-weak-handler) - Memory safer implementation of android.os.Handler.
- [Byte Buddy](http://bytebuddy.net) - Runtime code generation library with support for Android.

### Wireless

- [SmartGattLib](https://github.com/movisens/SmartGattLib) - Simplifies the work with Bluetooth SMART devices (a.k.a. Bluetooth Low Energy in Bluetooth 4.0).

### Other

- [Android Support library](http://developer.android.com/tools/support-library/index.html) - The Android Support Library package is a set of code libraries that provide backward-compatible versions of Android framework API.
- [Google Play Services](http://developer.android.com/google/play-services/index.html) - Library to access Google services, such as account syncing, Google+ (sharing, single sign-on), Google Maps, Location APIs, Google Play Games, Cloud Messaging, Android Device Manager, and others.
- [Tape](https://github.com/square/tape) - A lightning fast, transactional, file-based FIFO for Android and Java.
- [Android Annotation framework](https://github.com/excilys/androidannotations) - Using Java annotations, developers can show their intent and let AndroidAnnotations generate the plumbing code at compile time.
- [Guava: Google Core Libraries for Java](https://github.com/google/guava) - Collections, caching, primitives support, concurrency libraries, common annotations, string processing, I/O, and so forth.
- [Android Scripting](https://github.com/damonkohler/sl4a) - Allows to run scripting languages on Android.
- [Android Priority Job Queue](https://github.com/path/android-priority-jobqueue) - Implementation of a Job Queue to easily schedule jobs (tasks) that run in the background, improving UX and application stability.
- [RateMeMaybe](https://github.com/Kopfgeldjaeger/RateMeMaybe) - Asks the user if (s)he wants to open the Play Store to rate your application.
- [Easy Rating Dialog](https://github.com/fernandodev/easy-rating-dialog) - Lib provides a simple way to display an alert dialog for rating app.
- [ZXing Android-Integration](https://github.com/zxing/zxing) - Integration with Barcode Scanner via Intent.
- [Gradle Retrolambda Plugin](https://github.com/evant/gradle-retrolambda) - Java 8 Lambdas on Android!
- [Caffeine](https://github.com/percolate/caffeine) - A collection of utility classes that help make Android development faster.

## Resources

- [Vogella Tutorials](http://www.vogella.com/tutorials/android.html) - Very good tutorials by Lars Vogel.
- [Android Design in Action Video series] (https://www.youtube.com/playlist?list=PLWz5rJ2EKKc8j2B95zGMb8muZvrIy-wcF) The video series by Android Design Team of Google.
- [Android Design in Action slides] (https://play.google.com/store/apps/details?id=com.astuetz.android.adia&feature=md)- The application that gives you access to the slides of the video series.
- [Android DevBytes Video Series] (https://www.youtube.com/playlist?list=PLWz5rJ2EKKc_XOgcRukSoKKjewFJZrKV0) - It is the technical counterpart of Android Design in Action series.
- [Developing for Android](https://medium.com/google-developers/developing-for-android-introduction-5345b451567c) - A series of articles from Googler [Chet Hasae](https://plus.google.com/+ChetHaase/posts/5grfChTEvQ9) and others, answering most commonly asked question: "What are some of the important rules to keep in mind when developing Android applications?".
- [Android Hive Tutorials](http://www.androidhive.info) - Very good tutorials for beginners.
- [Android Weekly](http://androidweekly.net) - Newsletter with weekly information about android.
- [Android Asset Studio](http://romannurik.github.io/AndroidAssetStudio/) - Generator for icons and other assets.
- [Android Action Bar Style Generator](http://jgilfelt.github.io/android-actionbarstylegenerator/).
- [Device Art Generator](http://developer.android.com/distribute/tools/promote/device-art.html) - Wraps app screenshots in real device artwork.
- [Android UI design resources] (http://androiduiux.com/free-design-resources/) - Gives you wide variety of design resources form a Google Developer Expert in UI/UX.
- [Pencil Project] (http://pencil.evolus.vn/) - An open source prototyping software.
- [Google Wear App](https://github.com/mbcrump/FirstGoogleWearableApp) - This is an open source Google Wear App that uses speech recognition to calculate a tip.
- [How to Make Android Apps](https://www.youtube.com/playlist?list=PLGLfVvz_LVvSPjWpLPFEfOCbezi6vATIh) - Video tutorials by Derek Banas.
- [android-blogs](https://github.com/vbauer/android-blogs) - List with blogs about Android.

### More lists of libraries
- [The Android Arsenal](http://android-arsenal.com) - Large list of android libraries
- [DevAppsDirect - Demo Market](https://play.google.com/store/apps/details?id=com.inappsquared.devappsdirect) - App that demonstrates different libraries.
- [Square libraries](http://square.github.io/#android) - Multiple high quality libraries by square.
- [Android.hew.io](http://android.hew.io) - Yet another list of android libraries.

## Development Alternatives

My personal recommendation is (for now) to use the android api to build a native app. Scala can help to build this native apps with cleaner code. But there are also use cases where alternatives like cross-platform development can be useful.

### C&#35;

- [Xamarin](http://xamarin.com) - Framework to create native iOS, Android, Mac and Windows apps in C#.

### HTML, CSS and Javascript

- [PhoneGap](http://phonegap.com) - Open source framework by Adobe to create cross platform mobile apps using HTML, CSS, and JavaScript.
- [Titanium](http://www.appcelerator.com/titanium/) - Open-source framework to create 'native' cross platform apps using JavaScript.
- [NativeScript](http://www.nativescript.org) - An open-source framework to build native iOS and Android apps with JavaScript from a single code base.
- [React Native](https://github.com/facebook/react-native) - A framework for building native apps with React by Facebook.
- [Ionic Framework](http://ionicframework.com) - A framework to build hybrid apps with mobile-optimized HTML, CSS and JS with AngularJS.
- [Apache Cordova](https://github.com/apache/cordova-android) - Cordova based applications are, at the core, applications written with web technology: HTML, CSS and JavaScript.
- [Reapp.io](http://reapp.io/) - Cordova based framework to build hybrid apps with mobile-optimized HTML, CSS and JS with ReactJS.

### Lua
- [Corona SDK](http://coronalabs.com/products/corona-sdk/) - Framework to create native iOS and Android Apps (especially Games).

### Scala
- [Scala on Android](http://macroid.github.io/ScalaOnAndroid.html) - Introduction to Scala on Android.
- [Scaloid](https://github.com/pocorall/scaloid) - Library for less painful Android development with Scala.
- [Macroid](https://github.com/macroid/macroid) - A modular functional UI language for Android.

### Groovy
- [Groovy on Android](http://melix.github.io/blog/2014/06/grooid.html) - Introduction to Groovy on Android.
- [Groovy Language Support for Android](https://github.com/melix/groovy-android-gradle-plugin) - Gradle Plugin for Compiling Groovy for Android.
- [SwissKnife](https://github.com/Arasthel/SwissKnife) - A multi-purpose Groovy library containing view injection and threading for Android using annotations.

### Kotlin
- [Anko](https://github.com/JetBrains/anko) - DSL for Android written in Kotlin by JetBrains.
- [Kotterknife](https://github.com/JakeWharton/kotterknife) - Android view injection writen in Kotlin based on ButterKnife
- [Android Kotlin Samples](https://github.com/irontec/android-kotlin-samples) - Some basic Android code samples writen in Kotlin.
- [KAndroid](https://github.com/pawegio/KAndroid) - Lightweight library providing useful extensions to eliminate boilerplate code in Android SDK.

# Performance
- [awesome-android-performance](https://github.com/Juude/awesome-android-performance) - awesome list of android performance

# Other Awesome Lists
Other amazingly awesome lists can be found in the [awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness) list.

## Contributing

Your contributions are always welcome! Please read the [contribution guidelines](contributing.md) first.
