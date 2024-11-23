# Reaction Tester Game

The **Reaction Tester Game** is a simple web-based application designed to measure and improve reaction times. It is implemented using **HTML**, **CSS**, and **JavaScript**, showcasing basic interactive web development techniques.

## Code Explanation

### Structure
- **HTML**: Defines the basic structure of the game, including a heading, description, and a hidden `div` element (`#shape`) that serves as the clickable target.
- **CSS**: Styles the target `div` and positions it dynamically. It also applies a clean design to ensure focus remains on the game.
- **JavaScript**: Implements the game's logic, handling the appearance, randomization, and timing of the clickable target.

### Functionality
1. **Target Randomization**:
   - The `#shape` appears at random positions on the screen with varying sizes and colors.
   - A random color is generated using the `getRandomColor` function.

2. **Reaction Time Measurement**:
   - The game calculates the time elapsed between the appearance of the `#shape` and the user's click.
   - The reaction time is displayed in an alert box.

3. **Interactive Behavior**:
   - Once the `#shape` is clicked, it disappears, and a new one reappears in a different location.
   - The process repeats, keeping the game engaging.

### Usage
- Open the game in a browser.
- Wait for the `#shape` to appear on the screen.
- Click the `#shape` as quickly as possible.
- View your reaction time in seconds, displayed in an alert box.
- Repeat to improve your reaction speed!

This project is a fun way to test reflexes and learn the basics of dynamic web development.

