# GIT and GITHUB popular commands

### Log and Config account

__git config --global user.name "username"__  
__git config --global user.email "email"__  

### Get Start

__git init__  // get start to a local repo as .git repo
__touch__     // create a local file
__git clone URL-do-repositorio-do-github__  // clone remote repo that will host the local repo

### Manage Modification

__git status__        // check modifications stage
__git add .__         // add all local files
__git add file-name__      // add a especific file
  __git commit -m "message"__          // commit repo's modification with a message
__git push -u origin branch-name__     // push to a especific branch (master default)
__git push__                           // push comum  
__git merge__                          // join branch's

### Check Updates

__git show__   // show the latest updates (press Shift + q to get out)
__git log__    // show all latest updates
__git show update code__   // show an especific update (see on git log)
__git remote -v__          // check remotes' repos

### Branch

__git branch branch-name__    // create a branch  
__git checkout branch-name__  // set some branch
__git branch -r__                // list remote repo's branches
__git branch__           // show all branches
__git branch -D branch-name__             // delete a local branch
__git push origin --delete branch-name__  // delete a remote branch

### Update 

__git remote add origin github-repository-url__ // update remote repo source local's repo
__git pull__  // update the local's repo

### Go Back to some Commit

__git checkout commit-changed-code__  // see on git log
