# My-Calculator

# Calculator Application

## Overview

This is a simple calculator web application developed using HTML, CSS, and JavaScript. The calculator provides basic arithmetic operations such as addition, subtraction, multiplication, and division.

## Features

- Responsive user interface for performing calculations.
- Interactive buttons to input numbers and operators.
- Results are displayed dynamically on the calculator screen.
- Supports clearing the screen for new calculations.

## File Structure

### `calculator.html`

- **HTML**: Contains the structure of the calculator interface using a table.
- **CSS**: Inline styles for basic formatting and layout.
- **JavaScript**: Script to handle button clicks and perform arithmetic calculations.

## Usage

1. Open the `calculator.html` file in any modern web browser.
2. Use the numbered buttons to input values.
3. Use the `+`, `-`, `*`, or `/` buttons for arithmetic operations.
4. Press the `=` button to display the result.
5. Press `C` to clear the screen and start a new calculation.

## Code Highlights

### HTML Table

The calculator interface is built using an HTML table where:

- Each cell (`<td>`) represents a button.
- The screen is implemented using a `<td>` element spanning four columns.

### JavaScript Functions

- `clickHandler(value)`: Appends the clicked value to the calculator screen.
- `clickEvaluate()`: Evaluates the expression displayed on the screen and displays the result.
- `emptyScreen()`: (Currently unused) Intended to clear the screen.

## Known Issues

- The `C` button is not yet functional. The `emptyScreen()` function needs to be implemented and linked to this button.
- Minor typo in the JavaScript (`documet` instead of `document`) prevents evaluation from functioning correctly.

## Future Improvements

- Add support for more operations (e.g., square root, percentage).
- Improve UI styling for a more modern look.
- Make the calculator responsive for mobile devices.
- Implement error handling for invalid expressions.

## How to Run

Simply open the `calculator.html` file in any web browser to use the calculator. No additional setup is required.

## Author

Vedanta Nanda


