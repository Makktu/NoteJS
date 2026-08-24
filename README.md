# NoteJS

A lightweight, single-file JavaScript scratchpad for quick code testing and experimentation.

## Overview

NoteJS is a pure vanilla JavaScript scratchpad that provides a simple, distraction-free environment for testing code snippets.
It runs directly in the browser.
The entire application is contained in a single HTML file with no dependencies, installation, or further setup required.

## Features

- **Single HTML File**: No installation, no dependencies, just open and use
- **File Save & Open**: Open local JavaScript files, manually save changes with standard file operations (Save, Save As), and create new files
- **Autosave**: Automatic real-time saving to disk when a file is open, with a dedicated toolbar on/off toggle
- **Two-Panel Layout**: Code editor on the left, console output on the right
- **Syntax Highlighting**: Full syntax highlighting with customizable themes
- **Theme Selection**: Choose from multiple editor themes including Darcula, Material, Dracula, Monokai, and more
- **Font Size Controls**: Adjust font size separately for both code editor and output panels
- **IntelliSense**: Code completion for keywords, built-in functions, and user-defined variables
- **Autocomplete Toggle**: Option to turn off code completion to practice manual coding skills
- **Console Capture**: All console output (log, error, warn) is displayed in the output panel
- **Auto-indentation**: Proper code formatting with smart indentation
- **Keyboard Shortcuts**: Ctrl+Enter/Cmd+Enter to run, Ctrl+S/Cmd+S to save, Ctrl+Shift+S/Cmd+Shift+S for Save As, Ctrl+O/Cmd+O to open, Tab for completion/indentation
- **Error Reporting**: Clear display of runtime and syntax errors
- **Persistent Settings**: Your theme, font size, autosave, and autocomplete preferences are remembered between sessions
- **Copy Buttons**: Easily copy code or output with a single click
- **Dark Theme**: Easy on the eyes with customizable dark and light editor themes

## Why NoteJS?

NoteJS was created with a few key principles in mind:

1. **Simplicity First**: No complex setup or configuration
2. **Zero Dependencies**: Works offline, no external services required
3. **Instant Feedback**: Run your code and see results immediately
4. **Distraction-Free**: Focus on your code without unnecessary features
5. **Cross-Platform**: Works on any device with a modern browser

## Usage

1. Download the single HTML file (`note-js.html`). Nothing else needed.
2. Open it in any modern browser.
3. Start writing JavaScript code in the left panel or open an existing file (`Open` button or `Ctrl+O`/`Cmd+O`).
4. Save your work manually with `Save` (`Ctrl+S`/`Cmd+S`) or `Save As...` (`Ctrl+Shift+S`/`Cmd+Shift+S`).
5. Enable `Autosave` in the toolbar to automatically save changes to your file as you type.
6. Run the code with the Run button or `Ctrl+Enter`/`Cmd+Enter`.
7. See the output in the right panel.

## File Operations & Autosave

- **Open File**: Open any `.js` or text file from your computer using the `Open` button or `Ctrl+O`/`Cmd+O`.
- **Save File**: Save modifications directly to the current file with the `Save` button or `Ctrl+S`/`Cmd+S`. If no file is open, you will be prompted to choose a save destination.
- **Save As**: Save your current code as a new file at any time using `Save As...` or `Ctrl+Shift+S`/`Cmd+Shift+S`.
- **Autosave**: Toggle autosave on or off using the switch in the top toolbar. When turned on and a file is active, your changes are automatically saved to disk a second after you stop typing.
- **File Status Badge**: Shows current file name, unsaved changes indicator (`●`), and live save status timestamps.

## Customization Options

NoteJS offers several customization options:

### Theme Selection

- Click the theme dropdown next to the NoteJS logo to choose from multiple editor themes
- Themes seamlessly style the **entire application** (headers, buttons, background, output console, modals, dropdowns, and hints) for a unified aesthetic
- Options include:
  - **Night Owl**: A true dark, deep-blue theme inspired by VS Code's Night Owl
  - **Darcula**: Classic JetBrains dark theme
  - **Material**: Material Design dark slate
  - **Dracula**: Popular vibrant purple/pink dark theme
  - **Monokai**: Classic warm high-contrast dark theme
  - **Nord**: Arctic cool bluish-gray palette
  - **Solarized**: Solarized Dark cyan/teal aesthetic
  - **Tomorrow Night**: High-contrast pure black theme
  - **Ambiance**: Warm dark espresso/olive palette
  - **Eclipse**: Crisp clean light theme
  - **IntelliJ**: Modern light gray IntelliJ theme

### Font Size Controls

- Adjust the font size for the code editor using the dropdown in the code panel
- Separately control the font size for the output panel
- Font sizes range from 12px to 24px

### Autocomplete Toggle

- Turn code completion on or off using the toggle switch in the code panel
- Practice your coding skills without assistance when turned off
- All preferences are saved between sessions

### Autosave Toggle

- Turn automatic saving on or off directly from the toolbar switch
- Remembers your preference across browser sessions

## Code Completion

NoteJS features intelligent code completion:

- Start typing and see suggestions for both built-in functions and your own variables
- Press Tab or Ctrl+Space to trigger completion manually
- Navigate suggestions with arrow keys
- User-defined variables and functions are highlighted differently from built-in ones
- Autocomplete is context-aware and won't interfere when typing brackets or braces

## Keyboard Shortcuts

- **Ctrl+Enter / Cmd+Enter**: Execute code
- **Ctrl+S / Cmd+S**: Save current file
- **Ctrl+Shift+S / Cmd+Shift+S**: Save As (new file)
- **Ctrl+O / Cmd+O**: Open file
- **Tab**: Indent or complete code
- **Ctrl+Space**: Force show code completion
- **Escape**: Close modals

## Compatibility

NoteJS works in all modern browsers, including:

- Google Chrome
- Mozilla Firefox
- Microsoft Edge
- Safari

*Note: Native direct-to-disk saving and autosave use the standard File System Access API (supported in Chrome, Edge, Opera). In browsers without File System Access API, fallback download and file reading are seamlessly provided.*

## Project Ethos

NoteJS embraces the philosophy that the best tools are the simplest ones.
Inspired by the humble sticky note or scrap paper, NoteJS provides just enough functionality
to be useful without the complexity and overhead of larger development environments.

The entire application is built with vanilla JavaScript - no frameworks, no build systems, no package managers. This keeps the tool lightweight, portable, and focused on its core purpose: quickly testing code snippets.

## Future Plans

Will always maintain the simplicity of a single HTML file, no matter how large it might get,

Future enhancements may include:

- Multiple tabs for working on several snippets
- Enhanced console output with interactive objects
- Find/Replace functionality
- Wider choice of themes
- Customizable keyboard shortcuts
- Localization
- Other language support (Python, Go, etc.)

## License

MIT License - feel free to use, modify, and distribute as you see fit.

## Acknowledgments

- Inspired by browser developer tools and the simplicity of paper notes
- Uses [CodeMirror](https://codemirror.net/) for editor functionality (loaded via CDN)
