# Auto Typer - Multi Keyword Edition

## 📝 Overview

The **Auto Typer - Multi Keyword Edition** is a powerful desktop application built with Python and Tkinter that acts as a phrase expander or auto-responder. It monitors keyboard input and automatically replaces a defined **keyword** with a longer **message**, complete with a customizable typing delay.

This application is designed for scenarios where you need to quickly type complex phrases, code snippets, or standardized responses by simply typing a short trigger word. Its multi-keyword support allows for great flexibility, and the ability to set a global stop keyword ensures you always have immediate control.

## ✨ Features

* **Multi-Keyword Support:** Configure multiple unique keyword-message-delay pairs simultaneously.
* **Real-Time Monitoring:** Uses the `keyboard` library to monitor typed characters in real-time across any application.
* **Customizable Typing Delay:** Set an individual delay (interval) for typing each message to simulate natural typing speed or for compatibility with slow input fields.
* **Instant Keyword Deletion:** Upon detection, the keyword is automatically backspaced out before the message is typed.
* **Global Stop Keyword:** Define a specific phrase to immediately halt any ongoing or pending auto-typing action for instant control.
* **F6 Reset Hotkey:** Press **F6** at any time to reset the application's status to "Idle" and clear the stop flag.
* **Mouse Movement Interruption:** Typing is automatically interrupted if the mouse position changes, preventing accidental input.
* **Visual Status Updates:** Clear status labels indicate if the app is Idle, Typing, or has been interrupted.
* **Tkinter GUI:** User-friendly graphical interface for easy management of keywords.

## 🛠️ Installation and Setup

### Prerequisites

You must have **Python 3.x** installed on your system.

### Dependencies

This project requires the following Python libraries:

1.  `tkinter` (Usually included with standard Python installations)
2.  `pyautogui`
3.  `keyboard`
4.  `winsound` (Windows-specific for beeps/sounds)

You can install the required external libraries using `pip`:

```bash
pip install pyautogui keyboard
