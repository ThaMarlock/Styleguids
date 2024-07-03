# Styleguide for Version

## Contents

1. Preamble
2. Structure
3. Naming Conventions
4. Formatting
5. Examples
6. Alpha/Beta Version

## Preamble
This styleguide defines the structure and rules for versioning software programs.

## Structure
- **MAJOR**: Indicates major, potentially breaking changes.
- **MINOR**: Indicates the addition or enhancement of features.
- **PATCH**: Indicates bug fixes and minor improvements.
- **BUILD**: Indicates the build iteration for internal tracking.
  
## Naming Conventions
### **MAJOR**
  - This number is incremented if a major change has been made.
    - Used when compatibility with older versions is limited or not possible.
    - Examples:
      - Overhaul of the software architecture.
      - Removal of deprecated features.

### **MINOR**
  - This number is incremented if a minor change has been made.
    - Addition of new functions or extension of existing functions.
    - Introduction or extension of APIs.
    - Performance updates.
    - Examples:
      - Adding a new module.
      - Optimizing an existing feature for better performance.

### **PATCH**
  - This number is incremented if a patch change has been made.
    - Bug fixes.
    - Corrections of spelling mistakes.
    - Code cleanups and refactoring.
    - Examples:
      - Fixing a security vulnerability.
      - Correcting a typo in the user interface.

### **BUILD**
  - This number is incremented for every new build that has been made.
    - Used for internal tracking of development progress.
    - Examples:
      - Daily or continuous integration builds.

## Formatting
- The version number consists of four sections separated by periods.
- Each section is crucial and represents specific information about the software version.
- The format is as follows:
  ```
  MAJOR.MINOR.PATCH.BUILD
  ```



## Examples
- **1.0.0.0**
  - Initial release.
- **1.1.0.0**
  - First minor update with new features.
- **1.1.1.0**
  - First patch with bug fixes and minor improvements.
- **1.1.1.1**
  - First build iteration after the initial patch.

## Alpha/Beta Version
- **Pre-release Versions**: For versions that are not final releases (e.g., beta, alpha), consider appending labels.
  - Example: `1.0.0-alpha`, `1.0.0-beta`
