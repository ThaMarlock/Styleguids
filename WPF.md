
# Styleguide for WPF (Windows Presentation Foundation)

## Contents

1. Preamble
2. XAML Formatting
3. Nanming Conventions
4. Styles and Templates
5. Code-Behind (C#) Naming Conventions

## Preamble
While WPF doesn't have a single official style guide, here are some recommendations based on best practices and promoting maintainability:

## XAML Formatting

### Indentation
- Consistent indentation (typically 2 spaces) is crucial for readability.
  
### Line Length
- Aim for reasonable line length to avoid horizontal scrolling. Consider line breaks for complex attributes
  
### Closing Tags
- Always include closing tags for elements, even for self-closing elements like <Button />.
  
### Whitespace
- Use whitespace strategically to improve readability. Separate attributes with a space and a newline for complex elements

## Naming Conventions

### XAML Elements
- Use PascalCase for custom controls and user controls (e.g., <MyCustomButton>)
  
### Resource Keys
- Use descriptive names that reflect their purpose (e.g., ButtonStyle1, CommonGridTemplate)
  
### Attached Properties
- Follow the property name with attached property syntax (e.g., Grid.RowSpan="2")

## Styles and Templates

### Style Organization
- Group related styles in a single ResourceDictionary file for better maintainability.

### Style Inheritance
- Leverage inheritance to create base styles and derive specific styles from them.

### Control Templates
- Utilize Control Templates for extensive customization of control appearance and behavior.

### Triggers
- Use triggers within styles to modify control behavior based on specific conditions.

## Code-Behind (C#) Naming Conventions

### Classes
- PascalCase (e.g., MainWindow, UserDataManager)

### Methods, Properties
- PascalCase for public members, camelCase for private members (e.g., GetUserData, _isEnabled)

### Variables, Parameters
- camelCase (e.g., userName, isAvailable)
