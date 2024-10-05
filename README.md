# Pomodoro-timer 🍅

This is a "Pomodoro Timer" built using Python and Tkinter. The Pomodoro Technique is a time management method that breaks work into intervals (typically 25 minutes) separated by short breaks. After several work sessions, a longer break is taken. This application helps you manage your work sessions and breaks by using a countdown timer!

## Features

- **Work Sessions**: Default 25-minute work sessions.
- **Breaks**: Short breaks (5 minutes) after each work session and a long break (20 minutes) after every 4 sessions.
- **Visual Timer**: Displays the countdown timer in the form of minutes and seconds.
- **Progress Tracking**: Displays checkmarks (✔) after each completed work session to help you track your progress.

## Files

- `pomodoro_timer.py`: The main script containing the logic for the Pomodoro timer.
- `tomato.png`: Image used as the background for the timer display.

## Pomodoro Timer Logic

- **Work Sessions**: The timer is set to 25 minutes (default) for work.
- **Breaks**: After each work session, a short break of 5 minutes is initiated. After 4 work sessions, a long break of 20 minutes is taken.
- **Countdown Timer**: The countdown mechanism reduces time by seconds and updates the UI every second.
- **Reset**: You can reset the timer at any time using the reset button, which will stop the current timer and reset the progress.
- **Visual Feedback**: Checkmarks (✔) are added to the screen to track completed work sessions.
