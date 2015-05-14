#==============================================================
# => Bash History
#
# Make bash history more inuitive, and overall easier to use
#==============================================================

# I Want my history to last forever and sync wether or not I log out
# http://unix.stackexchange.com/questions/1288/preserve-bash-history-in-multiple-terminal-windows
export HISTFILESIZE=1000000000
export HISTSIZE=$HISTFILESIZE
export HISTCONTROL=ignoredups:erasedups

# append history entries right away
shopt -s histappend
export HISTTIMEFORMAT="%m/%d/%y %T " # Save history timestamps
export PROMPT_COMMAND="history -a;$PROMPT_COMMAND"
