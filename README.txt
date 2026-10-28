POCKET EXPENSE - ANDROID PROJECT
================================

What this is
------------
A beginner-friendly Android Studio project. It wraps the offline Pocket Expense
web interface inside a native Android app using WebView. It does not need an
internet connection for the app features. Data is stored locally on the device
using browser localStorage.

Features
--------
- Monthly budget (tap the budget amount to change it)
- Add and delete expenses
- Category summary
- Add and delete subscriptions
- Offline local storage

Build an APK (free)
-------------------
1. Install Android Studio from https://developer.android.com/studio
2. Extract PocketExpenseAndroid.zip.
3. In Android Studio choose File > Open and select the extracted PocketExpenseAndroid folder.
4. Wait for Gradle sync to finish. If asked, install Android SDK Platform 35 and accept licenses.
5. For a quick test: connect an Android phone with USB debugging enabled, or create an emulator, then press Run (green triangle).
6. To make an APK: Build > Build Bundle(s) / APK(s) > Build APK(s).
7. When finished, click "locate" in the notification. The APK is usually at:
   app/build/outputs/apk/debug/app-debug.apk
8. Transfer the APK to your Android phone and open it to install. Android may ask you to allow
   installation from that source. Only install APKs you built or trust.

Notes
-----
- This project is a starter prototype, not a published Play Store app.
- It does not have login, cloud sync, bank connection, or automatic renewal notifications.
- Data is saved on that device in the app's local storage. Uninstalling the app or clearing
  its storage may erase the data.
- The Android project requires Android Studio/Gradle to build the APK; this ZIP is source code,
  not a precompiled APK.
