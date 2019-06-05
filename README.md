# PSU_42sh_2028
Recreating a shell based on the tcsh

to use it : 
Make re + ./42sh
and then use it like a shell

to use bonuses : 
You must untar the .tar in the bonus directory
type tar -xvf bonus.tar
make re + ./42sh

Description :
Parsing with a tokenizer

Builtins : 
cd : Change the current working directory
env : display the env
setenv : set a new env variable or change an existing one
unsetenv : remove one or more variable from the env
yes : loop and display y or the given args
echo : display the given arguments
exit : exit the shell with the give return value
alias : display aliases or add a new one for a command
unalias : remove one or more aliases
where : display all known instances of the given command
which : display the path used by the shell to do the given command
whoami : display username
builtins : display all shell builtins
set : display local env
unset : unset one or more local variables
repeat : repeat the given command N times

Game in bonus part: 
Tictatoe by typing tictactoe
Snake by typing snake
Correct price by typing correct_price
