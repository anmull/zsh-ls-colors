# LS_COLORS for zsh

The [LS_COLORS](https://github.com/trapd00r/LS_COLORS) repository by [trapd00r](https://github.com/trapd00r) includes color mappings for hundreds of file extensions. However, due to the structure of the repository it can create conflicts with zsh plugin managers (LS_COLORS file may be sourced before ls_colors.sh).

This also removes the coreutils requirements for macOS users to build `ls_colors.sh`.

# Installation

### Plugin Managers

```
# zgen
zgen load anmull/zsh-ls-colors

# zplug
zplug anmull/zsh-ls-colors

# antigen
antigen bundle anmull/zsh-ls-colors
```

### Manual

```
git clone https://github.com/anmull/zsh-ls-colors
source "zsh-ls-colors/ls_colors.sh"
```
