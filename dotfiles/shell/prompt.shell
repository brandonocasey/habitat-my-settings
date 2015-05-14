#==============================================================
# => Bash Prompt
#
# Make your bash prompt look awesome, and make its colors
# differ if you are the root user
#==============================================================

# Fancy Shell
if [ $(id -u) -ne 0 ]; then
    COLOR_TWO=$LIGHT_BLUE
    COLOR_THREE=$GREY
    COLOR_FOUR=$CYAN
    COLOR_FIVE=$LIGHT_BLUE
else
    COLOR_TWO=$RED
    COLOR_THREE=$ORANGE
    COLOR_FOUR=$YELLOW
    COLOR_FIVE=$BROWN
fi


PS1=""
# Smiley face
PS1+="\`if [ \$? = 0 ]; then echo '\[${LIGHT_BLUE}\]:)\[${RESET}\]'; else echo '\[${RED}\]:(\[${RESET}\]'; fi\`"
PS1+="\[${WHITE}\]"             # Start the white color
PS1+=" \T "                        # Time
PS1+="\[${COLOR_THREE}\]"       # Start Color Three
PS1+="\u"                          # User
PS1+="\[${WHITE}\]"             # Start Color White
PS1+="@"                           # Just an at symbol
PS1+="\[${COLOR_FOUR}\]"        # Start Color 4
PS1+="\h"                          # Current hostname
PS1+="\[${WHITE}\]"             # Start Color White
PS1+=":"                           # colon
PS1+="\[${WHITE}\]"            # Start Color White
PS1+="\w"                         # Full pwd (working directory)
PS1+="\[${WHITE}\]"            # Start Color White
PS1+="\[${RESET}\]"            # Reset Color
PS1+="\n"                          # New Line
PS1+="\[${COLOR_FIVE}\]"        # Color five
PS1+="\$"                          # dollar character
PS1+="\[${RESET}\]"             # Reset color
PS1+=" "                           # space
