This homework assignment requires you to manipulate the repository that you have cloned.
Please follow these instructions carefully. Please work in the directory pulled down from git and within a single window on your pi. This exercise includes recording your command history and saving information to the pwd that will be pushed back to github classroom for grading.

0) Change the pwd to the 'FileManip' directory created by the git pull command.
1) Dump your current shell history into a file called 'orig-hist.txt'
2) Clear your shell history. Check to see if it has been successfully cleared.
3) Dump your current shell history into a file called '00-hist.txt'
4) Create an alias for your method for clearing your history called 'chist'
5) Dump your current shell history into a file called '01-hist.txt'
6) Run "chist" Check to see if the history was successfully cleared.
7) Dump your current shell history into a file called '02-hist.txt'
8) Run the command "alias compTxt='md5sum *.txt | cut -c1-32 | sort | uniq -c | sort -nr'
9) Dump your current shell history into a file called '03-hist.txt'
10) Run the command 'compTxt > comparison-results.txt'
11) Create an alias for 'rm' that forces a prompt for confirmation before a file is deleted.
12) In one line, create an empty file called "should-remain.txt"
13) Dump your current shell history into a file called '04-hist.txt'
14) Perform the command "rm * .txt". Only delete the "orig-hist.txt" file.
15) Copy the 02-hist.txt file to 06-hist.txt.
16) Run the command "alias dupHash='compTxt | grep "2 " | cut -c9- > duplicateHash' "
17) Run the command "alias dupFiles='md5sum *.txt | grep -f duplicateHash' | grep -c35-"
18) Add and commit the changes to your git repository with the "git add *" and "git commit -m <Msg>" commands
19) Push your changes to your git repository with the "git push" command.

