# Pomodoro Timer with To-Do List and XP Rewards

This project is a productivity application that combines a Pomodoro timer with a to-do list and a gamified reward system. It's designed to help users stay focused, manage tasks efficiently, and stay motivated by earning XP (experience points) for completing tasks and work sessions.

 Features

- Pomodoro Timer: A 15-minute timer to improve focus through timed work sessions.
- Task Management: Add, complete, and remove tasks with a user-friendly to-do list.
- Gamified Experience: Earn XP for completing tasks and Pomodoro sessions, and level up as you progress.
- Progress Tracking: Visual XP bar and level display provide motivation and a sense of accomplishment.
- Sound Notifications: Play sound effects for leveling up, earning XP, and completing the timer.
- Local Storage: Your progress, tasks, and XP are saved locally so you can pick up where you left off.

 How to Use

1. Start the Timer:
   - Click the "15 mins" button to start the Pomodoro timer.
   - Once the timer ends, you'll earn XP and a sound will play to notify you.

2. Manage Tasks:
   - Use the input field to add tasks and click the "Add Task" button.
   - Mark tasks as complete by clicking them, earning XP for each completed task.
   - Remove tasks by clicking the "X" button next to them.

3. Track Progress:
   - Your level and XP bar update automatically as you earn XP.
   - Progress is saved locally, so reloading the page won't erase your data.

 Changing the Sound Effects

You can customize the sound effects used in the application for events like leveling up, earning XP, and the timer ending. Follow these steps to replace the default sound files:

1. Locate the `sounds` Folder:
   - Navigate to the directory where your project files are stored.
   - Open the `sounds` folder.

2. Replace Sound Files:
   - Replace the existing sound files with your desired audio files. Make sure to use the same filenames:
     - `level-up.mp3` (plays when you level up)
     - `timer-end.mp3` (plays when the Pomodoro timer ends)
     - `xp-gain.mp3` (plays when you earn XP by completing tasks)
   - Supported formats: Ensure your audio files are in a format supported by modern browsers (e.g., MP3).

3. Verify File Structure:
   - The `sounds` folder should look like this:
     ```
     sounds/
     ├── level-up.mp3
     ├── timer-end.mp3
     ├── xp-gain.mp3
     ```

4. Test the Changes:
   - Reload the application in your browser.
   - Perform actions like completing tasks, starting/stopping the timer, and leveling up to ensure the new sounds are working as intended.

 Technologies Used

- HTML/CSS/JavaScript: Frontend development.
- LocalStorage: Saves user data such as tasks, XP, and level.
- Audio API: Plays sound effects for key events.

 Future Improvements

- Add settings for customizing timer durations and XP rewards.
- Enable users to upload custom sounds directly via the interface.
- Implement dark/light mode toggle.

 Contribution

Feel free to fork the repository and contribute! If you encounter any issues or have suggestions for improvement, please open an issue or submit a pull request.

---

Happy productivity! 🎉

