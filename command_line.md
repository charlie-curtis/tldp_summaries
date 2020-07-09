## Command Cheat sheet

alias - list your aliases
set - one of bashes built in functions. It has a lot of functionality (set -x shows prints the command before bash runs it. set +x toggles it off)
!* - the set of arguments that were run as part of the last command (echo !*)
CTRL + R - start a reverse search of your history. CTRL + R followed by typing "ssh" will show your most recent ssh commands. Press CTRL + R will scrollback in history by one step.
CTRL + Z - suspends a program running; type fg to resume it (useful when you want to minimize a text editor)
man -k OR apropos - search whatis database for a specific string
> - redirect stdout
>> - redirect stdout, append mode
2> - redirect stderr
&> - redirect stderr and stdout
tee - mostly used in combination with pipes; you can print text to both stdout AND some file if desired echo "test" | tee test.txt

