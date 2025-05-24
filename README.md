# ✏️ vik — A Minimalist Terminal Text Editor

**vik** is a lightweight, terminal-based text editor written in C, inspired by the [kilo text editor](https://viewsourcecode.org/snaptoken/kilo/). It’s a great learning project that explores low-level terminal handling, raw input processing, and text manipulation — all without relying on external libraries.

---

## 🚀 Features

* Smooth and responsive terminal UI
* Syntax highlighting (basic, extendable)
* File open/save functionality
* Cursor movement with arrow keys
* Scrollable view for large files
* Clean exit handling (with save prompt)
* Line numbering support
* UTF-8 support (optional, depending on implementation)


## 📦 Getting Started

### Requirements

* GCC or Clang (any C99-compatible compiler)
* A POSIX-compliant terminal (Linux/macOS/WSL)

### Build

```bash
git clone https://github.com/kalminx/vik.git
cd vik
make
./vik filename.txt
```

No external dependencies. The editor compiles to a single binary.

---

## 🛠 Controls

| Key          | Action                       |
| ------------ | ---------------------------- |
| Arrow Keys   | Move cursor                  |
| Page Up/Down | Scroll                       |
| Ctrl + S     | Save file                    |
| Ctrl + Q     | Quit editor                  |
| Ctrl + F     | Search text (if implemented) |

---

## 📚 Learning Goals

This project helped me gain hands-on experience with:

* Terminal I/O in raw mode
* Escape sequences and screen rendering
* Efficient memory management in C
* File I/O and buffer handling
* State-driven input processing

It closely follows the structure of the [kilo editor tutorial](https://viewsourcecode.org/snaptoken/kilo/), with room for personal tweaks and additional features.

---

## 📁 Folder Structure

```
vik/
├── vik.c       # Main source code
├── Makefile
├── README.md
```

---

## 🧠 Credits

* Based on the awesome [kilo tutorial](https://viewsourcecode.org/snaptoken/kilo/)
* Original concept by [Salvatore Sanfilippo](https://github.com/antirez/kilo)

---

## 📜 License

MIT License. See [LICENSE](./LICENSE) for details.
