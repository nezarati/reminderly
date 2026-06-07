# ⏰ Reminderly – Smart Reminders, Notes & Pomodoro

### [🔗 Live Demo](https://nezarati.github.io/reminderly/index.html)

> A single‑file, privacy‑first productivity app combining smart reminders, flexible notes, and a Pomodoro timer. Natural language date parsing, browser notifications, tags, subnotes, drag‑and‑drop, bulk actions, and offline storage – all in a sleek dark UI. No dependencies, no sign‑up, just open the HTML and go.

![Reminderly Screenshot](https://via.placeholder.com/800x500/0b0f19/e8ecf1?text=Reminderly+Screenshot)  
*(Replace this with an actual screenshot of your app)*

---

## ✨ Features

### 🕒 Smart Reminders
- **Natural language date parsing** – Type `now`, `tomorrow`, `12 dec`, `0.5h`, `1m`, `next week`…
- **One‑time or recurring** – Daily, weekly, monthly, yearly.
- **Countdown badges** – See how much time remains.
- **Browser notifications + alarm ring** – Never miss a reminder.
- **Snooze or dismiss** via a modal.

### 📝 Flexible Notes
- **Plain notes** and **checklist‑style subnotes**.
- **Tag support** – Use `#tags` in titles for organisation.
- **Search** across titles, tags, and subnotes.

### 🍅 Pomodoro Timer
- Preset durations: **25 min**, **15 min**, **5 min break**, **45 min**.
- Automatic focus/break cycles.
- Audio notifications at session end.

### 🎛️ Bulk Actions & Multi‑select
- **Ctrl+Click** to select multiple items.
- Bulk mark done/undone, or delete.
- Drag‑and‑drop to **reorder** or turn items into **subtasks**.

### 📱 Responsive & Touch‑Friendly
- Works on mobile, tablet, and desktop.
- Action buttons (✔ ✎ ✕) appear on hover (desktop) and are always visible on touch screens.

### 💾 Data Ownership
- All data lives in your browser’s **localStorage**.
- **Export** as JSON → full backup.
- **Import** any backup to restore or migrate.
- No servers, no accounts, no tracking.

---

## 🚀 How to Use

1. **Open the app** – just open `index.html` in any modern browser.
2. **Enable notifications** (optional) – the app will ask; grant for pop‑up alerts and sound.
3. **Add a reminder** – switch to ⏰ tab, type a title and a date (e.g. `tomorrow 3pm`), then click **+ Set Reminder**.
4. **Add a note** – switch to 📝 tab, write your note, add subnotes if needed.
5. **Start a Pomodoro** – switch to 🍅 tab, pick a preset and press ▶ Start.
6. **Manage items** – double‑click to toggle done, use ✎ to edit inline, ✕ to delete.
7. **Organise** – drag the `⋮⋮` handle to reorder, drop onto another item to make it a subtask.
8. **Search & filter** – use the search bar or click any `#tag`.

---

## ⌨️ Keyboard Shortcuts

| Shortcut | Action |
|----------|--------|
| `Ctrl+Click` | Multi‑select |
| `Double‑click` on item | Toggle done / undone |
| `↑` | Move selected item **up** |
| `↓` | Move selected item **down** |
| `→` | Indent (make subtask of above item) |
| `←` | Outdent (move to top level) |
| `Delete` / `Backspace` | Delete selected item (with confirmation) |
| `s` (without Ctrl) | Toggle star / priority |
| `Escape` | Deselect / cancel editing |

---

## 💾 Data Management

- **Export** – Click 📥 to download a JSON backup.
- **Import** – Click 📤 and select a previously exported file.  
  ⚠️ Importing **replaces** all current data. A confirmation dialog will appear.
- **Storage** – Data is stored in `localStorage`. To avoid data loss, **export regularly**.

---

## 🔧 Customisation (for developers)

The entire app is a single HTML file with embedded CSS and JS.  
You can tweak:

- **Colours** – edit the CSS variables under `:root` in the `<style>` block.
- **Pomodoro presets** – change the preset array in the JavaScript.
- **Sound** – modify the `playRingOnce()` function.
- **Date parsing** – extend the `parseNaturalDate()` function.

No external dependencies – just vanilla HTML, CSS, and JavaScript.

---

## 🌐 Browser Support

- Chrome / Edge (v90+)
- Firefox (v90+)
- Safari (v14+)
- Opera

**Notifications** may require HTTPS or `localhost`. If you open the file directly (`file://`), notifications might not work in some browsers – use a local server for full support.

---

## 📄 License

This project is licensed under the **MIT License**.

MIT License

Copyright (c) 2025 Ali & Mahdi

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

text

---

## 🙏 Acknowledgements

- Inspired by countless productivity apps.
- Built with ❤️ using plain web technologies.
- No trackers, no ads, no nonsense.

---

## 🐞 Issues & Support

Found a bug or have a feature request?  
👉 **[Open an issue on GitHub](https://github.com/nezarati/reminderly/issues)**
