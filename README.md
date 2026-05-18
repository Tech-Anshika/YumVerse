# 🍔 YumVerse

**YumVerse** is a modern, cross-platform mobile application built with **React Native** and **Expo**. It serves as your ultimate digital cookbook, allowing users to discover, search, and save their favorite recipes with an elegant and user-friendly interface.

## ✨ Features

- **🏠 Discover Recipes:** Browse a curated feed of delicious recipes on the home screen.
- **🔍 Advanced Search:** Easily find recipes based on ingredients, meal types, or cuisines.
- **❤️ Favorites:** Save your most loved recipes for quick access later.
- **🔐 Secure Authentication:** Seamless user login and signup powered by **Clerk**.
- **📱 Cross-Platform:** Works flawlessly on both iOS and Android devices.
- **⚡ Fast & Fluid UI:** Smooth animations and transitions using `react-native-reanimated`.

---

## 🛠️ Tech Stack

- **Framework:** [React Native](https://reactnative.dev/)
- **Platform/Tooling:** [Expo](https://expo.dev/)
- **Routing:** [Expo Router](https://docs.expo.dev/router/introduction/) (File-based navigation)
- **Authentication:** [Clerk Expo](https://clerk.com/docs/quickstarts/expo)
- **UI & Animations:** `react-native-reanimated`, `@expo/vector-icons`
- **Language:** JavaScript/JSX

---

## 🚀 Getting Started

Follow these instructions to get a local copy up and running.

### 1. Prerequisites
- Node.js installed on your machine
- Expo CLI installed globally (optional but recommended)
- Expo Go app installed on your physical device OR an iOS Simulator/Android Emulator set up on your computer.

### 2. Installation
Clone the repository and install the necessary dependencies:

```bash
git clone https://github.com/Tech-Anshika/YumVerse.git
cd YumVerse
npm install
```

### 3. Environment Variables
Since the app uses Clerk for authentication, you will need your Clerk Publishable Key.
Create a `.env` file in the root directory and add your key:

```env
EXPO_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key_here
```

### 4. Run the App
Start the development server:

```bash
npx expo start
```
From the terminal, you can:
- Press `i` to open in iOS simulator
- Press `a` to open in Android emulator
- Scan the QR code using the **Expo Go** app on your physical device.

---

## 📂 Project Structure

```text
YumVerse/
├── app/
│   ├── (auth)/        # Authentication screens (Login, Signup)
│   ├── (tabs)/        # Main tab navigation (Home, Search, Favorites)
│   ├── recipe/        # Detailed recipe viewing screens
│   └── _layout.jsx    # Root layout configuration
├── assets/            # Images, fonts, and other static assets
├── components/        # Reusable UI components
├── constants/         # App-wide constants (colors, themes, config)
├── hooks/             # Custom React hooks
└── services/          # API calls and backend services
```

---

## 🤝 Contributing
Contributions, issues, and feature requests are welcome! 
Feel free to check the [issues page](https://github.com/Tech-Anshika/YumVerse/issues).

## 📝 License
This project is licensed under the MIT License.
