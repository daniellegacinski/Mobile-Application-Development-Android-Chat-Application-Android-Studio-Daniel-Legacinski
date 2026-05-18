# Mobile-Application-Development-Android-Chat-Application-Android-Studio-Daniel-Legacinski
# 💬 Easy Chat — Android Chat Application

**Easy Chat** is an Android real-time chat application created in **Android Studio** using **Java** and **Firebase**.

The app allows users to log in with a phone number, create a profile, search for other users, open chat rooms, send messages, view recent chats, edit profile information, upload profile images, and receive Firebase Cloud Messaging notifications.

---

## 📱 About the Project

This project is a mobile chat application similar to a simple messenger app.

The main idea of the application is:

> Users can register with their phone number, create a username, find other users, and chat with them in real time.

The project uses Firebase services for authentication, database storage, profile images, and notifications.

---

## ✨ Features

- 📞 Phone number login
- 🔐 OTP verification
- 👤 Username setup
- 🔎 Search users
- 💬 Real-time chat
- 🕒 Recent chats list
- 🧑 Profile screen
- 🖼️ Profile image upload
- 🔔 Push notifications with Firebase Cloud Messaging
- 📱 Bottom navigation menu
- ☁️ Firebase Firestore database
- 🗂️ Firebase Storage support
- 🎨 Clean Android UI
- ⚙️ Built with Java and Android Studio

---

## 🛠️ Technologies Used

| Technology | Description |
|----------|-------------|
| Java | Main programming language |
| Android Studio | IDE used to create the project |
| Gradle | Build system |
| XML | Used for layouts and UI |
| Firebase Authentication | Used for phone number login and OTP |
| Firebase Firestore | Used for storing users, chats and messages |
| Firebase Storage | Used for profile images |
| Firebase Cloud Messaging | Used for notifications |
| FirebaseUI Firestore | Used for Firestore RecyclerView adapters |
| Glide | Used for loading images |
| ImagePicker | Used for selecting profile pictures |
| OkHttp | Used for notification/network requests |
| Country Code Picker | Used for phone number country codes |
| Material Components | Used for modern Android UI |

---

## 📁 Project Structure

```text
Android_Chat_Application/
│
├── app/
│   ├── src/
│   │   └── main/
│   │       ├── java/com/example/easychat/
│   │       │   ├── adapter/
│   │       │   │   ├── ChatRecyclerAdapter.java
│   │       │   │   ├── RecentChatRecyclerAdapter.java
│   │       │   │   └── SearchUserRecyclerAdapter.java
│   │       │   │
│   │       │   ├── model/
│   │       │   │   ├── ChatMessageModel.java
│   │       │   │   ├── ChatroomModel.java
│   │       │   │   └── UserModel.java
│   │       │   │
│   │       │   ├── utils/
│   │       │   │   ├── AndroidUtil.java
│   │       │   │   └── FirebaseUtil.java
│   │       │   │
│   │       │   ├── ChatActivity.java
│   │       │   ├── ChatFragment.java
│   │       │   ├── FCMNotificationService.java
│   │       │   ├── LoginOtpActivity.java
│   │       │   ├── LoginPhoneNumberActivity.java
│   │       │   ├── LoginUsernameActivity.java
│   │       │   ├── MainActivity.java
│   │       │   ├── ProfileFragment.java
│   │       │   ├── SearchUserActivity.java
│   │       │   └── SplashActivity.java
│   │       │
│   │       ├── res/
│   │       │   ├── drawable/
│   │       │   ├── layout/
│   │       │   ├── menu/
│   │       │   ├── mipmap/
│   │       │   ├── values/
│   │       │   └── xml/
│   │       │
│   │       └── AndroidManifest.xml
│   │
│   ├── build.gradle
│   └── google-services.json
│
├── build.gradle
├── settings.gradle
├── gradle.properties
├── gradlew
├── gradlew.bat
└── README.md
