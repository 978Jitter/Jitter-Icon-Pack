🎨 Design Language
High-Contrast Monochrome: Crisp silver-white (#CFCFD3 / #FFFFFF) line-art and geometric glyphs built for dark desktop surfaces (#0D090A / #181012) without visual clutter.

Technical & Utility Motifs: Pulse-waveform icons for removable media and hardware utilities, hexagonal badges, terminal glyphs, clean angular folders, and dedicated icons for network captures, keys, databases, and text lists.

📦 Coverage
Places & File Manager (Thunar): Custom folder glyphs for Home, Desktop, Recent, Trash, Documents, Music, Pictures, Videos, Downloads, File System, and Browse Network.

XFCE Settings & System Tools: Uniform geometric icons across Appearance, Panel, Window Manager, Display, Bluetooth, Power Manager, Keyboard, and Session & Startup.

Panel, System Tray & Mimetype Symbolics: Crisp launcher icons, monochrome tray status indicators (volume, battery levels, Wi-Fi, Bluetooth, cellular, power), and scalable -symbolic.svg mimetype icons for code, capture files, keys, and databases.

⚙️ Installation
Create your local icons directory if it does not exist:

Bash
mkdir -p ~/.local/share/icons
Copy the JITTER theme folder into your local icons directory and refresh the icon cache:

Bash
cp -r JITTER ~/.local/share/icons/
gtk-update-icon-cache -f -t ~/.local/share/icons/JITTER
