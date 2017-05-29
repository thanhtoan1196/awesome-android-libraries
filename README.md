List of Android Libraries [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/thanhtoan1196/awesome-android)
======================
A curated list of awesome Android libraries. Feel free to contrubute.

## Other Awesome List
- [awesome-android](https://github.com/thanhtoan1196/awesome-android)
- [awesome-android-ui](https://github.com/thanhtoan1196/awesome-android-ui)
- [awesome-android-tips](https://github.com/thanhtoan1196/awesome-android-tips)

## Index
- [Networking](#networking)
- [JSON](#json)
- [Image Loader](#image-loader)
- [Rx](#rx)
- [Background Processing](#background-processing)
- [Pub/Sub](#pubsub)
- [Database](#database)
- [NoSQL](#nosql)
- [Annotation](#annotation)
- [Utility](#utility)
- [SharedPreference](#sharedpreference)
- [Time](#time)
- [Image Processing](#image-processing)
- [Hotfix](#hotfix)
- [Social Networks](#social-networks)
- [SDK](#sdk)
- [Tracking](#tracking)
- [Crash Monitoring](#crash-monitoring)
- [Performance](#performance)
- [Logger](#logger)
- [Debug](#debug)
- [Test](#Test)
- [Permission](#permission)
- [Security](#security)
- [Validation](#validation)
- [Notifications](#notifications)
- [SVG](#svg)
- [Media](#media)
- [Camera](#camera)
- [Fonts](#fonts)
- [Theme / Skin](#themeSkin)
- [Maps](#maps)
- [Cache](#cache)
- [Gesture](#gesture)
- [Kotlin](#kotlin)
- [WebRTC](#webrtc)
- [Bluetooth](#bluetooth)
- [Android Wear](#android-wear)
- [App / Demo](#appdemo)
- [Other](#other)
- [About Me](#about-me)

## Networking
Name | Description
--- | ---
**[Retrofit](http://square.github.io/retrofit/)** | Type-safe HTTP client for Android and Java by Square, Inc.
[Fast-Android-Networking](https://github.com/amitshekhariitbhu/Fast-Android-Networking) | Fast Android Networking Library is a powerful library for doing any type of networking in Android applications which is made on top of OkHttp Networking Layer
[ion](https://github.com/koush/ion) | Android Asynchronous Networking and Image Loading
[Async Http Client](https://github.com/AsyncHttpClient/async-http-client) | Asynchronous Http and WebSocket Client library for Java
[OkHttp](https://github.com/square/okhttp) | An HTTP & HTTP/2 client for Android and Java applications
[android-async-http](https://github.com/loopj/android-async-http) | An asynchronous, callback-based Http client for Android built on top of Apache's HttpClient libraries
[unirest-java](https://github.com/mashape/unirest-java) | Unirest in Java: Simplified, lightweight HTTP client library
[AndroidAsync](https://github.com/koush/AndroidAsync) | AndroidAsync is a low level network protocol library
[autobahn-java](https://github.com/crossbario/autobahn-java) | WebSocket & Web Application Messaging Protocol (WAMP) in Java for Android and Java 8
[android-upload-service](https://github.com/gotev/android-upload-service) | Easily upload files (FTP / Multipart / Binary) in the background with progress indication notification
**[chuck](https://github.com/jgilfelt/chuck)** | Chuck intercepts and persists all HTTP requests and responses inside your application, and provides a UI for inspecting their content
**[robospice](https://github.com/stephanenicolas/robospice)** | Repo of the Open Source Android library : RoboSpice. RoboSpice is a modular android library that makes writing asynchronous long running tasks easy
[NetworkEvents](https://github.com/pwittchen/NetworkEvents) | Android library listening network connection state and change of the WiFi signal strength with event bus
[node-android](https://github.com/InstantWebP2P/node-android) | Run Node.js on Android by rewrite Node.js in Java with the compatible API

## JSON 
Name | Repository
--- | ---
**[Gson](https://github.com/google/gson)** | A Java serialization/deserialization library to convert Java Objects into JSON and back
[moshi](https://github.com/square/moshi) | A modern JSON library for Android and Java
[ig-json-parser](https://github.com/Instagram/ig-json-parser) | Fast JSON parser for java projects
[Jackson](http://jackson.codehaus.org/) |  Formerly known as the standard JSON library for Java

## Image Loader
Name | Repository
--- | ---
**[Glide](https://github.com/bumptech/glide)** | An image loading and caching library for Android focused on smooth scrolling
[Fresco](http://frescolib.org) | An Android library for managing images and the memory they use
[ion](https://github.com/koush/ion) | Android Asynchronous Networking and Image Loading
[Picasso](https://github.com/square/picasso) | A powerful image downloading and caching library for Android
[Universal Image Loader](https://github.com/nostra13/Android-Universal-Image-Loader) | Powerful and flexible library for loading, caching and displaying images on Android
**[Keyframes](https://github.com/facebookincubator/Keyframes)** | A library for converting Adobe AE shape based animations to a data format and playing it back on Android and iOS devices

## Rx
Name | Repository
--- | ---
**[RxJava2Interop](https://github.com/akarnokd/RxJava2Interop)** | Library to convert between RxJava 1.x and 2.x reactive types
[ReactiveNetwork](https://github.com/pwittchen/ReactiveNetwork) | Android library listening network connection state and Internet connectivity with RxJava Observables
[Rx.Network](https://github.com/andrefio/Rx.Network) | Observe Android's CONNECTIVITY_CHANGE broadcasts using RxJava
[ReactiveWiFi](https://github.com/pwittchen/ReactiveWiFi) | Android library listening available WiFi Access Points and related information with RxJava Observables
[Android-ReactiveLocation](https://github.com/mcharmas/Android-ReactiveLocation) | Small library that wraps Google Play Service API in brilliant RxJava Observables reducing boilerplate to minimum
[RxFile](https://github.com/pavlospt/RxFile) | Rx methods to get a File and Image or Video thumbnails from a Document Provider on Android (Drive, Dropbox etc)
[RxDownload](https://github.com/ssseasonnn/RxDownload) | Multi-thread download tool based on RxJava
[rx-preferences](https://github.com/f2prateek/rx-preferences) | Reactive SharedPreferences for Android
[Rx.ContentObservable](https://github.com/andrefio/Rx.ContentObservable) | The RxAndroid creators decided to remove APIs deemed "not absolutely fundamental to all apps" beginning in the library's v1.0.0 release
[RxAndroidBle](https://github.com/Polidea/RxAndroidBle) | RxAndroidBle is a powerful painkiller for Android's Bluetooth Low Energy headaches. It is backed by RxJava, implementing complicated APIs as handy reactive observables
[RxNetty](https://github.com/ReactiveX/RxNetty) | Reactive Extension (Rx) Adaptor for Netty

## Background Processing
Name | Repository
--- | ---
[Android Priority Job Queue](https://github.com/yigit/android-priority-jobqueue) | A Job Queue specifically written for Android to easily schedule jobs (tasks) that run in the background, improving UX and application stability
[android-job](https://github.com/evernote/android-job) | Android library to handle jobs in the background
[Zorn](https://github.com/HendrixString/Android-Zorn) | Async Workers and Worker managers for Android
[Bolts](https://github.com/BoltsFramework/Bolts-Android) | Bolts is a collection of low-level libraries designed to make developing mobile apps easier
[Tape](https://github.com/square/tape) | A lightning fast, transactional, file-based FIFO for Android and Java

## Pub/Sub
Name | Repository
--- | ---
[EventBus](https://github.com/greenrobot/EventBus) | Android optimized event bus that simplifies communication between Activities, Fragments, Threads, Services, etc
[AndroidEventBus](https://github.com/hehonghui/AndroidEventBus) | A lightweight eventbus library for android, simplifies communication between Activities, Fragments, Threads, Services, etc
[Otto](https://github.com/square/otto) | An enhanced Guava-based event bus with emphasis on Android suppor
[drekkar](https://github.com/coshx/drekkar) | An Android event bus for WebView and JS

## Database
Name | Repository
--- | ---
[storio](https://github.com/pushtorefresh/storio) | Beautiful API for SQLiteDatabase and ContentResolver
[DBFlow](https://github.com/Raizlabs/DBFlow) | A blazing fast, powerful, and very simple ORM android database library that writes database code for you
[DBFlowManager](https://github.com/wajahatkarim3/DBFlowManager) | A quick and easy database manager plugin library for your DBFlow databases
[Cupboard](https://bitbucket.org/littlerobots/cupboard) | Cupboard for Android is simple persistence that gets out of your way and is easy to add to your existing code base
[sugar](https://github.com/satyan/sugar) | Insanely easy way to work with Android Database
[sqlbrite](https://github.com/square/sqlbrite) | A lightweight wrapper around SQLiteOpenHelper which introduces reactive stream semantics to SQL operations.
[sqlbrite-migrations](https://github.com/lykmapipo/sqlbrite-migrations) | 
[Android-Orma](https://github.com/gfx/Android-Orma) | A lightning-fast ORM for Android as a wrapper of SQLiteDatabase 
[SquiDB](https://github.com/yahoo/squidb) | is a simple SQLite database layer for Android 
[LitePal](https://github.com/LitePalFramework/LitePal) | An Android library that allows developers to use SQLite database extremely easy.
[SQLiteProvider](https://github.com/novoda/SQLiteProvider) | Extended SQLite functionality for Android
[android-database-sqlcipher](https://github.com/sqlcipher/android-database-sqlcipher) | Android SQLite API based on SQLCipher
[realm-java](https://github.com/realm/realm-java) | Realm is a mobile database: a replacement for SQLite & ORMs
[android-realm-asset-helper](https://github.com/eggheadgames/android-realm-asset-helper) | A small library to help with Realm.IO integration in Android apps
[ActiveAndroid](https://github.com/pardom/ActiveAndroid) | Active record style SQLite persistence for Android 
[requery](https://github.com/requery/requery) | modern SQL based query & persistence for Java / Kotlin / Android
[sqlitemagic](https://github.com/SiimKinks/sqlitemagic) | Compile time processed, annotation driven, no reflection SQLite database layer for Android
[AndroidQuery](https://github.com/FredJul/AndroidQuery) | AndroidQuery is an Android ORM for SQLite and ContentProvider which focuses on easy of use and performances thanks to annotation processing and code generation
[RestorableSQLiteDatabase](https://github.com/yaa110/RestorableSQLiteDatabase) | A wrapper to replicate android's SQLiteDatabase with restoring capability.
[sqldelight](https://github.com/square/sqldelight) | Generates Java models from CREATE TABLE statements
[TriOrm](https://github.com/HendrixString/Android-TriOrm) | a 3d database ORM experiment

## NoSQL
Name | Repository
--- | ---
[Couchbase-Lite-Android](https://github.com/couchbase/couchbase-lite-android) | Lightweight, embedded, syncable NoSQL database engine for Android
[SnappyDB](http://www.snappydb.com/) | A key-value database for Android
[SimpleNoSQL](https://github.com/Jearil/SimpleNoSQL) | A simple NoSQL client for Android. Meant as a document store using key/value pairs and some rudimentary querying. Useful for avoiding the hassle of SQL code
[RxSimpleNoSQL](https://github.com/xmartlabs/RxSimpleNoSQL) | Reactive extensions for SimpleNoSQL

## Annotation
Name | Repository
--- | ---
**[Dagger 2](https://github.com/google/dagger)** | A fast dependency injector for Android and Java
**[Butter Knife](https://github.com/JakeWharton/butterknife)** | Bind Android views and callbacks to fields and methods
**[AndroidAnnotations](https://github.com/androidannotations/androidannotations)** | Fast Android Development. Easy maintainance
[transfuse](https://github.com/johncarl81/transfuse) | A Dependency Injection and Integration framework for Google Android
**[Favor](https://github.com/soarcn/Favor)** | A easy way to use android sharepreference
[preferencebinder](https://github.com/denley/preferencebinder) | A SharedPreference "injection" library for Android
[barber](https://github.com/hzsweers/barber) | A custom view styling library for Android that generates the obtainStyledAttributes() and TypedArray boilerplate code for yo
[android-contentprovider-generator](https://github.com/BoD/android-contentprovider-generator) | A tool to generate Android ContentProviders
[javapoet](https://github.com/square/javapoet) | A Java API for generating .java source files
**[parceler](https://github.com/johncarl81/parceler)** | Android Parcelables made easy through code generation
[auto-parcel](https://github.com/frankiesardo/auto-parcel) | Android Parcelable models made easy
[Icepick](https://github.com/frankiesardo/icepick) | Android Instance State made easy
[icicle](https://github.com/segunfamisa/icicle) | An annotation based tool for saving and restoring instance states
**[Akatsuki](https://github.com/tom91136/Akatsuki)** | Android states and arguments made easy with annotations
[fragmentargs](https://github.com/sockeqwe/fragmentargs) | Annotation Processor for setting arguments in android fragments
**[ActivityStarter](https://github.com/MarcinMoskala/ActivityStarter)** | Simple Android Library, that provides easy way to start the Activities with arguments
[IntentBuilder](https://github.com/emilsjolander/IntentBuilder) | Type safe intent building for services and activities
[OnActivityResult](https://github.com/vanniktech/OnActivityResult) | OnActivityResult annotation compiler for Android

## Utility
Name | Repository
--- | ---
**[AndroidUtilCode](https://github.com/Blankj/AndroidUtilCode)** | Android developers should collect the following utils
[essentials](https://github.com/greenrobot/essentials) | General purpose utilities and hash functions for Android and Java
[AndroidCommons](https://github.com/alexvasilkov/AndroidCommons) | Various useful utilities for Android apps development
[caffeine](https://github.com/percolate/caffeine) | A collection of utility classes that help make Android development faster (and safer!)
[JustWeTools](https://github.com/lfkdsk/JustWeTools) | Some useful tools
**[colorize](https://github.com/cesarferreira/colorize)** | Access to 1000+ colors on android
[android-intents](https://github.com/marvinlabs/android-intents) | A small library which will save you from writing the same intent creation code again and again for the most simple tasks
[phrase](https://github.com/square/phrase) | Phrase is an Android string resource templating library
[android_dbinspector](https://github.com/infinum/android_dbinspector) | Android library for viewing and sharing in app databases
**[slinger](https://github.com/allegro/slinger)** | Slinger - deep linking library for Android
[easydeviceinfo](https://github.com/nisrulz/easydeviceinfo) | Get device information in a super easy way
[seismic](https://github.com/square/seismic) | Android device shake detection
[AndroidProcesses](https://github.com/jaredrummler/AndroidProcesses) | Get running processes on Android
[AndroidProcess](https://github.com/wenmingvs/AndroidProcess) | determine whether App is in the foreground or background
[Foredroid](https://github.com/steveliles/Foredroid) | Utility for detecting and notifying when your Android app goes background / becomes foreground
[apk-parser](https://github.com/clearthesky/apk-parser) | Apk parser lib for java
[APKParser](https://github.com/jaredrummler/APKParser) | APK parser for Android
[uber-apk-signer](https://github.com/patrickfav/uber-apk-signer) | A tool that helps signing and zip aligning single or multiple Android application packages (APKs) with either debug or provided release certificates. It supports v1 and v2 Android signing scheme has embedded a debug keystore and auto verifies after signing 
[wire](https://github.com/square/wire) | Clean, lightweight protocol buffers for Android and Java
[thrifty](https://github.com/microsoft/thrifty) | Thrift for Android that saves you methods
[CalDAV/CardDAV](https://davdroid.bitfire.at/) | DAVdroid is an award-winning open-source CalDAV/CardDAV synchronization app for Android 4+
[cling](https://github.com/4thline/cling) | UPnP/DLNA library for Java and Android
[CastCompanionLibrary-android](https://github.com/googlecast/CastCompanionLibrary-android) | CastCompanionLibrary-android is a library project to enable developers integrate Cast capabilities into their applications faster and easier
[RoboGif](https://github.com/izacus/RoboGif) | A small utility to record Android device screen to a GIF

## SharedPreference
Name | Repository
--- | ---
[hawk](https://github.com/orhanobut/hawk) | Secure, simple key-value storage for Android
[ConcealSharedPreference-Android](https://github.com/afiqiqmal/ConcealSharedPreference-Android) | Android Secure SharedPreferences Using Facebook Conceal Encryption
[Treasure](https://github.com/baoyongzhang/Treasure) | Very easy to use wrapper library for Android SharePreferences
[tray](https://github.com/grandcentrix/tray) | A SharedPreferences replacement for Android with multiprocess support
[esperandro](https://github.com/dkunzler/esperandro) | Easy SharedPreference Engine foR ANDROid
[TypedPreferences](https://github.com/johnjohndoe/TypedPreferences) | Preference wrappers for primitive types for Android

## Time
Name | Repository
--- | ---
[ThreeTenABP](https://github.com/JakeWharton/ThreeTenABP) | An adaptation of the JSR-310 backport for Android
[Joda Time Android](https://github.com/dlew/joda-time-android) | Joda-Time library with Android specialization
[truetime-android](https://github.com/instacart/truetime-android) | Android NTP time library. Get the true current time impervious to device clock time changes

## Image Processing
Name | Repository
--- | ---
[pollexor](https://github.com/square/pollexor) | Java client for the Thumbor image service which allows you to build URIs in an expressive fashion using a fluent API
[GPUImage for Android](https://github.com/CyberAgent/android-gpuimage) | Android filters based on OpenGL (idea from GPUImage for iOS)
[Compressor](https://github.com/zetbaitsu/Compressor) | An android image compression library
[Tiny](https://github.com/Sunzxyong/Tiny) | An image compression framework
[AndroidFaceCropper](https://github.com/lafosca/AndroidFaceCropper) | Android bitmap Face Cropper 

## Hotfix
Name | Repository
--- | ---
[tinker](https://github.com/Tencent/tinker) | Tinker is a hot-fix solution library for Android, it supports dex, library and resources update without reinstall apk
[Amigo](https://github.com/eleme/Amigo) | A hotfix library for Android platform, and not just this...
[AndFix](https://github.com/alibaba/AndFix) | AndFix is a library that offer hot-fix for Android App.
[HotFix](https://github.com/dodola/HotFix) | Android App hot fix patch dynamic framework
[Nuwa](https://github.com/jasonross/Nuwa) | Nuwa, pure java implementation, can hotfix your android application.
[Fit](https://github.com/KeithYokoma/Fit) | Framework for dispatching various procedure on update application

## Social Networks
Name | Repository
--- | ---
[socialauth-android](https://github.com/3pillarlabs/socialauth-android) | SocialAuth repository which contains socialauth android version and samples
[AndroidSocialNetworks](https://github.com/antonkrasov/AndroidSocialNetworks) | Library for easy work with Facebook, Twitter, LinkedIn and Google on Android
[ASNE](https://github.com/gorbin/ASNE) | ASNE library for simple integration of social networks: Twitter, Facebook, Google Plus, LinkedIn, Instagram, Vkontakte, Odnoklassniki
[SocialLoginManager](https://github.com/jaychang0917/SocialLoginManager) | Android social login (facebook, google) helper powered by RxJava
[SocialAuthHelper](https://github.com/stfalcon-studio/SocialAuthHelper) | Easy social network authorization for Android. Supports Facebook, Twitter, Instagram, Google+, Vkontakte
[ANE-Facebook](https://github.com/freshplanet/ANE-Facebook) | Air Native Extension (iOS and Android) for the Facebook mobile SDK
[Twitter-Helper](https://github.com/krazykira/Twitter-Helper) | A helper library that helps making twitter integration easy

## SDK
Name | Repository
--- | ---
[Firebase](https://firebase.google.com/docs/android/setup) | Firebase gives you the tools to develop high-quality apps, grow your user base, and earn more money. We cover the essentials so you can monetize your business and focus on your users
[cloudrail-si-android-sdk](https://github.com/CloudRail/cloudrail-si-android-sdk/) | Unified API Library for: Cloud Storage, Social Profiles, Payment, Email, SMS & POIs. Included services are Dropbox, Google Drive, OneDrive, Box, Facebook, GitHub, Google+, LinkedIn, Instagram, Slack, Twitter, Windows Live, Yahoo, PayPal, Stripe, Mailjet, Sendgrid, Twilio, Nexmo, Google Places, Foursquare, Yelp
[ParseAlternativesServices](https://github.com/minhhuy150894/ParseAlternativesServices) | Parse Alternative back-end services for developer
[deepstream.io](https://github.com/deepstreamIO/deepstream.io) | deepstream is a new type of server that syncs data and sends events across millions of clients
[thumbor](https://github.com/thumbor/thumbor) | thumbor is an open-source photo thumbnail service by globo.com
[android-checkout](https://github.com/serso/android-checkout) | Library for Android In-App Billing (Version 3+)
[PayPal-Android-SDK](https://github.com/paypal/PayPal-Android-SDK) | Accept PayPal and credit cards in your Android app
[donations](https://github.com/SufficientlySecure/donations) | Donations library for Android. Supports Google Play Store, Flattr, PayPal, and Bitcoin
[Applozic-Android-SDK](https://github.com/AppLozic/Applozic-Android-SDK) | Android Real Time Chat & Messaging SDK
[qiscus-sdk-android](https://github.com/qiscus/qiscus-sdk-android) | Qiscus provide everything you need to power up your app with chats
[card.io-Android-SDK](https://github.com/card-io/card.io-Android-SDK) | card.io provides fast, easy credit card scanning in mobile apps
[aws-sdk-android](https://github.com/aws/aws-sdk-android) | Official mirror of version 2 of the AWS Mobile SDK for Android
[evernote-sdk-android](https://github.com/evernote/evernote-sdk-android) | Evernote SDK for Android
[open-weather-retriever-z](https://github.com/czack810150/open-weather-retriever-z) | A wrapper that gets weather information from OpenWeatherMap
[WeatherLib](https://github.com/survivingwithandroid/WeatherLib) | Android Weather Library: android weather lib to develop weather based app fast and easily

## Tracking
Name | Repository
--- | ---
**[Google Analytics](https://developers.google.com/analytics/devguides/collection/android/v4/)** | https://developers.google.com/analytics/devguides/collection/android/v4
**[Firebase Analytics](https://firebase.google.com/docs/analytics/)** | https://firebase.google.com/docs/analytics
[liquid-sdk-android](https://github.com/lqd-io/liquid-sdk-android) | https://onliquid.com
[HockeySDK-Android](https://github.com/bitstadium/HockeySDK-Android) | https://hockeyapp.net
[Packetzoom](https://packetzoom.com) | https://packetzoom.com
[MobileAppTracking](https://www.tune.com/) | https://www.tune.com
[Countly](https://count.ly) | https://count.ly
[CleverTap](https://clevertap.com) | https://clevertap.com
[mixpanel-android](https://github.com/mixpanel/mixpanel-android) | http://mixpanel.com
[clevertap-android-sdk](https://github.com/CleverTap/clevertap-android-sdk) | https://clevertap.com

## Crash Monitoring
Name | Repository
--- | ---
**[Sherlock](https://github.com/ajitsing/Sherlock)** | https://github.com/ajitsing/Sherlock
**[Fabric Crashlytics](https://get.fabric.io/)**  | https://get.fabric.io 
[Splunk MINT](https://mint.splunk.com/) | https://mint.splunk.com 
[Bugsnag](https://www.bugsnag.com/) | https://www.bugsnag.com/
[Catcho](https://github.com/alhazmy13/Catcho) | https://github.com/alhazmy13/Catcho 
[Apteligent](https://www.apteligent.com/) | https://www.apteligent.com
[BugfenderSDK](https://bugfender.com/) | https://bugfender.com

## Performance
Name | Repository
--- | ---
[leakcanary](https://github.com/square/leakcanary) | A memory leak detection library for Android and Java
**[BlockCanaryEx](https://github.com/seiginonakama/BlockCanaryEx)** | Make performance bottleneck detection easily when app blocked
[AndroidPerformanceMonitor](https://github.com/markzhai/AndroidPerformanceMonitor) | A transparent ui-block detection library for Android, app only needs one-line-code to setup
[TinyDancer](https://github.com/friendlyrobotnyc/TinyDancer) | An android library for displaying fps from the choreographer and percentage of time with two or more frames dropped
[ANR-WatchDog](https://github.com/SalomonBrys/ANR-WatchDog) | A simple watchdog that detects Android ANR (Application Not Responding) error and throws a meaningful exception

## Logger
Name | Repository
--- | ---
**[Hugo](https://github.com/JakeWharton/hugo)** | Annotation-triggered method call logging for your debug builds
**[logger](https://github.com/orhanobut/logger)** | Simple, pretty and powerful logger for android
**[LoggingInterceptor](https://github.com/ihsanbal/LoggingInterceptor)** | An OkHttp interceptor which pretty logs request and response data
**[Timber](https://github.com/JakeWharton/timber)** | A logger with a small, extensible API which provides utility on top of Android's normal Log class
[EzyLogger](https://github.com/afiqiqmal/EzyLogger) | Simple Logger for Android
[logback-android](https://github.com/tony19/logback-android) | The reliable, generic, fast and flexible logging framework for Java on Android
[puree-android](https://github.com/cookpad/puree-android) | A log collector for Android
[pidcat](https://github.com/JakeWharton/pidcat) | Colored logcat script which only shows log entries for a specific application package
[Ok2Curl](https://github.com/mrmike/Ok2Curl) | Convert OkHttp requests into curl logs

## Debug
Name | Repository
--- | ---
**[stf](https://github.com/openstf/stf)** | Control and manage Android devices from your browser
**[stetho](https://github.com/facebook/stetho)** | Stetho is a debug bridge for Android applications, enabling the powerful Chrome Developer Tools and much more
[debug-bottle](https://github.com/kiruto/debug-bottle) | Debug Bottle is an Android runtime debug / develop tools written using kotlin language
[Android-Debug-Database](https://github.com/amitshekhariitbhu/Android-Debug-Database) | A library for debugging android databases and shared preferences
[under-the-hood](https://github.com/patrickfav/under-the-hood) | Under the Hood is a flexible and powerful Android debug view library. It uses a modular template system that can be easily extended to your needs, although coming with many useful elements built-in
[uber-adb-tools](https://github.com/patrickfav/uber-adb-tools) | A tool that enables advanced features through adb installing and uninstalling apps like wildcards and multi device support. Useful if you want to clean your test device from all company apks or install a lot of apks in one go. Written in Java so it should run on your platform
[ViewInspector](https://github.com/xfumihiro/ViewInspector) | View Inspection Toolbar for Android Development
[debugkit](https://github.com/hulab/debugkit) | DebugKit lib for Android allows you to use a fancy hovering debug tool to trigger some actions directly in the app. This tool is very useful to trigger some event at runtime, and to have a written feedback directly on your testing phone screen
[AppMethodOrder](https://github.com/zjw-swun/AppMethodOrder) | Know all the function calls the order and time-consuming
**[Takt](https://github.com/wasabeef/Takt)** | Takt is Android library for measuring the FPS using Choreographer
**[Traceur](https://github.com/T-Spoon/Traceur)** | Easier RxJava2 debugging with better stacktraces 
[Android-DebugPort](https://github.com/jasonwyatt/Android-DebugPort) | Android DebugPort is a drop-in utility which allows you to write and execute code within your app's context, at runtime, and from the comfort of your computer's terminal. Think of it as a window into your application through which you can both inspect and modify its state 
[AndroidSnooper](https://github.com/jainsahab/AndroidSnooper) | Android library to record the network calls through the interceptor mechanism of the http clients 
[debug-artist](https://github.com/baristaventures/debug-artist) | Make developers life easier with some tools, you can add it to your debug builds and have some debug libraries like Leakcanary and others without extra work
[scalpel](https://github.com/JakeWharton/scalpel) | A surgical debugging tool to uncover the layers under your app

## Test
Name | Repository
--- | ---
[robotium](https://github.com/RobotiumTech/robotium) | https://robotium.com/
[selendroid](https://github.com/selendroid/selendroid) | http://selendroid.io/
[robolectric](https://github.com/robolectric/robolectric) | http://robolectric.org/
[spoon](https://github.com/square/spoon) | http://square.github.io/spoon/
[macaca-android](https://github.com/macacajs/macaca-android) | https://macacajs.github.io/
[assertj-android](https://github.com/square/assertj-android) | http://square.github.io/assertj-android/
[junit4](https://github.com/junit-team/junit4) | http://junit.org/junit4/
[android-junit-report](https://github.com/jsankey/android-junit-report) | A custom instrumentation test runner for Android that generates XML reports for integration with other tools
[powermock](https://github.com/powermock/powermock) | PowerMock is a Java framework that allows you to unit test code normally regarded as untestable
[green-coffee](https://github.com/mauriciotogneri/green-coffee) | Android library that allows you to run your acceptance tests written in Gherkin in your Android instrumentation tests
[sixpack-java](https://github.com/sixpack/sixpack-java) | A Java client for the Sixpack A/B testing framework
[RESTMock](https://github.com/andrzejchm/RESTMock) | REST API mocking made easy

## Permission
Name | Repository
--- | ---
[PermissionHelper](https://github.com/k0shk0sh/PermissionHelper) | Android Library to help you with your runtime Permissions
[Gota](https://github.com/alhazmy13/Gota) | Simplifying Android Permissions

## Security
Name | Repository
--- | ---
**[android-proguard-snippets](https://github.com/krschultz/android-proguard-snippets)** | Proguard configurations for common Android libraries
[AndResGuard](https://github.com/shwenzhang/AndResGuard) | proguard resource for Android by wechat team
[Secure-Pref-Manager](https://github.com/prashantsolanki3/Secure-Pref-Manager) | Secure Preference Manager for android. It uses various Encryption to protect your application's Shared Preferences
[secure-preferences](https://github.com/scottyab/secure-preferences) | Android Shared preference wrapper than encrypts the values of Shared Preferences. It's not bullet proof security but rather a quick win for incrementally making your android app more secure
[Grab'n Run](https://github.com/lukeFalsina/Grab-n-Run) | Grab’n Run, a simple and effective Java Library for Android projects to secure dynamic code loading
[tweetnacl-java](https://github.com/InstantWebP2P/tweetnacl-java) | Fast Curve Crypto Library - TweetNaCl in Java
[AESCrypt-Android](https://github.com/scottyab/AESCrypt-Android) | Simple API to perform AES encryption on Android. This is the Android counterpart to the AESCrypt library Ruby and Obj-C 
[open-keychain](https://github.com/open-keychain/open-keychain) | OpenKeychain is an OpenPGP implementation for Android

## Validation
Name | Repository
--- | ---
**[android-saripaar](https://github.com/ragunathjawahar/android-saripaar)** | UI form validation library for Android
[Android-Validator](https://github.com/throrin19/Android-Validator) | Form Validator Library for Android
[android-validation-komensky](https://github.com/inmite/android-validation-komensky) | A simple library for validating user input in forms using annotations
[AwesomeValidation](https://github.com/thyrlian/AwesomeValidation) | Android validation library which helps developer boil down the tedious work to three easy steps
[NextInputs](https://github.com/yoojia/NextInputs) | A text input validation library for Java
[android-complexify](https://github.com/infinum/android-complexify) | An Android library which makes checking the quality of user's password a breeze

## Notifications
Name | Repository
--- | ---
[android-remote-notifications](https://github.com/kaiwinter/android-remote-notifications) | Pulls notifications from a remote JSON file and shows them in your app
[AndroidHeartBeatFixer](https://github.com/joaopedronardari/AndroidHeartBeatFixer) | Way to set heartbeat interval and the User receive PushNotifications from GCM. Based on related post in Google Forums about HeartBeat problem

## SVG
Name | Repository
--- | ---
[svgkit-android](http://scand.com/products/svgkit-android/index.html) | SVG Kit for Android is a flexible and quite fast library supporting SVG Tiny specs
[sharp](https://github.com/Pixplicity/sharp) | SVG for Android
[androidsvg](https://github.com/BigBadaboom/androidsvg) | SVG rendering library for Android
[vectalign](https://github.com/bonnyfone/vectalign) | Tool for create complex morphing animations using VectorDrawables (allows morphing between any pair of SVG images
[SVG2Drawable](https://github.com/StanKocken/SVG2Drawable) | Use a jar executable to create a Drawable class to display a SVG on Android
[svg2android](https://github.com/inloop/svg2android) | SVG to Android VectorDrawable XML resource file

## Media
Name | Repository
--- | ---
[ijkplayer](https://github.com/Bilibili/ijkplayer) | Android/iOS video player based on FFmpeg n3.3, with MediaCodec, VideoToolbox support
[ExoPlayer](https://github.com/google/ExoPlayer) | An extensible media player for Android
[mp4parser](https://code.google.com/p/mp4parser/) | A Java API to read, write and create MP4 files
[MediaRecorderDialog](https://github.com/alhazmy13/MediaRecorderDialog) | Android has a built in microphone through which you can capture audio and store it , or play it in your phone. There are many ways to do that but with this dialog you can do all thats with only one dialog
[AndroidVideoCache](https://github.com/danikula/AndroidVideoCache) | Cache support for any video player with help of single line
[FFmpeg](https://github.com/FFmpeg/FFmpeg) | FFmpeg is a collection of libraries and tools to process multimedia content such as audio, video, subtitles and related metadata
[libstreaming](https://github.com/fyhertz/libstreaming) | libstreaming is an API that allows you, with only a few lines of code, to stream the camera and/or microphone of an android powered device using RTP over UDP
[AndroidFFmpeg](https://github.com/appunite/AndroidFFmpeg) | FFmpeg build for android random architectures with example jni
[android-ffmpeg-java](https://github.com/guardianproject/android-ffmpeg-java) | Android Java wrapper around ffmpeg command line binary
[android-ffmpeg](https://github.com/guardianproject/android-ffmpeg) | a system for building custom ffmpeg binaries for Android
[jcodec](https://github.com/jcodec/jcodec) | JCodec is a library implementing a set of popular video and audio codecs
[ipcam-view](https://github.com/niqdev/ipcam-view) | MJPEG video streaming on Android
[AndroidAudioConverter](https://github.com/adrielcafe/AndroidAudioConverter) | Convert audio files inside your Android app easily. Supported formats: AAC, MP3, M4A, WMA, WAV and FLAC
[AudioPlayerView](https://github.com/HugoMatilla/AudioPlayerView) | AudioPlayerView is an Android view that loads audio from an url and have basic playback tools
[UserAwareVideoView](https://github.com/kevalpatel2106/UserAwareVideoView) | A customized video view that will automatically pause video is user is not looking at device screen!!!!!
[android-ffmpeg-with-rtmp](https://github.com/cine-io/android-ffmpeg-with-rtmp) | script(s) to build ffmpeg for android, including support for RTMP (and OpenSSL)
[FFmpeg-Android](https://github.com/OnlyInAmerica/FFmpeg-Android) | Script and Instructions for building FFmpeg for Android

## Camera
Name | Repository
--- | ---
[EasyCamera](https://github.com/Glamdring/EasyCamera) | Wrapper around the android Camera class that simplifies its usage
[Landscape video camera](https://github.com/jmolsmobile/LandscapeVideoCamera) | Powerful custom Android Camera with granular control over the video quality and filesize, restricting recordings to landscape only

## Fonts
Name | Repository
--- | ---
**[Calligraphy](https://github.com/chrisjenx/Calligraphy)** | Custom fonts in Android the easy way

## Theme / Skin
Name | Repository
--- | ---
**[Colorful](https://github.com/garretyoder/Colorful)** | Android runtime theme library
**[aesthetic](https://github.com/afollestad/aesthetic)** | A fast and easy to use plug-and-play dynamic theme engine. Powered by Rx, for Android apps
[MagicaSakura](https://github.com/Bilibili/MagicaSakura) | An Android multi theme library which supporting both daily colorful theme and night theme
[ColorArt](https://github.com/MichaelEvans/ColorArt) | iTunes 11-style color matching code for Android
[ChatKit](https://github.com/stfalcon-studio/ChatKit) | Flexible components for chat UI implementation with flexible possibilities for styling, customizing and data management
[Android-Skin-Loader](https://github.com/fengjundev/Android-Skin-Loader) | Dynamic loading local skin
[AndroidChangeSkin](https://github.com/hongyangAndroid/AndroidChangeSkin) | Change skin without having to restart Activity

## Maps
Name | Repository
--- | ---
[GraphHopper](https://graphhopper.com) | An open source route planning library and server using OpenStreetMap
[Mapsforge](https://github.com/mapsforge/mapsforge) | Vector map library written in Java - running on Android and Desktop
[smart-location-lib](https://github.com/mrmans0n/smart-location-lib) | Android library project that lets you manage the location updates to be as painless as possible
[Google-Directions-Android](https://github.com/jd-alexander/Google-Directions-Android) | This project allows you to calculate the route between two locations and displays it on a map
[android-maps-extensions](https://github.com/mg6maciej/android-maps-extensions) | Android Maps Extensions is a library extending capabilities of Google Maps Android API v2
[android-maps-utils](https://github.com/googlemaps/android-maps-utils) | Handy extensions to the Google Maps Android API

## Cache
Name | Repository
--- | ---
[DiskLruCache](https://github.com/JakeWharton/DiskLruCache) | Java implementation of a Disk-based LRU cache which specifically targets Android compatibility
[ASimpleCache](https://github.com/yangfuhai/ASimpleCache) | A simple cache for android and java
[CacheUtilsLibrary](https://github.com/westlinkin/CacheUtilsLibrary) | A simple Android utils library to write any type of data into cache files and read them later
[Reservoir](https://github.com/anupcowkur/Reservoir) | Android library to easily serialize and cache your objects to disk using key/value pairs

## Gesture
Name | Repository
--- | ---
[sensey](https://github.com/nisrulz/sensey) | Detecting gestures in a snap

## Kotlin
Name | Repository
--- | ---
[anko](https://github.com/Kotlin/anko) | Pleasant Android application development
[kotterknife](https://github.com/JakeWharton/kotterknife) | View "injection" library for Android
[KAndroid](https://github.com/pawegio/KAndroid) | Kotlin library for Android
[KPreferences](https://github.com/mohamad-amin/KPreferences) | A Kotlin library for reactive and boilerplate-free SharedPreferences in Android
[KotlinPreferences](https://github.com/MarcinMoskala/KotlinPreferences) | Android Library to make SharedPreferences usage easier

## WebRTC
Name | Repository
--- | ---
[AndroidRTC](https://github.com/pchab/AndroidRTC) | https://github.com/pchab/AndroidRTC

## Bluetooth
Name | Repository
--- | ---
[android-beacon-library](https://github.com/AltBeacon/android-beacon-library) | Allows Android apps to interact with BLE beacons
[Android-BluetoothSPPLibrary](https://github.com/akexorcist/Android-BluetoothSPPLibrary) | Bluetooth Serial Port Profile which comfortable to developer application to communication with microcontroller via bluetooth
[AndroidSmoothBluetooth](https://github.com/palaima/AndroidSmoothBluetooth) | Smooth communication via bluetooth with other android devices or microcontrollers such as Arduino
[android-lite-bluetoothLE](https://github.com/litesuits/android-lite-bluetoothLE) | BLE Framework. Based on Bluetooth 4.0. Based on callback. Extremely simple! Communication with BluetoothLE(BLE) device as easy as HTTP communication
[BluetoothHelper](https://github.com/a-voyager/BluetoothHelper) | Bluetooth Helper Library
[SmartGattLib](https://github.com/movisens/SmartGattLib) | SmartGattLib is a Java library that simplifies the work with Bluetooth SMART devices
[Bluetooth-LE-Library](https://github.com/alt236/Bluetooth-LE-Library---Android) | This library allows for easy access to a Bluetooth LE device's AdRecord and RSSI value. It offers additional functionality for iBeacons
[Blueteeth](https://github.com/RobotPajamas/Blueteeth) | A simple, lightweight library intended to take away some of the cruft and tediousness of using the Android BLE

## Android Wear
Name | Repository
--- | ---
[BusWear](https://github.com/tajchert/BusWear) | EventBus for Android Wear devices
[DaVinci](https://github.com/florent37/DaVinci) | DaVinci is an image downloading and caching library for Android Wear
[WearMenu](https://github.com/florent37/WearMenu) | An Android Wear Menu implementation
[Teleport](https://github.com/Mariuxtheone/Teleport) | Data Sync & Messaging Library for Android Wear

## App / Demo
Name | Repository
--- | ---
[open-source-android-apps](https://github.com/pcqpcq/open-source-android-apps) | Open-Source Android Apps
[android-support-23.2-sample](https://github.com/liaohuqiu/android-support-23.2-sample) | Sample Project for Android Support Library 23.2
[MovieGuide](https://github.com/esoxjem/MovieGuide) | Movie discovery app showcasing MVP, RxJava, Dagger 2 and Clean Architecture
[MusicDNA](https://github.com/harjot-oberai/MusicDNA) | A Music Player for android that renders beautiful DNA(Visualization) of the currently playing music
[remusic](https://github.com/aa112901/remusic) | Nusic player online
[LeeCo](https://github.com/Nightonke/LeeCo) | LeeCo is an awesome app for (including unlock) problems, solutions, discuss(from leetcode) and comments
[Tower](https://github.com/DroidPlanner/Tower) | Ground Control Station for Android Devices
[Telecine](https://github.com/JakeWharton/Telecine) | Record full-resolution video on your Android devices
[FlyRefresh](https://github.com/race604/FlyRefresh) | The implementation of https://dribbble.com/shots/2067564-Replace
[Etar-Calendar](https://github.com/Etar-Group/Etar-Calendar) | Material Design Calendar
[HomeMirror](https://github.com/HannahMitt/HomeMirror) | Android application powering the mirror in my house
[TranslateApp](https://github.com/maoruibin/TranslateApp) | A translations app without interruptions, copy words and translate directly, show result by top view
[uhabits](https://github.com/iSoron/uhabits) | Simple habit tracker for Android
[AisenWeiBo](https://github.com/wangdan/AisenWeiBo) | Sina microblogging third-party Android client
[Villains-and-Heroes](https://github.com/andremion/Villains-and-Heroes) | Android app built with MVP architectural approach and uses Marvel Comics API that allows developers everywhere to access information about Marvel's vast library of comics
[BookReader](https://github.com/JustWayward/BookReader) | Network fiction reader
[bookdash-android-app](https://github.com/bookdash/bookdash-android-app) | Book Dash is an Android App for the NPO where you can download books in different languages for free
[seadroid](https://github.com/haiwen/seadroid) | Android client for Seafile
[FolioReader-Android](https://github.com/FolioReader/FolioReader-Android) | A Java ePub reader and parser framework for Android
[AndroidTV-workshop](https://github.com/odigeoteam/AndroidTV-workshop) | This repository contains Android native source code needed for "TV future is Apps: tvOS vs Android TV" workshop presented during Codemotion 2016
[android-oss](https://github.com/kickstarter/android-oss) | Kickstarter for Android. Bring new ideas to life, anywhere
[MusicDNA](https://github.com/harjot-oberai/MusicDNA) | A Music Player for android that renders beautiful DNA(Visualization) of the currently playing music
[Just-Another-Android-App](https://github.com/athkalia/Just-Another-Android-App) | An Android base app with loads of cool libraries/configuration
[open-event-android](https://github.com/fossasia/open-event-android) | Open Event Android App Generator
[PocketHub](https://github.com/pockethub/PocketHub) | PocketHub Android App
[ribot-app-android](https://github.com/ribot/ribot-app-android) | The ribot studio app for the Android Platform
[Telegram](https://github.com/DrKLO/Telegram) | Telegram for Android source
[iosched](https://github.com/google/iosched) | The Google I/O 2016 Android App
[android-mvp-architecture](https://github.com/MindorksOpenSource/android-mvp-architecture) | This repository contains a detailed sample app that implements MVP architecture using Dagger2, GreenDao, RxJava2, FastAndroidNetworking and PlaceholderView
[GivesMeHopeAndroidClient](https://github.com/jparkie/GivesMeHopeAndroidClient) | An unofficial Gives Me Hope Android client for educational purposes
[EffectiveAndroidUI](https://github.com/pedrovgs/EffectiveAndroidUI) | Sample project created to show some of the best Android practices to work in the Android UI Layer. The UI layer of this project has been implemented using MVP or MVVM (without binding engine) to show how this patterns works
[philm](https://github.com/chrisbanes/philm) | Movie collection and information app for Android
[archi](https://github.com/ivacf/archi) | Repository that showcases 3 Android app architectures: "Standard Android", MVP and MVVM. The exact same app is built 3 times following the different patterns
[LeafPic](https://github.com/HoraApps/LeafPic) | LeafPic is an ad-free, open-source and material-designed android gallery alternative
[plaid](https://github.com/nickbutcher/plaid) | An Android app which provides design news & inspiration as well as being an example of implementing material design
[CoCoin](https://github.com/Nightonke/CoCoin) | CoCoin, Multi-view Accounting Application
[SimplifyReader](https://github.com/chentao0707/SimplifyReader) | An Android app based on Google Material Design design, including news read, picture browsing
[InstaMaterial](https://github.com/frogermcs/InstaMaterial) | Implementation of Instagram with Material Design (originally based on Emmanuel Pacamalan's concept)
[kickmaterial](https://github.com/byoutline/kickmaterial) | Crowdfunding app concept for Android. Created to showcase new trends in Android development with strong focus on Material Design
[android-boilerplate](https://github.com/ribot/android-boilerplate) | Android boilerplate app that showcases architecture and libraries used at ribot
[NotifyUtil](https://github.com/wenmingvs/NotifyUtil) | Notification tools
[ColorfulNews](https://github.com/kaku2015/ColorfulNews) | A news-reading App (MVP+Dagger2+RxJava+Retrofit2+Material Design)
[SmarterStreaming](https://github.com/daniulive/SmarterStreaming) | SmarterStreaming, which is an excellent cross-platform Live Streaming publisher/playback SDK, based on RTMP/RTSP protocol, developed by daniulive
[UI-Motion](https://github.com/andremion/UI-Motion) | How to apply meaningful and delightful motion in a sample Android app
[wire-android](https://github.com/wireapp/wire-android) | Wire for Android
[Popular-Movies-App](https://github.com/maksim-m/Popular-Movies-App) | A simple Android app, that helps you discover most popular and most rated movies. Project 1 & 2 of Udacity Android Developer Nanodegree
[e-contact-android](https://github.com/Yalantis/e-contact-android) | E-contact app helps citizens of Dnipro and neighboring regions to solve problems citizens have in their everyday lives by providing a reliable channel of communication with local authorities
[RxJava-Android-Samples](https://github.com/kaushikgopal/RxJava-Android-Samples) | Learning RxJava for Android by example
[android-architecture](https://github.com/googlesamples/android-architecture) | A collection of samples to discuss and showcase different architectural tools and patterns for Android apps
[RxJava2-Android-Samples](https://github.com/amitshekhariitbhu/RxJava2-Android-Samples) | RxJava 2 Android Examples - Migration From RxJava 1 to RxJava 2 - How to use RxJava 2 in Android
[FlatBuffer](https://github.com/amitshekhariitbhu/FlatBuffer) | FlatBuffer : Android Sample Application
[Mysplash](https://github.com/WangDaYeeeeee/Mysplash) | An Unsplash Client
[FastAccess](https://github.com/k0shk0sh/FastAccess) | A tiny launcher or as Samsung likes to call it Floating Toolbox
[JieCaoVideoPlayer](https://github.com/lipangit/JieCaoVideoPlayer) | Android VideoPlayer MediaPlayer VideoView MediaView Float View And Fullscreen
[MotionViews-Android](https://github.com/uptechteam/MotionViews-Android) | Code Guide: How to create Snapchat-like image stickers and text stickers
[Signal-Android](https://github.com/WhisperSystems/Signal-Android) | A private messenger for Android
[wechat](https://github.com/motianhuo/wechat) | A High Copy WeChat ,SNS APP
[BlurTestAndroid](https://github.com/patrickfav/BlurTestAndroid) | This is a simple App to test some blur algorithms on their visual quality and performance
[card.io-Android-source](https://github.com/card-io/card.io-Android-source) | The open-source code for the card.io-Android-SDK: provides fast, easy credit card scanning in mobile apps
[JamsMusicPlayer](https://github.com/psaravan/JamsMusicPlayer) | A free, powerful and elegant music player for Android
[Reflection No Reflection](https://github.com/stephanenicolas/reflection-no-reflection) | A proof on concept to create an API that is 100% compatible reflection API, but without any reflection. Performance stuff for Android and Java
[Mizuu](https://github.com/MizzleDK/Mizuu) | Popular media indexer app for Android
[Mover](https://github.com/Codetail/Mover) | Client for local youtube alternative site, Project closed, because of user agreement violation and will not be supported, but pull requests & issues will be cool
[Talon-for-Twitter](https://github.com/klinker24/Talon-for-Twitter) | 100% open source version of my popular Talon for Twitter app on Android
[u2020](https://github.com/JakeWharton/u2020) | A sample Android app which showcases advanced usage of Dagger among other open source libraries
[MaterialPowerMenu](https://github.com/naman14/MaterialPowerMenu) | A demo of the power menu with Reveal and other animations
[Pocket](https://github.com/RxKotlin/Pocket) | This is a first kotlin project
[android-examples](https://github.com/nisrulz/android-examples) | Simple basic isolated apps, for budding android devs 
[googlesamples](https://github.com/googlesamples) | Google Samples
[codelabs](https://codelabs.developers.google.com/?cat=Android) | Google Developers Codelabs provide a guided, tutorial, hands-on coding experience
[android-testing](https://github.com/googlesamples/android-testing) | A collection of samples demonstrating different frameworks and techniques for automated testing
**[qualitymatters](https://github.com/artem-zinnatullin/qualitymatters)** | This is the app that follows all principles of [Android Development Culture Document](http://artemzin.com/blog/android-development-culture-the-document-qualitymatters/) 
[Bandhook-Kotlin](https://github.com/antoniolg/Bandhook-Kotlin) | A showcase music app for Android entirely written using Kotlin language
[android-kotlin-samples](https://github.com/irontec/android-kotlin-samples) | Some basic samples of Kotlin for Android
[Kotlin-Example](https://github.com/myinnos/Kotlin-Example) | An example for who are all going to start learning Kotlin programming language to develop Android application

## Other 
Name | Repository
--- | ---
**[TaggerString](https://github.com/polok/TaggerString)** | TaggerString is very light library which allows to build dynamic string resource in much more readable way
**[Android-Material-Icon-Generator](https://github.com/Maddoc42/Android-Material-Icon-Generator)** | Android icons with looooong material shadows!
**[Conductor](https://github.com/bluelinelabs/Conductor)** | A small, yet full-featured framework that allows building View-based Android applications
[FileDownloader](https://github.com/lingochamp/FileDownloader) | Multitask、Breakpoint-resume、High-concurrency、Simple to use、Single/NotSingle-process
[AndroidDevTools](https://github.com/inferjay/AndroidDevTools) | Collected the required development of Android Android SDK
[gplay.ws](https://gplay.ws/) | Easily create a badge for your own android application in a single step
[Rajawali](https://github.com/Rajawali/Rajawali) | Android OpenGL ES 2.0/3.0 Engine
[scrollscreenshot](https://github.com/PGSSoft/scrollscreenshot) | Make Android screenshots of scrollable screen content
**[dex-method-counts](https://github.com/mihaip/dex-method-counts)** | Command-line tool to count per-package methods in Android .dex files
[swiftp](https://github.com/ppareit/swiftp) | FTP server for your android device
[gradle-packer-plugin](https://github.com/mcxiaoke/gradle-packer-plugin) | gradle-packer-plugin is a tool Android multi-channel package Gradle plugin can be easily automated building systems integration
[Layout-to-Image](https://github.com/vipulasri/Layout-to-Image) | Android Layout (Relative Layout, Linear Layout etc) to Image
[Android-Link-Preview](https://github.com/LeonardoCardoso/Android-Link-Preview) | It makes a preview from an url, grabbing all the information such as title, relevant texts and images. This a version for Android of my web link preview
[gifcap](https://github.com/outlook/gifcap) | Create GIFs from Android devices (pronounced "gif cap")
[android-weak-handler](https://github.com/badoo/android-weak-handler) | Memory safer implementation of android.os.Handler
[FingerprintAuthHelper](https://github.com/pro100svitlo/FingerprintAuthHelper) | A small library that allows You to easily manage fingererprint authentication inside your Activity or Fragment on devices with fingerprint scanner and Android M and higher
[bytebuddy](https://github.com/raphw/byte-buddy/) | Runtime code generation for the Java virtual machine 
[Androl4b](https://github.com/sh4hin/Androl4b) | A Virtual Machine For Assessing Android applications, Reverse Engineering and Malware Analysis
[sl4a](https://github.com/damonkohler/sl4a) | SL4A brings scripting languages to Android by allowing you to edit and execute scripts and interactive interpreters directly on the Android device
[transai](https://github.com/Jintin/transai) | transai is a command line tool to help you do Android and iOS translation management. You can extract string files to csv format, or generate string files from csv file for both Android, iOS and Mac
[magellan](https://github.com/wealthfront/magellan) | The simplest navigation library for Android
[condom](https://github.com/oasisfeng/condom) | Condom is a thin library to wrap the naked Context in your Android project before passing it to the 3rd-party SDK
[DroidPlugin](https://github.com/DroidPluginTeam/DroidPlugin) | It enables the host app run any third-party apk without installation, modification and repackage, which benefit a lot for collaborative development on Android
[screenshott](https://github.com/nisrulz/screenshott) | Take a screenshot of your view layout , programmatically!
[packagehunter](https://github.com/nisrulz/packagehunter) | Hunt down all package information
[zentone](https://github.com/nisrulz/zentone) | Easily generate pure audio tone of any frequency in android
[ActivityRouter](https://github.com/mzule/ActivityRouter) | Router activities and methods with url for android
[ReLinker](https://github.com/KeepSafe/ReLinker) | ReLinker fixes these issues by replacing the standard System.loadLibrary call with a more reliable implementation
[davdroid](https://github.com/bitfireAT/davdroid) | DAVdroid – CalDAV/CardDAV synchronization for Android 4+ devices
**[java-error-handler](https://github.com/Workable/java-error-handler)** | Error handling library for Android and Java
[USB-Device-Info](https://github.com/alt236/USB-Device-Info---Android) | This application will provide information about almost all currently plugged-in USB devices
[usb-serial-for-android](https://github.com/mik3y/usb-serial-for-android) | Android USB host serial driver library for CDC, FTDI, Arduino and other devices
**[Android-Material-Design-Colors](https://github.com/wada811/Android-Material-Design-Colors)** | Android Material Design Colors
**[keyboard-dismisser](https://github.com/GabrielSamojlo/keyboard-dismisser)** | Dismiss your keyboard by tapping anywhere outside it
[PdfMyXml](https://github.com/HendrixString/Android-PdfMyXml) | convert android xml layouts into PDF document, works on all versions of Android
[dexposed](https://github.com/alibaba/dexposed) | dexposed enable 'god' mode for single android application

## About Me
- Github:  https://github.com/thanhtoan1196
- Facebook: https://www.facebook.com/thanhtoan1196       
- Email: thanhtoan1196@gmail.com

## License

    Copyright 2017 Tran Van Thanh Toan

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.