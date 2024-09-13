# Keylogger Script

This is a basic keylogger script built using Python's pynput library. It records keystrokes into a text file (key_log.txt) and stops logging when the Esc key is pressed.

## Features
Logs all key presses to a text file (key_log.txt).
Stops recording when the Esc key is pressed.
Handles both alphanumeric and special keys.

## Requirements
To run this script, you need to install the following dependencies:
Python 3.x
pynput library
You can install the pynput library using pip:
```bash 
pip install pynput
```

## Usage
1- Clone the repository or copy the script to your local machine.
2- Make sure you have Python and pynput installed.
3- Run the script:
```bash
python keylogger.py
```
4- The script will start logging keystrokes to the key_log.txt file. To stop the script, press the Esc key.

## Code Explanation

1- on_press: This function is called whenever a key is pressed. It logs the key character to the key_log.txt file.
2- on_release: This function is called whenever a key is released. If the Esc key is pressed, the logging stops.
3- The script uses the pynput library's Listener class to monitor key presses and releases.

## Important Notes

Use this script responsibly! Make sure you have permission to log keystrokes on any machine you're using this script on.
