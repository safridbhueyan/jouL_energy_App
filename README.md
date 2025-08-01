# ⚡ Joul App

Joul is a Flutter-based electric car battery charging app. It allows users to locate nearby EV charging stations, view live charger availability, monitor battery status, and remotely start or stop charging. Designed for modern EV owners, Joul simplifies the charging experience.

---

## 🚀 Overview

Joul is crafted using **Flutter**, providing a clean UI and powerful EV-focused features. The app includes:

- **Charging Station Discovery**: Real-time map of nearby charging points.
- **Live Charging Control**: Start/stop charging and view progress.
- **Battery Monitoring**: Track current battery %, range, and status.
- **Station Details**: View charger types, ports, cost, and distance.
- **Settings & Customizations**: Theme, preferences, and charging notifications.

---

## 🔑 Features

- 🔋 **Battery Dashboard** – View charge %, remaining range, voltage.
- 📍 **Station Finder** – See and filter all nearby chargers.
- ⚡ **Remote Charging** – Start and stop charging directly from the app.
- 📊 **Charging History** – Track past sessions with timestamp and cost.
- 📌 **Station Info** – Map, address, charger types, availability.
- ⚙️ **Settings Flow** – Customize preferences (theme, alerts, etc.)

---

## 🧠 Folder Structure

```bash
lib/
├── core/
│   ├── constants/           # Padding, colors, typography
│   ├── theme/               # AppTheme and ThemeMode
│   └── utils/               # Helpers (e.g., time, distance calc)
├── data/
│   ├── models/              # EV, Battery, Station, User
│   ├── services/            # API calls, Firebase
│   ├── repository/          # Abstracted data layer
│   └── routes/              # App routes
├── provider/
│   ├── battery_provider.dart
│   ├── station_provider.dart
│   └── auth_provider.dart
├── src/
│   ├── screens/             # home, map, station_detail, charging
│   ├── components/          # cards, station_tile, battery_indicator
│   └── dialogs/             # confirm dialogs, alerts
└── main.dart                # Entry point of the app


## Getting Started

These instructions will help you get started with the **Morsl** app development environment, so you can run the app locally.

### Prerequisites

Make sure you have the following installed on your machine:
- **Flutter SDK**: Follow the [Flutter installation guide](https://docs.flutter.dev/get-started/install).
- **Dart SDK**: Flutter comes with Dart, so you don’t need to install it separately.
- **Android Studio** or **Visual Studio Code** for development.
- An **Android** or **iOS** emulator, or a real device to run the app.

### Installing

1. **Clone the repository:**
   ```bash
   git clone https://github.com/backbencherstudio/celina_food_image_app.git
   cd celina_food_image_app
