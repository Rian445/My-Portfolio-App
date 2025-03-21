# Portfolio App

This Flutter app allows you to easily transform your existing portfolio website into a mobile app. If you already have a portfolio website, you can quickly turn it into a Flutter-based mobile application by following the steps below.

## Features

- **Easy Integration:** Seamlessly integrate your existing portfolio website into the app.
- **Dynamic WebView:** Load your website within the app using a WebView.
- **Customizable AppBar:** Personalize the app bar with your branding, including title, icons, and colors.
- **Offline Caching:** Ensure your portfolio is accessible even without an internet connection by caching the website content.
- **PDF Viewer Integration:** View any PDFs directly within the app using a Google Docs viewer.
- **Navigation Buttons:** Easily navigate back or return to the homepage with built-in navigation buttons.


## Setup Instructions

### Prerequisites

- Flutter SDK installed on your machine.
- Android Studio or Xcode for running the app on an emulator or physical device.


### Steps

1. **Clone the Repository:**
```bash
git clone https://github.com/Rian445/My-Portfolio-App
cd your-repo-name
```

2. **Install Dependencies:**
```bash
flutter pub get
```

3. **Run the App:**
```bash
flutter run
```

4. **Modify the URL:**
    - Open `lib/main.dart`
    - Replace 'https://portfolio-rian-islams-projects.vercel.app/' with your portfolio website URL.
5. **Customize the AppBar:**
    - Open `lib/webview_screen.dart`
    - Modify the AppBar widget to change the title, icons, and colors according to your needs.

## Code Structure

- **main.dart**: The entry point of the application. It sets up the MaterialApp and initializes the WebViewScreen with the portfolio URL.
- **webview_screen.dart**: Contains the WebViewScreen widget, which handles the WebView, caching, and navigation logic.


## Dependencies

- **webview_flutter**: For embedding web content.
- **url_launcher**: For handling external URLs and email links.
- **flutter_cache_manager**: For caching web content.
- **connectivity_plus**: For checking network connectivity.
- **http**: For fetching HTML content for caching.

