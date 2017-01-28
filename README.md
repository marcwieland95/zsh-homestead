# zsh-homestead
This is just a simple helper function according to the documentation on [Laravel Homestead](https://laravel.com/docs/5.4/homestead).
Run commands like homestead up or  homestead ssh from anywhere on your system.

## Installation:
Clone homestead-plugin into `~/.oh-my-zsh/plugins/` with the name homestead.
```
cd ~/.oh-my-zsh/plugins
git clone git@github.com:marcwieland95/zsh-homestead.git homestead
```

Add homestead to the plugins array inside `~/.zshrc`.
```
open -t ~/.zshrc
plugins=(git homestead)
```
