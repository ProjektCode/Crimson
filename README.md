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

Copy `Themes/Discord/` contents to:
- **Windows**: `%USERPROFILE%\AppData\Roaming\BetterDiscord\themes\`
- **macOS**: `~/Library/Application Support/BetterDiscord/themes/`
- **Linux**: `~/.config/BetterDiscord/themes/`

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
<summary><strong>Zed</strong></summary>

Copy `Themes/Zed/crimson.json` to:
- **Windows**: `%USERPROFILE%\AppData\Roaming\Zed\themes\`
- **macOS**: `~/.config/zed/themes/`
- **Linux**: `~/.config/zed/themes/`

Then select "Crimson Dark" or "Crimson Light" in Zed's theme picker.
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
