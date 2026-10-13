# SOS Emergency App

## About the Project

The SOS Emergency App is an Android application designed to help users send emergency alerts and share their location with trusted contacts during critical situations.

The application is developed using Java and XML in Android Studio.

## Features

* SOS emergency alert functionality
* Emergency contact management
* Location sharing support
* Emergency message functionality
* Emergency helpline information
* First-aid information
* Shake detection support (where implemented and supported)

## Technologies Used

* Java
* XML
* Android Studio
* Gradle
* Android SDK
* Google Play Services Location
* Google Maps (where configured)

## Requirements

* Android Studio
* Android SDK
* Java Development Kit compatible with the project Gradle configuration
* Android phone or emulator

Some features may require location permissions, SMS permissions, a SIM card, an internet connection, or an API key.

## How to Run

1. Clone or download this repository.
2. Open the project in Android Studio.
3. Allow Gradle synchronization to finish.
4. Install any missing Android SDK components if prompted.
5. Connect an Android phone or start an emulator.
6. Click the Run button in Android Studio.

## Build the APK

From the project root directory, run:

```powershell
.\gradlew.bat assembleDebug
```

After a successful build, find the APK at:

```text
app/build/outputs/apk/debug/app-debug.apk
```

## Disclaimer

This application is intended as an emergency-assistance project. Do not rely on it as a replacement for official emergency services. Verify permissions, location accuracy, network availability, and message delivery before use.

## License

Check the applicable license and original project terms before redistributing or modifying this software.
