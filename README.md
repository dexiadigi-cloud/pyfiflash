# PyFiFlash - Python Final Flash

Learn Python by writing real code. A single-file web app: parameterized drills,
mastery-based progression (nail each drill twice in a row), FSRS spaced review,
and locked final exams with a targeted "Hammer" rework loop for anything you miss.

- **Python Fundamentals** pack: 57 drills + 3 challenge finals (String, Array, Math)
- **Python Intermediate** pack: 71 drills + 3 capstone finals (word_freq, BankAccount, parse_records)
- **Python Advanced** pack: 67 drills + 3 capstone finals (memoize, find_errors, longest_unique)
- **Build Your Own Questions** wizard: paste up to 20 of your own test questions and get a full curriculum built backward from them
- Real Python in the browser via [Pyodide](https://pyodide.org); progress saves on-device (localStorage); no account, no server

Just open `index.html` - no build step, no dependencies to install.

## Install it as an app

PyFiFlash is one HTML file, so "installing" means putting it where your device
can open it like an app. The first launch needs internet once (it downloads the
Python engine, ~10 MB, which your browser then caches).

### Mac
- **Easiest:** double-click `index.html` - it opens in your browser. Bookmark it.
- **Dock app:** host it (see GitHub Pages below) and open the link in Safari,
  then **File > Add to Dock** (macOS Sonoma or later). In Chrome: **⋮ > Save and
  share > Install page as app**.

### Windows (PC)
- Double-click `index.html`, or open your hosted link in Chrome/Edge and use
  **⋮ > Save and share > Install page as app** (Chrome) or
  **⋯ > Apps > Install this site as an app** (Edge). It gets a Start menu entry
  and opens in its own window.

### iPhone / iPad
iOS can't open local HTML files, so this needs the hosted link (GitHub Pages
below):
1. Open the Pages URL in **Safari**
2. Tap **Share > Add to Home Screen**
3. It gets a home-screen icon and opens fullscreen like a native app

### Android
- Open the Pages URL (or the local file) in **Chrome**
- Tap **⋮ > Add to Home screen** (or **Install app**)
- It gets a home-screen icon and opens fullscreen

### Offline note
After the first load, the browser caches the Python engine, so the app mostly
works offline - but offline use isn't guaranteed (there's no service worker
yet). If the engine can't load, the app will tell you to check your connection.

## Hosting it free with GitHub Pages (for the iOS path)

1. Push this repo to GitHub
2. Go to **Settings > Pages**
3. Under "Build and deployment", pick **Deploy from a branch**, branch `main`, folder `/ (root)`
4. Wait a minute - your app is live at `https://<your-username>.github.io/<repo>/`

## Project layout

| File | What it is |
|---|---|
| `index.html` | The entire app (v7.3.2) |
| `LICENSE` | MIT License |
| `THIRD_PARTY_NOTICES.md` | ts-fsrs (MIT, vendored) and Pyodide (MPL-2.0, loaded from CDN) |

## License

MIT - see [LICENSE](LICENSE). © 2026 Jeremiah Lee.

## Brand assets

The PyFiFlash name, logo, icon, and wordmark are the exclusive property of
Jeremiah Lee and are **not** covered by the MIT License. All rights reserved -
you may not use them without permission. (They're embedded in `index.html`;
the license on the code doesn't grant you rights to the brand.)
