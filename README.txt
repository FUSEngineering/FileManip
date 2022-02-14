This homework assignment requires you to manipulate the repository that you have cloned.
Please follow these instructions carefully. Please work in the directory pulled down from git and within a single window on your pi. This exercise includes recording your command history and saving information to the pwd that will be pushed back to github classroom for grading.

1) Dump your current shell history into a file called 'orig-hist.txt'
2) Clear your shell history.
3) Dump your current shell history into a file called '00-hist.txt'
4) Create an alias for your method for clearing your history called 'chist'
5) Run "chist"
6) Dump your current shell history into a file called '01-hist.txt'
7) Run the command "alias compTxt='md5sum *.txt | cut -c1-32 | sort | uniq -c | sort -nr'
8) Dump your current shell history into a file called '02-hist.txt'
9) Run the command 'compTxt > comparison-results.txt'
10) Create an alias for 'rm' that forces a prompt for confirmation before a file is deleted.
11) In one line, create an empty file called "should-remain.txt"
12) Perform the command "rm * .txt". Only delete the "orig-hist.txt" file.
13) Add and commit the changes to your git repository with the "git add *" and "git commit -m <Msg>" commands
14) Push your changes to your git repository with the "git push" command.

