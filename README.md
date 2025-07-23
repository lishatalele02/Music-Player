
# 🎵 Android Music Player App

This is a simple Music Player application developed using **Android Studio (Version: Ladybug)**. The app allows users to play, pause, stop, shuffle, and navigate through categorized songs like **Marathi**, **English**, and **Hindi**. It uses `MediaPlayer`, `ExpandableListView`, and a custom UI with `SeekBar` for song tracking.

---

## 🛠 Features

- 🎶 Categorized Song List (Marathi, English, Hindi)
- ▶️ Play / ⏸ Pause / ⏹ Stop Buttons
- ⏭ Play Next Song
- 🔀 Shuffle Mode On/Off
- 📶 Song Time Progress via SeekBar
- 💬 User-friendly UI with song title display and current time tracker

---

## 🧰 Technologies Used

- Android Studio (Ladybug)
- Java (Android SDK)
- XML Layouts
- MediaPlayer API
- ExpandableListView

---

## 📁 Project Structure

- `activity_main.xml` – UI layout of the app
- `MainActivity.java` – Core functionality for media control and song management
- `AndroidManifest.xml` – App configuration

---

## 🚀 Getting Started

1. Clone or download the project.
2. Open the project in **Android Studio (Ladybug)**.
3. Add your song files (`.mp3`) to `res/raw` directory. Ensure the filenames match those in the code (`kaakan_marathi.mp3`, `perfect.mp3`, etc.).
4. Run the app on an emulator or physical device.

---

## 🔊 Supported Song Categories

- Marathi Songs (e.g., kaakan_marathi, mla_ved_lagale)
- English Songs (e.g., night_changes, perfect)
- Hindi Songs (e.g., pehla_pyaar, humdard)

> Song files must be added to `res/raw` with the correct name and `.mp3` format.

---

## 📋 Screens Included

- **MainActivity.java**: Handles UI actions and music playback.
- **ExpandableListAdapter.java**: Adapter to populate songs under categories.
- **activity_main.xml**: UI layout with buttons, seek bar, and song list.
- **AndroidManifest.xml**: App configuration and launcher settings.

---

## 📱 UI Highlights

- Light-on-dark theme for immersive feel
- Highlighted buttons with color-coded actions
- Smooth seek bar tracking with real-time updates

---

## 📌 Future Enhancements

- [ ] Add a mini-player in notification bar
- [ ] Create playlists and favorite songs
- [ ] Support background play and service
- [ ] Add animations or transitions for better UX

---

## 🧑‍💻 Author

Developed by: **Lisha Talele**  
Tool Used: **Android Studio (Ladybug)**  
Language: **Java**

---

## 📃 License

This project is for educational purposes. You are free to modify and use it for learning or personal apps.

