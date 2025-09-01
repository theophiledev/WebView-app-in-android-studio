# WebViewApp

A simple Android application that loads a Laravel web application inside a WebView. The app includes a **loading spinner** while the page loads and handles **back navigation** within the WebView.

---

## Features

- Load any web application (Laravel app, ngrok URL, or deployed URL) inside WebView.
- Circular **loading spinner** shown while the page is loading.
- Smooth **back button navigation** in WebView history.
- Fully supports **JavaScript** and **DOM storage**.
- Handles file and content access inside WebView.

---

## Screenshots

![Screenshot of WebViewApp](path/to/your/screenshot.png)  
*Replace the path with your actual screenshot file.*

---

## Getting Started

### Prerequisites

- Android Studio 4.x or higher
- Android device or emulator running Android 5.0 (API 21) or higher
- Internet connection (for loading web app)

### Installation

1. Clone the repository:

```
git clone https://github.com/theophiledev/Web-app-in-android.git
Open the project in Android Studio.

Build and run on your device/emulator.

How to Use

Launch the app.

The WebView will load your Laravel app URL (https://8f71aa4c100c.ngrok-free.app by default).

Wait for the loading spinner to disappear.

Use the back button to navigate within the WebView history.

Project Structure

MainActivity.java – Main activity that handles WebView and spinner.

activity_main.xml – Layout file with WebView and ProgressBar.

AndroidManifest.xml – App manifest with internet permission.

Notes

Update the URL in MainActivity.java to your deployed Laravel app or ngrok URL.

Make sure the app has Internet permission in AndroidManifest.xml:

<uses-permission android:name="android.permission.INTERNET"/>

License

This project is licensed under the MIT License. See the LICENSE
 file for details.

Author

BENIMANA Theophile
Email: btbenimana@gmail.com

Phone: +250782858743

```

