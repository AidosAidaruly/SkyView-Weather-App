# 🌤️ SkyView Weather App

A Flutter weather application built as part of Assignment #8 (Platform-Specific App Assets, Build & Release).

## 📱 About

SkyView is a clean, release-ready weather app that displays real-time weather data for cities around the world using the [Open-Meteo API](https://open-meteo.com/) — no API key required.

## ✨ Features

- 🔍 Search weather by city name
- 🌡️ Current temperature & feels-like temperature
- 💧 Humidity percentage
- 💨 Wind speed in m/s
- 🌤️ Weather condition with emoji icons
- 🌙 Day/Night indicator
- 🎨 Animated gradient background that changes with weather
- ⚡ Quick-access chips for popular cities (Astana, Almaty, London, Tokyo, Dubai)

## 🏙️ Supported Cities

Astana, Almaty, London, New York, Tokyo, Paris, Dubai, Moscow, Istanbul, Berlin

## 🛠️ Tech Stack

- **Flutter** — UI framework
- **Dart** — programming language
- **Open-Meteo API** — free weather data, no API key needed
- **http** package — API requests

## 🚀 Getting Started

### Prerequisites
- Flutter SDK installed
- Android emulator or physical device

### Installation

```bash
git clone https://github.com/YOUR_USERNAME/release_ready_flutter_app.git
cd release_ready_flutter_app
flutter pub get
flutter run
```

### Build Release APK

```bash
flutter build apk --release
```

The APK will be at: `build/app/outputs/flutter-apk/app-release.apk`

## 📁 Project Structure

lib/
main.dart          # Main app logic and UI
assets/
icon/              # App icon
splash/            # Splash screen image
android/             # Android configuration
ios/                 # iOS configuration
pubspec.yaml         # Dependencies and metadata

## 📦 Dependencies

```yaml
dependencies:
  flutter:
    sdk: flutter
  http: ^1.2.0
  cupertino_icons: ^1.0.8
```



## 📋 Assignment Info

- **Course:** Cross-Platform Mobile Development
- **Assignment:** #8 — Platform-Specific App Assets, Build & Release
- **Version:** 1.0.0+1

- 
