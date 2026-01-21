# RealTimeChat - WhatsApp Style Messaging App

[![Kotlin](https://img.shields.io/badge/language-Kotlin-blueviolet)](https://kotlinlang.org)
[![Android](https://img.shields.io/badge/platform-Android-green)](https://developer.android.com)
[![Firebase](https://img.shields.io/badge/backend-Firebase-orange)](https://firebase.google.com)
[![License](https://img.shields.io/badge/license-MIT-blue)](LICENSE)

A modern, real-time chat application for Android built with **Kotlin**, inspired by WhatsApp. It supports one-on-one messaging, real-time delivery, typing indicators, online/offline status, and secure user authentication — all powered by **Firebase**.

https://github.com/yourusername/RealTimeChat/assets/your-video-or-screenshot.gif  
*(Add a short demo GIF/video here – highly recommended!)*

## ✨ Features

- **User Authentication** — Email/Password + Phone Number OTP (Firebase Auth)
- **Real-time Messaging** — Instant message delivery & read receipts (Firebase Realtime Database / Firestore)
- **Typing Indicators** & **Online/Last Seen** status
- **Profile Management** — Update name, profile picture, status
- **Chat List** — Recent conversations with timestamps
- **Media Sharing** — Send images (Firebase Storage coming soon / already implemented)
- **Clean & Modern UI** — Material 3 design + dark mode support
- **Push Notifications** — (Optional – FCM integration in progress)
- **End-to-End Encrypted** — (Planned for future updates)

## 🛠️ Tech Stack

- **Language** → Kotlin (100%)
- **IDE** → Android Studio
- **Architecture** → MVVM + Clean Architecture (recommended)
- **Backend & Real-time** → Firebase (Authentication + Realtime Database / Firestore + Storage)
- **UI** → Jetpack Compose **OR** XML with Material Components
- **Dependency Injection** → Hilt (recommended)
- **Coroutines** + **Flow** for async operations
- **Other Libraries** → Glide / Coil (image loading), Navigation Component, Room (local cache – optional)

## 📸 Screenshots

*(Add 4–6 high-quality screenshots here)*

| Login Screen | Chat List | Chat Screen | Profile |
|--------------|-----------|-------------|---------|
| ![Login](screenshots/login.png) | ![Chats](screenshots/chats.png) | ![Messaging](screenshots/chat.png) | ![Profile](screenshots/profile.png) |

## 🚀 Getting Started

### Prerequisites

- Android Studio Hedgehog / Iguana / Latest
- Firebase project set up (see below)
- Minimum SDK: 24 (Android 7.0)

### Firebase Setup

1. Create a new project on [Firebase Console](https://console.firebase.google.com/)
2. Add your Android app to the project
3. Download `google-services.json` and place it in `app/` folder
4. Enable **Authentication**, **Realtime Database** (or Firestore), **Storage**, and **Cloud Messaging** (optional)

### Installation

```bash
# Clone the repository
git clone git@github.com:mark-j-yadav/RealTime_Chat_Appliction_Android.git

# Open in Android Studio
cd RealTime_Chat_Appliction_Android
# Open with Android Studio

# Build & Run on emulator/device