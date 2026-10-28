# StudentHub — Android Application Development Assignment 2

A Java + XML Android app demonstrating common application screens and local demo authentication.

## Features
- Splash screen with app logo/name and navigation to Login.
- Login with email/username and password.
- Registration with name, valid email, minimum password length, and confirm-password validation.
- Forgot Password screen with simulated local recovery.
- Reset Password with validation and local storage.
- Dashboard with a 2 × 2 GridLayout of module cards.
- Profile screen showing account information and Logout.
- Explicit Intents between Activities.
- `strings.xml`, default colors, and `values-night/colors.xml` for night mode.
- Uses ConstraintLayout (Splash), LinearLayout (forms), and GridLayout (Dashboard).

## Demo login
- Email: `demo@studenthub.com`
- Password: `Student123`

You can also register a new local demo account. This project does not use a backend; passwords are stored locally for assignment demonstration only.

## Navigation
Splash → Login → Dashboard → Profile → Logout  
Login → Register → Login  
Login → Forgot Password → Reset Password → Login

## Run in Android Studio
1. Extract the ZIP.
2. Open Android Studio and select **Open**.
3. Select the extracted `StudentHub_Android_Project` folder (the folder containing `settings.gradle`).
4. Let Gradle sync finish. Use JDK 17 if Android Studio asks.
5. Select an emulator or connect an Android phone, then press **Run ▶**.

## GitHub
Create a new empty repository on GitHub, then either use Android Studio's **VCS / Share Project on GitHub** option if available, or upload the extracted project through GitHub's website. Do not upload generated `build/` folders.
