# Squam for Visual Studio Code

Syntax highlighting for the [Squam](https://squ.am) programming language.

## Features

- Syntax highlighting for `.squ` files
- Bracket matching and auto-closing
- Comment toggling (`//` and `/* */`)
- Code folding

## Installation

### From VSIX (local)

1. Package the extension:
   ```bash
   cd vsc
   npx vsce package
   ```

2. Install in VS Code:
   - Open Command Palette (`Cmd+Shift+P`)
   - Run "Extensions: Install from VSIX..."
   - Select the generated `.vsix` file

### Development

1. Open the `vsc` folder in VS Code
2. Press `F5` to launch Extension Development Host
3. Open a `.squ` file to test syntax highlighting

## License

MIT
