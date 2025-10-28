# Fun Signup App (Flutter)

## 🎯 Objective
A simple and interactive Flutter app that lets users sign up by entering their name, email, and password.  
It demonstrates **form validation**, **screen navigation**, and **animations** in Flutter.

---

## 🧩 Features
✅ Input validation for name, email, and passwords  
✅ Confirm Password field (checks both passwords match)  
✅ Emoji Avatar Picker (select a fun emoji as your avatar)  
✅ Welcome screen with fade & scale animation  
✅ Easy navigation between signup and welcome screens  

---

## ⚙️ Building the Release APK
To generate your release build:
```bash
flutter build apk --release
```

Your release APK will be available at:
```
build/app/outputs/flutter-apk/app-release.apk
```

---

## 💡 Checks to Perform
✅ Leave fields empty → see validation error  
✅ Enter invalid email (without @) → see email error  
✅ Enter short password → see password error  
✅ Enter valid data → navigate to welcome screen with animation  

---

## 📸 Output Preview
- **Signup Screen:** Includes name, email, password, confirm password, avatar picker, and sign-up button.  
- **Welcome Screen:** Displays a fun emoji avatar, user's name, and success animation.

---