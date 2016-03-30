# VimIDE
This is the .vimrc and .vim directories I use in my development. They are an assortment of plugins and configurations that accomplish the following:

Color coding
Mouse support
Smart open (Ctrl-p, then type filename)
Function list (F4)
Directory tree (F5)
Multiple tabs (Ctrl-t when opening a file to open in new tab)
Variable definition jumps (Ctrl-])
Find in files (\vv on name you want to find, or ":Grep <name>")
Smart commenting ("gcc" on line you want to comment)
Autocomplete (tab when typing in variable)
Compare functionality (vimdiff <file1> <file2> from command prompt)

Make sure to install exuberant ctags to get the full benefit. Tags are generated on every save, so you do not have to worry about generating the tags file yourself.

The plugins were initially assembled for C, though I have used it for other development as well.
