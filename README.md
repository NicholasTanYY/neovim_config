# Neovim configuration

This repo consists of the neovim configuration I am using. It follows the tutorial as shown in [this](https://www.youtube.com/playlist?list=PLsz00TDipIffreIaUNk64KxTIkQaGguqn) Youtube course.

## Shortcuts

- `<C-n>` opens the file tree to the left
- `<leader>fg` opens the global fuzzy finder (basically global ctrl f)
- `<C-p>` opens a fuzzy search for files names
- `<leader>gp` opens a preview of the changes registered by git in the hunk format
- `<leader>gt` shows who changed that when the cursor hovers over it

## Adding more plugins

Add more plugins to the table by adding each plugin to the plugins folder with the appropriate format.
By default, nvim compiles all the plugins from the plugins folder into a lua table.