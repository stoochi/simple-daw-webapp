# Minimal Drum Step Sequencer

A modern, browser-based drum step sequencer for quick rhythm creation, education, and experimentation. Features a clean, icon-based UI, pattern save/load, MIDI/WAV export, custom samples, themes (including a special "BIRTHDAY" mode), and more—all in a single HTML file.

---

## Features

- **Step Sequencer Grid:** Click to toggle drum hits for up to 8 drum rows.
- **Add/Remove Drum Rows:** Add custom rows (up to 8) and remove any beyond the original 4.
- **Custom Samples:** Drag and drop your own audio files onto drum labels.
- **Mute/Solo/Audition:** Per-row mute, solo, and audition buttons.
- **Pattern Save/Load:** Save/load patterns as JSON.
- **Export:** Export your beat as WAV or MIDI.
- **Pattern Copy/Paste:** Right-click the grid to copy/paste patterns.
- **Themes:** Multiple color themes, including video backgrounds and a festive "BIRTHDAY" mode with animated GIFs.
- **Responsive UI:** Works on desktop and mobile browsers.

---

## How to Run

**You must run this app from a local server to ensure all features (especially video/audio backgrounds) work correctly.**

### Quick Start (Recommended)

1. **Download or clone this repository.**
2. Open a terminal/command prompt in the project folder.
3. Run a simple Python HTTP server:

   **For Python 3:**
   ```
   python -m http.server 8000
   ```

   **For Python 2:**
   ```
   python -m SimpleHTTPServer 8000
   ```

4. Open your browser and go to:  
   [http://localhost:8000](http://localhost:8000)

---

## File Structure

- `index.html` — Main application file.
- `samples/` — Default drum samples (kick, snare, hat, clap).
- `cartibirthday.mp4` — Birthday theme video background.
- `cakespin.gif` — Birthday theme animated GIF.
- *(Add any other custom samples or assets as needed)*

---

## Usage Tips

- Click the **help icon** (<span class="material-symbols-rounded" style="font-size:1em;vertical-align:middle;">help</span>) in the top right for a full guide.
- Try the **BIRTHDAY** theme for a fun surprise!
- Save your patterns before closing or reloading the page to avoid losing your work.

---

## Credits

Created by [Your Name].  
Uses [Google Material Symbols](https://fonts.google.com/icons) for icons.

---

## License

MIT License (or your preferred license).


Feel free to fork the repository and submit pull requests for any improvements or features you would like to add.

## License

This project is open-source and available under the MIT License.
