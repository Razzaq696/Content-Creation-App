# Content Craetion — Android App

A powerful Android application for video downloading, splitting, and face filtering with Firebase authentication and license management.

---

## Features

- 🔐 License activation (Trial & Key-based)
- 🔥 Firebase email/password authentication
- 🎬 Video Download, Split, and Face Filter tools
- 👑 Admin panel for user management
- 📱 Role-based dashboard

---

## Tech Stack

- **Language:** Java
- **Platform:** Android (min SDK 21+)
- **Backend:** REST API (Railway)
- Link(https://railway.com/project/fb684ab1-ac8c-41db-a379-53b53340f37e?)
- Git hub backend rep (https://github.com/Razzaq696/Content-Creation-Tool)
- **Database:** Firebase Realtime Database
- **Auth:** Firebase Authentication

---

## App Flow
License Screen → Login → Dashboard → Video Tool / Admin Panel

---

## Screens

| Screen | Description |
|---|---|
| LicenseActivity | Activate via trial or license key |
| LoginActivity | Firebase email/password login |
| DashboardActivity | Main menu (role-based) |
| VideoToolActivity | Download, Split, Face Filter |
| AdminActivity | Manage users (admin only) |

---

## Setup Instructions



### 1. Clone the Repository
```bash
git clone https://github.com/Razzaq696/Content-Creation
cd Content Craetion/android_app
```

### 2. Open in Android Studio
- Open Android Studio
- Click **"Open an Existing Project"**
- Select the `android_app/` folder
- Wait for Gradle sync to complete

### 3. Configure API
Edit `app/src/main/java/com/Content Craetion/api/ApiClient.java` and set your BASE_URL and API_KEY.

### 4. Configure Firebase
Add your `google-services.json` file to the `app/` directory.

### 5. Build APK
Build → Build Bundle(s) / APK(s) → Build APK(s)
Output: `app/build/outputs/apk/debug/app-debug.apk`

---

## Installation

1. Enable **Unknown Sources** on your Android phone
2. Transfer the APK to your phone
3. Tap to install

---

## Requirements

- Android Studio Hedgehog or later
- Android phone with API level 21+ (Android 5.0+)
- Active internet connection

---

## License

This project is private. Unauthorized distribution is prohibited.

---

## Developer

**Content Craetion**  
Built with ❤️ for video content creators
