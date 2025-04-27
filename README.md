# vscode-gmat-script-v0.1.0
GMAT Script is a specialized VS Code extension designed to enhance productivity for GMAT test preparation and practice. This tool helps users efficiently work with GMAT-related scripts, formulas, and practice problems within Visual Studio Code.
# gmat-script README

![GMAT Script Extension](https://img.shields.io/badge/VS%20Code-GMAT%20Script-blue)
![Version](https://img.shields.io/badge/version-0.0.1-green)

A Visual Studio Code extension that provides development tools for working with GMAT (General Mission Analysis Tool) script files. This extension enhances your GMAT scripting experience with syntax highlighting, code completion, hover information, snippets, and execution capabilities.

## Features

This extension enhances GMAT script development with several powerful features:

### Syntax Highlighting and Language Support
- Dedicated grammar for `.script` files
- Color coding for GMAT keywords, commands, and parameters

![Syntax Highlighting]

### IntelliSense and Code Completion
- Command autocompletion
- Object type suggestions after `Create` statements
- Property autocompletion based on object types
- Variable reference suggestions

![Code Completion]

### Hover Information
- Detailed documentation when hovering over:
  - GMAT commands
  - Object types
  - Object properties
  - Variables

![Hover Information]

### Code Snippets
- Comprehensive collection of snippets for common GMAT objects:
  - Spacecraft configurations (Keplerian and Cartesian)
  - Force models
  - Propagators
  - Burns (Impulsive and Finite)
  - Tanks and thrusters
  - Visualization resources (OrbitView, XYPlot)
  - Locators (Contact, Eclipse)
  - Loops and control structures
  - And many more

![Code Snippets]

### Script Execution
- Run GMAT scripts directly from VS Code
- View execution output in a dedicated channel
- Configure path to GMAT executable

![Script Execution]

### Script Analysis
- Basic static analysis of GMAT scripts
- Count of commands, variables, and comments
- List of created objects

![Script Analysis]

## Installation

1. Install the extension from the VS Code marketplace
2. Configure the path to your GMAT executable:
   - Use command `GMAT: Configure Executable Path`
   - Or set `gmat-script.gmatExecutablePath` in settings

## Requirements

- Visual Studio Code 1.99.0 or newer
- GMAT installed on your system
- Configure the path to your GMAT executable to use the run command

## Usage

### Running Scripts
- Open a `.script` file in VS Code
- Use keyboard shortcut: `Ctrl+Shift+R` (Windows/Linux) or `Cmd+Shift+R` (Mac)
- Or use command: `GMAT: Run Script`
- Or right-click in editor and select `GMAT: Run Script`

### Analyzing Scripts
- Use keyboard shortcut: `Ctrl+Shift+A` (Windows/Linux) or `Cmd+Shift+A` (Mac)
- Or use command: `GMAT: Analyze Script`
- Or right-click in editor and select `GMAT: Analyze Script`

### Using Snippets
Type snippet prefixes (like `create-spacecraft`, `propagate`, etc.) to access predefined code blocks.

## Extension Settings

This extension contributes the following settings:

* `gmat-script.gmatExecutablePath`: Path to the GMAT executable

## Known Issues

Calling out known issues can help limit users opening duplicate issues against your extension.

- This is an initial release (0.0.1) and may have bugs or incomplete features
- Detailed analysis of GMAT scripts is limited

## Release Notes

### 0.0.1

Initial release of GMAT Script extension with the following features:
- Syntax highlighting for GMAT script files
- IntelliSense and autocompletion for GMAT commands and objects
- Hover documentation for commands and properties
- Code snippets for common GMAT objects and patterns
- Run GMAT scripts directly from VS Code
- Basic script analysis capabilities

---

## Following extension guidelines

Ensure that you've read through the extensions guidelines and follow the best practices for creating your extension.

* [Extension Guidelines](https://code.visualstudio.com/api/references/extension-guidelines)

## Author

**Moussa FALL** ([@kallah94](https://github.com/kallah94))

**Enjoy!**
