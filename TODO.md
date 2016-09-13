* NERDTree folder sidebar
* switch between windows & splits
* findout why shell scripts turn weird colors sometimes...
* write a find_replace binary
	* exclude
* investigate these vim plugins:
	* https://github.com/jiangmiao/auto-pairs vs delimate
	* https://github.com/airblade/vim-gitgutter
	* https://github.com/Shougo/neocomplete.vim
	* https://github.com/SirVer/ultisnips
* only use osxkeychain on osx git config
* create neovim plugin
* add deps
	* pip3 install neovim
	* python3
	* git-extras
* update habitat to use bpkg
* update habitat to have plugin hooks
	* pre.habit
	* main.habit
	* post.habit
	* cmd.habit
	* etc!
* include time in debug output
* use callbacks
	* habitat_update_settings calls the next step in the process
	* which has a callback to the next step, and so on
* do this http://stackoverflow.com/questions/5698284/in-my-vimrc-how-can-i-check-for-the-existence-of-a-color-scheme
* differnt current search term highlight vim
* make vimman better (no vim flash before use)
* add a fn to change CWD on login
* add an alias to refer to $HOME/Projects
* find the bash command that fixes the previous command, think it was a swear word
* keybind
	To delete a line without sticking it in the registers:
	"_dd
* integrate with NVM

# New habitat
* update_settings <cb> -> run "pre" <cb> -> run "main" <cb> -> run "post" <cb> -> cleanup <cb>

