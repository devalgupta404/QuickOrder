# QuickOrder

A modern food ordering Android app built with Kotlin and Jetpack Compose, featuring Firebase authentication and Firestore database.

## Screenshots

<p align="center">
  <img src="https://github.com/user-attachments/assets/288cecac-088e-4a82-ba25-eb7427b3f5a4" width="200" alt="Home Screen"/>
  <img src="https://github.com/user-attachments/assets/80531e52-b0f4-4aef-b6c9-6336b9289f13" width="200" alt="Menu Screen"/>
  <img src="https://github.com/user-attachments/assets/666a2d38-675e-4e6d-b97a-73a24295d434" width="200" alt="Cart Screen"/>
  <img src="https://github.com/user-attachments/assets/fdd97c59-f4d6-4538-8cc6-27154285ac81" width="200" alt="Order Screen"/>
</p>

## Features

- User authentication with Firebase
- Browse food menu with categories
- Add items to cart
- QR code generation for orders
- Real-time order tracking
- Material Design 3 UI
- Swipe to refresh

## Tech Stack

- **Language:** Kotlin
- **UI:** Jetpack Compose
- **Architecture:** MVVM
- **Backend:** Firebase (Auth, Firestore, Analytics)
- **Navigation:** Navigation Compose
- **Design:** Material Design 3

## Prerequisites

- Android Studio Hedgehog (2023.1.1) or later
- JDK 11 or higher
- Android SDK 35
- A Firebase project (for authentication and database)

## Build Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/devalgupta404/QuickOrder.git
cd QuickOrder
```

### 2. Firebase Setup

1. Go to [Firebase Console](https://console.firebase.google.com/)
2. Create a new project or use an existing one
3. Add an Android app with package name `com.example.quickorder`
4. Download the `google-services.json` file
5. Place it in the `app/` directory

### 3. Build the Project

**Using Android Studio:**
1. Open the project in Android Studio
2. Wait for Gradle sync to complete
3. Click **Run** or press `Shift + F10`

**Using Command Line:**

```bash
# Debug build
./gradlew assembleDebug

# Release build
./gradlew assembleRelease

# Install on connected device
./gradlew installDebug
```

### 4. Run Tests

```bash
# Unit tests
./gradlew test

# Instrumented tests
./gradlew connectedAndroidTest
```

## Build Configuration

| Property | Value |
|----------|-------|
| Compile SDK | 35 |
| Min SDK | 23 (Android 6.0) |
| Target SDK | 35 |
| Java Version | 11 |

## Dependencies

- Jetpack Compose BOM
- Firebase Authentication
- Firebase Firestore
- Firebase Analytics
- Navigation Compose
- Material Design 3
- Accompanist SwipeRefresh
- QR Code Generator (zxing)
- Coil (Image Loading)



## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Author

**Deval Gupta** - [@devalgupta404](https://github.com/devalgupta404)
