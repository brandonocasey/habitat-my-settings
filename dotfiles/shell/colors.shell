#==============================================================
# => Bash Colors
#
# Make bash more colorsful through several exports, which will
# be helpful should we need them in later scripts
#==============================================================

if ! is_installed "dircolors"; then
    # Colors on Mac
    export LSCOLORS=GxFxCxDxBxegedabagaced
else
    eval $(dircolors -b $HOME/.dircolors)
fi


export CLICOLOR=1
# Always color grep
export GREP_OPTIONS='--color=auto'


