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


## General
- Max Characters per line: 92
- Code and Comments in different lines and never in the same line


### Naming Conventions
- Classes, methods, enums, public fields, public properties, namespaces: PascalCase (e.g., MyClass, GetUserData)
- Local variables, parameters: camelCase (e.g., userName, isAvailable)
- Private, protected, internal, and protected internal fields and properties: _camelCase (e.g., _userData, _isEnabled)
- Interfaces: Start with I (e.g., IDataProvider)
- Filenames and directory names: PascalCase (e.g., MyClass.cs)
- File Naming: Ideally, match the main class name within the file (e.g., MyClass.cs for MyClass class). For each class a new file.


### Indention
- Use 2 spaces per indentation level.


### Braces
- Always use curly braces for code blocks, even single-line statements.


## Ordering

### Copyright and Info
Copyright adn info text is at the top of the file. Contains:
- Copyright text (Year, Company, 'All rights reserved' text)
- Author
- License information
- Description
- Install (if neccessery)
- Run/Start (if neccessery)
- Stop (if neccessery)
- Version


### Using
Using's are in a region.
Using's are listed directly after the copyright and info part.
Using's are listed in alphabetical order with a special for the System using's, which are listed before the other using's


### Namespace
The namespace are written with two blank line after the using's region
Brackets start in the next line

### Enum's
Enum's are in a region.
Enum's are listed in the next line after the opening bracket of the namespace.
Enum's are listed in accessable and then in alphabetical order.


### Class
Class start two blank lines after the Enum's region.
Class have always the name of the file. 
Only one Class per file. Only exception are private class's
Brackets start in the next line.


### Constant's
Constant's are in a region.
Constant's are listed in the next line after the opening bracket of the class.
Constant's are listed in accessable and then in alphabetical order.


### Field's
Field's are in a region.
Field's are lited two blank lines after the constant's region.
Field's are listed in accessable and then in alphabetical order.


### Propertie's
Propertie's are in a region.
Propertie's are listed two blank lines after the field's region.
Propertie's are listed in accessable and then in alphabetical order.


### Constructor's
Constructor's are in a region.
Constructor's are listed two blank lines after the propertie's region.
Constructor'S are listed in accssable and then in a alphabetical order.


### Method's
Method's are in a region.
Method's are listed two blank lines after the constructor's region.
Method's are listed in accessable and then in alphabeticaln oder.

### Event Hanlder
Event Handler are in a region.
Event Handler are listed two blank lines after the method's region.
Event Handler are listed ni´´in assseccable and aphabetical order.

### Event
Event are in a region.
Event are listed two blank lines after the event handler region.
Event are listed in accessable and then in alphabetical order.


## Extended Conventions


### Modifiers
- Order: public protected internal private new abstract virtual override sealed static readonly extern unsafe volatile async


### ref and out
- Use out for non-input returns. Place after other parameters.
- Use ref sparingly, only for necessary input mutation.
- Avoid ref for struct optimization or passing modifiable containers.
- Code and Comments in different lines and never in the same line


## Structure
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
    - Event (OnPropertyChange)

## Structure Class (Functional Classe's [static])

- Copyright text
- using'S
- namespace
  - enum's
  - class
    - constant's
    - field's
    - propertie'S
    - Method'S
    - Event (OnPropertyChange)

## Structure Class (Functional Classe's)

- Copyright texgt
- using's
- namespace
  - enum's
  - class
    - constant's
    - field's
    - properties
    - Constructor
    - Method'S
    - Event