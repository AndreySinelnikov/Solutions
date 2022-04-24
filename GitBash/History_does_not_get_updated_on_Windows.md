CONTEXT: 

Upon closing with X button, command history does not get saved in ~/.bash_history (typing "exit" works, but only for a given session)

SOLUTION: 

1. IN user directory, ADD _.bash_profile_ text file

2. IN  _.bash_profile_, ADD `PROMPT_COMMAND='history -a'`
