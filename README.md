# Flutter Authentication UI

✨ A Flutter-based Authentication UI featuring 🔑 two types of Sign-In & Sign-Up forms. 🎨 Easily customizable and ready for integration with Firebase or any backend! 🚀

## 📌 Features
- 🔑 **Two Authentication Forms** (Standard & Minimal)
- 🎨 **Modern & Clean UI** with intuitive design
- 🔄 **Fully Responsive** for mobile and tablet
- 🔧 **Easily Customizable** (colors, fonts, layouts)
- 🔗 **Ready for Firebase or any Backend Integration**
- 🚀 **Smooth Animations & UI Effects**

## 📸 Screenshots
<p align="center">
  <img src="assets/screenshots/signin.png" width="250"> 
  <img src="assets/screenshots/signup.png" width="250"> 
</p>

## 🚀 Getting Started
### 1️⃣ Prerequisites
Make sure you have Flutter installed on your system.

```sh
flutter --version
```

### 2️⃣ Clone the Repository
```sh
git clone https://github.com/Hifza-Khalid/flutter_auth_forms.git
cd flutter_auth_forms
```

### 3️⃣ Install Dependencies
```sh
flutter pub get
```

### 4️⃣ Run the App
```sh
flutter run
```

## 🔥 Firebase Integration (Optional)
To integrate Firebase Authentication:
1. Create a Firebase project at [Firebase Console](https://console.firebase.google.com/).
2. Add your `google-services.json` (Android) and `GoogleService-Info.plist` (iOS) files to the project.
3. Install Firebase dependencies:
   ```sh
   flutter pub add firebase_auth firebase_core
   ```
4. Initialize Firebase in your `main.dart`:
   ```dart
   void main() async {
     WidgetsFlutterBinding.ensureInitialized();
     await Firebase.initializeApp();
     runApp(MyApp());
   }
   ```

## 📂 Project Structure
```
flutter_auth_forms/
├── lib/
│   ├── main.dart
│   ├── screens/
│   │   ├── signin_screen.dart
│   │   ├── signup_screen.dart
│   ├── widgets/
│   │   ├── custom_button.dart
│   │   ├── input_field.dart
│   ├── utils/
│   │   ├── themes.dart
├── assets/
│   ├── screenshots/
│   │   ├── signin.png
│   │   ├── signup.png
```

## 🛠 Technologies Used
- **Flutter** (UI Framework)
- **Dart** (Programming Language)
- **Firebase** (Authentication - Optional)

## 🤝 Contributing
Contributions are welcome! Feel free to submit a pull request or open an issue.

## 📜 License
This project is licensed under the MIT License.
