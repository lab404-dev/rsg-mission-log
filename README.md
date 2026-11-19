# 🤠 Outlaw & Heist Log

**A fan-made mission and request tracker for Red Dead Redemption and Grand Theft Auto.**

Outlaw & Heist Log is a browser-based companion application developed by **Lab404-Dev**. It helps players organize missions, character requests, collectibles, side objectives, and personal notes across four Rockstar Games titles.

The interface combines a western-inspired journal aesthetic with a modern heist-planning dashboard, featuring individual visual themes and sound effects for each game.

## 🎮 Supported Games

| Game | Theme | Journal |
|---|---|---|
| Red Dead Redemption II | Western / Dark Red | Arthur Morgan's Journal |
| Red Dead Redemption | Classic Western / Orange | John Marston's Log |
| Grand Theft Auto V | Urban / Green | Los Santos Heist Board |
| Grand Theft Auto VI | Vice City / Neon Pink | Vice City Casebook |

Switching between games automatically updates the interface, color palette, typography, character list, and contextual descriptions.

## ✨ Features

### 📋 Mission & Request Management
- Create custom objectives and requests.
- Assign objectives to predefined characters.
- Add optional notes, locations, and additional details.
- Mark objectives as completed or reopen them.
- Delete individual entries.
- Select objectives to view their full details.

### 📊 Completion Tracking
- Real-time completion statistics.
- Dynamic progress bar.
- Percentage-based completion indicator.
- Separate progress tracking for each game.

### 🔍 Task Filtering
Organize objectives using three filters:

- **All** — Display every objective.
- **Active** — Show unfinished objectives.
- **Completed** — Display finished objectives.

Completed objectives can also be cleared in bulk with a confirmation dialog.

### 🎨 Dynamic Game Themes

Each supported title has its own visual identity.

| Game | Primary Accent | Typography |
|---|---|---|
| RDR II | Red | Cinzel / Oswald |
| RDR I | Orange | Rye / Oswald |
| GTA V | Green | Anton / Oswald |
| GTA VI | Pink / Cyan | Bebas Neue / Montserrat |

The interface uses CSS custom properties to dynamically change backgrounds, accents, cards, buttons, and typography.

### 🔊 Procedural Sound Effects

The application includes a custom sound engine built with the **Web Audio API**.

Sound effects are generated directly in the browser without external audio files.

Different sound profiles are implemented for each game:

- **RDR II / RDR I:** Soft journal-writing sounds, wooden menu interactions, and paper effects.
- **GTA V:** Subtle digital notification tones inspired by the iFruit interface.
- **GTA VI:** Warm analog synthesizer tones with a Vice City-inspired atmosphere.

Sound effects can be enabled or disabled using the SFX toggle. The preference is saved locally.

### 💾 Local Storage & Backup

All objectives and preferences are stored locally in the browser using `localStorage`.

The application supports:

- Automatic saving of objectives.
- Persistent active-game selection.
- Persistent sound preferences.
- JSON backup export.
- JSON backup import.
- Separate objective storage for all four games.

No backend or external database is required.

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| HTML5 | Application structure |
| CSS3 | Custom styling and game themes |
| JavaScript (ES6+) | Application logic and interactions |
| Tailwind CSS | Utility-based styling |
| Web Audio API | Procedural sound generation |
| LocalStorage API | Persistent browser storage |
| Google Fonts | Game-inspired typography |

## 🚀 Getting Started

### Requirements

- A modern web browser.
- An internet connection for loading Tailwind CSS and Google Fonts.

### Run Locally

1. Clone the repository:

   ```bash
   git clone https://github.com/Lab-404-Dev/outlaw-heist-log.git
   ```

2. Navigate to the project directory:

   ```bash
   cd outlaw-heist-log
   ```

3. Open `index.html` in your browser.

Alternatively, use Visual Studio Code with the Live Server extension.

No installation, build process, or backend configuration is required.

## 📁 Project Structure

```text
outlaw-heist-log/
│
├── index.html       # Main application
└── README.md        # Project documentation
```

The application is currently implemented as a standalone HTML document containing its own CSS and JavaScript.

## 🔐 Data & Privacy

- All task data is stored in the browser's local storage.
- No user accounts or authentication are required.
- No backend server is used.
- Data is not automatically synchronized between browsers or devices.
- Clearing browser storage may permanently remove saved objectives.

**Recommendation:** Export JSON backups periodically to preserve your progress.

## ⚠️ Disclaimer

Outlaw & Heist Log is an unofficial fan-made project developed by **Lab404-Dev**.

It is not affiliated with, endorsed by, sponsored by, or associated with Rockstar Games, Take-Two Interactive, or their subsidiaries.

All game names, characters, and related trademarks belong to their respective owners.

## 👨‍💻 Developer

**Lab404-Dev**

*Independent development. Practical tools. Clean execution.*

---

<sub>Made for outlaws, heist planners, and completionists.</sub>
