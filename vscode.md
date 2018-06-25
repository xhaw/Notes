# VS Code

## Useful Shortcuts

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

- Toggle panel: <kbd>⌘</kbd><kbd>j</kbd>

### File navigation:

- Focus on file explorer: <kbd>⌘</kbd><kbd>e</kbd> 

```json
{
  "key": "cmd+e",
  "command": "workbench.files.action.focusFilesExplorer"
}
```

- Then use arrow keys or hjkl to navigate
