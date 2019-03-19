## FunkyBerlin ZSH theme

![FunkyBerlin](https://raw.githubusercontent.com/Ottootto2010/funkyberlin-zsh-theme/master/showcase.png)

A colorfull two-line theme with support for GIT and SVN.

Add the theme to ~/.oh-my-zsh/themes

Overriding and adding themes
Adding and customizing your own themes pretty much works the same as with plugins.

Themes are located in a themes folder and must end with .zsh-theme. The basename of the file is the name of the theme.

zsh_custom
└── themes
    └── my_awesome_theme.zsh-theme
Then edit your .zshrc to use that theme.

ZSH_THEME="my_awesome_theme"
Remember that customizations always take precedence over built-ins. If you happen to enjoy a particular theme that comes packaged with oh-my-zsh, but would like to change just a little detail inside of it – let's say you love the agnoster theme, it will be the easiest to copy the agnoster.zsh-theme file to your custom/themes directory and customize it.

If you don't change its filename, your .zshrc file can stay the same: ZSH_THEME="agnoster" will be perfect and still take your changes into account. You might also want to consider this before filing a new issue or pull request that just changes a trivial detail inside of a built-in theme.

