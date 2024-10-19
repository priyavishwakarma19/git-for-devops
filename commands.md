# Commands Reference

## Directory Operations
- `mkdir devops-batch-8`  
  Creates a new directory named `devops-batch-8`.

- `cd devops-batch-8`  
  Changes the current directory to `devops-batch-8`.

- `cd`  
  Changes to the home directory.

- `cd /`  
  Changes to the root directory.

- `ls`  
  Lists files and directories in the current directory.

- `mkdir logs`  
  Creates a new directory named `logs`.

## Searching Files
- `grep junoon /home/ubuntu/`  
  Searches for the term "junoon" in the `/home/ubuntu/` directory.

- `grep junoon -r /home/ubuntu/`  
  Recursively searches for "junoon" in `/home/ubuntu/`.

- `grep hello -r /home/ubuntu/`  
  Recursively searches for "hello" in `/home/ubuntu/`.

- `grep search -r /home/ubuntu/`  
  Recursively searches for "search" in `/home/ubuntu/`.

- `grep WARN -ir Zookeeper_2k.log`  
  Case-insensitively searches for "WARN" in `Zookeeper_2k.log`.

- `grep WARN -i Zookeeper_2k.log > warnings_only_log`  
  Saves case-insensitive "WARN" occurrences from `Zookeeper_2k.log` to `warnings_only_log`.

- `awk '/INFO/ {print $1 $2 $3}' Zookeeper_2k.log`  
  Prints the first three fields of lines containing "INFO" from `Zookeeper_2k.log`.

- `awk '/WARN/' pv_log.txt`  
  Prints all lines containing "WARN" from `pv_log.txt`.

## File Manipulation
- `vim twt.txt`  
  Opens or creates `twt.txt` for editing in Vim.

- `cat password.txt`  
  Displays the content of `password.txt`.

- `sed -i 's/test12345/***/g' password.txt`  
  Replaces all instances of `test12345` with `***` in `password.txt`.

- `find . -name *.log`  
  Finds all `.log` files in the current directory.

- `find . -name *.txt`  
  Finds all `.txt` files in the current directory.

## Script Execution
- `chmod 774 backup.sh`  
  Changes the permissions of `backup.sh`.

- `./backup.sh`  
  Executes the `backup.sh` script.

- `./install_package.sh zip`  
  Executes the `install_package.sh` script with `zip` as an argument.

- `vim hello.sh`  
  Opens or creates `hello.sh` for editing in Vim.

- `./hello.sh`  
  Executes the `hello.sh` script.

- `vim variables.sh`  
  Opens or creates `variables.sh` for editing in Vim.

- `./variables.sh`  
  Executes the `variables.sh` script.

## Git Operations
- `git init`  
  Initializes a new Git repository.

- `git status`  
  Displays the current status of the repository.

- `git add filename`  
  Stages a file for commit.

- `git commit -m "message"`  
  Commits the staged changes with a message.

- `git branch`  
  Lists all branches in the repository.

- `git checkout branch_name`  
  Switches to a specified branch.

- `git log`  
  Shows the commit history.

## Miscellaneous
- `clear`  
  Clears the terminal screen.

- `pwd`  
  Displays the current working directory.

- `date`  
  Shows the current date and time.

- `echo "hello dosto"`  
  Prints "hello dosto" to the terminal.

- `crontab -e`  
  Edits the crontab for scheduling tasks.
