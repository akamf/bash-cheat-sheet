# bash-cheat-sheet
A cheat sheet containg some useful bash commands and explanations


# Bash Cheat Sheet

| cmd | meaning | explanation | example use |
| --- | --- | --- | --- |
| ls | list | List files and directories | `ls ~/code/projects/` |
| cd | change directory | Navigate to a different directory | `cd ~/Documents` |
| pwd | print working directory | Show the current directory path | `pwd` |
| mkdir | make directory | Create a new directory | `mkdir my_folder` |
| rmdir | remove directory | Delete an empty directory | `rmdir old_folder` |
| rm | remove | Delete a file or directory | `rm file.txt` |
| rm -r | remove recursively | Delete a directory and its contents | `rm -r my_folder` |
| cp | copy | Copy files or directories | `cp file.txt backup.txt` |
| cp -r | copy recursively | Copy directories and their contents | `cp -r dir1 dir2_backup` |
| mv | move | Move or rename a file or directory | `mv file.txt new_folder/` |
| touch | create file | Create a new empty file | `touch newfile.txt` |
| cat | concatenate | Display the contents of a file | `cat file.txt` |
| less | view file | View a file page by page | `less file.txt` |
| head | first lines | Show the first 10 lines of a file | `head file.txt` |
| tail | last lines | Show the last 10 lines of a file | `tail file.txt` |
| tail -f | follow file | View real-time updates to a file | `tail -f logfile.log` |
| echo | print text | Print text to the terminal | `echo "Hello, world!"` |
| whoami | current user | Show the current logged-in user | `whoami` |
| who | logged-in users | Show currently logged-in users | `who` |
| uname | system info | Display system information | `uname -a` |
| df | disk free | Show disk space usage | `df -h` |
| du | disk usage | Show size of files and directories | `du -sh my_folder/` |
| free | memory usage | Display memory usage | `free -m` |
| ps | process status | List running processes | `ps aux` |
| top | system monitor | Show real-time system processes | `top` |
| htop | advanced monitor | Interactive system monitor (requires install) | `htop` |
| kill | terminate process | Kill a process by ID | `kill 1234` |
| killall | kill by name | Kill all processes matching a name | `killall firefox` |
| pkill | kill by pattern | Kill processes matching a pattern | `pkill -f my_script.py` |
| grep | search text | Find text in a file | `grep "error" logfile.log` |
| find | locate files | Search for files by name | `find /home -name "*.txt"` |
| locate | locate files | Quickly find files (requires `updatedb`) | `locate myfile.txt` |
| history | command history | Show command history | `history | grep "git"` |
| alias | create shortcut | Create a shortcut for a command | `alias ll="ls -la"` |
| unalias | remove alias | Remove an alias | `unalias ll` |
| chmod | change permissions | Modify file permissions | `chmod 755 script.sh` |
| chown | change owner | Change file owner | `chown user:user file.txt` |
| ln | link files | Create a symbolic link | `ln -s original.txt link.txt` |
| tar | archive | Create/extract tar archives | `tar -cvf archive.tar my_folder/` |
| tar -xvf | extract tar | Extract a tar archive | `tar -xvf archive.tar` |
| zip | compress | Create a zip archive | `zip archive.zip file.txt` |
| unzip | extract zip | Extract files from a zip archive | `unzip archive.zip` |
| scp | secure copy | Copy files over SSH | `scp file.txt user@server:/path/` |
| rsync | sync files | Sync files between directories or remote systems | `rsync -av source/ dest/` |
| wget | download | Download files from a URL | `wget https://example.com/file.zip` |
| curl | fetch data | Retrieve data from a URL | `curl -O https://example.com/file.zip` |
| ssh | secure shell | Connect to a remote server via SSH | `ssh user@server.com` |
| exit | exit shell | Close the terminal session | `exit` |
| clear | clear screen | Clears the terminal screen | `clear` |
| env | environment variables | Show environment variables | `env` |
| export | set environment variable | Set an environment variable | `export MY_VAR="hello"` |
| unset | remove variable | Remove an environment variable | `unset MY_VAR` |
| source | run script | Execute a script in the current shell | `source script.sh` |
| bash | new shell | Start a new Bash shell | `bash` |
| crontab | schedule tasks | Edit scheduled tasks for the user | `crontab -e` |
| jobs | background jobs | Show background processes | `jobs` |
| bg | resume job | Resume a background process | `bg %1` |
| fg | foreground job | Bring a background job to the foreground | `fg %1` |
| nohup | run process | Run a command that won’t stop on logout | `nohup myscript.sh &` |
| xargs | process list | Convert input to arguments | `echo "file1 file2" | xargs rm` |
| sed | stream editor | Replace text in a file | `sed 's/old/new/g' file.txt` |
| awk | text processing | Extract data from a file | `awk '{print $2}' file.txt` |
| cut | extract fields | Extract fields from lines | `cut -d':' -f1 /etc/passwd` |
| tr | translate | Replace characters | `echo "hello" | tr 'a-z' 'A-Z'` |
| diff | compare files | Show differences between files | `diff file1.txt file2.txt` |
| sort | sort lines | Sort file contents | `sort myfile.txt` |
| uniq | unique lines | Remove duplicate lines | `sort myfile.txt | uniq` |
| wc | word count | Count words, lines, and characters | `wc -l file.txt` |
| tee | write & print | Write output to file and print | `ls | tee output.txt` |
| sleep | delay execution | Pause execution for a duration | `sleep 5` |
| time | measure time | Measure execution time | `time ls` |
| yes | repeat input | Repeat a string until interrupted | `yes "hello"` |
