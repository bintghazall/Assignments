to add new files on batch you can run the following command
    touch filename
to add files of similar file types, you can add collectively instead of individually
    git add *.html
    git add *.css
    git add *.js
Add all files in the current directory
    git add .
check status of your work, gives rundown of changes made, commit history, current directory, branches etc
    git status
making commit, like a restore point with a message stating what was done
    git commit //this opens new terminal for you to write your message or use the shorthand below, press i to insert text however only the words without the initial # tag will be taken as the comment(press escape and :wq  to close the commit terminal)
    git commit -m "commit message"
