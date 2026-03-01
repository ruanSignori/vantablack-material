# Vantablack Material Dark

A VSCode theme that combines the ultra-dark background from Vantablack with the syntax highlighting colors from Material Dark.

## Preview

- **Background**: Vantablack-inspired dark theme (`#0d0d0d`)
- **Syntax Colors**: Material Dark style

| Element | Color |
|---------|-------|
| Functions | `#DCDCAA` (Yellow) |
| Types/Classes | `#4EC9B0` (Teal) |
| Control Keywords | `#C586C0` (Purple) |
| Variables | `#9CDCFE` (Light Blue) |
| Strings | `#CE9178` (Orange) |
| Numbers | `#569cd6` (Blue) |

## Installation

1. Clone this repository
2. Copy to VS Code extensions folder:
   - Windows: `%USERPROFILE%\.vscode\extensions`
   - Mac/Linux: `~/.vscode/extensions`
3. Restart VS Code
4. Select "Vantablack Material Dark" from File > Preferences > Color Theme

## Publishing to Marketplace

```bash
npm install -g vsce
vsce package
vsce publish
```

## License

MIT
