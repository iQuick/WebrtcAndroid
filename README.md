# WebrtcAndroid

This is an Android Studio reference project for WebRTC based video and voice calling app.

## build

* date:2022/02/09
* M85


gn configuration is：

```shell
gn gen out/android/release/arm --args='is_debug=false target_os="android" target_cpu="arm" rtc_use_h264=true '
gn gen out/android/release/arm64 --args='is_debug=false target_os="android" target_cpu="arm64" rtc_use_h264=true '
gn gen out/android/release/x64 --args='is_debug=false target_os="android" target_cpu="x64" rtc_use_h264=true '
gn gen out/android/release/x86 --args='is_debug=false target_os="android" target_cpu="x86" rtc_use_h264=true '
```