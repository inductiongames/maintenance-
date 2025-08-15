# Site Under Maintenance – Countdown Page

A minimal, single-page web app that displays a maintenance message and a live countdown timer.  
Easily customizable via URL parameters, and ready to host for free on GitHub Pages.

---

## 🚀 Features

- **Live Countdown**  
  Counts down to a target date and time, with customizable duration.
- **Maintenance Banner**  
  Shows a friendly message and icon while your site is offline.
- **Theme Toggle**  
  Switch between dark and light themes with one click.
- **Responsive Design**  
  Works beautifully on mobile and desktop.
- **Easy Setup**  
  No build tools or dependencies—just one HTML file.

---

## 🛠 Usage

### 1. Host on GitHub Pages

1. Create a repository and add the `index.html` file.
2. Enable GitHub Pages in repository settings.
3. Your site will be live at `https://USERNAME.github.io/REPOSITORY_NAME/`.

### 2. Countdown Customization

You can set the countdown target via URL parameters:

- `timefrom`: **Start time** in [ISO 8601 format](https://en.wikipedia.org/wiki/ISO_8601), e.g. `2025-08-15T19:10:00Z`
- `duration`: **Duration** in seconds (default is 10800 seconds = 3 hours)

**Examples:**

- Default (uses hardcoded date and 3h duration):  
  ```
  https://USERNAME.github.io/REPOSITORY_NAME/
  ```

- Custom start time (3h default duration):  
  ```
  https://USERNAME.github.io/REPOSITORY_NAME/?timefrom=2025-08-15T19:10:00Z
  ```

- Custom start time and custom duration (e.g. 2 hours):  
  ```
  https://USERNAME.github.io/REPOSITORY_NAME/?timefrom=2025-08-15T19:10:00Z&duration=7200
  ```

### 3. Theme Toggle

Click the "Toggle Theme" button to switch between dark and light modes.

---

## 📁 File Structure

```
index.html    # Main single-page web app
README.md     # This help file
```

---

## 📝 Customization

- Edit the maintenance message, icon, or styles in `index.html` to suit your branding.
- The timer logic is in a `<script>` block at the bottom of the file.

---

## 💡 License

MIT License – free to use, modify, and share.

---

## 🤝 Contributions

Pull requests and suggestions welcome!
