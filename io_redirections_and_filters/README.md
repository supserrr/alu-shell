# Shell, I/O Redirections and Filters

## Task 0: Hello World
A script that prints “Hello, World”, followed by a new line to the standard output.

## Task 1: Confused Smiley
A script that displays a confused smiley "(Ôo)'.

## Task 2: Let's Display a File
A script that displays the content of the /etc/passwd file.

## Task 3: What About 2?
A script that displays the content of /etc/passwd and /etc/hosts.

## Task 4: Last Lines of a File
A script that displays the last 10 lines of /etc/passwd.

## Task 5: First Lines of a File
A script that displays the first 10 lines of /etc/passwd.

## Task 6: Line #2
A script that displays the third line of the file iacta.

## Task 7: It is a good file that cuts iron without making a noise
A script that creates a file named exactly *\\'"Best School"'\\*$\?*****:) containing the text Best School ending by a new line.

## Task 8: Save current state of directory
A script that writes into the file ls_cwd_content the result of the command ls -la. If the file ls_cwd_content already exists, it should be overwritten. If the file ls_cwd_content does not exist, create it.

## Task 9: Duplicate last line
A script that duplicates the last line of the file iacta.

## Task 10: No more javascript
A script that deletes all the regular files (not the directories) with a .js extension that are present in the current directory and all its subfolders.

## Task 11: Don't just count your directories, make your directories count
A script that counts the number of directories and sub-directories in the current directory.

## Task 12: What’s new
A script that displays the 10 newest files in the current directory, one file per line, sorted from the newest to the oldest.

## Task 13: Unique Words
This script reads a list of words and prints those that appear exactly once, sorted.

## Task 14: Find That Word
This script displays lines containing the pattern "root" from the /etc/passwd file.

## Task 15: Count That Word
This script counts and displays the number of lines that contain the pattern "bin" in /etc/passwd.

## Task 16: What's Next?
This script displays lines containing the pattern "root" along with three lines after them from /etc/passwd.

## Task 17: I Hate Bins
This script displays all lines in /etc/passwd that do not contain the pattern "bin".

## Task 18: Letters Only Please
This script displays all lines of the /etc/ssh/sshd_config file starting with a letter.

## Task 19: A to Z
This script replaces all occurrences of characters 'A' with 'Z' and 'c' with 'e' from input.

## Task 20: Without C, You Would Live in Hiago
This script removes all letters 'c' and 'C' from input.

## Task 21: Pipe
This script reads the `/etc/passwd` file and extracts the usernames by using the `cat` command piped to `cut`, which splits the content on the colon `:` delimiter and retrieves the first field.

## Task 22: Sort
This script sorts the contents of the `/etc/passwd` file in reverse order using the `sort` command, allowing users to view the entries from Z to A.

## Task 23: Uniq
This script identifies and lists unique usernames from the `/etc/passwd` file. It first sorts the entries and then applies the `uniq` command to filter out duplicate usernames.

## Task 24: Grep
This script searches for the username "root" in the `/etc/passwd` file using the `grep` command. It ignores case sensitivity to ensure all variations of "root" are found.

## Task 25: Egrep
This script utilizes `egrep` to find and display occurrences of the usernames "root" and "daemon" in the `/etc/passwd` file. It uses the `-o` option to print only the matched parts of the line.
