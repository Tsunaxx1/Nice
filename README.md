# HomeFix Mobile App

A React Native mobile application for booking home services and repairs. This app connects users with skilled taskers who can help with various home-related tasks such as cleaning, moving, painting, and electrical work.

## Features

- User authentication (Login/Sign Up)
- Browse service categories
- Search for specific services
- Book skilled taskers
- View tasker profiles and ratings
- Real-time notifications
- Account management

## Screenshots

The app includes the following screens:
- Splash Screen
- Login/Sign Up
- Home Dashboard
- Service Booking
- Notifications
- Settings

## Prerequisites

- Node.js (v14 or later)
- npm or yarn
- React Native CLI
- Android Studio (for Android development)
- Xcode (for iOS development, macOS only)

## Installation

1. Clone the repository:
```bash
git clone [repository-url]
cd homefix-app
```

2. Install dependencies:
```bash
npm install
# or
yarn install
```

3. Start the Metro bundler:
```bash
npm start
# or
yarn start
```

4. Run the app:

For iOS:
```bash
npm run ios
# or
yarn ios
```

For Android:
```bash
npm run android
# or
yarn android
```

## Project Structure

```
src/
  ├── screens/          # Screen components
  ├── components/       # Reusable components
  ├── navigation/       # Navigation configuration
  ├── assets/          # Images, fonts, etc.
  └── utils/           # Helper functions
```

## Dependencies

- react-native
- @react-navigation/native
- @react-navigation/stack
- react-native-vector-icons
- react-native-safe-area-context
- react-native-screens
- react-native-gesture-handler

## Contributing

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Create a new Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details. 