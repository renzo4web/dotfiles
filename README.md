# dotfiles
Vim and bash configs


### ***nvim =>  ~./.config/***
### ***.vim =>  ~./***

### :PlugInstall then :CocInstall
:CocInstall coc-eslint
eslint.showOutputChannel

:CocInstall https://github.com/dsznajder/vscode-es7-javascript-react-snippets

sudo pacman -Syu python-pip
python3 -m pip install --user --upgrade pynvim

### To avoid absulote imports

"typescript.preferences.importModuleSpecifier": "relative"

### Mac only

- external keyboard(logitech)

https://github.com/neosergio/Latam-Keyboard
