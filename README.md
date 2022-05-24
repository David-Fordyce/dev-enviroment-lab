# dev-enviroment-lab
# dev-enviroment-lab
# dev-enviroment-lab
echo >> README.md
echo "## OS" >> README.md
echo >> README.md
echo $OSTYPE >> README.md
echo >> README.md
echo "## Shell" >> README.md
echo >> README.md
echo $SHELL >> README.md
echo >> README.md
echo "## zsh location" >> README.md
echo >> README.md
which zsh >> README.md
echo >> README.md
echo "## code alias" >> README.md
echo >> README.md
which code >> README.md
echo >> README.md
echo "## GitHub CLI version" >> README.md
echo >> README.md
gh --version >> README.md
echo >> README.md
echo "## npm version" >> README.md
echo >> README.md
npm --version >> README.md
echo >> README.md
echo "## node version" >> README.md
echo >> README.md
node --version >> README.md
echo >> README.md
echo "## nodemon version" >> README.md
echo >> README.md
nodemon --version >> README.md
echo >> README.md
echo "## Heroku version" >> README.md
echo >> README.md
heroku --version >> README.md
echo >> README.md
echo "## Git version" >> README.md
echo >> README.md
git --version >> README.md
echo >> README.md
echo "## Git email" >> README.md
echo >> README.md
git config --global user.email >> README.md
echo >> README.md
echo "## Git Default Branch" >> README.md
echo >> README.md
git config --global init.defaultBranch >> README.md
echo >> README.md
echo "## Git Merge Behavior" >> README.md
echo >> README.md
git config --global pull.rebase >> README.md
echo >> README.md
echo "## Global Git Ignore" >> README.md
echo >> README.md
git config --global core.excludesfile >> README.md
echo >> README.md
echo "## Contents of ~/.gitignore_global" >> README.md
echo >> README.md
cat ~/.gitignore_global >> README.md
echo >> README.md
echo "## Contents of ~/.zshrc" >> README.md
echo >> README.md
cat ~/.zshrc >> README.md


## OS

darwin21.0

## Shell

/bin/zsh

## zsh location

/bin/zsh

## code alias

code not found

## GitHub CLI version

gh version 2.10.1 (2022-05-10)
https://github.com/cli/cli/releases/tag/v2.10.1

## npm version

8.5.5

## node version

v16.15.0

## nodemon version

2.0.16

## Heroku version

heroku/7.60.2 darwin-x64 node-v14.19.0

## Git version

git version 2.36.1

## Git email

d4dyce121@gmail.com

## Git Default Branch

main

## Git Merge Behavior

false

## Global Git Ignore

/Users/davidfordyce/.gitignore_global

## Contents of ~/.gitignore_global


## Contents of ~/.zshrc

# If you come from bash you might have to change your $PATH.
# export PATH=$HOME/bin:/usr/local/bin:$PATH

# Path to your oh-my-zsh installation.
export ZSH="$HOME/.oh-my-zsh"

# Set name of the theme to load --- if set to "random", it will
# load a random theme each time oh-my-zsh is loaded, in which case,
# to know which specific one was loaded, run: echo $RANDOM_THEME
# See https://github.com/ohmyzsh/ohmyzsh/wiki/Themes
ZSH_THEME="robbyrussell"

# Set list of themes to pick from when loading at random
# Setting this variable when ZSH_THEME=random will cause zsh to load
# a theme from this variable instead of looking in $ZSH/themes/
# If set to an empty array, this variable will have no effect.
# ZSH_THEME_RANDOM_CANDIDATES=( "robbyrussell" "agnoster" )

# Uncomment the following line to use case-sensitive completion.
# CASE_SENSITIVE="true"

# Uncomment the following line to use hyphen-insensitive completion.
# Case-sensitive completion must be off. _ and - will be interchangeable.
# HYPHEN_INSENSITIVE="true"

# Uncomment one of the following lines to change the auto-update behavior
# zstyle ':omz:update' mode disabled  # disable automatic updates
# zstyle ':omz:update' mode auto      # update automatically without asking
# zstyle ':omz:update' mode reminder  # just remind me to update when it's time

# Uncomment the following line to change how often to auto-update (in days).
# zstyle ':omz:update' frequency 13

# Uncomment the following line if pasting URLs and other text is messed up.
# DISABLE_MAGIC_FUNCTIONS="true"

# Uncomment the following line to disable colors in ls.
# DISABLE_LS_COLORS="true"

# Uncomment the following line to disable auto-setting terminal title.
# DISABLE_AUTO_TITLE="true"

# Uncomment the following line to enable command auto-correction.
# ENABLE_CORRECTION="true"

# Uncomment the following line to display red dots whilst waiting for completion.
# You can also set it to another string to have that shown instead of the default red dots.
# e.g. COMPLETION_WAITING_DOTS="%F{yellow}waiting...%f"
# Caution: this setting can cause issues with multiline prompts in zsh < 5.7.1 (see #5765)
# COMPLETION_WAITING_DOTS="true"

# Uncomment the following line if you want to disable marking untracked files
# under VCS as dirty. This makes repository status check for large repositories
# much, much faster.
# DISABLE_UNTRACKED_FILES_DIRTY="true"

# Uncomment the following line if you want to change the command execution time
# stamp shown in the history command output.
# You can set one of the optional three formats:
# "mm/dd/yyyy"|"dd.mm.yyyy"|"yyyy-mm-dd"
# or set a custom format using the strftime function format specifications,
# see 'man strftime' for details.
# HIST_STAMPS="mm/dd/yyyy"

# Would you like to use another custom folder than $ZSH/custom?
# ZSH_CUSTOM=/path/to/new-custom-folder

# Which plugins would you like to load?
# Standard plugins can be found in $ZSH/plugins/
# Custom plugins may be added to $ZSH_CUSTOM/plugins/
# Example format: plugins=(rails git textmate ruby lighthouse)
# Add wisely, as too many plugins slow down shell startup.
plugins=(git)

source $ZSH/oh-my-zsh.sh

# User configuration

# export MANPATH="/usr/local/man:$MANPATH"

# You may need to manually set your language environment
# export LANG=en_US.UTF-8

# Preferred editor for local and remote sessions
# if [[ -n $SSH_CONNECTION ]]; then
#   export EDITOR='vim'
# else
#   export EDITOR='mvim'
# fi

# Compilation flags
# export ARCHFLAGS="-arch x86_64"

# Set personal aliases, overriding those provided by oh-my-zsh libs,
# plugins, and themes. Aliases can be placed here, though oh-my-zsh
# users are encouraged to define aliases within the ZSH_CUSTOM folder.
# For a full list of active aliases, run `alias`.
#
# Example aliases
# alias zshconfig="mate ~/.zshrc"
# alias ohmyzsh="mate ~/.oh-my-zsh"
