# VS Code

## Shortcuts

### Terminal

- Toggle terminal: <kbd>⌃</kbd><kbd>`</kbd>
- Switch focus between active editor group and terminal: <kbd>⌃</kbd><kbd>`</kbd>

add to keyboard shortcut file:

```json
{
  "key": "ctrl+`",
  "command": "workbench.action.terminal.focus",
  "when": "!terminalFocus"
},
{
  "key": "ctrl+`",
  "command": "workbench.action.focusActiveEditorGroup",
  "when": "terminalFocus"
}
```

- Toggle panel: <kbd>⌘</kbd><kbd>j<kbd>
