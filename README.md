# Awesome Qt
A curated list of awesome Qt and QML libraries, resources, projects, and shiny things. Inspired by [awesome-cpp](https://github.com/fffaraz/awesome-cpp) and other awesome lists.

Pull requests of new projects/apps/libraries are welcome :)

- [Awesome Qt/QML](#awesome-qt-qml)
    - [Android](#android)
    - [Apple iOS](#apple-ios)
    - [Async](#async)
    - [Binding](#binding)
    - [Compression](#compression)
    - [Cryptography](#cryptography)
    - [Database](#database)
    - [Development](#development)
    - [Editor Integration](#editor-integration)
    - [Game Engine](#game-engine)
    - [Graphics](#graphics)
    - [Hardware](#hardware)
    - [Images](#images)
    - [Javascript](#javascript)
    - [JSON](#json)
    - [Logging](#logging)
    - [Math](#math)
    - [Misc](#misc)
    - [Multimedia](#multimedia)
    - [Networking](#networking)
    - [Package Manager](#package-manager)
    - [QML Specific](#qml-specific)
    - [SDKs](#sdks)
    - [Styling](#styling)
    - [Templates](#templates)
    - [Testing](#testing)
    - [Visualization](#visualization)
    - [Web Frameworks](#web-frameworks)
    - [X11/Wayland](#x11wayland)
- [Software](#software)

## Android
* [androidnative.pri](https://github.com/benlau/androidnative.pri) - Calling Android functions from Qt without using JNI.
* [quickandroid](https://github.com/benlau/quickandroid) - QML Theme and Component Library for Android.
* [QuteLauncher](https://github.com/Iktwo/QuteLauncher) - QML Android Launcher.
* [QtVlcMediaPlayer](https://github.com/mzafers/QtVlcMediaPlayer) - LibVLC integrated Qt QML MediaPlayer for Android.
* [qmlcontactlist](https://github.com/tripolskypetr/qmlcontactlist) - The easy way to extend contacts from android to qml.
* [qml-filedialog](https://github.com/dobokirisame/qml-filedialog) - Qt Quick File picker.
* [QtAndroidTools](https://github.com/FalsinSoft/QtAndroidTools) - QtAndroidTools is a library that allows to simplify access to some native Android features from QML.

## Apple iOS
* [quickios](https://github.com/benlau/quickios) - QML Theme and Component Library for iOS.
* [CuteContacts-iOS](https://github.com/amarchen/CuteContacts-iOS) - Qt/QML-based clone of iOS7 contacts application UI.

## Async
* [QuickStreams](https://qbeon.github.io/QuickStreams/) - An asynchronous programming library for the QML programming language ([source](https://github.com/qbeon/QuickStreams)).
* [asyncfuture](https://github.com/benlau/asyncfuture) - AsyncFuture - Use QFuture like a Promise object.
* [quickpromise](https://github.com/benlau/quickpromise) - Quick Promise - QML Promise Library.
* [quickfuture](https://github.com/benlau/quickfuture) - Using QFuture in QML.

## Binding
* [Language Bindings](https://wiki.qt.io/Language_Bindings) - List of available bindings, maintained in the Qt Wiki.
* [Language Bindings](https://en.wikipedia.org/wiki/List_of_language_bindings_for_Qt_5) - List of language bindings, maintained on Wikipedia.
* [Qml.Net](https://github.com/pauldotknopf/Qml.Net) - Qml.Net is cross-platform integration of Qml/QtQuick for .NET Core/.NET Framework/Mono. It is a binding that brings .NET types into JavaScript with full interoperability.
* [DOtherside](https://github.com/filcuc/DOtherSide) - C language library for creating bindings for the Qt QML language.
* [Bindgen](https://github.com/Papierkorb/bindgen/) - Binding and wrapper generator for C++ libraries, focused on Crystal.
* [qt5.cr](https://github.com/Papierkorb/qt5.cr) - Bindings to Crystal via Bindgen. 
* [PyQt](http://www.riverbankcomputing.com/software/pyqt/) - PyQt is a set of Python v2 and v3 bindings for Qt and runs on all platforms supported by Qt including Windows, MacOS/X and Linux. PyQt5 supports Qt v5.
* [PySide](http://qt-project.org/wiki/PySide) - The PySide project provides LGPL-licensed Python bindings for the Qt. It also includes complete toolchain for rapidly generating bindings for any Qt-based C++ class hierarchies.
* [PyOtherSide](http://thp.io/2011/pyotherside/) - A Qt 5 QML Plugin that provides access to a Python 3 interpreter from QML.
* [go-qt](https://github.com/therecipe/qt) - Qt binding for Go (Golang) with support for Windows / macOS / Linux / Android / iOS / Sailfish OS / Raspberry Pi / AsteroidOS.
* [qmlrs](https://github.com/cyndis/qmlrs) - qmlrs allows the use of QML/QtQuick code from Rust.
* [libqmlbind](https://github.com/seanchas116/libqmlbind) - A C library for creating QML bindings for other languages easily through exporting objects to QML.
* [lablqml](https://github.com/Kakadu/lablqml) - Let's write QML/QtQuick GUI's for OCaml and Reason.
* [pythonqt](http://pythonqt.sourceforge.net) - A library for embedding Python into your application.

## Compression
* [KArchive](https://projects.kde.org/projects/frameworks/karchive) - A library for creating, reading, writing and manipulating file archives like zip and tar. It also provides transparent compression and decompression of data, using formats like gzip, via a subclass of QIODevice.

## Cryptography
* [Qt Cryptographic Architecture (QCA)](http://delta.affinix.com/qca/) - Taking a hint from the similarly-named Java Cryptography Architecture, QCA aims to provide a straightforward and cross-platform crypto API, using Qt datatypes and conventions.

## Database
* [QxOrm](http://www.qxorm.com) - QxOrm library is an Object Relational Mapping (ORM) library for C++/Qt developers.
* [QtMongo](https://github.com/manuels/QtMongo) - Bindings for QML to MongoDB.
* [QmlSql](https://github.com/JosephMillsAtWork/QmlSql) - A couple of wrapper classes that are for QSql.
* [qtleveldb](https://github.com/paulovap/qtleveldb) - Qt/QML wrapper for Google's LevelDB.
* [sqlite-editor-qtqml](https://github.com/ndesai/sqlite-editor-qtqml) - A SQLite Editor written in Qt+QML.

## Development
* [QHot](https://github.com/patrickelectric/qhot) - Hot reload of nested QML projects.
* [qml-online](https://patrickelectric.work/qmlonline/) - WebAssembly QML viewer.
* [qml-livereload](https://github.com/penk/qml-livereload) - Simple QtQuick app live viewer.
* [hotloader.pri](https://github.com/benlau/hotloader.pri) - Hot Reload QML Files.
* [terrariumapp](http://www.terrariumapp.com/) - UI Prototyping Tool for Coders ([source](https://github.com/penk/terrarium-app)).
* [qmlfmt](https://github.com/jesperhh/qmlfmt) - command line application that formats QML files.
* [QmlExplorer](http://surfsky.github.io/QmlExplorer/) - A Qt QML running environment and examples explorer app.
* [doxyqml](https://github.com/agateau/doxyqml) - Doxyqml turns .qml into pseudo-C++ which Doxygen can then use to generate documentation.
* [Qmljsify](https://github.com/e-fever/qmljsify) - Convert an NPM package into a QML friendly JavaScript file.
* [qml-quickstart](https://github.com/qaap/qml-kickstart) - QML kickstart boilerplate with live reload and HTTP caching.
* [qmlscriptconsole](https://github.com/frankencode/qmlscriptconsole) - The QML Script Console.

## Editor Integration
* [vim-qml](https://github.com/peterhoeg/vim-qml) - QML syntax highlighting for vim.
* [qml-mode](https://github.com/cataska/qml-mode) - Qt Declarative UI (QML) mode for Emacs.
* [Sublime-QML](https://github.com/skozlovf/Sublime-QML) - QML support for Sublime Text 2 and Sublime Text 3.
* [intellij-qml](https://github.com/kropp/intellij-qml) - QML support for IntelliJ-based IDEs.
* [atom-language-qml](https://github.com/rschiang/atom-language-qml) - QML language support for Atom.

## Game Engine
* [Bacon2D](https://github.com/Bacon2D/Bacon2D) - Bacon2D is a framework to ease 2D game development, providing ready-to-use QML elements representing basic game entities needed by most of games.
* [QmlOgre](https://github.com/advancingu/QmlOgre) - Integrates Ogre3D into Qt QML scenes by rendering Ogre to FBOs.

## Graphics
* [qml-box2d](https://github.com/qml-box2d/qml-box2d) - Box2D QML plugin.
* [Chart.qml](https://github.com/qyvlik/Chart.qml) - Chart.qml like Chart.js.
* [qml-ogdf](https://github.com/schulzch/qml-ogdf) - This plug-in provides a binding of Open Graph Drawing Framework to QtQML (Version 5.0+).
* [qml_framerate](https://github.com/vannell/qml_framerate) - Display QML Window frame rate (FPS).

## Hardware
* [qml-cvcamera](https://github.com/chili-epfl/qml-cvcamera) - CVCamera is a QML wrapper for fast camera access using OpenCV. It works on desktop and Android.
* [pot](https://github.com/carlonluca/pot) - Raspberry Pi accelerated video/image rendering with Qt: custom QML components and QtMultimedia backend.
* [QtJoysticks](https://github.com/alex-spataru/QJoysticks) - The QJoysticks library allows your Qt application to read input from both real joysticks/gamepads (using SDL) and a virtual joystick (using the keyboard).
* [QmlPedalboard](https://github.com/danieloneill/QmlPedalboard) - A Udev rule, a tiny Arduino program, a Qml Component, and a test Qml app to interface a pedal board with QML.
* [Qt Touch Bar](https://github.com/andeplane/qt-touchbar/) - A QML item for the Apple Touch Bar

## Images
* [QML-Loaders](https://github.com/Furkanzmc/QML-Loaders) - Loading animation implementations in QML.
* [qqr.js](https://github.com/M4rtinK/qqr.js) - QML bindings for qr.js Javascript QR code library.
* [imagequick](https://github.com/hluk/imagequick) - Simple image browser written in QML.
* [QMLExif](https://github.com/Match-Yang/QMLExif) - QMLExif is a pulgin for reading exif infomation from image file by libexif.

## Javascript
* [Node.qml](https://github.com/trollixx/node.qml) - Node.qml is an effort to provide a Node.js compatibility layer to QML applications.
* [Quickly](https://github.com/quickly/quickly) - ES6 and Node.js-like environment for QML.
* [quicknative](https://github.com/paulondc/quicknative) - Native components for QML.
* [quickflux](https://github.com/benlau/quickflux) - QuickFlux is an implementation of Flux Application Architecture Framework from Facebook.
* [qredux](https://github.com/benlau/qredux) - Redux for QML.
* [qml_underscorejs](https://github.com/diro/qml_underscorejs) - A port of underscore.js to Qt/QML.
* [react-qml](https://github.com/grassator/react-qml) - A bridge library that allows to use React.js with QML.
* [qml-browserify](https://github.com/bhdouglass/qml-browserify) - Browserify for QML (archived, moved to [GitLab](https://gitlab.com/bhdouglass/qml-browserify)).
* [Qondrite](https://github.com/achipa/Qondrite) - QML wrapper for Asteroid, a Javascript Meteor client library.

## JSON
* [qsyncable](https://github.com/benlau/qsyncable) - A solution of nested Json List Model.
* [spine-qml-converter](https://github.com/vmatikainen/spine-qml-converter) - Converts Spine by Esoteric Software export json format into native QML items and animations.

## Logging
* [qmllogging](https://github.com/muflihun/qmllogging) - Single-header only, Easylogging++ wrapper for advanced logging support for QML applications (unmaintained).
* [QmlLogger](https://github.com/prplmnky/QmlLogger) - Simple Javascript Based Logger For QML.

## Math
* [biginteger](https://github.com/benlau/biginteger) - QML BigInteger library.
* [QCustomPlot](https://www.qcustomplot.com/index.php/introduction) - is a Qt C++ widget for plotting and data visualization.

## Misc
* [qmlweb](https://github.com/qmlweb/qmlweb) - A QML engine in a web browser.
* [qmlwebdriver](https://github.com/cisco-open-source/qtwebdriver) - QtWebDriver is a WebDriver implementation for Qt.
* [qml-virtualkey](https://github.com/MidoriYakumo/qml-virtualkey) - Pure QML in-app virtual key/keyboard/pad.
* [textsecure-qml](https://github.com/janimo/textsecure-qml) - TextSecure UI in Go and QML.
* [poor-maps](https://github.com/otsaloma/poor-maps) - Maps and navigation.
* [qml-presentation-system](https://github.com/qt-labs/qml-presentation-system) - This is a slide presentation system written in QML.
* [qtshell](https://github.com/benlau/qtshell) - Manipulate files by a shell command style API.
* [sparkqml](https://github.com/benlau/sparkqml) - SparkQML - A QML Document Viewer for State and Transition Preview.
* [qmlweb-parser](https://github.com/qmlweb/qmlweb-parser) - A QML parser in JavaScript.
* [qml-creative-controls](https://github.com/jcelerier/qml-creative-controls) - QML controls for creative applications and creative coding.
* [qtci](https://github.com/benlau/qtci) - Collection of scripts to build Qt application in command line environment.
* [qml-gnatt](https://github.com/dinusv/qml-gantt) - QML Gantt - An efficient implementation of a gantt chart library for qml.
* [qml-chilitags](https://github.com/chili-epfl/qml-chilitags) - QMLChilitags is a QML wrapper for the fiducial marker tracker Chilitags.
* [phoneME-QML](https://github.com/QKit/phoneME-QML/wiki) - QML interface for phoneME, which allows you to run Java MIDlets (JaveME, MIDP).
* [QtQuickVcp](https://github.com/qtquickvcp/QtQuickVcp) - A Virtual Control Panel for Machinekit written in Qt/C++/QML.
* [qmlcore](https://github.com/pureqml/qmlcore) - QML to HTML5 translator, both for mobile and desktop targets.
* [qml-handwriting](https://github.com/penk/qml-handwriting) - Open source handwriting recognition keyboard written in QML/JavaScript.
* [SortFilterProxyModel](https://github.com/oKcerG/SortFilterProxyModel) - A nicely exposed QSortFilterProxyModel for QML.
* [qmlsaver](https://github.com/proDOOMman/qmlsaver) - Screensaver written in Qt4/QML.
* [QtFreeVirtualKeyboard](https://github.com/githubuser0xFFFF/QtFreeVirtualKeyboard) - A QML based on screen virtual keyboard for embedded QML applications.
* [Qt-Advanced-Docking-System](https://github.com/mfreiholz/Qt-Advanced-Docking-System) - Advanced Docking System for Qt.
* [qtermwidget](https://github.com/lxde/qtermwidget) - The terminal widget for QTerminal.
* [qmltermwidget](https://github.com/lirios/qmltermwidget) - This project is a QML port of qtermwidget.
* [yat](https://github.com/jorgen/yat) - Terminal Emulator written in C++ and qml.
* [qmlnotify](https://github.com/alamminsalo/qmlnotify) - Desktop notification server which implements org.freedesktop.Notifications, using modern Qt/Qml technologies.
* [qml-slideshow](https://github.com/pkobrien/qml-slideshow) - QML Slideshow: the Declarative Hierarchical Finite Slide Machine & Toolkit.
* [aqt-cassowary](https://github.com/Ableton/aqt-cassowary) - Aqt.Cassowary (pronounced like Acute Cassowary) is a Qt plugin that allows you to run a incremental linear constraint solver in QML applications, providing a declarative interface that fits naturally in the QML programming model.
* [qml-colorpicker](https://github.com/rshest/qml-colorpicker) - A basic colorpicker control made in Qt Quick/QML.
* [qmltooltip](https://github.com/bobbaluba/qmltooltip) - A simple tooltip system for QML.
* [QML-Code-editor](https://github.com/andeplane/QML-Code-editor) - A simple code editor using QML and C++.
* [QmlPrinter](https://github.com/tanelipe/QmlPrinter) - Simple Qt component which allows user to print out a QML view from C++.
* [SlideMenu](https://github.com/anatolyk82/SlideMenu) - Implementation of a slide menu in QML.
* [QMLRearrangeableTreeView](https://github.com/MrEricSir/QMLRearrangeableTreeView) - A list-based TreeView that can be rearranged with a mouse or touch device.
* [DateSelector](https://github.com/qyvlik/DateSelector) - Date selector in QML.
* [KeePassTouch](https://github.com/DannyGB/KeePassTouch) - Ubuntu Touch Version of KeePass (QML & C++).
* [qnite](https://github.com/evonove/qnite) - qnite is a charting library that provides a really high level API (via QML) to customize and render interactive charts in your Qt applications.
* [QmlGrid](https://github.com/hahn-kev/QmlGrid) - This is a QML Data grid using Qt Quick Controls 2.
* [qml-cache](https://github.com/chili-epfl/qml-cache) - qml-cache is a persistent app-exclusive key-value store plugin.
* [QCar](https://github.com/damian0/QCar) - Car computer software written in Qt/QML & C++.
* [ProgressBarCollection](https://github.com/KhoaTranProgrammer/ProgressBarCollection) - A collection of progress bars.
* [bodyweight-timer](https://github.com/neversun/bodyweight-timer) - time supporting app for traing purposes (bodyweight-training) on Jolla Sailfish OS.
* [QmlStateMachine](https://github.com/rchamberlin/QmlStateMachine) - Sample Qt project to show how to use a C++ state machine with QML for UI.
* [qmlcompletionbox](https://github.com/dant3/qmlcompletionbox) - Just an example of completion box in Qt with QtQuick.
* [qmlmatrix](https://github.com/skarbat/qmlmatrix) - Matrix animation running on QT5 framework QML engine.
* [QMLTable](https://github.com/spuschhof/QMLTable) - Table implementation for Qt 5 with QtQuick Components 2.
* [qmlofflinesceen](https://github.com/Ashifta/qmlofflinesceen) - This Project create images in a OpenGLFramebuffer, this is to grab images from qml file without actual viewer.
* [qmltranslator](https://github.com/uralbash/qmltranslator) - Class for translations strings in C++/Qml code.
* [QML-UI-Animations](https://github.com/Furkanzmc/QML-UI-Animations) - QML implementations of various UI concepts by various artists.
* [SolarSystem](https://github.com/Instand/SolarSystem) - Solar system model based on Qt3D framework.
* [QMLTreeView](https://github.com/arunpkqt/QMLTreeView) - QMl TreeView with custom folder list model in C++.
* [QQuickDock](https://github.com/unseon/QQuickDock) - Docking window for Qt Quick.
* [nodeeditor](https://github.com/paceholder/nodeeditor) - Qt Node Editor. Dataflow programming framework.
* [QtMvvm](https://github.com/Skycoder42/QtMvvm) - A mvvm oriented library for Qt, to create Projects for Widgets and Quick in parallel.
* [QtRestClient](https://github.com/Skycoder42/QtRestClient) - A library for generic JSON-based REST-APIs, with a mechanism to map JSON to Qt objects.
* [QtAutoUpdater](https://github.com/Skycoder42/QtAutoUpdater) - A Qt library to automatically check for updates and install them.
* [QMarkdownTextEdit](https://github.com/pbek/qmarkdowntextedit) - A C++ Qt QPlainTextEdit widget with markdown highlighting support and some other extras.
* [QSourceHighlite](https://github.com/Waqar144/QSourceHighlite) - A lightweight source code/syntax highlighter written in Qt C++.


## Multimedia
* [QtAv](https://github.com/wang-bin/QtAV) - A multimedia playback framework based on Qt and FFmpeg to write a player easily.
* [qmlvideo](https://github.com/longwei/qmlvideo) - QML video element backend by libVLC, rendered on gl texture.
* [QmlVlcDemo](https://github.com/RSATom/QmlVlcDemo) - Simple demo app for QmlVlc lib.
* [qmlmidi](https://github.com/jarnoh/qmlmidi) - MIDI plugin for Qt Quick. Enables using MIDI input or output devices from declarative QML.
* [qml-recorder](https://github.com/sverzegnassi/qml-recorder) - A QML plugin for audio recording.
* [Elisa](https://community.kde.org/Elisa) - Music Player.
* [Kamoso](https://github.com/KDE/kamoso) - Webcam Application.
* [Webvfx](http://rectalogic.github.io/webvfx/) - WebVfx is a video effects framework that allows video effects (filters, transitions etc.) authored using QtQuick.

## Networking
* [libmaia](https://github.com/wiedi/libmaia) - libmaia is a easy-to-use XML-RPC library for Qt.
* [libcommuni](http://communi.github.io/) - A cross-platform IRC framework written with Qt ([source](https://github.com/communi/libcommuni)).
* [qxmpp](https://github.com/qxmpp-project/qxmpp) - Cross-platform C++ XMPP client and server library.
* [lightbulb](https://github.com/ksiazkowicz/lightbulb) - Open-source XMPP client for Symbian, written using QML and QtQuick libraries.
* [qml-sockets](https://github.com/jemc/qml-sockets) - Exposing Qt's C++ socket objects to QML for declarative use.
* [HttpRequest](https://github.com/qyvlik/HttpRequest) - HttpRequest such as XMLHttpRequest, but more powerful.
* [protobuf-qml](https://github.com/nsuke/protobuf-qml) - Efficient schematized serialization and RPC for QtQuick2 applications through Protocol Buffers and gRPC bindings.
* [QuickDownload](https://github.com/Larpon/QuickDownload) - Easy way to download files with Qt QML and C++.
* [QML-WebSocket](https://github.com/misterion/QML-WebSocket) - This is a lightweight Qt Qml wrapper for legacy version of websocketpp.
* [QtMqtt](https://github.com/toni1991/QtMqtt) - Qt and QML Mqtt Library.
* [qml-soap](https://github.com/folibis/qml-soap) - qml-soap is simple SOAP client plugin created to use mostly with QML.
* [qml-tcpsockets](https://github.com/chili-epfl/qml-tcpsockets) - QML wrappers for `QTcpServer` and `QTcpSocket`.
* [kdeconnect-kde](https://github.com/KDE/kdeconnect-kde) - Software to connect with Andriod phones. App and Plasmoid are both in QML.
* [Liri](https://liri.io/apps/browser/) - Web Browser.
* [QSsh](https://github.com/lvklabs/QSsh) - SSH and SFTP support for Qt. This project is based on Qt Creator's `libQtcSsh.so`.
* [qtrest](https://github.com/qtrest/qtrest) - a small and simple REST API client for any Qt/QML application.
* [QtProtobuf](https://github.com/semlanik/qtprotobuf) - gRPC and Protobuf generator and bindings for Qt framework

## Package Manager
* [qpm](http://www.qpm.io/) - A package manager for Qt ([source](https://github.com/Cutehacks/qpm)).
* [Discover](https://userbase.kde.org/Discover) - Package manager GUI, including Flatpaks.

## QML Specific
* [frida-qml](https://github.com/frida/frida-qml) - Frida Qml plugin.
* [qmlc](https://github.com/qmlc/qmlc) - The Qml Compiler can be used to convert Qml source code files into precompiled Qml files. The precompiled Qml files are faster to load and do not expose the source code. Normally, the Qt either compiles the Qml files in the startup or interprets the Qml files runtime.
* [viewstack.pri](https://github.com/benlau/viewstack.pri) - ViewStack is a wrapper of StackView (QQC2) that provides a stateless interface.
* [quickcross](https://github.com/benlau/quickcross) - QML Cross Platform Utility Library.

## SDKs
* [Felgo](https://felgo.com/) - Felgo (previously V-Play Engine) allows easy cross-platform mobile games and apps development for all major platforms including iOS, Android, BlackBerry.
* [arcgis-runtime-toolkit-qt](https://github.com/Esri/arcgis-runtime-toolkit-qt) - This project contains QML source code for controls and utilities you can use with the ArcGIS Runtime SDK for Qt.
* [QtFirebase](https://github.com/Larpon/QtFirebase) - An effort to bring the Firebase C++ API to Qt + QML.
* [GATutorial-QML](https://github.com/lasconic/GATutorial-QML) - A simple integration of Google Analytics with Qt Quick for iOS and Android.
* [QtAdMob](https://github.com/yevgeniy-logachev/QtAdMob) - QtAdMob is a C++ lib for Qt with QML support, which allows to show ads from AdMob on Android and iOS platforms.
* [Kirigami](https://techbase.kde.org/Kirigami) - lightweight user interface framework for mobile and convergent applications.

## Styling
* [fluid](https://github.com/lirios/fluid) - Fluid is a collection of cross-platform QtQuick components for building fluid and dynamic applications.
* [fontawesome.pri](https://github.com/benlau/fontawesome.pri) - Using FontAwesome in QML.
* [font-awesome-qml](https://github.com/QMLCommunity/font-awesome-qml) - Font Awesome in QML (Qt Quick).
* [QMLFontAwesome](https://github.com/qCring/QMLFontAwesome) - Resources for FontAwesome support in your QML application.
* [qml-material](https://github.com/papyros/qml-material) - Material Design implemented in QtQuick.
* [qml-bootstrap](https://github.com/brexis/qml-bootstrap) - Sweet Qml components inspired from Ionic framework style for mobile and desktop Qt/Qml projects.
* [StratifyQML](https://github.com/StratifyLabs/StratifyQML) - Stratify Labs UI QML framework inspired by Twitter Bootstrap.
* [FlatUI-Controls-QML](https://github.com/Druage/FlatUI-Controls-QML) - This is custom made and themed QML controls. The controls are made to look and behave just like Flat UI Toolkit.
* [aqt-stylesheets](https://github.com/Ableton/aqt-stylesheets) - StylesSheets is a library for Qt/QML that allows you to apply CSS stylesheets to QML applications.

## Templates
* [qpm-qt-creator-project-template](https://github.com/benlau/qpm-qt-creator-project-template) - Qt Creator Project Templates with qpm.
* [quickflux-project-template](https://github.com/benlau/quickflux-project-template) - Project template using QuickFlux with unit tests.
* [QMLApplicationTemplate](https://github.com/qCring/QMLApplicationTemplate) - CMake project template for a simple QML application.
* [Qt-Qbs-Application](https://github.com/approximator/Qt-Qbs-Application) - Qt Qbs application boilerplate and useful scripts.
* [mini-qml](https://github.com/patrickelectric/mini-qml) - A minimal example to deploy Qml applications for Windows, Linux and Mac with Travis and AppVeyor.

## Testing
* [qmlunit](https://github.com/fgrehm/qmlunit) - An easy-to-use Unit Testing framework for Qt Declarative UI - QML [unmaintained].
* [testable](https://github.com/benlau/testable) - Qt/QML Test Runner and Utilities.
* [testrunner](https://github.com/benlau/testrunner) - Qt Test Runner - A tiny tool to execute multiple QTestLib application and combine the testing result into a summary report.
* [QmlSpec](https://github.com/jemc/QmlSpec) - QmlSpec is a replacement for QML's bundled-in unit testing module QtTest.

## Visualization
* [QuickVtk](https://github.com/qCring/QuickVtk) - A VTK prototyping application based on QtQuick/QML.
* [quickqanava](http://www.destrat.io/quickqanava/) - C++14 network/graph visualization library ([source](https://github.com/cneben/QuickQanava)).

## Web Frameworks
* [Cutelyst](https://cutelyst.org/) - Cutelyst is a web framework written in C++11 and Qt, performant and inspired in the Perl Catalyst Web Framework. ([source](https://github.com/cutelyst/cutelyst))
* [QDjango](http://qdjango.org/) - QDjango is a web framework written in C++ and built on top of the Qt library. Where possible it tries to follow django's API, hence its name.

## X11/Wayland
* [sddm](https://github.com/sddm/sddm) - QML based X11 and Wayland display manager.
* [shell](https://github.com/lirios/shell) - QtQuick and Wayland shell for convergence.
* [qmlcompmgr](https://github.com/amezin/qmlcompmgr) - It's a simple compositing manager for X11, written using Qt Quick and QML. Not ready for production.

# Learning
* [The QML Book](http://qmlbook.github.io/) - The QML Book. ([source](https://github.com/qmlbook/qmlbook))
* [Gcompris](http://www.gcompris.net/index-en.html) - For Kids. 
* [Ktouch](https://www.kde.org/applications/education/ktouch/) - Touch Typing Tutor.
* [RCSE](https://github.com/Rolisteam/rcse) - Rolisteam Character Sheet Editor: easier way to create a character sheet, rcse provides more than that. It helps learning QML: draw your page, generate code, change it, execute it, and see the result.
* [QML Coding Guidelines](https://github.com/Furkanzmc/QML-Coding-Guide): A collection of good practices when writing QML code.

# Software
* [files](https://github.com/lirios/files) - File manager.
* [tensor](https://github.com/davidar/tensor) - Tensor is an IM client for the Matrix protocol in development.
* [yat](https://github.com/jorgen/yat) - Terminal Emulator written in C++ and qml.
* [cool-retro-term](https://github.com/Swordfish90/cool-retro-term) - Is a terminal emulator which mimics the look and feel of the old cathode tube screens. It has been designed to be eye-candy, customizable, and reasonably lightweight.
* [Tiled](http://www.mapeditor.org/) - Tiled is a general purpose tile map editor. It is meant to be used for editing maps of any tile-based game, be it an RPG, a platformer or a Breakout clone.
* [yubioath-desktop](https://github.com/Yubico/yubioath-desktop) - Yubico Authenticator for Desktop (Windows, macOS and Linux).
* [pegasus-frontend](https://github.com/mmatyas/pegasus-frontend) - A cross platform, customizable graphical frontend for launching emulators and managing your game collection.
* [tdesktop](https://github.com/telegramdesktop/tdesktop) - Telegram Desktop messaging app.
* [panopticon](https://github.com/das-labor/panopticon) - A libre cross-platform disassembler.
* [TelegramQML](https://github.com/Aseman-Land/TelegramQML) - Telegram API tools for QtQml and Qml. It's based on Cutegram-Core and libqtelegram.
* [qmlvncviewer](https://github.com/heroyin/qmlvncviewer) - VNC viewer component by qt quick.
* [harbour-sailfinder](https://github.com/modulebaan/harbour-sailfinder) - Sailfinder source code & bug tracker.
* [Rolisteam](https://github.com/Rolisteam/rolisteam) - VirtualTableTop software to play Pen and paper role playing games.
* [IPConnect](https://github.com/shashwatdixit124/IPConnect) - P2P Chat and File Transfer Desktop Application.
* [QOwnNotes](https://github.com/pbek/QOwnNotes) - QOwnNotes is a plain-text file notepad and todo-list manager with markdown support and ownCloud / Nextcloud integration.

# Websites
* [inqlude.org](https://inqlude.org) - Website that list a lot of Qt/QML projects.
* [wiki.manjaro.org](https://wiki.manjaro.org/index.php?title=List_of_Qt_Applications) - The manjaro wiki has quie an Qt applications list.
