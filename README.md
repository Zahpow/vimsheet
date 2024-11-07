# vimsheet
A vim cheatsheet for vim


add to .vimrc in HOME/.vimrc

nnoremap <KEY> :!less <PATH><CR> 

this command prints the  contents of vimsheet when <KEY> is pressed in normalmode. Replace <KEY> with whatever you see fit and <PATH> with the location of vimsheets.

Example:

nnoremap ^p :!cat ~/.vimsheet.txt
