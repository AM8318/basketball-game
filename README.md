# Basketball Game

An interactive Java Swing basketball shooting game. Click the basketball to throw it toward a moving hoop, score points for successful shots, and manage three chances represented by heart icons.

## Features

- Moving basketball hoop.
- Adjustable hoop speed and ball speed using sliders.
- Score tracking.
- Three chances per game.
- Reset button.
- Java Swing components including `JFrame`, `JPanel`, `JLabel`, `JButton`, and `JSlider`.
- Custom 2D graphics drawn with Java AWT.

## Requirements

- Java Development Kit (JDK) 8 or newer.

## Project files

- `Project2Runner.java`: Starts the game window.
- `GamePanel.java`: Contains the game interface, drawing, controls, movement, scoring, and event handling.
- `heart.jpg`: Heart image used for remaining chances.
- `Color.java`: Included project file.
- `New-Text-Document.txt`: Reference link supplied with the project.

## How to run

1. Compile the Java files:

   ```bash
   javac Project2Runner.java GamePanel.java
   ```

2. Run the game:

   ```bash
   java Project2Runner
   ```

3. Click the basketball to shoot it. Use the sliders to adjust the hoop and ball speed.

## Notes

The source code currently loads the chance icon using the filename `heart.png`. Rename `heart.jpg` to `heart.png`, or update the `ImageIcon` path in `GamePanel.java` to `heart.jpg` before running.
