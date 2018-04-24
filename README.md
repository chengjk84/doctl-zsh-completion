# doctl-zsh-completion
ZSH completion for DigitalOcean CI (doctl)

# Dependencies
- 'zsh'
- 'oh-my-zsh'
- 'doctl'

# Installation using On-my-ZSH
Clone thise repository under current workspace
```bash
  git clone https://github.com/chengjk84/doctl-zsh-completion
  cd ./doctl-zsh-completion
  cp -r ./doctl  ~/.oh-my-zsh/custom/plugins/
```
Load the plugin on `.zshrc`
```bash
  plugins+=(doctl)
```
Restart your terminal emulator or source the `.zshrc` file
```bash
source ~/.zshrc
```
