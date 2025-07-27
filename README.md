🕒 Python Alarm Clock using Tkinter

This is a simple **Alarm Clock GUI application** built with **Python** using **Tkinter**. It allows the user to set a specific time, and when the current system time matches the set time, the application plays a sound to alert the user.

🔧 Features

- ⏰ Easy-to-use interface for setting alarm (Hour, Minute, Second)
- 🎵 Plays a sound when the alarm time is reached
- 🧵 Runs alarm checking in the background using threading
- 🪟 Built with Tkinter for a lightweight GUI

🚀 How It Works

1. User selects hour, minute, and second from dropdown menus.
2. Clicks the "Set Alarm" button.
3. The program continuously checks the system time.
4. When current time matches the alarm time, it plays a sound (`sound.wav`).

🧠 Concepts Used

- GUI Programming (`Tkinter`)
- Threading to keep the interface responsive
- Time and Date Handling (`datetime`, `time`)
- Event-driven programming
- Playing sound using `winsound` (Windows only)


