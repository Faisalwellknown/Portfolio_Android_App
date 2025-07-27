# 📱 Portfolio Android App

An Android multi-page portfolio application with OTP login, real-time Firebase integration, and Razorpay payment gateway support.

## 🚀 Features

- 🔐 OTP-based login authentication
- ☁️ Firebase Realtime Database integration
- 💳 Razorpay payment gateway
- 📄 Multi-page user interface
- 👤 Profile and contact info sections

## 🛠️ Tech Stack

- **Language**: Java
- **IDE**: Android Studio
- **Backend**: Firebase Auth & Realtime Database
- **Payment Gateway**: Razorpay Android SDK

## 📦 Dependencies

Make sure to add the following in your `build.gradle` files:

```gradle
// Razorpay
implementation 'com.razorpay:checkout:1.6.20'

// Firebase (Authentication + Database)
implementation 'com.google.firebase:firebase-auth:22.3.0'
implementation 'com.google.firebase:firebase-database:20.3.0'
🔑 Firebase Setup
Go to Firebase Console

Create a project and register your Android app.

Download the google-services.json file and place it in the app/ directory.

Enable Phone Authentication and Realtime Database.

💳 Razorpay Setup
Create an account at Razorpay Dashboard

Get your API Key ID and Secret.

Add Razorpay SDK and initialize it in your activity.

Configure the payment flow as per Razorpay docs.

🧪 Testing
OTP can be tested using Firebase test phone numbers.

Use Razorpay's test API keys for dummy transactions.

📸 Screenshots / Demo
Add screenshots or demo video link here (e.g., YouTube or embedded .mp4)

📁 APK File
You can test the latest build by installing this APK:

base.apk

📽️ Feedback Video
App Feedback Video


🧑‍💻 Author
Faisal Shaikh
