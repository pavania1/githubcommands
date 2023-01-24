# Git Commands
## $ git config user.name
    The git config command is a convenience function that is used to set Git configuration values on a global or local  level.
    
## $ git clone <repo>
    Git clone is a command for downloading existing source code from a remote repository .
     
## $ git branch <branch name>
     Git branch is very important , it is used for creating, deleting and also creating a new branch with in the existing branch.
    
## $git checkout
    command: $git checkout<branch name>
    To work in a branch, first you need to switch to it. We use git checkout mostly for switching from one branch to another. We can also use it for checking out files and commits.
## $git init
    Git init command used to creates  a new repository. 
## $git  status
    The Git status command gives us all the necessary information about the current branch. 

## $git add
    Git add command is used for adding the files to the repository.
    command: $git add<filename>
    $ git add -A // everything add at once.
    
## Git commit
    command: $ git commit -m "message"
    Git commit command is used to send some commit message.
## Git push
    command : $ git push <remote><branch name>
            : $git push -u origin<branch name>
    After committing your changes, the next thing you want to do is send your changes to the remote server. Git push uploads your commits to the remote repository.
## git fetch
    command: git fetch <remote url><branch name>
    This command will download the changes from the remote repository to the local repository. This will get the updates that are made to the remote repository into the local repository. This will only download the change and does not merge the changes.
    
## Git Pull
    command: $git pull<remote>
    The git pull command is used to get updates from the remote repo. This command is a combination of git fetch and git merge which means that, when we use git pull, it gets the updates from remote repository (git fetch) and immediately applies the latest changes in your local (git merge).

## Git revert
    command $ git revert <commit id>
    The Git revert command will undo the given commit, but will create a new commit without deleting the older one.

## Git rm
    command: $ git rm
## Git merge
    command: $ git merge <brach name>
    Git merge command is used for merging of the fetch branch to the newly or exixting branch.
    
## Git clean
    command: $ git clean -n 
    // shows which  would be removed.
    command: $ git clean -f
    // removes the file

## Git tag
    command: $git tag <tag name>
    This command is used to tag a commit and tag can be refered in future. A branch can have any number of tags. Tags can be names of the versions.

## Git stash
    command:$ git stash
    This command is used to switch the branch without making a commit, it is used for later use also.

## Git log
    The git log command displays all of the commits in a repository’s history.
    command: git log
    git log --stat //a summary line with the total number of files and lines changed. 
    git log --online // to get the commit details in online.
    git log -p or git long --patch
    // The specific changes that you made and the files that are modified is display.

## Git diff
    The git diff command is a widely used tool to track the changes. The git diff command allows us to compare different versions of branches and repository.
    command : git diff <branch1name><branch2name>




    
    
    

    

    