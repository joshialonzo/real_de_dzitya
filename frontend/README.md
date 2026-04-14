# Frontend Environment

This directory contains the Flutter application covering Web, Android, and iOS.

## Running Locally

To launch the application locally, you must first ensure you are in this directory:
```bash
cd frontend
```

### Web
To launch the app in Chrome:
```bash
flutter run -d chrome
```

### Mobile (iOS / Android)

If you need to boot up the iOS simulator directly from the terminal, you can run:
```bash
flutter emulators --launch apple_ios_simulator
```

Once a device or simulator is actively running, simply run:
```bash
flutter run
```
Flutter will either launch the app immediately (if only one device is found) or prompt you to press 1, 2, or 3 to select your target device from a list.

## Running Tests

To run the widget and unit tests locally, run:
```bash
flutter test
```

To run a specific test file (like the one you currently have open):
```bash
flutter test test/widget_test.dart
```

## Running the Full Stack Local Environment
*(See the [Firebase README](../firebase/README.md) for instructions on starting the local database and backend emulators alongside the Flutter app).*
