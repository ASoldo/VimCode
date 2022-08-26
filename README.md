# VimCode
Vim VS Code remaps
Paste to VS Code -> Users/User/AppData/Roaming/Code/User/settings.json

```json
"vim.commandLineModeKeyBindings": [    
],
"vim.useCtrlKeys": true,
"vim.normalModeKeyBindingsNonRecursive": [
{
"before": ["u"],
"commands": ["undo"]
},
{
"before": ["<C-r>"],
"commands": ["redo"]
}
],
"vim.handleKeys": {
  "<C-d>": true,
  "<C-c>": false,
  "<C-v>": false,
  "<C-x>": false,
  "<C-a>": false,
  "<C-q>": false,
  "<C-k>": false,
  "<C-n>": false,
  "<C-w>": false,
  "<C-b>": false,
}
```
Vim Cheat Sheet:
https://vim.rtorr.com
