# // JITTERTECH ICONS (`JITTER`)

A custom monochrome and silver-white vector icon pack engineered to pair seamlessly with the matte-black and crimson (`#E11D2E`) **Jitter-Shadow** desktop theme on Linux XFCE and portable ARM64 cyberdecks.

### 🎨 Design Language
* **High-Contrast Monochrome:** Crisp silver-white (`#CFCFD3` / `#FFFFFF`) line-art and geometric glyphs designed to pop against `#0D090A` and `#181012` dark surfaces without visual clutter.
* **Cyberdeck, RF & Security Motifs:** Custom pulse-waveform icons for removable drives and hardware tools, hexagonal badges, terminal glyphs, clean angular folders, and dedicated `.pcap`, `.pem`, `.sqlite3`, and wordlist icons.

### 📦 Coverage
* **Places & File Manager (Thunar):** Custom folder glyphs for `Home`, `Desktop`, `Recent`, `Trash`, `Documents`, `Music`, `Pictures`, `Videos`, `Downloads`, `Wordlists`, `File System`, and `Browse Network`[cite: 9, 10].
* **XFCE Settings & System Tools:** Uniform geometric icons across `Appearance`, `Panel`, `Window Manager`, `Display`, `Bluetooth`, `Power Manager`, `Keyboard`, and `Session & Startup`[cite: 10].
* **Panel, System Tray & Mimetype Symbolics:** Crisp dock launcher icons, monochrome tray status indicators (volume, battery levels, Wi-Fi/BT/cellular, power), and scalable `-symbolic.svg` mimetypes for code, packet captures, keys, and databases[cite: 9].

### ⚙️ Installation
1. Copy `JITTER` into your local icons directory:
   ```bash
   mkdir -p ~/.local/share/icons
   cp -r JITTER ~/.local/share/icons/
   gtk-update-icon-cache -f -t ~/.local/share/icons/JITTER
