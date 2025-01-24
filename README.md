# Digital Clock Application

This is a simple digital clock application built using JavaFX. The app displays the current time in a digital clock format, updating every second. It consists of four digits representing the hour and minute, along with a colon (`:`) separating them. The application uses basic JavaFX features such as scene creation, animation, and timeline updates.

## Features
- Real-time digital clock display
- Hour and minute are displayed in a digital format
- Updates every second
- Black background with white digits for visibility
- Uses JavaFX animation and timeline to update the clock every second

## Requirements
- Java 8 or later
- JavaFX libraries

## Setup and Installation

1. **Clone the repository (if applicable)**:
   ```bash
   git clone https://github.com/yourusername/digital-clock.git
   
2. **Compile and run the application:**
If you're using an IDE such as IntelliJ IDEA, Eclipse, or NetBeans, simply open the project and run the Driver class.

Alternatively, you can compile and run the program using the terminal/command line:

javac Driver.java

java Driver

Make sure you have the JavaFX libraries configured in your environment.

## How It Works

Main Window: The app creates a window using JavaFX and sets up a scene with a group of components representing the clock.

Digits Representation: The clock is represented by four Digits objects (for the hour and minute), along with a Colon object for the separator between the hour and minute.

Timeline Animation: A Timeline object is used to update the time every second. Each time the clock updates, the setDigit() method is called on the Digits objects to display the current hour and minute.

Real-Time Updates: The time is fetched from the system clock using LocalTime.now() and is updated on the screen every second.

## How to Use

Launch the Application: After running the application, a window will pop up showing the digital clock.

Real-Time Updates: The clock will automatically update every second to reflect the current system time.

Screenshots



## Future Improvements

Add support for 12-hour and 24-hour clock formats.

Improve the UI design with better styling and graphics.

Add features like alarm, timer, or stopwatch functionality.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
