## Files
.vim
    directory of file type configurations and plugins
.vimrc
    my vim configuration
.screenrc
    my screen configuration
.weechat
    my configuration for weechat, a great irc client
.gimp
    my tweaks/additions to gimp (fonts, brushes, etc)

## Instructions
### Creating source files
Any file which matches the shell glob `_*` will be linked into `$HOME` as a symlink with the first `_`  replaced with a `.`

For example:

    _bashrc

becomes

    ${HOME}/.bashrc

### Installing source files
It's as simple as running:

    ./install.sh

From this top-level directory.


## Requirements
* zsh

## Recommendation

### ZSH
Swicth your shell to `zsh`, then you will get `zgen` and `oh-my-zsh`, zgen helps you to manage themes, auto-completion and install them automatically when you load `zsh`
    chsh -s /bin/zsh

### Git
Git config, Very Important in `_gitconfig`
Change the `user.name` `user.email`  to yours 


### Theme

Edit `_zshrc`

```sh
    # zgen oh-my-zsh themes/arrow  
    zgen load caiogondim/bullet-train-oh-my-zsh-theme bullet-train 
```

### Font Settings
My current theme `bullet-train` needs powerline-font which are installed when you run `install.sh`
Open your Terminal preferances and choose a font name which contains `powerline`

### Mac users
    
* Install homebrew http://brew.sh
* brew install coreutils. 


    




