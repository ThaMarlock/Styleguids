# Styleguid for C-Sharp

## Contents

1. Preamble
2. Naming Conventions
3. Structure
4. Formatting
5. Examples
7. Ordering
8. Other Conventions

## Preamble
This document outlines the recommended coding style for C# projects. It aims to improve code readability, consistency, and maintainability, aligning with Google's internal practices for other languages.

## Naming Conventions
- Classes, methods, enums, public fields, public properties, namespaces: PascalCase (e.g., MyClass, GetUserData)
- Local variables, parameters: camelCase (e.g., userName, isAvailable)
- Private, protected, internal, and protected internal fields and properties: _camelCase (e.g., _userData, _isEnabled)
- Interfaces: Start with I (e.g., IDataProvider)
- Filenames and directory names: PascalCase (e.g., MyClass.cs)
- File Naming: Ideally, match the main class name within the file (e.g., MyClass.cs for MyClass class).

## Ordering

### Namespace using declarations
- Placed at the top, before any namespaces.
- Alphabetical order, with system imports preceding others.

### Class member ordering
- Nested classes, enums, delegates, and events.
- Static, const, and readonly fields.
- Fields and properties.
- Constructors and finalizers.
- Methods.

### Within each group
- Public members first

## Other Conventions

### Modifiers
- Order: public protected internal private new abstract virtual override sealed static readonly extern unsafe volatile async

### ref and out
- Use out for non-input returns. Place after other parameters.
- Use ref sparingly, only for necessary input mutation.
- Avoid ref for struct optimization or passing modifiable containers.

### Indention
- Use 4 spaces per indentation level.

### Braces
- Always use curly braces for code blocks, even single-line statements.


## General

- Max Characters per line: 92
- Code and Comments in different lines and never in the same line


## Methodes

- Each parameter in a seperate line
- Summery comment 
- Param's comment's
- Exception comment'S
- each one in a seperated line with the keyword /nodes before and after 
  
## Structure Class (general)

- Copyright text
- using's
- namespace
  - enum's
  - class
    - constant's
    - field's
    - propertie's
    - constructor'S
    - method's
    - event handler'S
    - event's

## Structure Class (DataClass)

- Copyright text
- using'S
- namespace
  - enum'S
  - class
    - constant'S
    - field's
    - propertie'S
    - Constructor's
    - Method's