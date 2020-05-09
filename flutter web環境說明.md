## 環境說明

[flutter 官網](https://flutter.dev/)

### Flutter 版本

```
Flutter 1.17.0 • channel stable • https://github.com/flutter/flutter.git
Framework • revision e6b34c2b5c (7 days ago) • 2020-05-02 11:39:18 -0700
Engine • revision 540786dd51
Tools • Dart 2.8.1
```

### Flutter doctor

其中 IntelliJ 為 java 開發IDE 不需要安裝

```
[✓] Flutter (Channel stable, v1.17.0, on Mac OS X 10.15.4 19E287, locale zh-Hant)
 
[✓] Android toolchain - develop for Android devices (Android SDK version 28.0.3)
[✓] Xcode - develop for iOS and macOS (Xcode 11.4.1)
[✓] Android Studio (version 3.5)
[!] IntelliJ IDEA Community Edition (version 2018.2.3)
    ✗ Flutter plugin not installed; this adds Flutter specific functionality.
    ✗ Dart plugin not installed; this adds Dart specific functionality.
[✓] VS Code (version 1.44.2)
[✓] Connected device (2 available)

```

### WebView 的網址設定
```
網址設定的位置在  /lib/main.dart 目前設定為 https://www.google.com
因應未來可能的問題，已手動將javascript全開，ssl檢查全關。
```


### XCode 上架前的準備

```
1。開發者帳號
2。置換bundle ID
3。選擇正確的provision profile
4。打包上傳至app
```

### Android 上架前的準備

```
1。開發者帳號
2。置換Application ID
3。置換package name
4。打包上傳至app
```

