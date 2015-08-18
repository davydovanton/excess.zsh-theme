# excess.zsh-theme
Simpe oh-my-zsh theme

![screenshot](https://raw.githubusercontent.com/davydovanton/excess.zsh-theme/master/themescreen.jpg)

## How to install

### Antigen

Add `antigen bundle davydovanton/excess.zsh-theme` to your `.zshrc`

### oh-my-zsh
Right now oh-my-zsh is not [adding more themes to the repo](https://github.com/robbyrussell/oh-my-zsh#dont-send-us-your-theme-for-now) so you'll have to:

1. Download the theme into oh-my-zsh's custom themes directory:`$ mkdir -p $ZSH_CUSTOM/themes && curl https://raw.githubusercontent.com/davydovanton/excess.zsh-theme/master/excess.zsh-theme -o $ZSH_CUSTOM/themes/excess.zsh-theme`
2. Set the theme in your .zshrc file: `ZSH_THEME="excess"`

### Zgen

Add `zgen load davydovanton/excess.zsh-theme` to your `.zshrc` with your other plugins and do a `zgen save`
