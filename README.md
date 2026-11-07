RockPaperSnap ✊✋✌️

An interactive, cross-platform mobile application built using React Native, Expo Router, and TypeScript. This project features a classic Rock Paper Scissors game showdown with dynamic state management, custom tab navigation, and custom UI styling.

📱 Features

Interactive Game Engine: Play Rock-Paper-Scissors against an automated computer opponent with randomized choice selection.

Real-time Score Tracker: Tracks total Wins, Draws, and Losses dynamically using React useState.

File-based Navigation: Seamless navigation between the Play Game screen and Game Rules screen using Expo Router Tab Navigation.

Custom Splash Screen: Configured native app splash screen during application initialization.

Modern UI & Flexbox Layout: Clean layout using React Native StyleSheet, custom icons (@expo/vector-icons), dynamic color indicators, and custom buttons.

🛠️ Tech Stack & Dependencies

Framework: Expo (SDK 57/58)

Routing: Expo Router

Language: TypeScript / React Native

Icons: @expo/vector-icons (Ionicons)

Build Tool: EAS CLI (Expo Application Services)

📁 Project Structure

RockPaperSnap/
├── app/
│   ├── _layout.tsx        # Root Stack Navigation Layout
│   └── (tabs)/
│       ├── _layout.tsx    # Tab Navigation Layout (Play & Rules)
│       ├── index.tsx      # Main Play Screen & Game Logic
│       └── rules.tsx      # Game Rules Screen
├── assets/
│   └── images/
│       └── appIcon.png    # App Icon & Splash Screen Graphic
├── Output_Screens/        # Application Screenshots
├── app.json               # Expo configuration & Splash screen setup
├── package.json           # Dependencies & Scripts
└── README.md              # Project Documentation


🚀 Getting Started

Prerequisites

Ensure you have Node.js installed on your machine and the Expo Go app installed on your mobile device (Android/iOS).

Installation

Clone the repository:

git clone https://github.com/YOUR_GITHUB_USERNAME/RockPaperSnap.git
cd RockPaperSnap


Install project dependencies:

npm install
npx expo install @expo/vector-icons


Run the development server:

npx expo start -c


Launch the App:

Scan the generated QR code using the Expo Go app on Android or the Camera app on iOS.

📦 Building the Standalone APK

To build a standalone Android package (.apk):

Install EAS CLI:

npm install -g eas-cli


Log in to Expo:

eas login


Configure & Build:

eas build:configure
eas build -p android --profile preview

