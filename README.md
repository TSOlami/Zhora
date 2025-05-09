# Zhora - React Native Mobile App

## What is Zhora?

Zhora is a React Native mobile app built with Expo. It has a tab-based navigation system with light and dark mode support. The app shows how to use different React Native features like animations, custom components, and responsive design.

## Technologies Used

### Core Framework
- **React Native** - For building the mobile app
- **Expo** - Development platform that makes React Native easier to use
- **TypeScript** - Programming language that adds types to JavaScript

### Navigation
- **Expo Router** - For navigation between screens
- **React Navigation** - For tab-based navigation

### UI Components
- **Reanimated** - For smooth animations
- **Expo Blur** - For blur effects (especially on iOS)
- **Expo Symbols** - For using SF Symbols on iOS and Material Icons on Android/web

### Device Features
- **Expo Haptics** - For vibration feedback on iOS
- **Expo Web Browser** - For opening links inside the app
- **Expo Linking** - For handling deep links
- **Expo Status Bar** - For controlling the status bar
- **Expo Splash Screen** - For customizing the app loading screen
- **Expo Constants** - For accessing device and app information

### Testing & Development
- **Jest** - For testing components
- **Babel** - For compiling JavaScript
- **ESLint** - For checking code quality

## Features

### UI Components
- **Themed Components** - Automatically adjust for light/dark mode
- **ParallaxScrollView** - Scrollable view with parallax effect
- **Collapsible** - Expandable/collapsible sections
- **HapticTab** - Tab bar with vibration feedback (iOS)
- **ExternalLink** - Links that open in the in-app browser
- **HelloWave** - Animated waving hand emoji

### Navigation
- **Tab Navigation** - Bottom tab bar for switching between screens
- **Custom Tab Bar** - With special styling for iOS (blur effect)
- **File-based Routing** - Using Expo Router's file system-based routing

### Styling & Theming
- **Light & Dark Mode** - Complete theme support
- **Custom Fonts** - Support for loading and using custom fonts
- **Design System** - Consistent text styles (title, subtitle, link, etc.)

### Platform Support
- **iOS** - Optimized for iOS with native-feeling components
- **Android** - Adapted for Android with appropriate alternatives
- **Web** - Support for running in web browsers

### Development Tools
- **Reset Project Script** - Script to create a clean project while preserving examples
- **Type Safety** - Full TypeScript support throughout the project

## Getting Started

1. Install dependencies:
   ```bash
   npm install
   ```

2. Start the app:
   ```bash
   npx expo start
   ```

3. Follow the terminal instructions to run on:
   - iOS simulator
   - Android emulator
   - Web browser
   - Physical device using Expo Go

## Project Structure

- **/app** - Main application screens using file-based routing
- **/components** - Reusable UI components
- **/constants** - App-wide constants (colors, etc.)
- **/hooks** - Custom React hooks
- **/assets** - Static assets (images, fonts)
- **/scripts** - Utility scripts for project

## Getting a Fresh Start

When you're ready to build your own app based on this template:

```bash
npm run reset-project
```

This will move the example code to an "app-example" folder and create a clean app structure.

## Learn More

- [Expo Documentation](https://docs.expo.dev/)
- [React Native Documentation](https://reactnative.dev/)
- [Expo Router Documentation](https://docs.expo.dev/router/introduction/)
