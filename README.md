# Android Common Screens Application (Java + XML)

An Android application built with Java and XML demonstrating core mobile app navigation, input validation, custom resources, and common screens.

## Features & Navigation Flow
- **Splash Screen:** Displays application branding and auto-navigates to Login.
- **Login Screen:** Input fields for email and password with validation.
- **Register Screen:** Input validation for full name, email, and matching passwords.
- **Forgot & Reset Password Screens:** Handles simulated password recovery workflows.
- **Dashboard / Home Screen:** Displays main modules using a structured `GridLayout`.
- **Profile Screen:** Shows user information and provides a Logout option.

## Technical Highlights
- **Layouts Used:** `LinearLayout`, `GridLayout`, `ConstraintLayout`.
- **Navigation:** Explicit `Intents` with activity stack management.
- **Resources:** Standard `strings.xml` and alternative night-mode resources (`res/values-night/colors.xml`).
