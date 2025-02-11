# **PROJECT TITLE :**

### **SIMPLE KEYLOGGER**
---
## **DESCRIPTION :**

A Python-based keylogger that records and logs keystrokes to a file. This project is designed for educational purposes to demonstrate how keyboard input can be captured programmatically. It uses the pynput library to monitor keystrokes and saves the logged data to a text file.

**Disclaimer :** This tool is for educational and ethical use only. Always ensure you have explicit permission before using it on any system. Unauthorized use of keyloggers is illegal and unethical.

---

## **Features :**

- **Keystroke Logging**: Captures and logs all keystrokes pressed by the user.
- **File Output**: Saves the logged keystrokes to a text file (`keylog.txt`).
- **Special Key Handling**: Logs special keys (e.g., `Shift`, `Ctrl`, `Esc`) in a readable format.
- **Easy to Use**: Simple command-line interface with clear instructions.

---

## **How It Works :**

The keylogger uses the `pynput` library to monitor keyboard events. When a key is pressed:
1. The key is logged to a file.
2. Special keys (e.g., `Shift`, `Ctrl`) are handled and logged in a descriptive format.
3. The keylogger stops when the `Esc` key is pressed.

---

## **Installation :**

**Install Dependencies :**
   - Install the `pynput` library:
     ```bash
     pip install pynput
     ```

---

## **Usage :**

1. Run the script:
   ```
   PRODIGY_CS_04.py
   ```
2. Start typing. All keystrokes will be logged to `keylog.txt`.
3. Press the `Esc` key to stop the keylogger.

---

## **Example Output:**

The logged keystrokes will be saved in `keylog.txt`. 

For example:
```
Hello[Key.shift]![Key.space]I[Key.space]am[Key.space]Sahil.
```

---

## Ethical Considerations

- **Permission**: Always obtain explicit permission before using this tool on any system.
- **Legal Compliance**: Be aware of local laws regarding privacy and monitoring. Unauthorized use of keyloggers is illegal.
- **Transparency**: Use this tool responsibly and only in environments where you have the right to monitor activity.
