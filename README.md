# ✨ My Local Start Page

A fully self-contained, customizable browser start page that runs entirely from a local HTML file—no server required.

![screenshot](screenshot.png) <!-- Optional: Replace or remove if you don't have a screenshot -->

---

## Features

- **Add / Edit / Delete links** — Quickly manage your favorite sites.
- **Reorder by Drag-and-Drop** — Toggle "Reorder" mode, then drag tiles.
- **Custom Search Bar** — Select from multiple search engines.
- **Local Persistence** — Links and settings are saved to your browser’s `localStorage`.
- **Import / Export** — Backup or transfer your links in JSON format.
- **Offline-Friendly** — Works with no internet connection (links still require internet, of course).

---

## Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/yourusername/local-start.git
cd local-start
```

### 2. Open the file

- Double-click `start.html`, or
- Drag it into your browser, or
- Open it with `file:///` in the address bar:
  ```
  file:///path/to/start.html
  ```

---

## Setting as Your Homepage

### Firefox (Linux, macOS, Windows)

1. Go to **Settings → Home**.
2. Under **Homepage and new windows**, choose **Custom URLs…**.
3. Paste the `file:///` path to `start.html`.

> **Note:** To also replace the new tab page in Firefox, you may need an extension such as [New Tab Override](https://addons.mozilla.org/firefox/addon/new-tab-override/).

### Chrome / Chromium

1. Go to **Settings → On startup**.
2. Select **Open a specific page or set of pages**.
3. Choose `start.html` via `file:///` path.

---

## Customization

- **Default Links** — Edit the `defaults` array in the `<script>` tag of `start.html`.
- **Default Search Engines** — Edit the `engines` array in the same script.
- **Styling** — Modify the `<style>` section to change colors, fonts, and layout.
- **Icons / Badges** — The small badge on each tile is generated from the title’s initials.

---

## Import / Export

- **Export** — Click **⇩ Export** to download a `.json` file containing your links.
- **Import** — Click **⇧ Import** and choose a previously saved JSON file.
- **Reset** — Click **⟲ Reset** to restore the default links.

---

## License

This project is released under the [MIT License](LICENSE).
