# Pomodoro Timer

This is a simple Pomodoro Timer application built using Python's Tkinter library. The Pomodoro technique is a time management method that breaks down work into intervals, traditionally 25 minutes in length, separated by short breaks.

## Features

- **Work Timer:** Default set to 25 minutes.
- **Short Break Timer:** Default set to 5 minutes.
- **Long Break Timer:** Default set to 20 minutes after 4 work intervals.
- **Start and Reset Buttons:** Easily start the timer or reset it.
- **Progress Checkmarks:** Track work intervals with checkmarks after each work session.

## How to Run

1. **Requirements:**  
   - You need to have Python installed on your system. Tkinter is part of the standard Python distribution, so no extra packages are required.
   - You need an image named `tomato.png` to display the visual in the UI (place it in the same directory as the script).

2. **Running the Application:**  
   - Simply run the `pomodoro.py` file.
   - The timer will start with a 25-minute work session, followed by short breaks, and a long break every 4 work intervals.

## Code Overview

### Main Components:
- **UI Setup:**
  The interface is created using Tkinter's `Canvas`, `Label`, and `Button` widgets to display the timer, start/reset buttons, and checkmarks.
  
- **Timer Mechanism:**
  - `start_timer()`: Manages the start of each work or break session based on the number of intervals completed.
  - `count_down()`: Manages the countdown for each session, updating the timer display every second.

- **Reset Function:**
  - `reset_timer()`: Cancels the current timer and resets the interface to its initial state.

## Customization

You can customize the time intervals by changing the following constants in the script:
- `WORK_MIN`: Work duration in minutes (default is 25).
- `SHORT_BREAK_MIN`: Short break duration in minutes (default is 5).
- `LONG_BREAK_MIN`: Long break duration in minutes (default is 20).

## Screenshot
Include a screenshot of the running application if possible.

## License

feel free to modify and distribute it.
