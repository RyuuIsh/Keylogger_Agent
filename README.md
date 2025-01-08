# Keylogger_Agent
A simple keylogging script built using Python's pynput module. This program listens for keyboard input and logs it into a file for analysis or debugging purposes.

## ⚠️ Disclaimer
This script is intended for educational purposes only and to demonstrate the capabilities of Python's pynput library. Unauthorized use of keyloggers to capture sensitive information without explicit consent is illegal and unethical. Use responsibly.

## Features
1. Keypress Logging:
- Logs both alphanumeric and special keys pressed on the keyboard.
2. Readable Logs:
- Outputs keystrokes in a clean, readable format into a log file.
3. Real-Time Feedback:
- Prints key events (pressed and released) to the console for monitoring.
4. Simple and Lightweight:
- Minimal setup with functionality powered by Python's pynput library.

## Working
1. Key Detection:
- The program listens for all key presses and releases using the pynput library's Listener.
2. Logging:
- Captures key events and writes them into a file named log.txt.
3. Stopping the Listener:
- Press the Esc key to stop the keylogger gracefully.

## Requirements
- Python 3.x
- pynput module (Install it using pip install pynput)

## Security Reminder 🔒
Always inform users before deploying a keylogger. Unauthorized deployment is a violation of privacy and can have legal consequences.

## Future Enhancements
- Encrypt the log file for added security.
- Add functionality to email or upload logs securely for remote monitoring.
- Log timestamps for each keypress to track events chronologically.
- Implement functionality to filter specific keys or combinations.
