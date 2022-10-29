
# Zuri's week 5 task

Learning how to use git and github


## FAQ

#### What is git?

Git is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency.

#### What is github?

GitHub is a website and cloud-based service that helps developers store and manage their code, as well as track and control changes to their code.

#### Common git commands

To add new files on batch you can run the following command  
    &emsp; touch filename  

To add files of similar file types, you can add collectively instead of individually  
    &emsp; git add *.html  
    &emsp; git add *.css  
    &emsp; git add *.js  

Add all files in the current directory  
    &emsp; git add .  

Check status of your work, gives rundown of changes made, commit history, current directory, branches etc  
    &emsp; git status  

Making commit, like a restore point with a message stating what was done  
    &emsp; git commit //this opens new terminal for you to write your message or use the shorthand below, press i to insert text however only the words without the initial # tag will be taken as the comment(press escape and :wq  to close the commit terminal)  
    &emsp; git commit -m "commit message"  

To make local new branch  
    &emsp; git checkout -b branch name  
  
To move from one branch to another  
   &emsp; git checkout branchName  

To check list of branches  
    &emsp; git branch  

To check list of files  
    &emsp; git ls-files  

To connect to remote repository  
    &emsp; git remote add origin repositoryUrl  

To push to master branch on repository  
    &emsp; git push -u origin main/master  

To create and push to new branch on repository  
   &emsp;git push --set-upstream origin branchName //Note to be on the local branch that has files you are trying to push to new repository branch  

To clone or make a copy of a repository forked from gitHub  
  &emsp; git clone   //make sure to be in the right directory on your local machine before cloning  

Compare and update a content in the repository with local copy  
  &emsp; git pull  remote  //used to fetch and download content from a remote repository and immediately update the local repository to match that content.  

To download commits, files and reference from a repository  
   &emsp; git fetch remote //Fetching is what you do when you want to see what everybody else has been working on.  

Merging different branches  
   &emsp; git status //check current state of files  
   &emsp; git log --merge //a log with a list of commits that conflict between the merging branches  
   &emsp; git diff  //find differences between states of a repository/files. This is useful in predicting and preventing merge conflicts.  
   
When git fails to start a merge  
   &emsp; git checkout  //used for undoing changes to files, or for changing branches  
   &emsp; git reset --mixed //can be used to undo changes to the working directory and staging area.  

When merge caused conflict  
   &emsp; git merge --abort  //exit from the merge process and return the branch to the state before the merge began.  
   &emsp; git reset //reset conflicted files to a know good state    