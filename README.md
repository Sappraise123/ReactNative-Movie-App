# 🎬 ReactNative Movie App

A sleek, cross-platform movie discovery app built with **React Native**, **Expo**, and **TypeScript**. Browse trending films, explore details, and enjoy a smooth, modern UI powered by NativeWind (Tailwind CSS).

---

## ✨ Features

- 🔍 **Movie Discovery** — Browse and search movies with real-time data
- 📱 **Cross-Platform** — Runs on iOS, Android, and Web
- 🎨 **Modern UI** — Styled with NativeWind (Tailwind CSS for React Native)
- ⚡ **Smooth Animations** — Powered by React Native Reanimated & Gesture Handler
- 🔐 **Auth Support** — Expo Auth Session integration
- 🗂️ **File-based Routing** — Clean navigation via Expo Router
- 🏗️ **TypeScript** — Fully typed codebase for reliability

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| React Native 0.79 + React 19 | Core framework |
| Expo SDK 53 | Build tooling & native APIs |
| Expo Router | File-based navigation |
| TypeScript | Type safety |
| NativeWind v4 + Tailwind CSS | Styling |
| React Native Reanimated | Animations |
| React Native Appwrite | Backend / database |
| Expo Linear Gradient | UI gradients |
| React Native Heroicons | Icon set |

---

## 📁 Project Structure

```
ReactNative-Movie-App/
├── app/              # Expo Router screens & layouts
├── components/       # Reusable UI components
├── services/         # API calls & data fetching
├── interfaces/       # TypeScript interfaces
├── types/            # Shared type definitions
├── constants/        # App-wide constants
├── assets/           # Images, fonts, and static files
├── app.json          # Expo app config
├── tailwind.config.js
└── tsconfig.json
```

---

## 🚀 Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) v18+
- [Expo CLI](https://docs.expo.dev/get-started/installation/) — `npm install -g expo-cli`
- iOS Simulator / Android Emulator **or** the [Expo Go](https://expo.dev/go) app

### Installation

```bash
# 1. Clone the repository
git clone https://github.com/Sappraise123/ReactNative-Movie-App.git
cd ReactNative-Movie-App

# 2. Install dependencies
npm install

# 3. Set up environment variables
cp .env.example .env
# Fill in your API keys in .env
```

### Running the App

```bash
# Start Expo dev server
npm start

# Run on Android
npm run android

# Run on iOS
npm run ios

# Run on Web
npm run web
```

---

## ⚙️ Environment Variables

Create a `.env` file in the root directory:

```env
EXPO_PUBLIC_TMDB_API_KEY=your_tmdb_api_key_here
EXPO_PUBLIC_APPWRITE_ENDPOINT=your_appwrite_endpoint
EXPO_PUBLIC_APPWRITE_PROJECT_ID=your_project_id
```

> ⚠️ Never commit your `.env` file. It's already in `.gitignore`.

---

## 🧪 Testing & Linting

```bash
# Run tests
npm test

# Lint the project
npm run lint
```

---

## 📦 Key Dependencies

```json
"expo": "~53.0.0",
"react-native": "0.79.5",
"react": "19.0.0",
"expo-router": "~5.1.7",
"nativewind": "^4.1.23",
"react-native-reanimated": "~3.17.4",
"react-native-appwrite": "^0.7.0"
```

---

## 🤝 Contributing

1. Fork the repo
2. Create a feature branch: `git checkout -b feature/your-feature`
3. Commit your changes: `git commit -m 'Add your feature'`
4. Push to the branch: `git push origin feature/your-feature`
5. Open a Pull Request

---

## 👤 Author

**Praise** — [@Sappraise123](https://github.com/Sappraise123)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
