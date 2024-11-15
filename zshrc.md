
## ~/.zshrc

export ZSH="$HOME/.oh-my-zsh"

# Set name of the theme to load --- if set to "random", it will
# load a random theme each time Oh My Zsh is loaded, in which case,
# to know which specific one was loaded, run: echo $RANDOM_THEME
# See https://github.com/ohmyzsh/ohmyzsh/wiki/Themes

ZSH_THEME="juanghurtado"

plugins=(git)


alias ll="ls -la"
alias cls="clear"
alias subl="sublime $1"


export wordlists="/usr/local/share/wordlistes"
export learning="$HOME/Desktop/sfdf/dsfdfs"

# give the prompt cool coloring
PROMPT=$'%{$GREEN_BOLD%}%n\|$(tput setaf 31)\%@\%{$RED%}@\$(tput setaf 245)\%m%{$WHITE%}:%{$YELLOW%}%~%u$(parse_git_dirty)$(git_prompt_ahead)%{$RESET_COLOR%}
%{$BLUE%}>%{$RESET_COLOR%}'

* michaelprovenzano| 2:29PM@michaels-mbp:~


export ZSH="$HOME/.oh-my-zsh"
