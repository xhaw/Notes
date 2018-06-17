# VS Code

## Shortcuts

### Terminal

- Toggle terminal: <kbd>⌃</kbd><kbd>`</kbd>
- Switch focus between active editor group and terminal: <kbd>⌃</kbd><kbd>`</kbd>

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
