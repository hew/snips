# js-snippets (wip)

Basic JS snippets.

## Installation

For VS Code: 

* **Not published to vs-code marketplace yet**.

For Vim: 

* `Plug 'neoclide/coc.nvim'`
* `:CocInstall https://github.com/hew/js-snippets.git#master`
* `:so %MYVIMRC`

## Snippets

|  Trigger  | Content       |
| -------:  | ------------- |
|  `cl→`    | console.log   |
|  `f→`     | arrow func    |
|  `b→`     | braces        |
|  `ct→`    | catch         |


## Settings

The `editor.snippetSuggestions` setting in vscode `settings.json` will show snippets on top of the suggestion list.

```json
"editor.snippetSuggestions": "top"
```

## Credits

- Thanks to [andys8](https://github.com/andys8) for [vscode-jest-snippets](https://github.com/andys8/vscode-jest-snippets)
