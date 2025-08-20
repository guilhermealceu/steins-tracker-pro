# Steins;Tracker

Steins;Tracker is a Windows desktop app that tracks your game time 100% locally and shows it in a visual, interactive dashboard. Focus on privacy, performance, and simplicity.

Free: https://github.com/guilhermealceu/steins-tracker-pro/releases

Buy (DLCs/Pro): https://pagbuypix.discloud.app/

## Main features

- Automatic game detection in the background
- Stats dashboard
  - Total time per game
  - Daily averages and period history
  - Sessions, streaks, and goals
  - Yearly heatmap and radial charts
- Per game view
  - Total time, session count, last played
  - Manual or folder based game addition
  - Friendly names and custom icons
- Log export (CSV)
- Customizable interface
  - Per page wallpapers
  - Themes, blur, opacity, and dark mode
  - Hide UI elements
- Welcome wizard with automatic language detection
- Import visuals and settings via JSON
- System monitoring
  - CPU, RAM, GPU
  - Temperatures (CPU/GPU)
  - Network speed, ping, and FPS
- Mobile access over LAN
  - QR Code to open the dashboard on the local network
  - Automatic use of the local IP
- Local only data (privacy)
- All in one installer (embedded local server and monitor; no Node.js needed)
- Automatic updates via GitHub Releases
- Pro/DLC support via token activation

## Installation

1. Download the latest .exe installer from Releases.
2. Run the installer and follow the wizard.
3. Optional: start with Windows.

Compatibility: Windows 10/11 64 bit.

## Tech

- Electron
- Node.js (bundled)
- Express, Chart.js, systeminformation, ping
- HTML5 + CSS3 + vanilla JavaScript

## Privacy

All data is stored locally in the user's Documents folder. Nothing is sent to external servers without explicit action.

Developed by Guilherme Dill (https://github.com/guilhermealceu)
Repository: https://github.com/guilhermealceu/steins-tracker-pro
