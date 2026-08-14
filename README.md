# Music Wallpaper 🎵🖼️ (Itachi Version)

Spoti Wall is a dynamic wallpaper generator that updates your desktop background with the currently playing song's album cover, title, artist name, and a random anime quote. It brings a visually immersive music experience to your desktop!

---

## ✨ Features

- 🎨 **Dynamic Wallpapers** – Updates wallpaper with the current song details.
- 🖼 **Album Cover Display** – Shows the album cover of the playing song.
- 🎵 **Song Info Overlay** – Displays song title and artist.
- 💬 **Anime Quotes** – Adds random inspiring anime quotes.

---

## 📸 Screenshots

### 🎶 
![Screenshot_1](https://github.com/user-attachments/assets/f722ab21-ef58-477d-9cb9-34e405fd1764)

### 🖼️
![Screenshot_2](https://github.com/user-attachments/assets/49cdb5fe-5783-4516-9a19-f283eab3c526)

---

## 🚀 Installation

### 1️⃣ Install Dependencies
Make sure you have Python installed, then run:

### 2️⃣ Run Spoti Wall
```bash
python Musi-Wall.py
```

---

## 🛠️ Building the Executable (recommended)
To create a executable (.exe file), run the following command:
```bash
python -m PyInstaller --onefile --windowed \
    --add-data "top.png;." \
    --add-data "back.png;." \
    --add-data "font3.ttf;." \
    --add-data "icon.ico;." \
    --add-data "moon.png;." \
    --icon=icon.ico Musi-Wall.py
```
This will generate a `Musi-Wall.exe` file inside the folder `dist`.

---

## 🎵 How It Works
1. Monitors your currently playing song using Windows Media API.
2. Extracts the song title, artist name, and album cover.
3. Generates a custom wallpaper using Pillow.
4. Sets the new wallpaper dynamically.

---

## 💡 Notes
- Works only on **Windows 10+**.
- the app runs in the background you can close it from the icon tray.



