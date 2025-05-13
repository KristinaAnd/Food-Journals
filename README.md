**Food Journals**

Food Journals is a mobile app built on React Native and Expo to track food intake through journaling with images and descriptions.

**Features:**
- User registration and login using local SQLite authentication.
- Add food journal entries with photo (from camera or gallery), description and category (breakfast, lunch, dinner, snacks).
- Filter journal entries by category.
- Edit and delete entries.
- Local data storage using expo-sqlite.
- Expo Go compatible (no dev-client required).

**Features:**
- Authentication: Register/login using email and password.
- Camera/Gallery: Add images from device camera or image gallery.
- Journaling: Create, update and delete food journal entries.
- Filter: Filter posts by meal categories.
- Offline: Work completely offline with local SQLite.

**Installation:**
1) Install Node.js and npm, and Expo CLI globally (npm install -g expo-cli).
2) Clone the repository:
3) Install dependencies: `npm install`
4) Install the required Expo modules: `npx expo install expo-sqlite expo-image-picker @react-native-picker/picker react-native-swipe-list-view`
5) Run the project: `npx expo start`
6) Scan the QR code in the terminal using Expo Go on your Android/iOS device.