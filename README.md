![Banner](./banner.jpg)

# 📲 Push Notification App with Firebase (Flutter)

This is a simple Flutter application integrated with Firebase Cloud Messaging (FCM) to demonstrate how to receive **push notifications** on Android.

> ⚠️ I'm a developer from Brazil 🇧🇷, so you may notice some code comments and strings written in **Portuguese (Brazilian)**.


# 🔧 Features

- Firebase initialization
- FCM token generation
- Permission request for notifications
- Logging token to the console
- Ready for integration with Firebase Messaging Console



# 🛠️ Technologies Used

- [Flutter](https://flutter.dev/)
- [Firebase Core](https://pub.dev/packages/firebase_core)
- [Firebase Messaging](https://pub.dev/packages/firebase_messaging)


# 🚀 Getting Started

# Prerequisites

- Flutter SDK installed
- Android Studio or VS Code
- Firebase project configured

# Clone the repository

```bash
git clone https://github.com/your-username/push_notification_flutter_firebase.git
cd push_notification_flutter_firebase
```

# Install dependencies

```bash
flutter pub get
```

# Run the app

```bash
flutter run
```


# 🔐 Important

Make sure to place your `google-services.json` file in:

```
android/app/google-services.json
```

> This file is **not** included in the repository for security reasons. You must download it from your own Firebase Console.


# 📂 Project Structure

```
lib/
  └── main.dart              # Main app logic (includes FCM setup)
android/
  └── ...                    # Android native files
```

# 🧠 Notes

- Some UI texts and logs are written in Portuguese (ex: `"Você clicou 3 vezes"`).
- Token is printed to the terminal after permission is granted.
- You can test push messages via Firebase Console or Postman.


# 🤝 Contributing

Pull requests are welcome! Feel free to suggest improvements.

Made with ❤️ by a Brazilian dev: **[José/Joseph Ferreira]**