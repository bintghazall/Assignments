
# Zuri's week 5 task

Learning how to use git and github


## FAQ

#### What is git?

Git is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency.

#### What is github?

GitHub is a website and cloud-based service that helps developers store and manage their code, as well as track and control changes to their code.

#### Common git commands

To add new files on batch you can run the following command <br/>
    touch filename <br/>

To add files of similar file types, you can add collectively instead of individually <br/>
    git add *.html <br/>
    git add *.css <br/>
    git add *.js <br/>

Add all files in the current directory<br/>
    git add . <br/>

Check status of your work, gives rundown of changes made, commit history, current directory, branches etc <br/>
    git status <br/>

Making commit, like a restore point with a message stating what was done <br/>
    git commit //this opens new terminal for you to write your message or use the shorthand below, press i to insert text however only the words without the initial # tag will be taken as the comment(press escape and :wq  to close the commit terminal) <br/>
    git commit -m "commit message" <br/>

To make local new branch <br/>
    git checkout -b branch name <br/>

To move from one branch to another <br/>
    git checkout branchName <br/>

To check list of branches <br/>
    git branch <br/>

To check list of files <br/>
    git ls-files <br/>

To connect to remote repository <br/>
    git remote add origin repositoryUrl <br/>

To push to master branch on repository <br/>
    git push -u origin main/master <br/>

To create and push to new branch on repository <br/>
   git push --set-upstream origin branchName //Note to be on the local branch that has files you are trying to push to new repository branch <br/>

To clone or make a copy of a repository forked from gitHub <br/>
   git clone   //make sure to be in the right directory on your local machine before cloning <br/>

Compare and update a content in the repository with local copy <br/>
  git pull  remote  //used to fetch and download content from a remote repository and immediately update the local repository to match that content. <br/>

To download commits, files and reference from a repository  <br/>
   git fetch remote //Fetching is what you do when you want to see what everybody else has been working on. <br/>

Merging different branches <br/>
   git status //check current state of files <br/>
   git log --merge //a log with a list of commits that conflict between the merging branches <br/>
   git diff  //find differences between states of a repository/files. This is useful in predicting and preventing merge conflicts.  <br/>
   
When git fails to start a merge   <br/>
   git checkout  //used for undoing changes to files, or for changing branches   <br/>
   git reset --mixed //can be used to undo changes to the working directory and staging area.   <br/>

When merge caused conflict   <br/>
   git merge --abort  //exit from the merge process and return the branch to the state before the merge began.  <br/>
   git reset //reset conflicted files to a know good state  <br/>



