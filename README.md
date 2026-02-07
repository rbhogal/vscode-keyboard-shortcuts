![banner](images/MelGeek-Mojo68-Plastic-Advance-65.webp)

# VS Code Keyboard Shortcuts

A quick reference guide for the most useful Visual Studio Code keyboard shortcuts on Mac and Windows.

## Navigation & Search

| Action | Mac | Windows |
|--------|-----|---------|
| Command Palette | `Cmd+Shift+P` | `Ctrl+Shift+P` |
| Quick Open (Go to File) | `Cmd+P` | `Ctrl+P` |
| Find | `Cmd+F` | `Ctrl+F` |

## Editing

| Action | Mac | Windows |
|--------|-----|---------|
| Undo | `Cmd+Z` | `Ctrl+Z` |
| Redo | `Cmd+Shift+Z` | `Ctrl+Y` or `Ctrl+Shift+Z` |
| Multi-cursor | `Cmd+Option+Down/Up` | `Ctrl+Alt+Down/Up` |
| Add Cursor to Selection | `Cmd+D` | `Ctrl+D` |
| Select All Occurrences | `Cmd+Shift+L` | `Ctrl+Shift+L` |
| Move Line Up/Down | `Option+Up/Down` | `Alt+Up/Down` |
| Duplicate Line Up/Down | `Shift+Option+Up/Down` | `Shift+Alt+Up/Down` |
| Jump to Start/End of Line | `Cmd+Left/Right` | `Home/End` |
| Jump to Start/End of Word | `Option+Left/Right` | `Ctrl+Left/Right` |
| Toggle Line Comment | `Cmd+/` | `Ctrl+/` |
| Toggle Block Comment | `Shift+Option+A` | `Shift+Alt+A` |
| Add Line Comment | `Cmd+K Cmd+C` | `Ctrl+K Ctrl+C` |
| Remove Line Comment | `Cmd+K Cmd+U` | `Ctrl+K Ctrl+U` |

## Display & Layout

| Action | Mac | Windows |
|--------|-----|---------|
| Toggle Sidebar | `Cmd+B` | `Ctrl+B` |
| Toggle Terminal | `Cmd+J` | `Ctrl+J` |
| Zoom In/Out | `Cmd+=/−` | `Ctrl+=/−` |

## File Management

| Action | Mac | Windows |
|--------|-----|---------|
| Save | `Cmd+S` | `Ctrl+S` |

## Code Intelligence

| Action | Mac | Windows |
|--------|-----|---------|
| Trigger Suggest | `Cmd+Space` | `Ctrl+Space` |
| Go to Definition | `F12` | `F12` |
| Peek Definition | `Option+F12` | `Alt+F12` |

## Commenting

| Action | Mac | Windows | Notes |
|--------|-----|---------|-------|
| Toggle Line Comment | `Cmd+/` | `Ctrl+/` | Comments/uncomments selected lines with `//` (or language equivalent) |
| Toggle Block Comment | `Shift+Option+A` | `Shift+Alt+A` | Wraps selection in `/* */` (or language equivalent) |
| Add Line Comment | `Cmd+K Cmd+C` | `Ctrl+K Ctrl+C` | Always adds comments, even if already commented |
| Remove Line Comment | `Cmd+K Cmd+U` | `Ctrl+K Ctrl+U` | Always removes comments |

**How to comment multiple lines:**
1. Select the lines you want to comment
2. Press `Cmd+/` (Mac) or `Ctrl+/` (Windows) to toggle line comments
3. Or use `Shift+Option+A` (Mac) / `Shift+Alt+A` (Windows) for block comments

## Tips

- **Command Palette** (`Cmd+Shift+P` / `Ctrl+Shift+P`) is your best friend - you can access almost any VS Code feature from here
- Use **Quick Open** (`Cmd+P` / `Ctrl+P`) and type `@` to go to symbols, or `:` to go to a line number
- Multi-cursor editing is extremely powerful for refactoring and batch edits
- Learn the difference between **Go to Definition** (F12) and **Peek Definition** (Alt/Option+F12) for different workflows

### Multi-Cursor Selection Tips

**Add Cursor to Selection** (`Cmd+D` / `Ctrl+D`):
1. Place cursor on a word or select text
2. Press `Cmd+D` - selects the word and finds next occurrence
3. Press `Cmd+D` again - adds cursor at next occurrence
4. Keep pressing to add more cursors one-by-one
5. Edit all instances simultaneously

**Select All Occurrences** (`Cmd+Shift+L` / `Ctrl+Shift+L`):
- Select a word or text
- Press `Cmd+Shift+L` to instantly add cursors at ALL occurrences
- Use this when you want to change every instance at once

**Example:**
```javascript
const name = "John";
console.log(name);
alert(name);
```
Put cursor on `name`, press `Cmd+D` three times (or `Cmd+Shift+L` once) to edit all instances together.

## Customization

You can view and customize all keyboard shortcuts in VS Code:
- Mac: `Cmd+K Cmd+S`
- Windows: `Ctrl+K Ctrl+S`

---

*For a complete list of shortcuts, visit [VSCode keyboard shortcuts for macOS](https://code.visualstudio.com/shortcuts/keyboard-shortcuts-macos.pdf).*

*For a complete list of shortcuts, visit [VSCode keyboard shortcuts for Windows](https://code.visualstudio.com/shortcuts/keyboard-shortcuts-windows.pdf).*
