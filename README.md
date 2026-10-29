Experiment 8 – Menus and WebView in Android

Aim

To implement Menus and WebView in an Android application using Kotlin.

Description

This Android application demonstrates how to create an Options Menu and use WebView to display web pages inside the application.

Features

- Options Menu
- Home page
- Google WebView
- YouTube WebView
- Exit option
- Internet access using WebView

Technologies Used

- Android Studio
- Kotlin
- XML
- WebView
- Android Options Menu

Menu Items

1. Home – Displays the home screen.
2. Google – Opens Google in WebView.
3. YouTube – Opens YouTube in WebView.
4. Exit – Closes the application.

Required Permission

<uses-permission android:name="android.permission.INTERNET" />

Project Structure

Experiment8/
├── app/
│   └── src/
│       └── main/
│           ├── java/
│           │   └── MainActivity.kt
│           ├── res/
│           │   ├── layout/
│           │   │   └── activity_main.xml
│           │   └── menu/
│           │       └── menu_main.xml
│           └── AndroidManifest.xml
└── README.md

Working

When the application starts, the home screen is displayed. The user can open the Options Menu and select Google or YouTube. The selected website is loaded inside the WebView. The Exit option closes the application.

Result

The Android application successfully implements an Options Menu and WebView for displaying web pages within the application.

Author

Prabha

Programme: MCA
University: Jain (Deemed-to-be University)
