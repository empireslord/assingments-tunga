1. A `PATH` variable is an environment variable which specifices the a set of directories where our executable programs are located.
1. A `PATH` varible will be needed when securing information and using a varible multiple tiomes.
1. We save a PATH variable by adding them to our `.bash_profile or .Zshrc`
1. A process is set of computer instructions that are currently being executed.
1. We list all the process running on our machine by using the `ps -aux`
1. A PID(process ID) is a unique identifier given to each process by the computer and its neccessary for stopping processes
1. You TERminate a process by using the command `kill` or `kill -9`
1. The `kill -9` stop process that can't be stopped by using the `kill` alone i.e the `kill -9` cna't be ignored by the system,
1. The `grep` flag the allows for case insensitive is the `-i` flag.
1. The `grep` flag the allows for certain number of match before the match  is the `-B` flag.
1. The `grep` flag the allows for a certain number of lines around the match is the `-C` flag.
1. The `grep` flag the allows for a certain number of lines after the match is the `-A` flag.
1. The `grep` flag the allows for a full word search is the `-w` flag.
1. The `grep` flag that shows you the line number of a match is the `-n` flag.

## Part 2
Write the following terminal commands to do the following (assume that `instructors.txt` is an imaginary file):
1. To find all the folders in the desktop that have "learn" in their nane the command passed will be `find ~/Desktop -name "learn"`
1. HOw to find all files inside the Desktop folder that start with a "P." `find ~/Desktop -name "P.*" `
1. How to find all files inside the Desktop folder that end with .txt. `find ~/Desktop -name "*.txt"`
1. To find all the files inside `desktop/views` folder that have `data` somewhere in the file name the command is `find ~/Desktop/views -name "*data*"`
1. For you to output the number of times "Elie" appeard in instuctor.txt  `grep -c "Elie" instructors.txt`
1. list all match that starta with the capital "P" `grep -w "P.*" instructors.txt`.
1. list all the line numbers that starts with a "z" in the `instructors.txt` (Should match regardless of case) `grep -ni "z.*" instructors.txt`.