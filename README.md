# Auto Typer

## 🚀 Overview

The **Auto Typer** is a powerful, desktop automation tool built with Python and `tkinter`. It allows users to define multiple messages, each triggered by a unique keyword or phrase. When the application detects a defined keyword being typed anywhere on the screen, it automatically backspaces the keyword and rapidly types out the corresponding full message. This is ideal for quickly inserting common phrases, code snippets, or long messages using short, customized triggers.

## ✨ Key Features

* **Multi-Keyword Support:** Configure an unlimited number of message/keyword pairs.
* **Customizable Delay:** Set a specific typing delay (interval) for each message for a more natural-looking typing effect.
* **Global Keyword Monitoring:** Utilizes the `keyboard` library to detect keywords even when the application is minimized or not in focus.
* **Safety Stop Feature:** Define a global stop keyword that, when typed, immediately halts any active or pending typing operations.
* **Mouse Interruption:** Typing is automatically interrupted if the mouse position changes, preventing unintended inputs.
* **Simple GUI:** An intuitive graphical user interface built with `tkinter` for easy management of keyword/message entries.
* **Status Updates:** Real-time status messages (Idle, Typing, Done, Interrupted) provide clear feedback.
* **Hotkeys:** Pressing **F6** resets the application's status to Idle, clearing any stop flags.

##Screenshot


## 🛠️ Installation

### Prerequisites

You must have Python (3.x recommended) installed on your system.

### Dependencies

This project relies on the following Python packages:

1.  `tkinter` (Usually included with standard Python installations)
2.  `pyautogui`
3.  `keyboard`
4.  `winsound` (Windows-specific, used for audio cues)

Install the required external dependencies using pip:

```bash
pip install pyautogui keyboard
