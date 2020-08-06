## Command Cheat sheet

`alias` - list your aliases

`set` - one of bashes built in functions. It has a lot of functionality (`set -x` prints the command before bash runs it. `set +x` toggles it off)

`!*` - the set of arguments that were run as part of the last command (echo !*)

`CTRL + R` - start a reverse search of your history. `CTRL + R` followed by typing "ssh" will show your most recent ssh commands. Press `CTRL + R` will scrollback in history by one step.

`CTRL + Z` - suspends a program running; type fg to resume it (useful when you want to minimize a text editor)

`man -k` OR `apropos` - search whatis database for a specific string

`>` - redirect stdout

`>>` - redirect stdout, append mode`

`2>` - redirect stderr

`&>` - redirect stderr and stdout

`tee` - mostly used in combination with pipes; you can print text to both stdout AND some file if desired `echo "test" | tee test.txt`

`$(echo "ls")` - use backticks or parenthesis for command substitution


perform multiple commands

  `command1 || command2`
  
  `command1 && command2`
  
  `command1; command2;`
  
`ln -s` - create symbolic link

`du` - prints filesize

`time` - track how long a program took to execute
  - `time sleep 2`

`who` - show which users are logged in

`w` - similar to `who` but also shows the user's activity

`df -h` - prints info about disk usage

`free` - prints memory statistics

`cal 9 2020` - displays the month of sept 2020 in a calendar format

`ps` - lists process information for your user & have a controlling terminal

`CTRL-Z` - suspends a program

`bg` - resumes the last program suspended; you can also supply the job_number 

`jobs` - lists any processes that you've sent to the background

`fg job_number` - brings the job to the foreground
