# Pyramid-Generator
This JavaScript project generates a pyramid of characters ("!" by default) and outputs it to the console. It allows for customizable pyramid height and an option to invert the pyramid structure.

![image](https://github.com/user-attachments/assets/91144189-e7a9-4ea0-a067-b9738c9a9c62)

## Features

- **Character Customization:** Allows you to specify the character used to build the pyramid (e.g., `"!"`).
- **Row Count:** You can adjust the number of rows in the pyramid by modifying the `count` variable.
- **Inversion:** The pyramid can be printed in an inverted format by toggling the `inverted` flag.

## Code Walkthrough

The project consists of JavaScript code that performs the following steps:

1. **Variable Initialization:**
   - `character`: Defines the character used for building the pyramid (default is `"!"`).
   - `count`: Specifies how many rows the pyramid should have.
   - `rows`: An array to store each row of the pyramid.
   - `inverted`: A flag to control whether the pyramid is printed normally or inverted.

2. **Padding Function:**
   - `padRow(rowNumber, rowCount)`: A helper function to calculate the spaces before and after the character pattern for each row.

3. **Loop to Build Pyramid:**
   - A loop runs from 1 to `count`, creating a row for each iteration and adding it to the `rows` array.
   - The rows are either added normally or prepended (if inverted) depending on the value of `inverted`.

4. **Result Construction:**
   - A final loop iterates over the rows array and concatenates each row into a string (`result`), which is then printed.

## Example Output

For `count = 5` and the default character `"!"`, the output would be:

