# misc

https://webinstall.dev

https://registry.npmmirror.com/binary.html

https://help.mirrorz.org

# ohmyzsh

Link: https://ohmyz.sh/
Github: https://github.com/ohmyzsh/ohmyzsh

```bash
# macos 自带 zsh

# archlinux
paru -S zsh

# setup
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

`~/.zshrc` 配置

```bash
# ignore this
ZSH_THEME="robbyrussell"
plugins=(zsh-syntax-highlighting zsh-autosuggestions zsh-completions)
```

# zoxide

Github: https://github.com/ajeetdsouza/zoxide

```bash
# macos
brew install zoxide
# archlinux
paru -S zoxide

# webinstall
curl -sS https://webi.sh/zoxide | sh
```

`~/.zshrc` 配置

```bash
eval "$(zoxide init zsh)"
```

# starship

Link: https://starship.rs
Github: https://github.com/starship/starship

```bash
curl -sS https://starship.rs/install.sh | sh

# macos
brew install starship
# archlinux
paru -S starship
```

`~/.zshrc` 配置

```bash
eval "$(starship init zsh)"
```

# mcfly

> ctrl+r 神器

Github: https://github.com/cantino/mcfly

```bash
# macos
brew install mcfly
# archlinux
paru -S mcfly
```

`~/.zshrc` 配置

```bash
eval "$(mcfly init zsh)"
```

# lazygit

Github: https://github.com/jesseduffield/lazygit

```bash
# macos
brew install lazygit
# archlinux
paru -S lazygit
```

# github-desktop

Github: https://github.com/desktop/desktop

```bash
# macos
brew install github
# archlinux
paru -S github-desktop-bin
```

# tokei

Github: https://github.com/XAMPPRocky/tokei

```bash
# macos
brew install tokei
# archlinux
paru -S tokei
```

# onefetch

Github: https://github.com/o2sh/onefetch

```bash
# macos
brew install onefetch
# archlinux
paru -S onefetch
```

# bat

Github: https://github.com/sharkdp/bat

```bash
# macos
brew install bat
# archlinux
paru -S bat 
```

`~/.zshrc` 配置

```bash
alias cat=bat
```

# exa

Github: https://github.com/ogham/exa

```bash
# macos
brew install exa
# archlinux
paru -S exa
```

`~/.zshrc` 配置

```bash
alias ls="exa --icons --sort type -a --git"
alias ll="exa --icons --long --sort type -a --git"
alias tree="exa --icons --git -a --tree -s type -I '.git|node_modules|bower_components'"
```

# yazi

Link: https://yazi-rs.github.io
Github: https://github.com/sxyazi/yazi

```bash
# macos
brew install yazi ffmpegthumbnailer unar jq poppler fd ripgrep fzf zoxide
brew tap homebrew/cask-fonts && brew install --cask font-symbols-only-nerd-font
brew install yazi --HEAD

# archlinux
paru -S yazi-git ffmpegthumbnailer unarchiver jq poppler fd ripgrep fzf zoxide
```

`~/.zshrc` 配置

```bash
alias x=yazi
```

# nvm

Github: https://github.com/nvm-sh/nvm

```bash
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.7/install.sh | bash
```

`~/.zshrc` 配置

```bash
export NVM_DIR="$([ -z "${XDG_CONFIG_HOME-}" ] && printf %s "${HOME}/.nvm" || printf %s "${XDG_CONFIG_HOME}/nvm")"
[ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh" # This loads nvm
```

# bun

Link: https://bun.sh
Github: https://github.com/oven-sh/bun

```bash
curl -fsSL https://bun.sh/install | bash
```

# carapace

Link: https://rsteube.github.io/carapace-bin
Github: https://github.com/rsteube/carapace-bin

```bash
# macos
brew tap rsteube/homebrew-tap
brew install rsteube/tap/carapace
# archlinux
paru -S carapace-bin
```

`~/.zshrc` 配置

```bash
zstyle ':completion:*' format $'\e[2;37mCompleting %d\e[m'
source <(carapace _carapace)
```

# jless

Link: https://jless.io
Github: https://github.com/PaulJuliusMartinez/jless

```bash
# macos
brew install jless
# arch
paru -S jless
```

`~/.zshrc` 配置

```bash
# fx = https://github.com/antonmedv/fx
alias fx="jless"
```

# pbcopy & pbpaste

> ohmyzsh: https://github.com/ohmyzsh/ohmyzsh/blob/master/lib/clipboard.zsh

```bash
alias pbcopy=clipcopy
alias pbpaste=clippaste
```

# ouch

> 支持多种格式的压缩解压工具

Github: https://github.com/ouch-org/ouch

```bash
# macos
cargo install ouch # homebrew 目前官方好像没有

# archlinux
paru -S ouch
```

`~/.zshrc` 配置

```bash
alias ox=ouch
```

# ripgrep

Github: https://github.com/BurntSushi/ripgrep

```bash
# macos
brew install ripgrep
# archlinux
brew install ripgpre
```

# igrep

Github: https://github.com/konradsz/igrep

```bash
# macos
brew tap konradsz/igrep https://github.com/konradsz/igrep.git
brew install igrep
# archlinux
paru -S igrep
```

# fd

Github: https://github.com/sharkdp/fd

```bash
# macos
brew install fd
# archlinux
paru -S fd
```

# paru

Github: https://github.com/Morganamilo/paru

```bash
sudo pacman -S paru
```

# tspin

> 看日志神器

Github: https://github.com/bensadeh/tailspin

```bash
# macos
brew install tailspin
# archlinux
paru -S tailspin
```

# xh

> curl/httpie 替代品

Github: https://github.com/ducaale/xh

```bash
# macos
brew install xh
# archlinux
paru -S xh
```

# hyperfine

Github: https://github.com/sharkdp/hyperfine

```bash
# macos
brew install hyperfine
# archlinux
paru -S hyperfine
```
