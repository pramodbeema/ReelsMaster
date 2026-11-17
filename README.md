# Reels Master (v2.0)

**The all-in-one desktop extension for YouTube Shorts, Instagram Reels, and Facebook Reels. Control video playback with essential shortcuts: spacebar play/pause, hands-free auto-scroll, interactive Instagram timeline scrubber, playback speed controls, customizable seeking, audio navigation, captions, and video conversion.**

Created by **Pramod Beema**

---

## 🎯 Universal Features

### 1. ⏯️ Space Bar Play/Pause (All 3 Platforms)
Press **Space** (or **'k'**) to pause and play YouTube Shorts, Instagram Reels, and Facebook Reels just like standard desktop video players. Safely suppresses unwanted browser page scrolling and blocks accidental button clicks.

### 2. 🔁 Hands-Free Auto-Scroll (All 3 Platforms)
- **Instagram & Facebook**: A clean on-screen **Auto** button is positioned on the **left side of the video being played**. When the current Reel finishes, it automatically advances to the next Reel without requiring any mouse clicks.
- **YouTube Shorts**: Auto button integrated natively in the action sidebar above Convert.
- Includes smart video loop detection for Meta's repeating video playback engine.

### 3. ⏱️ Interactive Instagram Timeline Scrubber (Native Single Bottom Line)
Hover your mouse over any Instagram Reel to reveal an interactive single-line seek bar right at the bottom edge of the player (matching YouTube & Facebook native designs). Features a live played gradient fill, draggable white circle handle, and floating time preview (`0:14 / 0:48`). Click or drag anywhere along the line to scrub smoothly with your mouse — especially useful when viewing Reels while logged out!

### 4. ⚡ Playback Speed Controls (All 3 Platforms)
Adjust playback speed using **>** (speed up) and **<** (slow down) (or Shift + . / ,) from 0.25x up to 2.0x with centered on-screen HUD speed feedback.

### 5. ⏩ Customizable Seeker (All 3 Platforms)
Use **arrow keys** (← →) to seek with visual feedback. Set your desired seek duration in seconds directly in the extension popup (slider from 1s to 30s, or 2s, 5s, 10s, 15s quick chips).

### 6. ⏮️ Restart from Beginning (All 3 Platforms)
Press **'0'** to restart the current video from the beginning (`0:00`).

### 7. 🔇 Volume & Mute Controls (All 3 Platforms)
Press **'m'** to quickly toggle audio mute/unmute, and use **Shift + ↑ / ↓** to adjust volume smoothly with on-screen percentage feedback.

### 8. 🎧 Audio Track Navigator (YouTube)
Press **'a'** to open the audio track selection menu with full keyboard navigation (↑/↓ + Enter, number keys 1–9, or press 'a' again to cycle).

### 9. 💬 Caption Toggle (YouTube & Reels)
Press **'c'** to toggle closed captions and subtitles.

### 10. 🔄 Video Converter (YouTube Shorts & Reels)
Convert YouTube Shorts to regular video format with the on-screen Convert button or the **Ctrl+Shift+F** (Mac: **Cmd+Shift+F**) keyboard shortcut.

---

## ⌨️ Universal Keyboard Shortcuts Reference

| Shortcut | Action | Supported Platforms |
|----------|--------|---------------------|
| **Space** / **k** | Play / Pause video (no page scroll) | YouTube, Instagram, Facebook |
| **&gt;** / **&lt;** (Shift + . / ,) | Speed Up / Slow Down playback (0.25x – 2.0x) | YouTube, Instagram, Facebook |
| **← →** | Seek video (custom seconds from popup) | YouTube, Instagram, Facebook |
| **Mouse Hover & Drag** | Interactive timeline scrubber bar | Instagram Reels |
| **0** | Restart video from beginning (`0:00`) | YouTube, Instagram, Facebook |
| **m** | Mute / Unmute active audio | YouTube, Instagram, Facebook |
| **Shift + ↑ ↓** | Increase / Decrease volume | YouTube, Instagram, Facebook |
| **c** | Toggle Captions / Subtitles | YouTube, Instagram, Facebook |
| **a** | Open audio track menu / cycle tracks | YouTube Shorts |
| **Ctrl+Shift+F** | Convert to standard video format | YouTube, Instagram, Facebook |

---

## 📥 Installation

### Chrome Web Store
*(Update coming soon to the Chrome Web Store)*

### Manual Installation (Developer Mode):
1. Download or clone this repository
2. Open Chrome/Edge/Brave/Opera and navigate to `chrome://extensions/`
3. Enable **Developer mode** in the top-right corner
4. Click **Load unpacked**
5. Select this folder (`fixytshorts-v1.7.1-full-project`)
6. Done! 🎉 Enjoy full control across YouTube Shorts, Instagram Reels, and Facebook Reels.

---

## 🆕 What's New in v2.0
- **Reels Master Tri-Platform Support**: Unified control for **YouTube Shorts**, **Instagram Reels**, and **Facebook Reels** in a single powerful extension.
- **Instagram Timeline Scrubber**: Interactive progress bar appears on hover over Instagram Reels, allowing mouse seeking even without signing in.
- **Left-Side Auto-Scroll Button**: Pixel-perfect, native-styled Auto-Scroll button positioned on the left side of active Reels on Instagram and Facebook.
- **No Duplicate Buttons**: Clean single-button architecture eliminating multiple injections on Facebook.
- **Tri-Brand Icon Design**: Brand new high-res master icon embodying YouTube Red, Instagram Sunset Gradient, and Facebook Royal Blue.

---

## 🔧 Technical Details

- **Manifest Version**: 3
- **Permissions**: `activeTab`, `storage`
- **Host Permissions**:
  - `https://www.youtube.com/*`
  - `*://*.instagram.com/*`
  - `*://*.facebook.com/*`
- **Zero Remote Code**: 100% compliant with Chrome Web Store security and privacy standards.

## 👤 Author

**Pramod Beema**  
- GitHub: [https://github.com/pramodbeema](https://github.com/pramodbeema)
- Email: bp.beema@gmail.com
