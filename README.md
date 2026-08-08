# Kurzgeschichten
Kurzgeschichten is a self-contained German dictation tool that trains your ear through active listening and writing. Upload any text with audio, sync sentences to the waveform, then type what you hear. Instant feedback, mistake analysis, XP, streaks, and smart review scheduling turn practice into measurable progress.
# Kurzgeschichten

### *German Dictation · Active Listening · Smart Review*

A self-contained, offline-first web application for practicing German listening comprehension through dictation. Upload any German text with its audio recording, sync sentences to the audio waveform, then type what you hear — with instant feedback, mistake tracking, and smart review scheduling.

---

## ✨ Why This Project Exists

Most language learning apps treat listening as a passive activity — you click "play" and follow along. **Kurzgeschichten** makes listening **active** by forcing you to reconstruct what you heard, word by word.

This approach combines:
- **Active recall** – retrieving the sentence from memory
- **Shadowing** – listening and repeating
- **Error analysis** – understanding exactly where you went wrong
- **Spaced repetition** – reviewing weak spots before you forget them

**The result:** Deeper encoding, better retention, and measurable progress.

---

## 🚀 What You Can Do

### Core Features

| Feature | Description |
|---------|-------------|
| **Upload Stories** | Paste any German text and add its matching audio (MP3, WAV, M4A) |
| **Waveform Sync** | Drag markers to align each sentence with its audio position |
| **Dictation Exercise** | Listen to one sentence at a time, then type what you heard |
| **Instant Feedback** | See every mistake highlighted with color-coded explanations |
| **Read Along Mode** | Listen and read simultaneously — no typing, just shadowing |
| **Smart Review** | Automatically schedules difficult sentences for review |
| **Live Accuracy Meter** | See your accuracy update in real-time as you type |

### Progress Tracking

| Feature | Description |
|---------|-------------|
| **Dashboard** | XP, levels, streaks, lifetime stats, and skill breakdown |
| **Writing DNA Profile** | 5-star ratings for articles, cases, word order, and more |
| **Weakness Analysis** | See your most common mistakes (articles, cases, capitalization) |
| **Difficult Words List** | Every word you've struggled with, sorted by mistakes |
| **Heat Map** | GitHub-style calendar showing your practice activity |
| **Charts** | Words/day, accuracy trends, typing speed, XP growth |
| **Personal Records** | Best accuracy, fastest typing, longest streak, and more |
| **Achievements** | Unlock milestones and track your progress |

### Gamification

| Feature | Description |
|---------|-------------|
| **XP System** | Earn XP for correct words, perfect sentences, and completing sessions |
| **Levels & Ranks** | Level up from "Anfänger" to "Sprachlegende" |
| **Streaks** | Track daily practice streaks with milestone rewards |
| **Combo System** | Consecutive perfect sentences build a combo for bonus XP |
| **Goals** | Daily, weekly, and monthly goals with progress tracking |

### Local & Private

| Feature | Description |
|---------|-------------|
| **100% Offline** | Everything runs in your browser — no server needed |
| **Local Storage** | All data stays in IndexedDB (no cloud, no accounts) |
| **Export/Import** | Backup and restore all your exercises and progress |
| **No Tracking** | Zero analytics, zero telemetry, zero external dependencies |

---

## 🎯 Who This Is For

- **German learners** who want to improve listening comprehension
- **Language teachers** looking for a dictation tool for students
- **Self-study learners** who want measurable progress tracking
- **Anyone** who prefers owning their data and working offline

---

## 🛠️ How to Use It

### Quick Start

1. **Open the app** – Just open `index.html` in your browser (Chrome, Firefox, Edge, Safari)
2. **Create an exercise** – Click "New Exercise" on the library page
3. **Paste a German text** – Any story, article, or dialogue
4. **Add audio** – Upload an MP3 file or paste a link
5. **Sync sentences** – Drag markers on the waveform to align each sentence
6. **Start practicing** – Choose "Schreiben →" (write mode) or "Lesen →" (read along)

### Modes

| Mode | What It Does | Best For |
|------|--------------|----------|
| **Write Mode** | Listen → Type → Check → Fix | Active recall, spelling, grammar |
| **Read Along** | Listen + Read → Shadow → Advance | Pronunciation, intonation, fluency |
| **Smart Review** | Auto-scheduled weak sentences | Spaced repetition, long-term retention |

### Keyboard Shortcuts

#### Exercise Mode
| Key | Action |
|-----|--------|
| `Space` | Play/Replay current sentence |
| `Enter` | Check answer or go to next |
| `←` / `→` | Previous/Next sentence |
| `Alt+A/O/U/S` | Insert ä/ö/ü/ß |

#### Read Along Mode
| Key | Action |
|-----|--------|
| `Space` | Replay current sentence |
| `Enter` | Next sentence |
| `←` / `→` | Previous/Next sentence |
| `Esc` | Return to library |

---

## 📊 Data Storage

**All data lives in your browser's IndexedDB.**

| Store | Content |
|-------|---------|
| `exercises` | Stories, sentences, audio (base64), progress, attempts |
| `profile` | XP, level, streaks, achievements, skill XP, word stats |
| `config` | XP values, level curve, ranks, achievements, goals |

**Backup:** Use the "Back up all" button to export everything as a JSON file. Restore later with "Restore."

---

## 🎨 Themes & Fonts

| Theme | Description |
|-------|-------------|
| **Light** | Clean, minimal, high contrast |
| **Dark Blue** | Easy on the eyes for night practice |
| **Black** | Maximum contrast, minimal distraction |

**20+ fonts** available in the font picker (default: Merriweather for readability).

---

## 🧠 Learning Science Behind It

| Principle | How It's Applied |
|-----------|------------------|
| **Active Recall** | You type from memory before seeing the answer |
| **Spaced Repetition** | Smart Review schedules weak sentences over time |
| **Error Correction** | Immediate feedback with specific explanations |
| **Desirable Difficulty** | Memory Difficulty modes limit replays |
| **Gamification** | XP, streaks, and combos motivate consistent practice |
| **Progress Visibility** | Dashboard shows improvement over time |

---

## 🔧 Technical Details

- **Vanilla JavaScript** – No frameworks, no build step
- **IndexedDB** – Local data persistence
- **Web Audio API** – Audio playback and waveform generation
- **SVG** – Charts and progress rings
- **CSS Variables** – Theme support (light/dark/black)
- **Google Fonts** – 20+ font options (loaded once)

### File Structure

```
index.html          # Single-file application
README.md           # This file
```

---

## 🤝 Contributing

1. Fork the repository
2. Make your changes in the single HTML file
3. Test thoroughly
4. Submit a pull request

**Guidelines:**
- Keep it self-contained (no external dependencies)
- Maintain offline-first behavior
- Respect `prefers-reduced-motion`
- Write plain JavaScript (no TypeScript, no JSX)

---

## 📝 License

MIT — Use it, modify it, share it. Attribution appreciated but not required.

---

## 🙏 Acknowledgements

- **Islem Zrelli** – Creator and maintainer
- **Google Fonts** – Beautiful typography
- **IndexedDB** – Local data persistence
- **Web Audio API** – Audio processing

---

## 📬 Contact

- **GitHub Issues** – For bugs and feature requests
- **Pull Requests** – For contributions

---

## 🌟 Star History

If you find this useful, please consider giving it a star on GitHub!

---

## ⚡ Quick Links

- **Live Demo:** [Your GitHub Pages URL]
- **Issues:** [Your GitHub Issues URL]
- **Changelog:** See commit history

---

**Made with ❤️ for German learners everywhere.**
