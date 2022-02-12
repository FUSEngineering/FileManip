This homework assignment requires you to manipulate the repository that you have cloned.
Please follow these instructions carefully. Please work within a single window on your pi.

1) Dump your current shell history into a file called 'orig-hist.txt'
2) Clear your shell history.
3) Dump your current shell history into a file called 'new-hist.txt'
4) Create an alias for your method for clearing your history called 'chist'
5) Run "chist"
6) Dump your current shell history into a file called 'another-hist.txt'
6) Run the command "alias compTxt='md5sum *.txt | cut -c1-32 | sort | uniq -c | sort -nr'
7) Dump your current shell history into a file called 'yet-another-hist.txt'
8) Run the command 'compTxt > comparison-results.txt'
9) Create an alias for 'rm' that forces a prompt for confirmation before a file is deleted.
10) In one line, create an empty file called "should-remain.txt"
11) Perform the command "rm * .txt". Only delete the "orig-hist.txt"
12) 