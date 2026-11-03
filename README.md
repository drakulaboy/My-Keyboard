<div align="center">

# ⌨️ My Keyboard

**A fully customizable Android keyboard. Build your own layout, look and gestures.**

![Android](https://img.shields.io/badge/Android-7.0%2B-3DDC84?logo=android&logoColor=white)
![Java](https://img.shields.io/badge/Java-pure%20Android%20SDK-orange)
![License](https://img.shields.io/badge/license-GPL--3.0-blue)
![Version](https://img.shields.io/badge/version-1.9.9.65-purple)

*No external libraries · Works offline · Languages: English, Русский, Română*

</div>

---

## ✨ Why My Keyboard?

Most keyboards let you pick a theme. **My Keyboard lets you design the keyboard itself.** You can change every key, layer,
row, colour, gesture and panel in a visual editor, and you see the result live on the keyboard. It brings together ideas
from HeliBoard, LeanType, Unexpected Keyboard, Multiling O, Jbak2, Typewise and SwiftKey.

---

## 📑 Contents

- [Layouts & visual editor](#-layouts--visual-editor)
- [Languages & dictionaries](#-languages--dictionaries)
- [Typing & correction](#-typing--correction)
- [Gestures](#-gestures)
- [Clipboard, templates & macros](#-clipboard-templates--macros)
- [Look & themes](#-look--themes)
- [Plugins (offline AI, voice, sounds)](#-plugins)
- [Privacy](#-privacy)
- [Credits & licences](#-credits--licences)

---

## 🧩 Layouts & visual editor

| Feature | What it does |
|---|---|
| **Visual layout editor** | Drag keys with your finger, resize them with a handle, add or remove rows and layers. Undo/redo for everything, plus a test field to try the layout. |
| **Any key, any action** | Characters, text, `{actions}` (copy, paste, select, cursor, undo, translate…), app launchers, pictures (PNG/SVG) and glyphs from any font. |
| **Long press & double tap** | Extra characters on every key, shown small in its corners. |
| **Corner symbols** | Up to 8 symbols or actions around a letter, typed with a short swipe (as in Unexpected Keyboard). |
| **Layers** | Letters, digits, symbols, numpad, a text editor layer (arrows, copy, paste), emoji layers, and layers that return after one key. |
| **Panels** | Rows that stay above the keys, such as a digits row or a toolbar of your own. They can scroll and use fixed widths in dp. |
| **Key shapes** | Normal, rounded and 3D keys, plus the Typewise-style **honeycomb** (hex) layout. |
| **T9 & T+** | A phone keypad per language, and a "two letters per key" layout, both with dictionary prediction. |
| **Split & floating** | A split keyboard for two thumbs, or a floating keyboard you can drag, resize and make see-through. |
| **Import** | HeliBoard / LeanType layouts and backups, Jbak2 layouts and skins, Gboard dictionaries, JSON layers. |
| **Templates** | Ready-made layouts, including Multiling-O-style symbols on letters. |

---

## 🌐 Languages & dictionaries

- **Many languages** with ready layouts (80+ HeliBoard layouts: QWERTY, ЙЦУКЕН, AZERTY, Greek, Hebrew, Hindi…).
- **Languages screen**: turn languages on and off, reorder them, and download a dictionary with one tap.
- **Switching languages**: 🌐 key, swipe along the space bar, or swipe up/down from the space bar.
- **🪭 Language fan (Multiling O style)**: swipe up from the space bar, slide to a language (inner ring) or a layer
  (outer ring) and let go. One gesture.
- **Space bar** shows the previous and next language, with optional round flags.
- **Per-app language**: each app can remember its own language.
- **Dictionaries**: built-in word lists enriched with FrequencyWords, HeliBoard `.dict` import, Multiling plugin
  dictionaries, and your own add-on lists.
- **Personal dictionary** keeps your spelling (`LeanType`, `iPhone`, `NASA`) and learns phrases.
- **Hide rude words** from suggestions, with an editable list per language.
- Old Church Slavonic, Church Slavonic and Glagolitic support with a built-in font.

---

## ✍️ Typing & correction

- **Suggestion strip** with next-word prediction. It can scroll, pin buttons, or hide itself.
- **Autocorrection** that knows your keyboard: a typo-aware model checks which keys are next to each other.
  ⌫ right after a correction undoes it.
- **Swipe typing** with its own engine (DTW path matching), or an optional external gesture library for more accuracy.
- **Fast two-thumb typing (rollover)**, plus chords such as `Space + letter` or `Ctrl + key`.
- **Shortcuts** that expand into text, with variables: `%date%`, `%clipboard%`, `%selection%`, `%cursor%`.
- **Auto-capitalisation, double-space period**, and cycling marks (`. ? ! ,`) with repeated spaces.
- **Per-character undo**, text wrapping in pairs (`()`, `""`, `**`), and growing selection (word → line → all).
- **Calculator & math layers**: fractions, math symbols and a built-in calculator.
- Type any character by its **Unicode code** (`U+0301`).

---

## 👆 Gestures

| Gesture | Default / options |
|---|---|
| Swipe along **space** | Switch language, move the cursor, or move by words |
| Quick **flick** on space | Its own action, separate from a swipe |
| Swipe **up / down** from space | Any action, a layer, or the **language fan** |
| Hold **space** | Touchpad mode (move the cursor like a laptop touchpad) |
| Swipe left from **⌫** | Delete whole words; then up to delete whole lines |
| Swipe **up** on a letter | Capital letter |
| Long swipes across the board | Your choice of actions (when swipe typing is off) |
| Slide from **?123** | Type one symbol and come back to the letters |
| Corner **joystick** | Arrow keys that move further the further you push |

⚠️ **Settings conflict checker**: when two settings get in each other's way, the keyboard tells you and offers one-tap fixes.

---

## 📋 Clipboard, templates & macros

- **Clipboard history** with pinning, coloured folders, numbering, editing, images (screenshots) and very long texts
  (up to 5,000,000 characters).
- **🔍 Search in the clipboard**: type on the keys and the matches appear in the strip.
- **Swipe gestures** on records (delete, pin, move, edit), with undo.
- **Templates panel** (as in Jbak2) with folders and ⚡ hot letters.
- **Macros**: `%key:selectall%%key:copy%`, `%ctrl:s%`, `%wait:300%`…
- **🎨 Visual panel editor**: give the clipboard and template panels their own colours, fonts, sizes, frames, columns,
  equal-height records and button positions. Tap a part of the live preview to edit it.
- **OTP codes** from SMS/notifications show up as a chip in the strip (optional).

---

## 🎨 Look & themes

- Light / dark / **day-night automatic** themes, with separate colours for day and night.
- **Theme manager** with previews and imports: **SwiftKey** themes, HeliBoard colours, Jbak2 skins.
- **Glass look**: blur, see-through keys and wallpaper backgrounds.
- Your own **fonts**, key icons, accent colours, press colours and popup styles.
- Key preview bubbles, the chosen symbol shown above the finger, and haptic and **sound packs** (import `.zip` packs:
  Mechvibes, kbsim, LeanType…).
- Landscape height, compact settings UI, and a RAM indicator.

---

## 🔌 Plugins

| Plugin | Notes |
|---|---|
| ✨ **Offline AI** | Fix errors and translate selected text with a local `.gguf` model (Qwen2.5 0.5B/1.5B) through the LeanType Offline AI plugin (llama.cpp). Runs in its own process. |
| 🎤 **Offline voice input** | LeanType Voice Plugin (Whisper) or the Parakeet v3 mod, which is faster and recognises 25 languages. |
| 〰️ **Swipe library** | An optional native gesture library for more accurate swipe typing. |
| 😀 **Emoji font** | Use any emoji font instead of the phone's own. |
| 🔊 **Key sounds** | Import sound packs. Each key can have its own sound. |
| 🔎 **Plugin finder** | Scans Download (or a chosen folder), tells what each APK or model is for and whether it fits your phone, and installs it. |

Also included: Google voice typing, Google Translate, and a storage and cache manager.

---

## 🔒 Privacy

- **Works offline.** Internet is used only when *you* download a dictionary or open a link.
- **Incognito mode**: switches on by itself in private fields, or by hand. Nothing is learned and nothing goes to the clipboard history.
- No ads and no analytics.
- Every special permission (microphone, files, notifications, installing plugins) is asked for only when you turn
  on the feature that needs it.
- **Full backup and restore** of all settings, layouts and dictionaries.

---

### Enabling the keyboard
1. Open **My Keyboard**.
2. Step 1: enable it in the system keyboard settings.
3. Step 2: choose it as the input method.
4. Step 3: open the layout editor and make it yours.

The full help is inside the app, in English, Russian and Romanian.

---

## 🙏 Credits & licences

- **Unexpected Keyboard**: layouts with corner symbols (GPL-3.0)
- **HeliBoard / LeanType**: layouts, colours and the plugin interfaces
- **FrequencyWords** (OpenSubtitles 2018): word frequencies (CC-BY-SA 4.0)
- **FreeSerif** (GNU FreeFont): Church Slavonic and Glagolitic font
- Ideas from **Multiling O**, **Jbak2**, **Typewise**, **SwiftKey** and **ChordBoard**

My Keyboard is released under the **GNU General Public License v3.0**. See [`LICENSE`](LICENSE).

<div align="center">

Made with ❤️ by **andreykamd** ·

</div>

