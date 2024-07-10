
## ~/.zshrc

alias ll="ls -la"

# give the prompt cool coloring
PROMPT=$'%{$GREEN_BOLD%}%n\|$(tput setaf 31)\%@\%{$RED%}@\$(tput setaf 245)\%m%{$WHITE%}:%{$YELLOW%}%~%u$(parse_git_dirty)$(git_prompt_ahead)%{$RESET_COLOR%}
%{$BLUE%}>%{$RESET_COLOR%}'

* michaelprovenzano| 2:29PM@michaels-mbp:~


export ZSH="$HOME/.oh-my-zsh"
