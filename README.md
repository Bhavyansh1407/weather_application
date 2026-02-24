# 🌤️ Weather App

A beautiful and dynamic **Flutter weather application** that fetches real-time weather data and adapts its theme color based on current weather conditions. Built with clean architecture using the Provider pattern for state management.

---

## 📱 Features

- 🌍 Fetch **real-time weather data** based on location
- 🎨 **Dynamic theme color** that changes based on current weather conditions
- 📦 Clean architecture with **Provider** state management
- 🌐 Supports both **Android and iOS** platforms
- 💧 Displays temperature, weather condition, and more
- ⚡ Lightweight and fast with efficient API calls

---

## 🛠️ Tech Stack

| Technology | Details |
|---|---|
| Framework | Flutter |
| Language | Dart (null-safe) |
| State Management | Provider (^6.0.1) |
| HTTP Requests | http (^0.13.4) |
| UI | Material Design + Cupertino Icons |
| Architecture | MVC (Models, Pages, Providers) |
| Platforms | Android & iOS |

---

## 📂 Project Structure

```
weather_app/
├── lib/
│   ├── main.dart                  # App entry point & Provider setup
│   ├── models/
│   │   └── weather_model.dart     # Weather data model + theme logic
│   ├── pages/
│   │   └── home_page.dart         # Main UI screen
│   └── providers/
│       └── weather_provider.dart  # State management & API calls
├── assets/
│   └── images/                    # Weather condition images
├── android/                       # Android platform files
├── ios/                           # iOS platform files
├── pubspec.yaml                   # Project dependencies
└── README.md
```

---

## 🚀 Getting Started

### Prerequisites

Make sure you have the following installed:

- [Flutter SDK](https://flutter.dev/docs/get-started/install) (>=3.18.0)
- Dart SDK (>=2.12.0)
- Android Studio or Xcode (for running on a device/emulator)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/bhavyansh1407/weather_app.git
   cd weather_app
   ```

2. **Install dependencies**
   ```bash
   flutter pub get
   ```

3. **Run the app**
   ```bash
   flutter run
   ```

---

## 📸 Screenshots

> _Add your app screenshots here once the app is running_

---

## 🏗️ How It Works

- On launch, the app initializes a `WeatherProvider` using `ChangeNotifierProvider` at the root level, making weather state accessible throughout the app.
- The `WeatherProvider` handles all API calls using the `http` package and notifies the UI of any state changes.
- The `WeatherModel` holds the weather data and contains logic to return a **dynamic theme color** based on current conditions (e.g., sunny = yellow, rainy = blue).
- The `MaterialApp` theme updates reactively whenever new weather data is loaded, giving the app a live, immersive feel.

---

## 🎯 Skills Demonstrated

- Real-time **API integration** with the `http` package
- **Provider** pattern for scalable state management
- **Dynamic UI theming** based on live data
- Clean **MVC project structure**
- Cross-platform mobile development with **Flutter & Dart**
- Working with **asynchronous programming** (async/await)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

> Built with Flutter 💙 | [bhavyansh1407](https://github.com/bhavyansh1407)
