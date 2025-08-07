My repository with tmux configuration info.

Not sure if cloning this directly will work the same way as with the neovim config: it seems some of these directories resist being uploaded to the repo? Anyway, it's not hard to replicate, since my tmux config is quite basic, and based almost entirely on this [video](https://www.youtube.com/watch?v=GH3kpsbbERo). It will take you from installation through basic use and recommended plugins. 

Among the most useful plugins described in that video is tmux-catppuccin, which really brings together the look of the terminal in combination with a catppuccin theme for Neovim. It also includes a very nice-looking upper status bar which nicely complements a Neovim lualine. 

I also personally recommend changing the default tmux prefix from Ctrl+B to something friendlier. Personally, I use Ctrl+J, which makes switching windows nice and fluid. Other useful changes mentioned in the video include indexing windows from 1 instead of 0 and allowing navigation in terminal output using Vim motions. 

Make sure to take tmux.conf and move it to outside the .tmux repository! 

