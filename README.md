# Neovim configuration

This repo consists of the neovim configuration I am using. It follows the tutorial as shown in [this](https://www.youtube.com/playlist?list=PLsz00TDipIffreIaUNk64KxTIkQaGguqn) Youtube course.

## Shortcuts

- `<C-n>` opens the file tree to the left
- `<leader>fg` opens the global fuzzy finder (basically global ctrl f)
- `<C-p>` opens a fuzzy search for files names
- `<leader>gp` opens a preview of the changes registered by git in the hunk format
- `<leader>gt` shows who changed that when the cursor hovers over it
- `<leader>gd` shows the definition of the method with documentation
- `<leader>ca` execute code actions if there is a mistake found in the code
- `<leader>gr` shows the references
- `<C-w-w>` or `<C-w-{arrow_key}>` to change focus panes  

## More commands

- (All commands that work with git, just replace `git` with `:Git`)
- `:sp <path_to_file>` opens the file in a split window

## Adding more plugins

Add more plugins to the table by adding each plugin to the plugins folder with the appropriate format.
By default, nvim compiles all the plugins from the plugins folder into a lua table.
