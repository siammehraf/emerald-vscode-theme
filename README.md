# VS Code Custom Theme & Editor Configuration

This repository contains a custom Visual Studio Code settings configuration focused on providing a dark, earthy green-themed UI with smooth editor behavior and enhanced readability.

---

## Features

- **Custom Font Family:** Uses `JetBrains Mono` as the primary font, with fallbacks to `Consolas`, `Courier New`, and monospace fonts.
- **Dark Earthy Green Backgrounds:** Custom background colors for the editor, sidebar, activity bar, status bar, and title bar that give a consistent dark, nature-inspired aesthetic.
- **Tab Styling:** Active and inactive tabs share the same dark background color, with a subtle active tab border and a hover background color to improve visual feedback.
- **Explorer Styling:** Customized sidebar titles, section headers, and list item selections to blend well with the dark green theme.
- **Editor Behavior:**
  - Word wrap enabled for better readability.
  - Smooth caret animation and cursor blinking.
  - Mouse wheel zoom enabled for quick font size adjustment.
  - Auto-format on save using Prettier, with Prettier configured as the default formatter.

---

## Fonts

The configuration uses the following fonts in order of preference:

- **JetBrains Mono** (Recommended)
- Consolas
- Courier New
- monospace (generic fallback)

### Installing JetBrains Mono

To get the full experience, it is recommended to install [JetBrains Mono](https://www.jetbrains.com/lp/mono/), a modern, open-source typeface specifically designed for coding.

---

## Color Customizations

The main colors applied:

| UI Element                  | Color     | Description                           |
| --------------------------- | --------- | ------------------------------------- |
| Editor background           | `#161A0E` | Dark earthy green for main editor     |
| Tabs (active/inactive)      | `#161A0E` | Consistent dark background            |
| Active tab border           | `#EAEFD3` | Light, contrasting border             |
| Tab hover background        | `#1F2315` | Slightly lighter green for hover      |
| Sidebar background          | `#161A0E` | Matches editor background             |
| Activity bar background     | `#161A0E` | Matches editor background             |
| Status bar background       | `#161A0E` | Matches editor background             |
| Title bar active bg         | `#161A0E` | Matches editor background             |
| Explorer title text         | `#EAEFD3` | Light text color                      |
| Explorer section header     | `#161A0E` | Matches editor background             |
| Explorer active selection   | `#2A2E16` | Slightly lighter dark green           |
| Explorer hover selection    | `#1F2315` | Slightly lighter green hover          |
| Explorer inactive selection | `#232812` | Dark green for out-of-focus selection |

---

## Editor Settings

- **Word Wrap:** Enabled (`"editor.wordWrap": "on"`)
- **Smooth Caret Animation:** Enabled (`"editor.cursorSmoothCaretAnimation": "on"`)
- **Mouse Wheel Zoom:** Enabled (`"editor.mouseWheelZoom": true`)
- **Cursor Blinking:** Smooth (`"editor.cursorBlinking": "smooth"`)
- **Format on Save:** Enabled with Prettier as the default formatter

---

## How to Use

1. Copy the contents of the `settings.json` file from this repository.
2. Open VS Code.
3. Open Settings (JSON) by pressing `Ctrl+Shift+P` (Windows/Linux) or `Cmd+Shift+P` (Mac) and searching for `Preferences: Open Settings (JSON)`.
4. Paste the configuration and save.
5. Make sure to install the [JetBrains Mono](https://www.jetbrains.com/lp/mono/) font for the intended font rendering.
6. Install the Prettier extension (`esbenp.prettier-vscode`) if you want formatting on save to work properly.

---

## License

This configuration is open for use and modification. Feel free to customize it further to suit your preferences!

---

## Contact

For questions or suggestions, open an issue or contact me directly.

---

Enjoy your cozy green-themed coding environment! 🌿
