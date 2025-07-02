# 📱 Screen Rotation CLI Tool (Linux)

A simple and handy bash script to **rotate your display screen** directly from the terminal using `gnome-randr.py`.

---

## 🚀 Features

- Rotate your screen to: `left`, `right`, `normal`, or `inverted`
- Lightweight and fast
- Useful for external monitor setups, portrait coding, fun screen flips, etc.
- Easy CLI usage
- Globally executable (from anywhere!)

---

## 📁 Prerequisites

- You must have the script `gnome-randr.py` (GNOME-based display manager helper)
- Linux system with GNOME (or GNOME-compatible)
- Terminal access with `sudo` privileges

---

## 🛠️ Installation

### 1. Clone or download this repo

```bash
git clone https://github.com/YOUR_USERNAME/screen-rotate-cli.git
cd screen-rotate-cli

2. Move the rotate script to /usr/local/bin
  sudo cp rotate /usr/local/bin
  sudo chmod +x /usr/local/bin/rotate

✅ Now you can use rotate command globally from anywhere in the terminal.

🧠 Usage
  rotate [orientation]

🧭 Valid Orientations
Command	Description
  right	Rotates screen to the right (portrait)
  left	Rotates screen to the left (portrait)
  normal	Resets screen to normal (landscape)
  inverted	Flips screen upside down

💡 Help Message
To view help any time:
  rotate -h

You’ll see:

Usage: rotate [orientation]

Arguments:
  right       Rotate screen to portrait (right)
  left        Rotate screen to portrait (left)
  normal      Set screen back to normal landscape
  inverted    Flip screen upside down

Options:
  -h, --help  Show this help message and exit

Example:
  rotate right      # Rotates screen to the right

🐛 Troubleshooting
Error: No orientation provided – You must pass one of the supported orientations.

Invalid orientation – Check spelling. Only these are valid: right, left, normal, inverted

Permission Denied – Try running chmod +x rotate or check /usr/local/bin permissions.

📂 File Structure

├── rotate               # Main bash script
├── README.md            # This file
🤝 Contribution
Feel free to fork, improve the script, or add support for multi-monitor setups!

📸 Demo (Optional)
Add a screenshot or GIF of you running rotate right in terminal and the screen flipping 🔄

📄 License
MIT License – do whatever you want, just don't rotate the world upside down 🌍😂

Made with 💻 + ☕ by @Sam7489

---

### 🛠 Bonus Tip: Add Fancy ASCII Logo (Optional)

If you wanna flex a bit, add an ASCII like:

```bash
echo "🌀 Screen Rotator Script 🌀"
