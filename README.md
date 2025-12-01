# 🎮 Game Projects Collection

A collection of classic arcade games built with C++ and SFML (Simple and Fast Multimedia Library). This repository contains multiple game implementations featuring engaging gameplay, smooth graphics, and cross-platform support.

## 🎯 Games Included

Our collection features 4 classic arcade games:

| Game | Description |
|------|-------------|
| **Arkanoid** | A classic brick-breaker game where you control a paddle to break bricks and clear levels |
| **Asteroid** | Navigate through space destroying asteroids while avoiding collisions |
| **Match 3 Gems** | Match three or more gems in a row to clear them and score points |
| **Tetris** | The timeless block-stacking puzzle game with increasing difficulty |

---

## 📥 Installation & Setup

### Windows Installation

1. **Download the repository:**
   - Navigate to the [GitHub](https://github.com/RRR-STAR/Games) repository main page
   - Click the **Code** dropdown button
   - Select **Download ZIP**

2. **Extract the files:**
   - Right-click the downloaded .zip file
   - Select **Extract All** and choose your destination folder

3. **Run a game:**
   - Navigate to the specific game folder (e.g., `Arkanoid Game/`)
   - Double-click `GAME (Windows).exe`
   - Grant permission if prompted by Windows

### Linux Installation

1. **Download the repository:**
   ```bash
   git clone https://github.com/RRR-STAR/Games.git
   cd Games
   ```
   
   Or download the ZIP file:
   - Navigate to the GitHub repository main page
   - Click the **Code** dropdown button
   - Select **Download ZIP**
   - Extract the downloaded file

2. **Extract the files (if using ZIP):**
   ```bash
   unzip Games-main.zip
   cd Games-main
   ```

3. **Make the game executable:**
   ```bash
   cd "Arkanoid Game"  # or your chosen game folder
   chmod +x 'GAME (Linux).sh'
   ```

4. **Run the game:**
   ```bash
   ./GAME\ \(Linux\).sh
   ```
   Or simply double-click the `GAME (Linux).sh` file in your file manager

---

## 🛠️ Development Guide

If you want to modify or extend these games, follow these steps:

### Prerequisites

**Install SFML Library:**

   **Windows:**
   - Download SFML from [sfml-dev.org](https://www.sfml-dev.org/download.php)
   - Follow the [official Windows setup guide](https://www.sfml-dev.org/tutorials/2.6/start-windows.php)
   - Link the SFML libraries in your C++ IDE

   **Linux:**
   - Using package manager (recommended):
     ```bash
     sudo apt update
     sudo apt install libsfml-dev
     ```
   
   - Or download manually:
     - Visit [sfml-dev.org](https://www.sfml-dev.org/download.php)
     - Download the Linux version
     - Follow the [official Linux setup guide](https://www.sfml-dev.org/tutorials/2.6/start-linux.php)

### Compiling from Source

```bash
# Linux example
g++ -c Code.cpp -o GameBinary -lsfml-graphics -lsfml-window -lsfml-system -lsfml-audio
./GameBinary
```

---

## 📱 Platform Support

| Platform | Status | Supported |
|----------|--------|-----------|
| Windows | ✅ | Fully Supported |
| Linux | ✅ | Fully Supported |
| macOS | ⚠️ | May require manual compilation |
| Mobile | ❌ | Not Supported |

> **Note:** These games are optimized for desktop and laptop devices. Mobile support is not currently available.

---

## 🔧 Technologies Used

- **Language:** C++
- **Graphics Library:** SFML 2.6 (Simple and Fast Multimedia Library)
- **Audio:** OpenAL (via SFML)
- **Development:** Cross-platform compatible

---

## 🚀 Quick Download

**[⬇️ Download All Games Now](https://github.com/RRR-STAR/Games/archive/refs/heads/main.zip)**

