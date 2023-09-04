# Stopwatch
A simple stopwatch application built using HTML, CSS, and JavaScript. This stopwatch allows you to start, stop, and reset the timer to track elapsed time with precision.

## Features

- **Start:** Begin the timer to track elapsed time.
- **Stop:** Pause the timer to capture intermediate time or to pause tracking.
- **Reset:** Reset the timer to zero.

## How to Use

1. Clone or download the repository to your local machine.
2. Open the `index.html` file in your web browser.
3. You will see the stopwatch display with three buttons: Start, Stop, and Reset.
4. Click the "Start" button to begin the stopwatch.
5. You can click the "Stop" button to pause the timer at any time.
6. To reset the timer, click the "Reset" button.
7. The elapsed time is displayed in the format `HH:MM:SS:MS`, where `HH` represents hours, `MM` represents minutes, `SS` represents seconds, and `MS` represents milliseconds.

## Hosted Link
https://ameya-shinde.github.io/Stopwatch/

## Code Explanation

- The stopwatch is built using HTML for structure, CSS for styling, and JavaScript for functionality.
- The elapsed time is calculated using the `Date` object and updated every 10 milliseconds.
- The `formatTime` function is used to format the elapsed time in a user-friendly manner.
- Event listeners are added to the "Start," "Stop," and "Reset" buttons to control the stopwatch.

## JS Functionality Used

This stopwatch project leverages several key JavaScript functionalities to provide accurate time tracking and user interactivity:

- **Date Object:** The stopwatch calculates elapsed time using the `Date` object, capturing precise time intervals.

- **Interval:** The `setInterval` function is used to update the elapsed time display every 10 milliseconds, ensuring accurate time tracking.

- **Event Listeners:** Event listeners are attached to the "Start," "Stop," and "Reset" buttons, enabling user interaction and control over the stopwatch.

- **Data Manipulation:** JavaScript is used to calculate and format the elapsed time in hours, minutes, seconds, and milliseconds, making it more user-friendly.

- **Disabling Buttons:** Buttons are enabled or disabled dynamically to prevent unintended actions during stopwatch operation.

These JavaScript functionalities work together to create a functional and user-friendly stopwatch experience.
