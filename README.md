### Mac?
1. Download iTerm2, VScode
2. Install zsh
    - Change theme to 'agnoster'
    - Install plugins: 'zsh-autosuggestions', 'zsh-syntax-highlighting' (and update .zshrc)
    - `cd ~/.oh-my-zsh/custom/plugins`
      - `git clone https://github.com/zsh-users/zsh-syntax-highlighting.git`
      - `git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions`
3. Install gogh theme #49
    - https://mayccoll.github.io/Gogh/ (`bash -c  "$(curl -sLo- https://git.io/vQgMr)" `)
4. Install powerline fonts
    - git clone https://github.com/powerline/fonts.git && cd fonts && ./install.sh
5. Update iTerm2 color and font (Meslo LG L DZ for Powerline)
6. Install brew
    - Install `python`, `go`
