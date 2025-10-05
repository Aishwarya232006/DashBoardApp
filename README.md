
# Responsive Dashboard App - Lab 4
## Student Information
- **Name:** Aishwarya Chhablani
- **Student ID:** N01711300
- **Course:** CPAN 213
- **Lab:** Lab 4 - Responsive Layouts with Flexbox
- **Date:** September 23, 2025
## Project Description
This responsive dashboard application demonstrates advanced Flexbox layout techniques,
responsive design patterns, and platform-specific styling in React Native.
## Features Implemented
- Responsive grid system with breakpoint detection
- Dashboard widgets with statistics and trends
- Orientation-aware layouts
- Platform-specific styling (iOS/Android)
- Pull-to-refresh functionality
- Performance-optimized StyleSheets
## Technologies Used
- React Native 0.72+
- React Native Orientation Locker
- React Native Vector Icons
- Platform-specific APIs
## Installation
1. Clone the repository
2. Install dependencies: `npm install`
3. Install iOS pods (macOS only): `cd ios && pod install`
4. Run on Android: `npx react-native run-android`
5. Run on iOS: `npx react-native run-ios`
## Project Structure:
ContactManagerApp/
│
├── android/                    # Native Android project files
├── ios/                        # Native iOS project files
│
├── src/                        # Your app’s main source code
│   ├── components/             # Reusable components (buttons, inputs, etc.)
│   ├── screens/                # All screens (HomeScreen, AddContactScreen, etc.)
│   ├── navigation/             # Stack or Tab navigation setup
│   ├── assets/                 # Images, fonts, icons
│   ├── utils/                  # Helper functions or constants
│   ├── App.tsx (or App.js)     # Main app entry (usually imports navigation)
│
├── node_modules/               # Auto-generated folder (you pasted this)
│
├── package.json                # Lists dependencies and scripts
├── babel.config.js             # Babel configuration
├── metro.config.js             # Metro bundler configuration
├── tsconfig.json               # TypeScript configuration (if using TS)
├── app.json                    # App configuration
└── README.md                   # Project documentation
