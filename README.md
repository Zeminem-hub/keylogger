# keylogger
# 🔐 Python Keylogger

A simple keylogger project created using the `pynput` Python library. This tool records keystrokes on the keyboard and stores them in a local `log.txt` file.

---

## 📌 Features

- Records every key pressed on the keyboard
- Handles special keys (space, enter, shift, control)
- Saves the logs to a file called `log.txt`
- Simple and minimalistic code using `pynput.keyboard.Listener`

---

## 📁 How It Works

This script uses Python’s `pynput` library to monitor and log keyboard events. Each key press is processed and saved to a file in real-time.

- `Listener` is started to capture key events
- Pressed keys are cleaned (e.g., removing quotes or handling special keys)
- Data is appended to `log.txt` continuously

---

## ⚙️ Requirements

- Python 3.x
- `pynput` library

You can install `pynput` using pip:

```bash
pip install pynput
