# Gym Membership Management Android Application

A full-stack Android and web application designed to streamline gym operations, member onboarding, subscription tracking, and automated fee reminders.

## Key Features

- **Member Management:** Digital onboarding, profile tracking, and membership plan lifecycle management.
- **Real-Time Cloud Sync:** Instant multi-device data synchronization powered by Firebase Realtime Database.
- **Secure Authentication:** Role-based login and access control using Firebase Authentication.
- **Automated WhatsApp Workflows:** One-click generation of customer billing receipts and proactive membership renewal reminders via WhatsApp.
- **White-Label Branding:** Configurable gym branding support for customized headers and receipts.
- **Native Android Packaging:** Built as a responsive web application and compiled into a standalone Android APK using Capacitor and Android Studio.

## Tech Stack

- **Frontend:** HTML5, CSS3, JavaScript (ES6+), Responsive UI Design
- **Mobile Framework:** Capacitor, Android Studio, Gradle
- **Backend & Database:** Firebase Authentication, Firebase Realtime Database

## Project Structure

├── www/                  # Core frontend source files (HTML, CSS, JavaScript)
├── capacitor.config.json # Capacitor native runtime configuration
├── package.json          # Project dependencies and build scripts
└── package-lock.json     # Locked dependency tree

## Setup & Installation

1. **Clone the repository:**
   git clone https://github.com/rocky7788/Gym.git
   cd Gym

2. **Install dependencies:**
   npm install

3. **Configure Firebase:**
   - Create a project in the Firebase Console.
   - Enable **Firebase Authentication** and **Firebase Realtime Database**.
   - Add your Firebase web configuration credentials to the frontend config file inside `www/`.

4. **Sync and Build for Android:**
   npx cap sync android
   npx cap open android
   Open the project in **Android Studio** to run on an emulator/device or generate a signed APK.

## Author

**Panchanana Jena**
- GitHub: https://github.com/rocky7788
- LinkedIn: https://www.linkedin.com/in/panchananajena1524
