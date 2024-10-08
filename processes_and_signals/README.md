# Shell, processes and signals 

This repository contains scripts that perform various shell tasks related to processes and signals. Below is the list of tasks and their descriptions. 

## Task 0: This script displays its own Process ID (PID) when executed.

## Task 1: This script displays a list of all currently running processes for all users, including processes that might not have a TTY, in a user-oriented format, showing the process hierarchy.

## Task 2: This script displays lines containing the word 'bash' from the list of processes, helping to identify the PID of Bash processes.

## Task 3: This script displays the PID and process name of all processes whose name contains 'bash'.

## Task 4: This script displays the message "To infinity and beyond" indefinitely with a 2-second delay between each iteration.

## Task 5: This script stops the process running "4-to_infinity_and_beyond" by killing it using the PID obtained with pgrep.

## Task 6: This script stops the process running "4-to_infinity_and_beyond" by manipulating its execution state using the /proc filesystem.

## Task 7: The 7-highlander script runs indefinitely, displaying "To infinity and beyond." When it receives a SIGTERM signal, it prints "I am invincible!!!" instead of stopping. The 67-stop_me_if_you_can script sends a SIGTERM signal to the 7-highlander process, demonstrating this behavior.

## Task 8: The 8-beheaded_process script kills the 7-highlander process. It uses the pkill command with the -f option to search for the process by its name and terminate it.

## Task 9: The 10-process_and_pid_file script creates a file in /var/run/myscript.pid containing its PID and runs indefinitely. It handles signals:
- SIGTERM: Displays "I hate the kill command."
- SIGINT: Displays "Y U no love me?!"
- SIGQUIT and SIGTERM: Deletes the PID file and terminates the script.
