# SnoDots NG
Algabraic, simplified, modernized dotfiles for SnoFox

## Using them
1. Install chezmoi & 1Password CLI
    * macOS: `brew install chezmoi && brew install --cask 1password-cli`
    * Linux: `sh -c "$(curl -fsLS get.chezmoi.io)" -- -b ~/.local/bin`
2. `chezmoi init git@gitlab.com/SnoFox/dotfiles.git`
3. `chezmoi diff`
4. `chezmoi apply` # if happy with the diff

# License
Unless otherwise noted in-line, see LICENSE
