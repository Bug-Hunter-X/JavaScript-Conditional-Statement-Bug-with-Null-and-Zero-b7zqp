# JavaScript Conditional Statement Bug with Null and Zero

This repository demonstrates a subtle bug in a JavaScript conditional statement that leads to unexpected behavior when handling null and zero values.

## Bug Description
The JavaScript function `foo` aims to return 0 for null input, -1 for negative numbers, and 1 for non-negative numbers. However, it incorrectly classifies 0 as a positive number.

## Bug Reproduction
1. Clone this repository.
2. Run `bug.js`.
3. Observe the unexpected output for the input value 0.

## Bug Solution
The solution involves restructuring the conditional statement to properly handle the case where x equals 0. The corrected logic is implemented in `bugSolution.js`.

## Contributing
Contributions are welcome! Feel free to open an issue or submit a pull request.