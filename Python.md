# Styleguide for Python

## Contents

1. Preamble
2. Nanming Conventions
3. Formatting
4. Imports
5. Linting

## Preamble
This document outlines the recommended coding style for Python projects, inspired by Google's internal style guide. It emphasizes readability, consistency, and maintainability.

## Naming Conventions

### Functions, variables, classes
- snake_case (e.g., get_user_data, is_available)
### Modules
- snake_case (e.g., data_provider.py)
### Constants
- UPPER_SNAKE_CASE (e.g., MAX_TRIES)
### Private members (functions, variables)
- Use a single leading underscore (e.g., _user_data, _is_enabled)
### Class attributes
- Use a double leading underscore (e.g., __version__)

## Formatting

### Indentation
- Use 4 spaces per indentation level
  
### Line Length
- Aim for a maximum of 79 characters per line (excluding comments).

### Blank Lines
- Separate functions and classes with a single blank line.

## Imports
- Use absolute imports from the project root whenever possible.
- Organize imports into sections
  - Standard library imports (alphabetical order)
  - Third-party library imports (alphabetical order)
  - Local application imports (relative to current module)

## Linting
- Utilize linters like pylint to enforce style consistency and identify potential errors.
