# .zshrc
Config file for oh-my-zsh to have proper:
- terminal color coding
- synthax color coding
- history navigation in terminal
- word navigation in terminal

## Setup

Reinstall [oh-my-zsh](https://ohmyz.sh/) with the curl command, then clone the plugins for styling and history navigation.

```bash
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)" 
```

Then always source the .zshrc file to sync the shell with latest changes.

```bash
source ~/.zshrc
```

## Plugins

To install plugins, clone the plugin and then add it to the plugins array in the .zshrc file.

```bash
plugins=(git zsh-autosuggestions zsh-syntax-highlighting zsh-history-substring-search [new-plugin...])
```

Checkout the complete list of available [oh-my-zsh plugins](https://github.com/ohmyzsh/ohmyzsh/wiki/plugins).

### Synthax highlighting

```bash
git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ~/.oh-my-zsh/custom/plugins/zsh-syntax-highlighting
```

### History Substring Search

```bash
 git clone https://github.com/zsh-users/zsh-history-substring-search ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-history-substring-search
```

### Autosuggestions

```bash
git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
```
