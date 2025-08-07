# WPM-Typing_Test

A simple and interactive Words Per Minute (WPM) typing test application built for the command line. This project uses Python's built-in curses library to create a dynamic, real-time typing experience right in your terminal.

✨ Features
Real-time Feedback: See your WPM and accuracy update as you type.

Color-Coded Text: Green characters for correct input, and red for mistakes, making it easy to spot errors.

Cursor Navigation: Use arrow keys (LEFT/RIGHT), HOME, and END to move the cursor for easy corrections.

Randomized Passages: A new typing passage is selected for each test to provide varied practice.

Performance Summary: After each test, get a summary of your WPM, accuracy, and total time, along with a personalized performance message.

Terminal UI: A clean and minimalist interface that works in any terminal emulator.

📋 Prerequisites
This application requires Python 3.x. The curses library is typically included with Python on Unix-like systems (Linux, macOS). For Windows, you may need to install a compatible version, like windows-curses.

To install windows-curses on Windows:

pip install windows-curses

🎮 How to Use
The application will start with an instructions screen. Press any key to begin.

Type the provided text as accurately as you can.

The WPM and Accuracy stats will update in real-time at the top of the screen.

Use the BACKSPACE key to correct mistakes.

Use the LEFT and RIGHT arrow keys to navigate the text you've typed.

Press ESC at any time to quit the test.

Once you finish the passage, a results screen will appear.

Press 'r' to retry with a new passage or ESC to exit the program.

📝 Project Structure
WPMTest class: The main class that encapsulates all the logic for the typing test, including the user interface, test loop, and result calculations.

start_screen(): Displays the welcome and instructions screen.

wpm_test(): Contains the core game loop for the typing test.

display_text(): Handles the rendering of the text, cursor, and stats.

results_screen(): Shows the final test results and performance feedback.

main(): The entry point of the application, which initializes the curses environment and runs the WPMTest instance.

📜 License
This project is open-source and available under the MIT License.
