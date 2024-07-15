[![lego project](https://img.shields.io/badge/powered%20by-lego-blue?logo=github)](https://github.com/melodysdreamj/lego)
[![pub package](https://img.shields.io/pub/v/flutter_native_splash_lego.svg)](https://pub.dartlang.org/packages/flutter_native_splash_lego)

# flutter_native_splash_lego
native splash screen for flutter project.

##  Installation
1. open terminal in the lego project root directory, enter the following command for install cli.
   and create a new lego project if you don't have one.
```bash
flutter pub global activate lego_cli
lego create
```
2. in terminal, enter the following command for add lego to project.
```bash
lego add flutter_native_splash_lego
```

3. pub image to assets folder, and update pubspec.yaml file.
```yaml
#@add start
flutter_native_splash:
  color: "#ffffff"
  #background_image: "assets/lego/flutter_native_splash_lego/splash_icon.png"
  image: assets/lego/flutter_native_splash_lego/splash_icon.png

  color_dark: "#ffffff"
  ##background_image_dark: "assets/lego/flutter_native_splash_lego/splash_icon.png"
  image_dark: assets/lego/flutter_native_splash_lego/splash_icon.png

  #android: false
  #ios: false
  #web: false

  #android_gravity: center
  #ios_content_mode: center
  #web_image_mode: center

  fullscreen: true
#@add end
```
3. in terminal, enter the following command for run flutter_native_splash
```bash
dart run flutter_native_splash:create
```