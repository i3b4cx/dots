# Published Configuration and Dotfiles Repository
---

### To install dots simply run:
```
cd
mkdir -p github && cd github
git clone git@github.com:i3b4cx/dots.git
cd dots
git submodule init
git submodule update .config/nvim
cp -rf .config/nvim ~/.config/nvim
cp .tmux.conf ~/.tmux.conf
```
