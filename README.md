# flutter_app

A new Flutter application.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://flutter.dev/docs/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://flutter.dev/docs/cookbook)

For help getting started with Flutter, view our
[online documentation](https://flutter.dev/docs), which offers tutorials,
samples, guidance on mobile development, and a full API reference.

---
:: Note ::

- Stateless : not-redraw
- Stateful : redraw
- ```const``` : make component not redraw
- ```_``` : variable name start with _ mean to private variable
- ```=>``` : arrow sign mean return
- ```onPressed``` : if no function assigned, it'll automatic disable state.
- use ```{}``` cover arguments for optional argument(s)
- ```..``` chaining call function (like builder)
- [Maps API](https://developers.google.com/maps) key need to set into platforms. [Google Maps for Flutter](https://pub.dev/packages/google_maps_flutter)
- [Flutter Location Plugin](https://pub.dev/packages/location) iOS need

iOS need to add following permission into :Info.plist
```
<key>NSLocationWhenInUseUsageDescription</key>
<string>ขอใช้หน่อย</string>
<key>NSLocationAlwaysUsageDescription</key>
<string>ขอใช้เหอะ</string>
```

- [URL luncher](https://pub.dev/packages/url_launcher/versions/6.0.3)
- generate app icons
```
$ flutter pub run flutter_launcher_icons:main
```


For generate /android, /ios, /web directories
```
flutter create .
```
