# Royal Sheers

A mobile app built with **React Native (Expo)**, designed with modular components, safe area support, custom fonts, and a navigation system. This app structure is ideal for rapid mobile development with clean separation of concerns.

## 🚀 Features

- Built using **Expo** for cross-platform support
- Custom Google Fonts using `@expo-google-fonts/neuton`
- Safe area handling with `react-native-safe-area-context`
- Centralized navigation with React Navigation
- Modular project structure:
  - `components/` for reusable UI elements
  - `screens/` for application views
  - `services/` for API or utility logic
  - `entities/` and `types/` for data modeling

## 🧰 Tech Stack

- **React Native** (with TypeScript)
- **Expo SDK**
- **React Navigation**
- **Google Fonts via Expo**
- **TypeScript**
- **Safe Area Context**

## 📁 Project Structure

```
royalsheers/
├── App.tsx                # App entry point
├── components/            # Reusable UI components
├── screens/               # Application screens
├── navigation/            # React Navigation setup
├── services/              # API services or helpers
├── types/                 # TypeScript interfaces and types
├── entities/              # Business domain models
├── assets/                # Static assets like images/fonts
```

## 📦 Setup & Installation

1. **Clone the repo**

   ```bash
   git clone https://github.com/kimenyu/royalsheers-frontend.git
   cd royalsheers-frontend
   ```

2. **Install dependencies**

   ```bash
   npm install
   ```

3. **Start the Expo server**

   ```bash
   npx expo start
   ```

   Or use:

   ```bash
   npm run android
   npm run ios
   npm run web
   ```

## 🧪 Scripts

```bash
npm run start      # Start the Expo project
npm run android    # Open Android emulator
npm run ios        # Open iOS simulator
npm run web        # Open in browser
npm run eject      # Eject from Expo (if needed)
```

## 📜 License

This project is licensed under the MIT License.

## 👨‍💻 Author

- **Kimenyu** – [kimenyu](https://github.com/kimenyu)

---

Feel free to contribute or raise issues to make this project even better!
