# dateback iOS (Flutter)

This repository contains the iOS app files copied from `h883/nova_hack` (main, tree `f02347da0e485ddd883dc90ac129a096a094cc7b`).

The app is written in Flutter. `lib/` contains the Dart application, `ios/` contains the Xcode project, and `pubspec.yaml` lists dependencies. The API/server implementation remains in the original repository.

## Run on iOS

On a Mac with Flutter and Xcode installed:

```bash
flutter pub get
cd ios && pod install && cd ..
flutter run -d <device-id>
```

Set your own Apple development team in Xcode when needed. Firebase and backend endpoints currently reference the original project's configuration. An iOS build and device test have not been performed as part of this copy.
