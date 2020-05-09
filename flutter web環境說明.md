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
2。置換帶有推播功能設定的bundle ID
3。選擇正確的provision profile
4。打包上傳至app
5。推播功能的p12需上傳至firebase後台
```

### Android 上架前的準備

```
1。開發者帳號
2。置換Application ID
3。置換package name
4。打包上傳至app
```

### FireBase 的準備

```
1。準備一個web 專案，新增ios、android應用程式
2。將GoogleService-Info.plist 取代目前xcode專案裡臨時的檔案
3。將google-services.json 取代目前 android studio裡臨時的檔案
4。android oreo 以上版本需要設定channel_id
5。利用firebase console發推播不用多做設定，若是利用servere呼叫 firebase api，則需要設定伺服器金鑰

```
