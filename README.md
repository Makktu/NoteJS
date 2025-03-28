# NoteJS

A lightweight, single-file JavaScript scratchpad for quick code testing and experimentation.

![NoteJS Screenshot](screenshot.png)

## Overview

NoteJS is a pure vanilla JavaScript scratchpad that provides a simple, distraction-free environment for testing JavaScript code snippets directly in your browser. The entire application is contained in a single HTML file with no dependencies, installation, or setup required.

## Features

- **Single HTML File**: No installation, no dependencies, just open and use
- **Two-Panel Layout**: Code editor on the left, console output on the right
- **Syntax Highlighting**: Full JavaScript syntax highlighting with Darcula theme
- **IntelliSense**: Code completion for JavaScript keywords, variables, and methods
- **Console Capture**: All console output (log, error, warn) is displayed in the output panel
- **Auto-indentation**: Proper code formatting with smart indentation
- **Keyboard Shortcuts**: Ctrl+Enter/Cmd+Enter to run, Tab for completion/indentation
- **Error Reporting**: Clear display of runtime and syntax errors
- **Dark Theme**: Easy on the eyes with a dark code editor theme

## Why NoteJS?

NoteJS was created with a few key principles in mind:

1. **Simplicity First**: No complex setup or configuration
2. **Zero Dependencies**: Works offline, no external services required
3. **Instant Feedback**: Run your code and see results immediately
4. **Distraction-Free**: Focus on your code without unnecessary features
5. **Cross-Platform**: Works on any device with a modern browser

## Usage

1. Download the single HTML file (`notejs.html`)
2. Open it in any modern browser
3. Start writing JavaScript in the left panel
4. Run your code with the Run button or Ctrl+Enter/Cmd+Enter
5. See the output in the right panel

## Code Completion

NoteJS features code completion similar to modern IDEs:

- Start typing and wait for suggestions to appear
- Press Tab or Ctrl+Space to trigger completion manually
- Navigate suggestions with arrow keys
- Press Enter to apply the selected suggestion

## Keyboard Shortcuts

- **Ctrl+Enter/Cmd+Enter**: Execute code
- **Tab**: Indent or complete code
- **Ctrl+Space**: Force show code completion

## Compatibility

NoteJS works in all modern browsers, including:

- Google Chrome
- Mozilla Firefox
- Microsoft Edge
- Safari

## Project Ethos

NoteJS embraces the philosophy that the best tools are often the simplest ones. Inspired by the humble sticky note or scrap paper, NoteJS provides just enough functionality to be useful without the complexity and overhead of larger development environments.

The entire application is built with vanilla JavaScript - no frameworks, no build systems, no package managers. This keeps the tool lightweight, portable, and focused on its core purpose: quickly testing JavaScript code.

## Limitations

- No file system access (by browser security design)
- Limited to JavaScript (TypeScript not supported in this version)
- No persistent storage (yet!)

## Future Plans

While maintaining the simplicity of a single HTML file, future enhancements may include:

- Local storage for saving snippets
- Multiple tabs for working on several snippets
- Enhanced console output with interactive objects
- Theming options
- Find/Replace functionality

## License

MIT License - feel free to use, modify, and distribute as you see fit.

## Contributing

Contributions are welcome! If you have ideas for improvements while maintaining the single-file simplicity, feel free to:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## Acknowledgments

- Inspired by browser developer tools and the simplicity of paper notes
- Uses [CodeMirror](https://codemirror.net/) for editor functionality (loaded via CDN)
