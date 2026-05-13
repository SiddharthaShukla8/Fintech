# Fintech App

A modern, scalable fintech mobile application built with React Native and Expo. This comprehensive template provides a production-ready foundation for developing feature-rich banking and financial applications with robust authentication, intuitive navigation, and professional UI components.

## 📋 Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
- [Project Structure](#project-structure)
- [Available Scripts](#available-scripts)
- [Contributing](#contributing)
- [License](#license)

## Overview

This application demonstrates best practices for mobile fintech development, including secure authentication flows, comprehensive state management, and reusable component architecture. It serves as an excellent starting point for developers looking to build sophisticated financial applications.

### Preview

<img src="./assets/images/Fintech Mobile App.png" alt="Fintech Mobile App Preview" width="600" />

*Professional preview of the Fintech application user interface*

## ✨ Features

### Core Functionality
- **🔐 Secure Authentication:** Comprehensive authentication system with support for traditional login, registration, and biometric authentication
- **💳 Tab-Based Navigation:** Intuitive bottom tab navigation providing seamless access to key sections (Dashboard, Cards, Investments, Payments, Profile)
- **📱 Modal Workflows:** Advanced modal implementations for critical operations including money transfers, card management, and transaction management
- **🎨 Professional UI Components:** Carefully crafted, reusable components including buttons, cards, inputs, and loading states

### Technical Features
- **🌐 State Management:** Context API-based global state management for authentication, theme, finance, and notifications
- **🔤 Type Safety:** Full TypeScript support ensuring code quality and preventing runtime errors
- **🎯 Responsive Design:** Mobile-first design approach with support for multiple screen sizes and orientations
- **⚡ Performance Optimized:** Optimized rendering and efficient state updates for smooth user experience

## 🛠️ Tech Stack

### Framework & Runtime
- **[React Native](https://reactnative.dev/)** - Cross-platform mobile development framework
- **[Expo](https://expo.dev/)** - Managed React Native platform simplifying development and deployment

### Navigation & Routing
- **[Expo Router](https://docs.expo.dev/router/introduction/)** - File-based routing for React Native
- **[React Navigation](https://reactnavigation.org/)** - Comprehensive navigation solution with support for tabs, stacks, and drawers

### UI & Styling
- **[Expo Blur](https://docs.expo.dev/versions/latest/sdk/blur-view/)** - Native blur view effects
- **[Expo Linear Gradient](https://docs.expo.dev/versions/latest/sdk/linear-gradient/)** - Gradient backgrounds and effects
- **[Lucide React Native](https://lucide.dev/guide/packages/lucide-react-native)** - Professional icon library
- **[Google Fonts - Inter](https://fonts.google.com/)** - Modern, readable typography

### Development Tools
- **[TypeScript](https://www.typescriptlang.org/)** - Superset of JavaScript with static typing
- **[ESLint](https://eslint.org/)** - Code quality and style consistency

## 🚀 Getting Started

### Prerequisites

- **Node.js** (LTS version 18+ recommended)
- **npm** or **yarn** package manager
- **Expo Go** app (available on [iOS App Store](https://apps.apple.com/app/expo-go/id982107779) and [Google Play Store](https://play.google.com/store/apps/details?id=host.exp.exponent))
- Android emulator or iOS simulator (optional, for local testing)

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/SiddharthaShukla8/Fintech.git
   cd Fintech
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Verify installation:**
   ```bash
   npm run lint
   ```

### Running the Application

1. **Start the development server:**
   ```bash
   npm run dev
   ```

2. **Connect to your device:**
   - **Mobile Device:** Scan the QR code displayed in the terminal using the Expo Go app
   - **Android Emulator:** Press `a` in the terminal
   - **iOS Simulator:** Press `i` in the terminal

3. **Hot Reload:** The app automatically reloads when you save changes

## 📜 Available Scripts

### Development
```bash
# Start the development server with telemetry disabled
npm run dev
```

### Production
```bash
# Create a production build for web platform
npm run build:web
```

### Code Quality
```bash
# Run ESLint to check code quality
npm run lint
```

## 📁 Project Structure

```
.
├── app/                           # Main application source code
│   ├── (tabs)/                    # Tab-based navigation layout
│   │   ├── _layout.tsx            # Tab layout configuration
│   │   ├── index.tsx              # Dashboard screen
│   │   ├── cards.tsx              # Cards management screen
│   │   ├── investments.tsx        # Investment portfolio screen
│   │   ├── payments.tsx           # Payment operations screen
│   │   └── profile.tsx            # User profile screen
│   ├── auth/                      # Authentication screens
│   │   ├── _layout.tsx            # Auth layout
│   │   ├── index.tsx              # Welcome screen
│   │   ├── login.tsx              # User login
│   │   ├── register.tsx           # User registration
│   │   └── biometric.tsx          # Biometric authentication
│   ├── modals/                    # Modal screens for workflows
│   │   ├── send-money.tsx         # Money transfer modal
│   │   ├── add-card.tsx           # Card addition modal
│   │   ├── request-money.tsx      # Money request modal
│   │   ├── split-bill.tsx         # Bill splitting modal
│   │   ├── transaction-history.tsx # Transaction log modal
│   │   └── (other modals...)
│   ├── _layout.tsx                # Root application layout
│   └── +not-found.tsx             # 404 error screen
├── components/                    # Reusable React components
│   ├── auth/                      # Authentication components
│   │   ├── AuthInput.tsx          # Custom authentication input
│   │   └── WelcomeScreen.tsx      # Welcome screen component
│   ├── modals/                    # Modal components
│   │   └── SendMoneyModal.tsx     # Send money modal component
│   └── ui/                        # Generic UI components
│       ├── AnimatedButton.tsx     # Animated button component
│       ├── Card.tsx               # Card display component
│       ├── LoadingButton.tsx      # Loading state button
│       └── Modal.tsx              # Modal wrapper component
├── contexts/                      # React Context providers
│   ├── AuthContext.tsx            # Authentication state management
│   ├── FinanceContext.tsx         # Financial data management
│   ├── NotificationContext.tsx    # Notification management
│   └── ThemeContext.tsx           # Theme state management
├── hooks/                         # Custom React hooks
│   └── useFrameworkReady.ts       # Framework initialization hook
├── assets/                        # Static assets
│   └── images/                    # Image files
├── app.json                       # Expo configuration
├── package.json                   # Project dependencies
├── tsconfig.json                  # TypeScript configuration
└── README.md                      # This file
```

## 🤝 Contributing

We welcome contributions from the community. To contribute:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

Please ensure your code follows the project's style guidelines and includes appropriate documentation.

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 📞 Support

For support, questions, or issues, please open an issue on the [GitHub repository](https://github.com/SiddharthaShukla8/Fintech/issues).

---

**Built with ❤️ by Siddhartha Shukla**