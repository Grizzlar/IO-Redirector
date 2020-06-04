# IO Redirector
A simple C program for redirecting a file's content, a command's output or user input to another program

Usage:<br>
  ./redirect | \<program\>
  
- Redirecting a command's output: type the command after a dollar sign. (ex: $echo -n hi)<br>
- Redirecting a file's content: type the file's address after a hashtag. (ex: #/home/user/file.txt)<br>
- Redirecting your input: If your input __starts with__ #, $ or \ you must escape the symbol using a backslash (\\) other than that no special work is required.