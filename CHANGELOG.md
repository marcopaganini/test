# Changelog

## v0.3.1 (Oct/2024)

- BUGFIX: Introduced a small hack to properly pretty print large numbers.
  Please note that rpn uses 64-bit floats internally, so numbers above 2^53
  cannot be reliably represented with full precision.
- BUGFIX: Small fix when printing the version number in the help page.

## v0.3.0 (Oct/2024)

- NEW: Added comment support. Anything starting with '#' is a comment.
- NEW: Added a demo GIF to the main github page.
- NEW: The `help` command now prints the binary version as well.

## v0.2.0 (Oct/2024)

- NEW: Added pagination to the help screen.
- NEW: Added trigonometric functions.
- NEW: Remove all irrelevant characters from input. It's now possible to type numbers with
  commas, dollar signs, etc. Please note that this assumes the decimal point to be "."
- NEW: Added f2c and c2f (Fahrenheit/Celsius conversion).
- BUGFIX: Fix parsing of decimal fractions (0.xx).

## v0.1.0

- Initial release