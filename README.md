List of Android Libraries [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/thanhtoan1196/awesome-android)
======================
A curated list of awesome Android libraries. Feel free to contrubute.

## Other Awesome List
- [awesome-android](https://github.com/thanhtoan1196/awesome-android)
- [awesome-android-ui](https://github.com/thanhtoan1196/awesome-android-ui)

## Index
- [Networking](#networking)
- [Image Loader](#image-loader)
- [Drawable](#drawable)
- [Dependency Injections](#dependency-injections)
- [JSON](#json)
- [O/R Mapping](#or-mapping)
- [NoSQL](#nosql)
- [Pub/Sub](#pubsub)
- [Logger](#logger)
- [Background Processing](#background-processing)
- [Fonts](#fonts)
- [Video](#video)
- [Parcelables](#parcelables)
- [Functional Programming](#functional-programming)
  - [Adding Java-8 Functional Programming Features](#adding-java-8-functional-programming-features)
  - [Functional Reactive Programming](#functional-reactive-programming)
- [Social Networks](#social-networks)
- [WebRTC](#webrtc)
- [Image Processing](#image-processing)
- [Camera](#camera)
- [Security](#security)
- [Media](#media)
- [Showcases](#showcases)
- [Maps](#maps)
- [Other](#other)

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
**[robospice](https://github.com/stephanenicolas/robospice)** | RoboSpice is a modular android library that makes writing asynchronous network requests easy
**[ReactiveNetwork](https://github.com/pwittchen/ReactiveNetwork)** | Android library listening network connection state and Internet connectivity with RxJava Observables
[NetworkEvents](https://github.com/pwittchen/NetworkEvents) | Android library listening network connection state and change of the WiFi signal strength with event bus
[ReactiveWiFi](https://github.com/pwittchen/ReactiveWiFi) | Android library listening available WiFi Access Points and related information with RxJava Observables
[node-android](https://github.com/InstantWebP2P/node-android) | Run Node.js on Android by rewrite Node.js in Java with the compatible API

## Image Loader
Name | Repository
--- | ---
**[Glide](https://github.com/bumptech/glide)** | An image loading and caching library for Android focused on smooth scrolling
[Fresco](http://frescolib.org) | An Android library for managing images and the memory they use
[ion](https://github.com/koush/ion) | Android Asynchronous Networking and Image Loading
[Picasso](https://github.com/square/picasso) | A powerful image downloading and caching library for Android
[Universal Image Loader](https://github.com/nostra13/Android-Universal-Image-Loader) | Powerful and flexible library for loading, caching and displaying images on Android

## Dependency Injections
Name | Repository
--- | ---
**[Dagger 2](https://github.com/google/dagger)** | A fast dependency injector for Android and Java
**[Butter Knife](https://github.com/JakeWharton/butterknife)** | Bind Android views and callbacks to fields and methods
**[AndroidAnnotations](https://github.com/androidannotations/androidannotations)** | Fast Android Development. Easy maintainance

## Code Generation
Name | Repository
--- | ---
**[Favor](https://github.com/soarcn/Favor)** | A easy way to use android sharepreference
[barber](https://github.com/hzsweers/barber) | A custom view styling library for Android that generates the obtainStyledAttributes() and TypedArray boilerplate code for yo
[android-contentprovider-generator](https://github.com/BoD/android-contentprovider-generator) | A tool to generate Android ContentProviders
[javapoet](https://github.com/square/javapoet) | A Java API for generating .java source files
**[parceler](https://github.com/johncarl81/parceler)** | Android Parcelables made easy through code generation
[auto-parcel](https://github.com/frankiesardo/auto-parcel) | Android Parcelable models made easy

## JSON 
Name | Repository
--- | ---
**[Gson](https://github.com/google/gson)** | A Java serialization/deserialization library to convert Java Objects into JSON and back
[moshi](https://github.com/square/moshi) | A modern JSON library for Android and Java
[ig-json-parser](https://github.com/Instagram/ig-json-parser) | Fast JSON parser for java projects
[Jackson](http://jackson.codehaus.org/) |  Formerly known as the standard JSON library for Java

## O/R Mapping 
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

## Pub/Sub
Name | Repository
--- | ---
[EventBus](https://github.com/greenrobot/EventBus) | Android optimized event bus that simplifies communication between Activities, Fragments, Threads, Services, etc
[AndroidEventBus](https://github.com/hehonghui/AndroidEventBus) | A lightweight eventbus library for android, simplifies communication between Activities, Fragments, Threads, Services, etc
[Otto](https://github.com/square/otto) | An enhanced Guava-based event bus with emphasis on Android suppor
[drekkar](https://github.com/coshx/drekkar) | An Android event bus for WebView and JS

## Logger
Name | Repository
--- | ---
**[Hugo](https://github.com/JakeWharton/hugo)** | Annotation-triggered method call logging for your debug builds
**[logger](https://github.com/orhanobut/logger)** | Simple, pretty and powerful logger for android
**[LoggingInterceptor](https://github.com/ihsanbal/LoggingInterceptor)** | An OkHttp interceptor which pretty logs request and response data
**[Timber](https://github.com/JakeWharton/timber)** | A logger with a small, extensible API which provides utility on top of Android's normal Log class
[logback-android](https://github.com/tony19/logback-android) | The reliable, generic, fast and flexible logging framework for Java on Android
[pidcat](https://github.com/JakeWharton/pidcat) | Colored logcat script which only shows log entries for a specific application package

## Background Processing
Name | Repository
--- | ---
[Android Priority Job Queue](https://github.com/yigit/android-priority-jobqueue) | A Job Queue specifically written for Android to easily schedule jobs (tasks) that run in the background, improving UX and application stability
[android-job](https://github.com/evernote/android-job) | Android library to handle jobs in the background
[Tape](https://github.com/square/tape) | A lightning fast, transactional, file-based FIFO for Android and Java
[Zorn](https://github.com/HendrixString/Android-Zorn) | Async Workers and Worker managers for Android

## Fonts
Name | Repository
--- | ---
[Calligraphy](https://github.com/chrisjenx/Calligraphy) | Custom fonts in Android the easy way
 
## Video
Name | Repository
--- | ---
[ExoPlayer](https://github.com/google/ExoPlayer) | https://github.com/google/ExoPlayer
[ijkplayer](https://github.com/bbcallen/ijkplayer) | https://github.com/bbcallen/ijkplayer
[mp4parser](https://code.google.com/p/mp4parser/) | https://github.com/sannies/mp4parser

## Parcelables
Name | Repository
--- | ---
[Akatsuki](https://github.com/tom91136/Akatsuki) | https://github.com/tom91136/Akatsuki
[Icepick](https://github.com/frankiesardo/icepick) | https://github.com/frankiesardo/icepick
[Parceler](https://github.com/johncarl81/parceler) | https://github.com/johncarl81/parceler
[icicle](https://github.com/segunfamisa/icicle) | https://github.com/segunfamisa/icicle
[ActivityStarter](https://github.com/MarcinMoskala/ActivityStarter) | https://github.com/MarcinMoskala/ActivityStarter

## Social Networks
Name | Repository
--- | ---
[ASNE](https://github.com/gorbin/ASNE) | https://github.com/gorbin/ASNE
[SocialLoginManager](https://github.com/jaychang0917/SocialLoginManager) |
[SocialAuthHelper](https://github.com/stfalcon-studio/SocialAuthHelper) |

## WebRTC
Name | Repository
--- | ---
[AndroidRTC](https://github.com/pchab/AndroidRTC) | https://github.com/pchab/AndroidRTC

## Image Processing
Name | Repository
--- | ---
[pollexor](https://github.com/square/pollexor) |
[GPUImage for Android](https://github.com/CyberAgent/android-gpuimage) | https://github.com/CyberAgent/android-gpuimage
[Compressor](https://github.com/zetbaitsu/Compressor) | Compressor is a lightweight and powerful android image compression library, also support RxJava
[Tiny](https://github.com/Sunzxyong/Tiny) |

## Camera
Name | Repository
--- | ---
[Landscape video camera](https://github.com/jmolsmobile/LandscapeVideoCamera) | https://github.com/jmolsmobile/LandscapeVideoCamera
[EasyCamera](https://github.com/Glamdring/EasyCamera) | https://github.com/Glamdring/EasyCamera

## Build
Name | Repository
--- | ---

## Security
Name | Repository
--- | ---
[Grab'n Run](https://github.com/lukeFalsina/Grab-n-Run) | https://github.com/lukeFalsina/Grab-n-Run

## Media
Name | Repository
--- | ---
[PdfMyXml](https://github.com/HendrixString/Android-PdfMyXml) | https://github.com/HendrixString/Android-PdfMyXml
[MediaRecorderDialog](https://github.com/alhazmy13/MediaRecorderDialog) | 

## Maps
Name | Repository
--- | ---
[GraphHopper](https://graphhopper.com) | https://github.com/graphhopper/graphhopper
[Mapsforge](https://github.com/mapsforge/mapsforge) | https://github.com/mapsforge/mapsforge

## Time
Name | Repository
--- | ---
[Joda Time Android](https://github.com/dlew/joda-time-android) | https://github.com/dlew/joda-time-android
[ThreeTenABP](https://github.com/JakeWharton/ThreeTenABP) |
[truetime-android](https://github.com/instacart/truetime-android) |

## Notifications
Name | Repository
--- | ---
[android-remote-notifications](https://github.com/kaiwinter/android-remote-notifications) | 
[AndroidHeartBeatFixer](https://github.com/joaopedronardari/AndroidHeartBeatFixer) |

## Applink 
Name | Repository
--- | ---
[Bolts](https://github.com/BoltsFramework/Bolts-Android) | https://github.com/BoltsFramework/Bolts-Android

## Security
Name | Repository
--- | ---
[Secure Preference Manager](http://prashantsolanki3.github.io/Secure-Pref-Manager/) | http://prashantsolanki3.github.io/Secure-Pref-Manager/
[Secure-Pref-Manager](https://github.com/prashantsolanki3/Secure-Pref-Manager) | https://github.com/prashantsolanki3/Secure-Pref-Manager

## Hotfix
Name | Repository
--- | ---
[tinker](https://github.com/Tencent/tinker) | Tinker is a hot-fix solution library for Android, it supports dex, library and resources update without reinstall apk
[Amigo](https://github.com/eleme/Amigo) | A hotfix library for Android platform, and not just this...
[AndFix](https://github.com/alibaba/AndFix) | AndFix is a library that offer hot-fix for Android App.
[DroidFix](https://github.com/bunnyblue/DroidFix) | 
[HotFix](https://github.com/dodola/HotFix) | 
[Nuwa](https://github.com/jasonross/Nuwa) | Nuwa, pure java implementation, can hotfix your android application.
[dexposed](https://github.com/alibaba/dexposed) | dexposed enable 'god' mode for single android application.
[Fit](https://github.com/KeithYokoma/Fit) | 

## Showcases
Name | Repository
--- | ---
[android-best-practices](https://github.com/futurice/android-best-practices) | https://github.com/futurice/android-best-practices
[BlurTestAndroid](https://github.com/patrickfav/BlurTestAndroid) | https://github.com/patrickfav/BlurTestAndroid | Unknown
[card.io-Android-source](https://github.com/card-io/card.io-Android-source) | https://github.com/card-io/card.io-Android-source
[iosched](https://github.com/google/iosched) | https://github.com/google/iosched
[JamsMusicPlayer](https://github.com/psaravan/JamsMusicPlayer) | https://github.com/psaravan/JamsMusicPlayer
[Reflection No Reflection](https://github.com/stephanenicolas/reflection-no-reflection) | https://github.com/stephanenicolas/reflection-no-reflection
[Mizuu](http://mizuu.tv/) | https://github.com/MizzleDK/Mizuu
[Mover](http://mover.uz) | https://github.com/Codetail/Mover
[Talon-for-Twitter](https://github.com/klinker24/Talon-for-Twitter) | https://github.com/klinker24/Talon-for-Twitter
[Telecine](https://github.com/JakeWharton/Telecine) | https://github.com/JakeWharton/Telecine
[u2020](https://github.com/JakeWharton/u2020) | https://github.com/JakeWharton/u2020
[MaterialPowerMenu](https://github.com/naman14/MaterialPowerMenu) | https://github.com/naman14/MaterialPowerMenu

## Performance_Tools
Name | Repository
--- | ---
[leakcanary](https://github.com/square/leakcanary) | https://github.com/square/leakcanary
[AndroidPerformanceMonitor](https://github.com/markzhai/AndroidPerformanceMonitor) | https://github.com/markzhai/AndroidPerformanceMonitor
[TinyDancer](https://github.com/friendlyrobotnyc/TinyDancer) | ![](https://raw.githubusercontent.com/brianPlummer/TinyDancer/master/assets/tiny_dancer_011_example.gif)
[ANR-WatchDog](https://github.com/SalomonBrys/ANR-WatchDog) |
[Packetzoom](https://packetzoom.com/blog/introducing-http-optimizer-and-analytics-service.html) |

## Gradle
Name | Repository
--- | ---
[gradle-play-publisher](https://github.com/Triple-T/gradle-play-publisher) | https://github.com/Triple-T/gradle-play-publisher
[dexcount-gradle-plugin](https://github.com/KeepSafe/dexcount-gradle-plugin) | https://github.com/KeepSafe/dexcount-gradle-plugin

## Intellij IDEA / Android Studio
Name | Repository
--- | ---
[android-xml-sorter](https://github.com/roana0229/android-xml-sorter) | 
[android-material-design-icon-generator-plugin](https://github.com/konifar/android-material-design-icon-generator-plugin) | 
[android-selector-chapek](https://github.com/inmite/android-selector-chapek) | 
[android-parcelable-intellij-plugin](https://github.com/mcharmas/android-parcelable-intellij-plugin) | 
[adb-idea](https://github.com/pbreault/adb-idea) | 
[android-butterknife-zelezny](https://github.com/avast/android-butterknife-zelezny) | 
[GsonFormat](https://github.com/zzz40500/GsonFormat) | 
[CodeGlance](https://github.com/Vektah/CodeGlance) | 
[ADBWIFI](https://github.com/layerlre/ADBWIFI) | 
[android-styler](https://github.com/alexzaitsev/android-styler) | 
[android-drawable-importer-intellij-plugin](https://github.com/winterDroid/android-drawable-importer-intellij-plugin) | 
[genymotion](https://plugins.jetbrains.com/plugin/7269-genymotion) | 
[dagger-intellij-plugin](https://github.com/square/dagger-intellij-plugin) | 
[gradle-dependencies-helper](https://plugins.jetbrains.com/plugin/7299-gradle-dependencies-helper) | 
[AndroidProguardPlugin](https://github.com/zhonghanwen/AndroidProguardPlugin) | 
[idea-markdown](https://github.com/nicoulaj/idea-markdown) |
[idea-multimarkdown](https://github.com/vsch/idea-multimarkdown) | 
[folding-plugin](https://github.com/dmytrodanylyk/folding-plugin) | 
[gradle-retrolambda](https://github.com/evant/gradle-retrolambda) | 
[idea-gitignore](https://github.com/hsz/idea-gitignore) | 
[checkstyle-idea](https://github.com/jshiell/checkstyle-idea) | 
[permissions-dispatcher-plugin](https://github.com/shiraji/permissions-dispatcher-plugin) | 
[jetbrains-wakatime](https://github.com/wakatime/jetbrains-wakatime) | 
[AndroidWiFiADB](https://github.com/pedrovgs/AndroidWiFiADB) | 
[AndroidLocalizationer](https://github.com/westlinkin/AndroidLocalizationer) | 
[]() | 

## Injector
Name | Repository
--- | ---
[androidannotations](https://github.com/androidannotations/androidannotations) |
[butterknife](https://github.com/JakeWharton/butterknife) |
[dagger](https://github.com/google/dagger) |
[preferencebinder](https://github.com/denley/preferencebinder) |
[fragmentargs](https://github.com/sockeqwe/fragmentargs) |
[transfuse](https://github.com/johncarl81/transfuse) |
[]() |

## Injector
Name | Repository
--- | ---
[OnActivityResult](https://github.com/vanniktech/OnActivityResult) |

## Kotlin
Name | Repository
--- | ---
[anko](https://github.com/Kotlin/anko) |
[kotterknife](https://github.com/JakeWharton/kotterknife) |
[KAndroid](https://github.com/pawegio/KAndroid) |
[android-kotlin-samples](https://github.com/irontec/android-kotlin-samples) |
[Kotlin-Example](https://github.com/myinnos/Kotlin-Example) |
[Pocket](https://github.com/RxKotlin/Pocket) |
[KPreferences](https://github.com/mohamad-amin/KPreferences) |
[]() |

## Adapter
Name | Repository
--- | ---
[SuperAdapter](https://github.com/byteam/SuperAdapter) |
[LastAdapter](https://github.com/nitrico/LastAdapter) |
[Renderers](https://github.com/pedrovgs/Renderers) |
[EfficientAdapter](https://github.com/StanKocken/EfficientAdapter) |
[RxRecyclerAdapter](https://github.com/ahmedrizwan/RxRecyclerAdapter) |
[]() |
[]() |

## Validation
Name | Repository
--- | ---
[android-saripaar](https://github.com/ragunathjawahar/android-saripaar) |
[Android-Validator](https://github.com/throrin19/Android-Validator) |
[android-validation-komensky](https://github.com/inmite/android-validation-komensky) |
[AwesomeValidation](https://github.com/thyrlian/AwesomeValidation) |
[NextInputs](https://github.com/yoojia/NextInputs) |
[android-complexify](https://github.com/infinum/android-complexify) |

## Gesture
Name | Repository
--- | ---
[sensey](https://github.com/nisrulz/sensey) |

## Bluetooth
Name | Repository
--- | ---
[android-beacon-library](https://github.com/AltBeacon/android-beacon-library) |
[Android-BluetoothSPPLibrary](https://github.com/akexorcist/Android-BluetoothSPPLibrary) |
[AndroidSmoothBluetooth](https://github.com/palaima/AndroidSmoothBluetooth) |
[android-lite-bluetoothLE](https://github.com/litesuits/android-lite-bluetoothLE) |
[BluetoothHelper](https://github.com/a-voyager/BluetoothHelper) |
[SmartGattLib](https://github.com/movisens/SmartGattLib) | SmartGattLib is a Java library that simplifies the work with Bluetooth SMART devices
[Bluetooth-LE-Library](https://github.com/alt236/Bluetooth-LE-Library---Android) |
[Blueteeth](https://github.com/RobotPajamas/Blueteeth) |

## SocialNetworks
Name | Repository
--- | ---
[AndroidSocialNetworks](https://github.com/antonkrasov/AndroidSocialNetworks) |

## Media
Name | Repository
--- | ---
[AndroidVideoCache](https://github.com/danikula/AndroidVideoCache) |
[FFmpeg](https://github.com/FFmpeg/FFmpeg) |
[libstreaming](https://github.com/fyhertz/libstreaming) |
[AndroidFFmpeg](https://github.com/appunite/AndroidFFmpeg) |
[android-ffmpeg-java](https://github.com/guardianproject/android-ffmpeg-java) |
[android-ffmpeg](https://github.com/guardianproject/android-ffmpeg) |
[mp4parser](https://github.com/sannies/mp4parser) |
[jcodec](https://github.com/jcodec/jcodec) |
[ipcam-view](https://github.com/niqdev/ipcam-view) |
[AndroidAudioConverter](https://github.com/adrielcafe/AndroidAudioConverter) |
[AudioPlayerView](https://github.com/HugoMatilla/AudioPlayerView) |
[UserAwareVideoView](https://github.com/kevalpatel2106/UserAwareVideoView) |
[android-ffmpeg-with-rtmp](https://github.com/cine-io/android-ffmpeg-with-rtmp) |
[ipcam-view](https://github.com/niqdev/ipcam-view) |
[FFmpeg-Android](https://github.com/OnlyInAmerica/FFmpeg-Android) |

## Embedded
Name | Repository
--- | ---
[usb-serial-for-android](https://github.com/mik3y/usb-serial-for-android) |

## Utility
Name | Repository
--- | ---
[easydeviceinfo](https://github.com/nisrulz/easydeviceinfo) |
[apk-parser](https://github.com/clearthesky/apk-parser) |
[APKParser](https://github.com/jaredrummler/APKParser) |
[JustWeTools](https://github.com/lfkdsk/JustWeTools) |
[AndroidProcesses](https://github.com/jaredrummler/AndroidProcesses) |
[AndroidProcess](https://github.com/wenmingvs/AndroidProcess) |
[tape](https://github.com/square/tape) |
[ColorArt](https://github.com/MichaelEvans/ColorArt) |
[timber](https://github.com/JakeWharton/timber) |
[wire](https://github.com/square/wire) |
[vector-compat](https://github.com/wnafee/vector-compat) |
[sharp](https://github.com/Pixplicity/sharp) |
[svgkit-android](http://scand.com/products/svgkit-android/index.html) |
[CalDAV/CardDAV](https://davdroid.bitfire.at/) |
[phrase](https://github.com/square/phrase) |
[seismic](https://github.com/square/seismic) |
[AndroidFaceCropper](https://github.com/lafosca/AndroidFaceCropper) |
[autobahn-java](https://github.com/crossbario/autobahn-java) |
[android_dbinspector](https://github.com/infinum/android_dbinspector) |
[joda-time-android](https://github.com/dlew/joda-time-android) |
[open-keychain](https://github.com/open-keychain/open-keychain) |
[Reservoir](https://github.com/anupcowkur/Reservoir) |
[EasyCamera](https://github.com/Glamdring/EasyCamera) |
[CastCompanionLibrary-android](https://github.com/googlecast/CastCompanionLibrary-android) |
[cling](https://github.com/4thline/cling) |
[secure-preferences](https://github.com/scottyab/secure-preferences) |
[TypedPreferences](https://github.com/johnjohndoe/TypedPreferences) |
[android-intents](https://github.com/marvinlabs/android-intents) |
[esperandro](https://github.com/dkunzler/esperandro) |
[AndroidCommons](https://github.com/alexvasilkov/AndroidCommons) |
[essentials](https://github.com/greenrobot/essentials) |
[puree-android](https://github.com/cookpad/puree-android) |
[hawk](https://github.com/orhanobut/hawk) |
[caffeine](https://github.com/percolate/caffeine) |
[tray](https://github.com/grandcentrix/tray) |
[colorize](https://github.com/cesarferreira/colorize) |
[IntentBuilder](https://github.com/emilsjolander/IntentBuilder) |
[RoboGif](https://github.com/izacus/RoboGif) |
[Foredroid](https://github.com/steveliles/Foredroid) |
[slinger](https://github.com/allegro/slinger) |
[CacheUtilsLibrary](https://github.com/westlinkin/CacheUtilsLibrary) |
[Treasure](https://github.com/baoyongzhang/Treasure) |
[Ok2Curl](https://github.com/mrmike/Ok2Curl) |
[thrifty](https://github.com/microsoft/thrifty) |
[KotlinPreferences](https://github.com/MarcinMoskala/KotlinPreferences) |
[ConcealSharedPreference-Android](https://github.com/afiqiqmal/ConcealSharedPreference-Android) |

## SDK
Name | Repository
--- | ---
[android-checkout](https://github.com/serso/android-checkout) |
[WeatherLib](https://github.com/survivingwithandroid/WeatherLib) |
[aws-sdk-android](https://github.com/aws/aws-sdk-android) |
[evernote-sdk-android](https://github.com/evernote/evernote-sdk-android) |
[ANE-Facebook](https://github.com/freshplanet/ANE-Facebook) |
[socialauth-android](https://github.com/3pillarlabs/socialauth-android) |
[PayPal-Android-SDK](https://github.com/paypal/PayPal-Android-SDK) |
[Applozic-Android-SDK](https://github.com/AppLozic/Applozic-Android-SDK) |
[donations](https://github.com/SufficientlySecure/donations) |
[card.io-Android-SDK](https://github.com/card-io/card.io-Android-SDK) |
[Android-ReactiveLocation](https://github.com/mcharmas/Android-ReactiveLocation) |
[Twitter-Helper](https://github.com/krazykira/Twitter-Helper) |
[liquid-sdk-android](https://github.com/lqd-io/liquid-sdk-android) |
[cloudrail](https://cloudrail.com) |
[cloudrail-si-android-sdk](https://github.com/CloudRail/cloudrail-si-android-sdk/) |
[qiscus-sdk-android](https://github.com/qiscus/qiscus-sdk-android) |
[ChatKit](https://github.com/stfalcon-studio/ChatKit) |
[thumbor](https://github.com/thumbor/thumbor) |
[ParseAlternativesServices](https://github.com/minhhuy150894/ParseAlternativesServices) |
[deepstream.io](https://github.com/deepstreamIO/deepstream.io) |
[open-weather-retriever-z](https://github.com/czack810150/open-weather-retriever-z) |
[HockeySDK-Android](https://github.com/bitstadium/HockeySDK-Android) |

## M
Name | Repository
--- | ---
[smart-location-lib](https://github.com/mrmans0n/smart-location-lib) |
[Google-Directions-Android](https://github.com/jd-alexander/Google-Directions-Android) |
[android-maps-extensions](https://github.com/mg6maciej/android-maps-extensions) |
[MapScaleView](https://github.com/pengrad/MapScaleView) |
[android-maps-utils](https://github.com/googlemaps/android-maps-utils) |
[AirMapView](https://github.com/airbnb/AirMapView) |

## Test
Name | Repository
--- | ---
[macaca-android](https://github.com/macacajs/macaca-android) |
[junit4](https://github.com/junit-team/junit4) |
[robotium](https://github.com/RobotiumTech/robotium) |
[stf](https://github.com/openstf/stf) |
[assertj-android](https://github.com/square/assertj-android) |
[selendroid](https://github.com/selendroid/selendroid) |
[Cafe](https://github.com/BaiduQA/Cafe) |
[android-junit-report](https://github.com/jsankey/android-junit-report) |
[powermock](https://github.com/powermock/powermock) |
[green-coffee](https://github.com/mauriciotogneri/green-coffee) |
[robolectric](https://github.com/robolectric/robolectric) |
[spoon](https://github.com/square/spoon) |
[sixpack-java](https://github.com/sixpack/sixpack-java) |
[RESTMock](https://github.com/andrzejchm/RESTMock) | REST API mocking made easy

## Tracking
Name | Repository
--- | ---
[MobileAppTracking](https://www.tune.com/) |
[Mixpanel](https://mixpanel.com/) |
[Countly](https://count.ly) |
[CleverTap](https://clevertap.com) |

## Debug
Name | Repository
--- | ---
[stf](https://github.com/openstf/stf) |
[Android-Debug-Database](https://github.com/amitshekhariitbhu/Android-Debug-Database) |
[under-the-hood](https://github.com/patrickfav/under-the-hood) |
[uber-adb-tools](https://github.com/patrickfav/uber-adb-tools) |
[debug-bottle](https://github.com/kiruto/debug-bottle) |
[ViewInspector](https://github.com/xfumihiro/ViewInspector) |
[scalpel](https://github.com/JakeWharton/scalpel) |
[stetho](https://github.com/facebook/stetho) |
[BlockCanaryEx](https://github.com/seiginonakama/BlockCanaryEx) |
[debugkit](https://github.com/hulab/debugkit) |
[AppMethodOrder](https://github.com/zjw-swun/AppMethodOrder) |
[Takt](https://github.com/wasabeef/Takt) | ![](https://github.com/wasabeef/Takt/raw/master/art/takt.gif)
[uber-apk-signer](https://github.com/patrickfav/uber-apk-signer) | 
[Traceur](https://github.com/T-Spoon/Traceur) | 
[Android-DebugPort](https://github.com/jasonwyatt/Android-DebugPort) | 
[AndroidSnooper](https://github.com/jainsahab/AndroidSnooper) | 
[debug-artist](https://github.com/baristaventures/debug-artist) | 

## App / Demo
Name | Repository
--- | ---
[MovieGuide](https://github.com/esoxjem/MovieGuide) |
[android-support-23.2-sample](https://github.com/liaohuqiu/android-support-23.2-sample) |
[MusicDNA](https://github.com/harjot-oberai/MusicDNA) |
[remusic](https://github.com/aa112901/remusic) |
[Bandhook-Kotlin](https://github.com/antoniolg/Bandhook-Kotlin) |
[LeeCo](https://github.com/Nightonke/LeeCo) |
[Tower](https://github.com/DroidPlanner/Tower) |
[Telecine](https://github.com/JakeWharton/Telecine) |
[FlyRefresh](https://github.com/race604/FlyRefresh) |
[Etar-Calendar](https://github.com/xsoh/Etar-Calendar) |
[HomeMirror](https://github.com/HannahMitt/HomeMirror) |
[TranslateApp](https://github.com/maoruibin/TranslateApp) |
[uhabits](https://github.com/iSoron/uhabits) |
[AisenWeiBo](https://github.com/wangdan/AisenWeiBo) |
[Villains-and-Heroes](https://github.com/andremion/Villains-and-Heroes) |
[BookReader](https://github.com/JustWayward/BookReader) |
[bookdash-android-app](https://github.com/bookdash/bookdash-android-app) |
[seadroid](https://github.com/haiwen/seadroid) |
[Opengur](https://github.com/Kennyc1012/Opengur) |
[FolioReader-Android](https://github.com/FolioReader/FolioReader-Android) |
[AndroidTV-workshop](https://github.com/odigeoteam/AndroidTV-workshop) |
[android-oss](https://github.com/kickstarter/android-oss) |
[MusicDNA](https://github.com/harjot-oberai/MusicDNA) |
[Just-Another-Android-App](https://github.com/athkalia/Just-Another-Android-App) |
[open-event-android](https://github.com/fossasia/open-event-android) |
[PocketHub](https://github.com/pockethub/PocketHub) |
[ribot-app-android](https://github.com/ribot/ribot-app-android) |
[Telegram](https://github.com/DrKLO/Telegram) |
[iosched](https://github.com/google/iosched) |
[android-mvp-architecture](https://github.com/MindorksOpenSource/android-mvp-architecture) |
[GivesMeHopeAndroidClient](https://github.com/jparkie/GivesMeHopeAndroidClient) |
[EffectiveAndroidUI](https://github.com/pedrovgs/EffectiveAndroidUI) |
[philm](https://github.com/chrisbanes/philm) |
[archi](https://github.com/ivacf/archi) |
[LeafPic](https://github.com/HoraApps/LeafPic) |
[plaid](https://github.com/nickbutcher/plaid) |
[CoCoin](https://github.com/Nightonke/CoCoin) |
[SimplifyReader](https://github.com/chentao0707/SimplifyReader) |
[open-source-android-apps](https://github.com/pcqpcq/open-source-android-apps) |
[InstaMaterial](https://github.com/frogermcs/InstaMaterial) |
[kickmaterial](https://github.com/byoutline/kickmaterial) |
[android-boilerplate](https://github.com/ribot/android-boilerplate) |
[NotifyUtil](https://github.com/wenmingvs/NotifyUtil) |
[ColorfulNews](https://github.com/kaku2015/ColorfulNews) |
[SmarterStreaming](https://github.com/daniulive/SmarterStreaming) |
[UI-Motion](https://github.com/andremion/UI-Motion) |
[wire-android](https://github.com/wireapp/wire-android) |
[Popular-Movies-App](https://github.com/maksim-m/Popular-Movies-App) |
[e-contact-android](https://github.com/Yalantis/e-contact-android) |
[RxJava-Android-Samples](https://github.com/kaushikgopal/RxJava-Android-Samples) |
[android-architecture](https://github.com/googlesamples/android-architecture) |
[RxJava2-Android-Samples](https://github.com/amitshekhariitbhu/RxJava2-Android-Samples) |
[FlatBuffer](https://github.com/amitshekhariitbhu/FlatBuffer) |
[Mysplash](https://github.com/WangDaYeeeeee/Mysplash) |
[FastAccess](https://github.com/k0shk0sh/FastAccess) |
[JieCaoVideoPlayer](https://github.com/lipangit/JieCaoVideoPlayer) |
[MotionViews-Android](https://github.com/uptechteam/MotionViews-Android) |
[Signal-Android](https://github.com/WhisperSystems/Signal-Android) |
[wechat](https://github.com/motianhuo/wechat) |
[Etar-Calendar](https://github.com/Etar-Group/Etar-Calendar) |
[]() |
[]() |

## Security
Name | Repository
--- | ---
[tweetnacl-java](https://github.com/InstantWebP2P/tweetnacl-java) |
[AESCrypt-Android](https://github.com/scottyab/AESCrypt-Android) |

## Tracking
Name | Repository
--- | ---
[countly-sdk-android](https://github.com/Countly/countly-sdk-android) |
[mixpanel-android](https://github.com/mixpanel/mixpanel-android) |
[clevertap-android-sdk](https://github.com/CleverTap/clevertap-android-sdk) |
[tune](https://www.tune.com/) |

## Theme / Skin
Name | Repository
--- | ---
[Android-Skin-Loader](https://github.com/fengjundev/Android-Skin-Loader) |
[AndroidChangeSkin](https://github.com/hongyangAndroid/AndroidChangeSkin) |
[Colorful](https://github.com/garretyoder/Colorful) |
[aesthetic](https://github.com/afollestad/aesthetic) |
[MagicaSakura](https://github.com/Bilibili/MagicaSakura) |

## Permission
Name | Repository
--- | ---
[PermissionHelper](https://github.com/k0shk0sh/PermissionHelper) |
[Gota](https://github.com/alhazmy13/Gota) |

## Crash Monitoring
Name | Repository
--- | ---
[Fabric Crashlytics](https://get.fabric.io/)  |
[HockeyApp](https://www.hockeyapp.net/) | 
[Splunk MINT](https://mint.splunk.com/) | 
[Bugsnag](https://www.bugsnag.com/) |
[Catcho](https://github.com/alhazmy13/Catcho) | 
[Apteligent](https://www.apteligent.com/) |
[BugfenderSDK](https://github.com/bugfender/BugfenderSDK-android-sample) | https://github.com/bugfender/BugfenderSDK-android-sample
[Sherlock](https://github.com/ajitsing/Sherlock) |

## Android Wear
Name | Repository
--- | ---
[BusWear](https://github.com/tajchert/BusWear) |
[DaVinci](https://github.com/florent37/DaVinci) |
[WearMenu](https://github.com/florent37/WearMenu) |
[Teleport](https://github.com/Mariuxtheone/Teleport) |

## Security & Decompiler
Name | Repository
--- | ---
[jadx](https://github.com/skylot/jadx) |
[simplify](https://github.com/CalebFenton/simplify) |
[apk2gold](https://github.com/lxdvs/apk2gold) |
[procyon](https://bitbucket.org/mstrobel/procyon) |
[classyshark.com](http://classyshark.com/) |
[backdoor-apk](https://github.com/dana-at-cp/backdoor-apk) |
[enjarify](https://github.com/google/enjarify) |
[dexterity](https://github.com/rchiossi/dexterity) |
[android-classyshark](https://github.com/google/android-classyshark) |
[]() |

## Cache
Name | Repository
--- | ---
[DiskLruCache](https://github.com/JakeWharton/DiskLruCache) |
[ASimpleCache](https://github.com/yangfuhai/ASimpleCache) |

## Rx
Name | Repository
--- | ---
[RxJava2Interop](https://github.com/akarnokd/RxJava2Interop) |
[RxFile](https://github.com/pavlospt/RxFile) |
[RxDownload](https://github.com/ssseasonnn/RxDownload) |
[RxAndroidBle](https://github.com/Polidea/RxAndroidBle) |
[Android-ReactiveLocation](https://github.com/mcharmas/Android-ReactiveLocation) |
[rx-preferences](https://github.com/f2prateek/rx-preferences) |
[Rx.Network](https://github.com/andrefio/Rx.Network) |
[Rx.ContentObservable](https://github.com/andrefio/Rx.ContentObservable) |
[RxNetty](https://github.com/ReactiveX/RxNetty) | Reactive Extension (Rx) Adaptor for Netty

## Other 
Name | Repository
--- | ---
[Rajawali](https://github.com/Rajawali/Rajawali) |
[android-proguard-snippets](https://github.com/krschultz/android-proguard-snippets) |
[android-best-practices](https://github.com/futurice/android-best-practices) |
[maven-android-sdk-deployer](https://github.com/simpligility/maven-android-sdk-deployer) |
[scrollscreenshot](https://github.com/PGSSoft/scrollscreenshot) |
[dex-method-counts](https://github.com/mihaip/dex-method-counts) |
[swiftp](https://github.com/ppareit/swiftp) |
[TaggerString](https://github.com/polok/TaggerString) |
[svg2android](https://github.com/inloop/svg2android) |
[gplay.ws](https://gplay.ws/) |
[AndroidDevTools](https://github.com/inferjay/AndroidDevTools) |
[gradle-packer-plugin](https://github.com/mcxiaoke/gradle-packer-plugin) |
[AndroidLocalizationer](https://github.com/westlinkin/AndroidLocalizationer) |
[Layout-to-Image](https://github.com/vipulasri/Layout-to-Image) |
[vectalign](https://github.com/bonnyfone/vectalign) |
[AndResGuard](https://github.com/shwenzhang/AndResGuard) |
[Android-Material-Icon-Generator](https://github.com/Maddoc42/Android-Material-Icon-Generator) |
[Android-Link-Preview](https://github.com/LeonardoCardoso/Android-Link-Preview) |
[gifcap](https://github.com/outlook/gifcap) |
[scrollscreenshot](https://github.com/PGSSoft/scrollscreenshot) |
[maven-android-sdk-deployer](https://github.com/simpligility/maven-android-sdk-deployer) |
[FileDownloader](https://github.com/lingochamp/FileDownloader) |
[android-weak-handler](https://github.com/badoo/android-weak-handler) |
[hawk](https://github.com/orhanobut/hawk) |
[FingerprintAuthHelper](https://github.com/pro100svitlo/FingerprintAuthHelper) |
[bytebuddy](http://bytebuddy.net) |
[Androl4b](https://github.com/sh4hin/Androl4b) |
[SmartGattLib](https://github.com/movisens/SmartGattLib) |
[tape](https://github.com/square/tape) |
[sl4a](https://github.com/damonkohler/sl4a) |
[transai](https://github.com/Jintin/transai) |
[magellan](https://github.com/wealthfront/magellan) |
[condom](https://github.com/oasisfeng/condom) |
[DroidPlugin](https://github.com/DroidPluginTeam/DroidPlugin) |
[screenshott](https://github.com/nisrulz/screenshott) |
[packagehunter](https://github.com/nisrulz/packagehunter) |
[zentone](https://github.com/nisrulz/zentone) |
[ActivityRouter](https://github.com/mzule/ActivityRouter) | <img src="https://raw.githubusercontent.com/mzule/ActivityRouter/master/gif/router.gif" width="250" height="490">
[byte-buddy](https://github.com/raphw/byte-buddy) |
[CastCompanionLibrary-android](https://github.com/googlecast/CastCompanionLibrary-android) |
[ReLinker](https://github.com/KeepSafe/ReLinker) |
[davdroid](https://github.com/bitfireAT/davdroid) |
[java-error-handler](https://github.com/Workable/java-error-handler) |
[alfi](https://github.com/cesarferreira/alfi) |
[USB-Device-Info](https://github.com/alt236/USB-Device-Info---Android) |
[androidsvg](https://github.com/BigBadaboom/androidsvg) |
[SVG2Drawable](https://github.com/StanKocken/SVG2Drawable) |
[svgkit-android](http://scand.com/products/svgkit-android/index.html) |
[Android-Material-Design-Colors](https://github.com/wada811/Android-Material-Design-Colors) |
[keyboard-dismisser](https://github.com/GabrielSamojlo/keyboard-dismisser) |
[EzyLogger](https://github.com/afiqiqmal/EzyLogger) |

## Books
Name | Repository
--- | ---
[AndroidShell](https://github.com/cesards/AndroidShell) |
[android](http://guides.codepath.com/android) |
[android_guides](https://github.com/codepath/android_guides) |
[from-java-to-kotlin](https://fabiomsr.github.io/from-java-to-kotlin/) |

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