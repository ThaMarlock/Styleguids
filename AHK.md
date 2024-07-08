# Styleguide for AHK (AutoHotKey)

## Contents

1. Preamble
2. Nanming Conventions
3. Structure
4. Formatting
5. Code Structure

## Preamble
While there isn't a single official style guide for AutoHotkey, here are some recommendations based on common practices and readability:

## Naming Conventions

### Functions and Hotkeys
- Use descriptive names that reflect their purpose (e.g., ProcessUserData, ^f::FormatText).
  
### Variables
- Use camelCase for local variables and parameters (e.g., userName, isAvailable).
- Consider using Hungarian notation (e.g., sText, iCount) for global variables if you have a large project for clarity.
  
### Labels
- Descriptive names that relate to their use (e.g., LoopStart, ExitRoutine).

## Strucutre



## Formatting

### Indentation
- Use consistent indentation (typically 2 or 4 spaces) to improve readability of code blocks.
  
### Line Length
- Aim for a reasonable line length to avoid horizontal scrolling. Consider line breaks for long expressions.

### Comments
- Use comments to explain complex logic or non-obvious code sections
- Start comments with ; for single-line comments.
- Use multi-line comments with /* and */ for detailed explanations.

## Code Structure

### Hotkeys
- Group related hotkeys together for better organization.
  
### Functions
- Define functions for reusable code blocks.
  
### Error Handling
- Consider using try...finally blocks for robust error handling.
