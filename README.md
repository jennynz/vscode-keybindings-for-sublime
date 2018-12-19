# VS Code keymaps for Sublime Text

This repo lists some of the more popular VS Code keymaps that you may wish to use in Sublime Text 3.

There are a lot of [Sublime-to-VSCode keymap packages](https://marketplace.visualstudio.com/items?itemName=ms-vscode.sublime-keybindings) out there, but there don't seem to be any going the other way. I use VS Code most of the time, but I also use the [Zettelklasten method](https://zettelkasten.de/) for note-taking, and [this Sublime Text extension](https://github.com/renerocksai/sublime_zk) has been the best tool that I've found that it. I prefer VS Code as a text editor, so I want to stay familiar with their main key bindings while being able to use this Zettelklasten Sublime plugin.

I've picked and chosen the key bindings which I use the most, so if you have any other key bindings you'd like to recommend, please raise an issue.

## Installation

### Key bindings

1. Copy the key bindings from the `*.sublime-keymap` file that suits your operating system.
2. Open `Preferences` > `Key Bindings`.
3. Paste the key bindings into `Default (*).sublime-keymap - User`

### Settings

This is just to turn on the `shift_tab_unindent` setting, which is set to `false` by default on Sublime Text.

1. Copy the setting from [Preferences.sublime-settings](Preferences.sublime-settings).
2. Open `Preferences` > `Settings`.
3. Paste the setting into `Preferences.sublime-settings - User`

I would also recommend installing [MoveTab](https://github.com/SublimeText/MoveTab) and [GotoTab](https://github.com/SublimeText/GotoTab) packages for Chrome-like behaviour. You can do this via Package Control (`ctrl+shift+p` > `Package Control: Install Package` and search `MoveTab` and `GotoTab`).

## Usage

Only the key bindings for Windows have been tested. Please raise an issue or submit a pull request if any of these aren't working on Linux or OSX.

### Windows & Linux

- `ctrl+shift+l`: Select all instances of the current selection in file (`find_all_under`)
- `ctrl+f2`: Select all instances of the current selection in file (`find_all_under`)
	+ N.B. The default keymap for Sublime Text already allows `ctrl+d` to expand the selection to include the current selection's next occurrence.
- `alt+shift+i`: Split a multi-line selection into multiple lines (`split_selection_into_lines`)
- `ctrl+b`: Toggle the sidebar (`toggle_side_bar`)
- `ctrl+shift+b`: Build project (`build`)
- `alt+up`: `swap_line_up`
- `alt+down`: `swap_line_down`
- `shift+tab`: unindent line regardless of cursor position in line (`shift_tab_unindent` setting set to `true`)

### OSX

- `ctrl+super+g`: Select all instances of the current selection in file (`find_all_under`)
- `super+f2`: Select all instances of the current selection in file (`find_all_under`)
	+ N.B. The default keymap for Sublime Text already allows `super+d` to expand the selection to include the current selection's next occurrence.
- `super+alt+l`: Split a multi-line selection into multiple lines (`split_selection_into_lines`)
- `super+b`: Toggle the sidebar (`toggle_side_bar`)
- `super+shift+b`: Build project (`build`)
- `alt+up`: `swap_line_up`
- `alt+down`: `swap_line_down`
- `shift+tab`: unindent line regardless of cursor position in line (`shift_tab_unindent` setting set to `true`)