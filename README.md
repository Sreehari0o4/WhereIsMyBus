# WhereIsMyBus

A modern mobile application that helps users track and monitor bus routes in real-time, providing accurate arrival times and convenient notifications.

![WhereIsMyBus App](https://via.placeholder.com/800x400?text=WhereIsMyBus+App)

## Features

- **Real-time Bus Tracking**: Monitor bus locations and estimated arrival times
- **Route Search**: Easily find bus routes and stops near your location
- **Notifications**: Get notified when your bus is approaching
- **Interactive Map**: View bus stops and routes on an interactive map
- **User-friendly Interface**: Modern, intuitive UI designed for ease of use
- **History Tracking**: Review your frequently used routes and stops

## Implementation Details

### Technology Stack

- **Frontend**: React Native with Expo
- **UI Libraries**: 
  - React Native Paper
  - React Native Elements
  - React Native Vector Icons
- **Navigation**: React Navigation for seamless screen transitions
- **State Management**: React Hooks for local state management
- **Maps Integration**: React Native Maps (placeholder for future implementation)

### Project Structure

```
WhereIsMyBus/
├── assets/            # Images, fonts, and other static assets
├── src/               # Source code
│   ├── components/    # Reusable UI components
│   ├── screens/       # Application screens
│   ├── navigation/    # Navigation configuration
│   ├── services/      # API services and data fetching
│   └── utils/         # Utility functions and helpers
├── App.tsx            # Main application component
├── app.json           # Expo configuration
└── package.json       # Dependencies and scripts
```

### Key Components

#### Bus Route Cards

Custom cards display important route information including:
- Route number
- Route name
- Estimated arrival time
- Proximity status (nearby or not)
- Notification options

#### Bottom Navigation

The app features a bottom navigation bar with four main sections:
- Home: View nearby routes and search
- Map: Interactive map view (placeholder)
- History: Track frequently used routes (placeholder)
- Settings: App configuration (placeholder)

#### Search Functionality

Users can search for specific bus routes or stops using the search bar located at the top of the home screen.

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn
- Expo CLI
- iOS/Android simulator or physical device with Expo Go app

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Sreehari0o4/WhereIsMyBus.git
   cd WhereIsMyBus
   ```

2. Install dependencies:
   ```bash
   npm install
   # or
   yarn install
   ```

3. Start the development server:
   ```bash
   npx expo start
   ```

4. Open the app on your device or simulator:
   - Scan the QR code with the Expo Go app (Android) or the Camera app (iOS)
   - Press 'a' to open on an Android emulator
   - Press 'i' to open on an iOS simulator

## Future Enhancements

- **Backend Integration**: Connect to a real-time transit data API
- **User Authentication**: Allow users to create accounts and save preferences
- **Favorite Routes**: Save frequently used routes for quick access
- **Push Notifications**: Send alerts when buses are approaching
- **Offline Mode**: Basic functionality when internet connection is unavailable

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Contact

Sreehari S Kumar - [@Sreehari0o4](https://github.com/Sreehari0o4)

Project Link: [https://github.com/Sreehari0o4/WhereIsMyBus](https://github.com/Sreehari0o4/WhereIsMyBus) 