<div align="center">
  <h1>💎 Crimson</h1>
  <p><strong>A modern, elegant color theme for developers</strong></p>
  <p><em>Deep obsidian backgrounds • Vibrant crimson accents • Beautiful syntax highlighting</em></p>
</div>

---

## ✨ Features

- **Dark & Light variants** — Optimized for any environment
- **Semantic color consistency** — Same meaning across all apps
- **Accessibility-first** — WCAG AA compliant contrast ratios
- **Unified terminal colors** — Consistent ANSI palette

## 🎨 Preview

| Dark Theme | Light Theme |
|------------|-------------|
| Deep obsidian background (`#0e0c0d`) | Clean snow white (`#fafafa`) |
| Vibrant crimson accents (`#dc143c`) | Rich ruby accents (`#c81e38`) |
| Emerald strings, Sky functions | Jade strings, Azure functions |

## 📦 Installation

<details>
<summary><strong>Discord</strong> (BetterDiscord/Vencord)</summary>

> Structure inspired by [Catppuccin Discord](https://github.com/catppuccin/discord) theme

**BetterDiscord:**
- **Windows**: `%USERPROFILE%\AppData\Roaming\BetterDiscord\themes\`
- **macOS**: `~/Library/Application Support/BetterDiscord/themes/`
- **Linux**: `~/.config/BetterDiscord/themes/`

**Vencord:**
- **Windows**: `%USERPROFILE%\AppData\Roaming\Vencord\themes\`
- **macOS/Linux**: `~/.config/Vencord/themes/`

Then enable in Discord settings → Themes.
</details>

<details>
<summary><strong>OpenCode</strong></summary>

Copy `Themes/Opencode/crimson.json` to OpenCode's themes directory and select in settings.
</details>

<details>
<summary><strong>Spicetify</strong> (Spotify)</summary>

> Based on [SharkBlue](https://github.com/MrBiscuit921/spicetify-themes/tree/master/SharkBlue) by MrBiscuit921

**Windows:**
```powershell
mkdir "$env:APPDATA\spicetify\Themes\Crimson"
Copy-Item "Themes\Spicetify\*" "$env:APPDATA\spicetify\Themes\Crimson\"
spicetify config current_theme Crimson color_scheme Dark
spicetify apply
```

**macOS/Linux:**
```bash
mkdir -p ~/.config/spicetify/Themes/Crimson
cp Themes/Spicetify/* ~/.config/spicetify/Themes/Crimson/
spicetify config current_theme Crimson color_scheme Dark
spicetify apply
```
</details>

<details>
<summary><strong>VS Code</strong></summary>

**Option 1: Install via Extensions folder**

Copy the `Themes/VSCode/` folder to:
- **Windows**: `%USERPROFILE%\.vscode\extensions\crimson-theme`
- **macOS/Linux**: `~/.vscode/extensions/crimson-theme`

Restart VS Code and select "Crimson Dark" or "Crimson Light" from **File → Preferences → Color Theme**.

**Option 2: Install as Extension (VSIX)**

1. In VS Code, press `Ctrl+Shift+P` → "Developer: Install Extension from Location..."
2. Navigate to `Themes/VSCode/` folder
3. Select the theme from Color Theme picker
</details>

<details>
<summary><strong>Zed</strong></summary>

Copy `Themes/Zed/crimson.json` to:
- **Windows**: `%USERPROFILE%\AppData\Roaming\Zed\themes\`
- **macOS**: `~/.config/zed/themes/`
- **Linux**: `~/.config/zed/themes/`

Then select "Crimson Dark" or "Crimson Light" in Zed's theme picker.
</details>

<details>
<summary><strong>Windows Terminal</strong></summary>

1. Open Windows Terminal settings (`Ctrl+,`)
2. Click "Open JSON file" at the bottom left
3. Add the contents of `Themes/WindowsTerminal/crimson.json` to the `schemes` array
4. Set `"colorScheme": "Crimson"` in your profile
</details>

<details>
<summary><strong>Kitty</strong></summary>

Copy `Themes/Kitty/crimson.conf` to your Kitty config:
- **Windows**: `%USERPROFILE%\.config\kitty\`
- **macOS/Linux**: `~/.config/kitty/`

Add to your `kitty.conf`:
```
include crimson.conf
```
</details>

<details>
<summary><strong>Obsidian</strong></summary>

Copy the `Themes/Obsidian/` folder to:
- **Windows**: `%USERPROFILE%\.obsidian\themes\Crimson\`
- **macOS/Linux**: `~/.obsidian/themes/Crimson/`

Or within your vault: `.obsidian/themes/Crimson/`

Then enable in Settings → Appearance → Themes.
</details>

<details>
<summary><strong>Firefox</strong></summary>

1. Navigate to your Firefox profile folder (`about:support` → Profile Folder → Open Folder)
2. Create a `chrome` folder if it doesn't exist
3. Copy `Themes/Browsers/Firefox/userChrome.css` and `userContent.css` to the `chrome` folder
4. In `about:config`, set `toolkit.legacyUserProfileCustomizations.stylesheets` to `true`
5. Restart Firefox
</details>

<details>
<summary><strong>OBS Studio</strong></summary>

Copy `Themes/OBSStudio/crimson.qss` to:
- **Windows**: `%APPDATA%\obs-studio\themes\`
- **macOS**: `~/Library/Application Support/obs-studio/themes/`
- **Linux**: `~/.config/obs-studio/themes/`

Restart OBS and select "Crimson" in Settings → General → Theme.
</details>

## 📖 Documentation

See the **[Style Guide](./STYLE_GUIDE.md)** for the complete color palette, usage guidelines, and design principles.

## 🎯 Color Philosophy

Crimson follows a complementary color scheme:

| Color | Usage |
|-------|-------|
| **Red** (Crimson/Ruby) | Keywords, errors, accents |
| **Green** (Emerald/Jade) | Strings, success states |
| **Blue** (Sky/Azure) | Functions, information |
| **Gold/Amber** | Types, warnings |
| **Cyan/Teal** | Enums, special syntax |

---

<div align="center">
  <p><em>Crafted with 💎 by developers, for developers</em></p>
</div>
