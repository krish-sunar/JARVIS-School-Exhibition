# J.A.R.V.I.S. MK-IV Interface - School Exhibition

An interactive, futuristic web application inspired by Iron Man's **J.A.R.V.I.S. AI Assistant**, specifically engineered for the School Exhibition display at DMI St. Joseph Global School.

[![Vercel Live Deployment](https://img.shields.io/badge/Vercel-Live_Deployment-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://jarvis-school-exhibition.vercel.app)
[![GitHub Repository](https://img.shields.io/badge/GitHub-Repository-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/krish-sunar/JARVIS-School-Exhibition)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)

---

## 🚀 Live Production & Repository Links
- **Live Web Application (Vercel)**: [https://jarvis-school-exhibition.vercel.app](https://jarvis-school-exhibition.vercel.app)
- **GitHub Repository**: [https://github.com/krish-sunar/JARVIS-School-Exhibition](https://github.com/krish-sunar/JARVIS-School-Exhibition)

---

## ✨ Features

- ⚛️ **Arc Reactor & Quantum Core Visualizer**: Dynamic HTML5 Canvas rendering glowing core particles, rotating HUD rings, and real-time equalizer waveforms.
- 🎙️ **Voice Recognition & Speech Synthesis**: Built with the Web Speech API (`SpeechRecognition` & `SpeechSynthesis`) for real-time voice commands and voice responses.
- 🎵 **Built-in MP3 Audio Engine**: Interactive music player HUD with playback of bundled songs (*Cupid*, *Choo Lo*, *Beat It*), featuring voice triggers, pause/resume, and on-screen audio controls.
- 🏫 **School Exhibition Profile**: Dedicated facts and history for DMI St. Joseph Global School (Established 2016, Founder Rev. Fr. Dr. J.E. Arul Raj, Principal Abraham Dennis).
- 👨‍🏫 **Teacher Profiles**: Instant voice responses for faculty members including Sir Hanif, Sir Rovi, Ma'am Khrienuo, Ma'am Komala, Sir Bisawajet, and Sir Temsu.
- 🇮🇳 **Bilingual Voice Support**: English and Hindi command recognition ("Kaise ho", "Tum kaun ho", "Hindi bolo").
- 💥 **Crazy Mode & Protocol Overloads**: High-intensity system overload animation routines with thermal breach warnings.
- 🌤️ **Live Weather & Math Engine**: Real-time meteorological satellite integration (Open-Meteo API) and inline speech math calculations.

---

## 🗣️ Supported Voice Commands

| Category | Voice Commands | Description |
| :--- | :--- | :--- |
| **Music Player** | `"Play music"`, `"Play Cupid"`, `"Play Choo Lo"`, `"Play Beat It"`, `"Pause music"`, `"Resume music"`, `"Next song"`, `"Stop music"` | Controls internal MP3 audio playback and displays HUD track info |
| **School Profile** | `"Tell me about school"`, `"Tell something about school"` | Recites key facts about DMI St. Joseph Global School |
| **Faculty Profiles** | `"Who is Sir Hanif"`, `"Who is Sir Rovi"`, `"Who is Ma'am Komala"`, `"Who is Ma'am Khrienuo"`, `"Who is Sir Bisawajet"`, `"Who is Sir Temsu"` | Displays & speaks teacher profile diagnostics |
| **Student Creators** | `"Who made you"`, `"Who is Krish"`, `"Who is Kekhrie"`, `"Who is Phillip"`, `"Who is Shekhar"`, `"Who is the laziest creator"` | Creator team credits & humor routines |
| **Hindi Commands** | `"Kaise ho"`, `"Tum kaun ho"`, `"Hindi bolo"` | Responds in fluent Hindi using native TTS voice |
| **System Protocols** | `"Go crazy"`, `"Crazy"`, `"Stop"`, `"Cancel"` | Triggers screen overload animations or halts active speech |
| **Utilities & Search** | `"What is the weather"`, `"Calculate 25 x 4"`, `"Search for [query]"`, `"Open Google"`, `"Open YouTube"` | Executes web API queries, math, or browser navigation |

---

## 🛠️ Project Structure

```text
JARVIS-School-Exhibition/
├── index.html        # Main entry point served on root production URL
├── jarvis.html       # Full JARVIS MK-IV interface and voice engine
├── beatit.mp3        # "Beat It - Michael Jackson" audio file
├── choolo.mp3        # "Choo Lo - The Local Train" audio file
├── cupid.mp3         # "Cupid - Fifty Fifty" audio file
├── vercel.json       # Vercel deployment configuration
└── README.md         # Documentation & project guide
```

---

## 💻 Local Development Setup

To run locally without any extra dependencies:

1. Clone the repository:
   ```bash
   git clone https://github.com/krish-sunar/JARVIS-School-Exhibition.git
   cd JARVIS-School-Exhibition
   ```
2. Open `index.html` or `jarvis.html` in Google Chrome or any modern Web Speech API supported browser.
3. Click the central **Arc Reactor Core** to grant microphone permissions and activate voice listening.

---

## 📄 License
This project is created for the School Exhibition display. All code is open source and available under the [MIT License](LICENSE).
