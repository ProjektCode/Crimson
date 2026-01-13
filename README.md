<div align="center">
  <h1>💎 Crimson</h1>
  <p><strong>A modern, elegant color theme for developers</strong></p>
  <p><em>Deep obsidian backgrounds • Vibrant crimson accents • Beautiful syntax highlighting</em></p>
</div>

---

## What this repo contains

Crimson is a theme pack for multiple apps. You install it by copying the correct file(s) from this repo’s `Themes/` folder into the app’s theme/config folder.

If you’ve never installed a theme before, start with **Quick Start** below.

## Quick Start (for first-time installers)

1. **Download this repo**
   - On GitHub: click **Code** → **Download ZIP**
   - Or if you already use git: clone the repo
2. **Unzip / extract** the downloaded ZIP
3. Open the extracted folder and find `Themes/`
4. Pick your app below and follow its steps

## Which files do I copy?

- Discord (BetterDiscord/Vencord): `Themes/Discord/crimson.theme.css`
- VS Code / Cursor / other VS Code-based editors: `Themes/VSCode/crimson-theme-1.0.0.vsix`
- Zed: `Themes/Zed/crimson.json`
- Windows Terminal: `Themes/WindowsTerminal/crimson.json`
- Kitty: `Themes/Kitty/crimson.conf`
- Obsidian: copy the folder `Themes/Obsidian/` (contains `manifest.json` + `theme.css`)
- Firefox: `Themes/Browsers/Firefox/userChrome.css` + `Themes/Browsers/Firefox/userContent.css`
- OBS Studio: `Themes/OBSStudio/crimson.obt` + `Themes/OBSStudio/crimson_*.ovt`
- Spicetify (Spotify): `Themes/Spicetify/color.ini` + `Themes/Spicetify/user.css` (requires Spicetify)
- OpenCode: `Themes/Opencode/crimson.json`

---

## Installation

<details>
<summary><strong>Discord</strong> (BetterDiscord / Vencord)</summary>

### What you need
- Discord with **BetterDiscord** or **Vencord** already installed.

### File to copy
- `Themes/Discord/crimson.theme.css`

### Install (recommended: no guessing paths)
1. Open Discord → **User Settings** (gear icon)
2. Scroll to your mod section (**BetterDiscord** or **Vencord**)
3. Open **Themes**
4. Click **Open Themes Folder**
5. Copy `crimson.theme.css` into that folder
6. Go back to Discord and toggle the theme ON

### Install (manual folder paths)
**BetterDiscord:**
- **Windows**: `%USERPROFILE%\\AppData\\Roaming\\BetterDiscord\\themes\\`
- **macOS**: `~/Library/Application Support/BetterDiscord/themes/`
- **Linux**: `~/.config/BetterDiscord/themes/`

**Vencord:**
- **Windows**: `%USERPROFILE%\\AppData\\Roaming\\Vencord\\themes\\`
- **macOS/Linux**: `~/.config/Vencord/themes/`

### If it doesn’t show up
- Make sure the file ends with `.theme.css`
- Refresh Discord: `Ctrl+R` (Windows/Linux) or `Cmd+R` (macOS)

</details>

<details>
<summary><strong>VS Code</strong> (and VS Code-based editors like Cursor, Windsurf, etc.)</summary>

### File to install
- `Themes/VSCode/crimson-theme-1.0.0.vsix`

### Install (recommended: no terminal)
1. Open your editor
2. Open the Command Palette:
   - Windows/Linux: `Ctrl+Shift+P`
   - macOS: `Cmd+Shift+P`
3. Run: **Extensions: Install from VSIX...**
4. Select: `Themes/VSCode/crimson-theme-1.0.0.vsix`
5. Restart the editor
6. Open the theme picker and choose **Crimson Dark** or **Crimson Light**

### Install via CLI (optional)
- VS Code: `code --install-extension Themes/VSCode/crimson-theme-1.0.0.vsix --force`

</details>

<details>
<summary><strong>Zed</strong></summary>

### File to copy
- `Themes/Zed/crimson.json`

### Install
1. Copy `crimson.json` into Zed’s themes folder:
   - **Windows**: `%USERPROFILE%\\AppData\\Roaming\\Zed\\themes\\`
   - **macOS**: `~/.config/zed/themes/`
   - **Linux**: `~/.config/zed/themes/`
2. Open Zed and select **Crimson Dark** or **Crimson Light** in the theme picker

</details>

<details>
<summary><strong>Windows Terminal</strong></summary>

### File to copy
- `Themes/WindowsTerminal/crimson.json`

### Install
1. Open Windows Terminal settings (`Ctrl+,`)
2. Click **Open JSON file**
3. Find the `"schemes"` array and add the contents of `Themes/WindowsTerminal/crimson.json`
4. In your profile, set `"colorScheme": "Crimson"`

</details>

<details>
<summary><strong>Kitty</strong></summary>

### File to copy
- `Themes/Kitty/crimson.conf`

### Install
1. Copy `crimson.conf` into your Kitty config folder:
   - **Windows**: `%USERPROFILE%\\.config\\kitty\\`
   - **macOS/Linux**: `~/.config/kitty/`
2. Edit your `kitty.conf` and add:
   ```
   include crimson.conf
   ```
3. Restart Kitty

</details>

<details>
<summary><strong>Obsidian</strong></summary>

### Folder to copy
- Copy the folder `Themes/Obsidian/`.

### Install (recommended: inside your vault)
1. Open your vault folder (where your notes live)
2. Find (or create) this folder: `.obsidian/themes/Crimson/`
3. Copy these files from `Themes/Obsidian/` into that `Crimson` folder:
   - `manifest.json`
   - `theme.css`
4. In Obsidian: **Settings** → **Appearance** → **Themes** → select **Crimson**

### If you can’t see `.obsidian`
- Enable “Show hidden files” in your file explorer

</details>

<details>
<summary><strong>Firefox</strong></summary>

### Files to copy
- `Themes/Browsers/Firefox/userChrome.css`
- `Themes/Browsers/Firefox/userContent.css`

### Install
1. In Firefox, open `about:support`
2. Find **Profile Folder** → click **Open Folder**
3. Create a folder named `chrome` (if it doesn’t exist)
4. Copy `userChrome.css` and `userContent.css` into the `chrome` folder
5. In `about:config`, set `toolkit.legacyUserProfileCustomizations.stylesheets` to `true`
6. Restart Firefox

</details>

<details>
<summary><strong>OBS Studio</strong></summary>

### Files to copy
- `Themes/OBSStudio/crimson.obt`
- `Themes/OBSStudio/crimson_Default.ovt`
- `Themes/OBSStudio/crimson_Dark.ovt`
- `Themes/OBSStudio/crimson_Light.ovt`

### Install
1. Copy those files into the OBS themes folder:
   - **Windows**: `%APPDATA%\\obs-studio\\themes\\`
   - **macOS**: `~/Library/Application Support/obs-studio/themes/`
   - **Linux**: `~/.config/obs-studio/themes/`
2. Restart OBS
3. In OBS: **Settings** → **Appearance** → **Theme**: select **Crimson**
4. Choose **Default / Dark / Light** under **Style**

</details>

<details>
<summary><strong>Spicetify</strong> (Spotify)</summary>

### Important
Spicetify is a separate tool. Installing Crimson for Spotify requires **Spicetify to already be installed and working**, and you will run a few commands.

### Files to copy
- `Themes/Spicetify/color.ini`
- `Themes/Spicetify/user.css`

### Install (Windows)
Run these in PowerShell:
```powershell
mkdir "$env:APPDATA\\spicetify\\Themes\\Crimson"
Copy-Item "Themes\\Spicetify\\*" "$env:APPDATA\\spicetify\\Themes\\Crimson\\"
spicetify config current_theme Crimson color_scheme Dark
spicetify apply
```

### Install (macOS/Linux)
```bash
mkdir -p ~/.config/spicetify/Themes/Crimson
cp Themes/Spicetify/* ~/.config/spicetify/Themes/Crimson/
spicetify config current_theme Crimson color_scheme Dark
spicetify apply
```

</details>

<details>
<summary><strong>OpenCode</strong></summary>

### File to copy
- `Themes/Opencode/crimson.json`

### Themes folder
- **Windows**: `%USERPROFILE%\\.config\\opencode\\themes\\`
- **macOS/Linux**: `~/.config/opencode/themes/`

### Install
1. Create the themes folder if it doesn’t exist
2. Copy `crimson.json` into the themes folder
3. In OpenCode:
   - Run `/theme` and pick **crimson**
   - Or set `"theme": "crimson"` in `~/.config/opencode/opencode.json`

</details>

---

## Troubleshooting (common beginner issues)

- **I can’t find AppData / .config / .obsidian**: those folders can be hidden by default. Enable “Show hidden files” in your file explorer.
- **What is `%USERPROFILE%` / `%APPDATA%`?**: on Windows, these are shortcuts to your user folders. You can paste them directly into File Explorer’s address bar.
- **I copied the file but nothing changed**: make sure you also enabled/selected the theme inside the app (most apps don’t auto-enable).

## Documentation

See `STYLE_GUIDE.md` for the full color palette and usage guidelines.
