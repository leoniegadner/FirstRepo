# FirstRepo
My first Repo.

Tutorial: https://product.hubspot.com/blog/git-and-github-tutorial-for-beginners

- git status: displays the state of the working directory and the staging area.
- git add <filename>: Adds <filename> to the staging environment. 
                      Staged files are files that are ready to be committed to the repository you are working on.
    -A: Adds all files.
- git commit: "A commit is a record of what changes you have made since the last time you made a commit. 
              Essentially, you make changes to your repo (for example, adding a file or modifying one) and then 
              tell git to put those changes into a commit." 
    -m: Write message related to the commit!
- git branch <branchname>: Creates new branch.
                    ‘A branch in Git is simply a lightweight movable pointer to one of these commits.’
- git checkout -b <branchname>: Creates new branch and moves to it.
- git remote add origin git@github.com:username/Reponame.git: Sets origin to certain github repository (?)
- git push -u origin <branchname>: Creates branch on the remote repository
              
