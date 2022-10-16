 Git and GitHub Basic Commands
 
Git is a version control system that lets you manage and keep track of your source code history. GitHub is a cloud-based hosting service that lets you manage Git repositories.

version - To display the version of git present on your machine.

 1. init - To initialize empty Git repository.
![git init](https://user-images.githubusercontent.com/92079088/195949034-36ee4509-427f-4360-89e6-7c31091ee34a.png)


 2. config - To introduce git with username and email id.
     a)  For username - 
    ![git config](https://user-images.githubusercontent.com/92079088/195949214-0d078851-308a-40e4-b715-8963d2c87d82.png)

  b) For email id - 
    ![git config email](https://user-images.githubusercontent.com/92079088/195949249-7a0f4e15-bdff-4fc8-99ff-47c73428bf29.png)

 3. status - To display the state of the working directory and the staging area.

 4. add - 
    a) git add "filename" - To add files to the staging area to track the files.

    b) git add . - To add all the files available in the repository.
    

 5. commit - To capture a snapshot of the project's currently staged changes.

 6. branch - 
    a) git branch - To list all the branches and to check the present branch in the Github repo.

    b) git branch developer1 - To create a new branch.

    c) git checkout developer1  - To switch from the new branch and move to the main branch.

 7. remote - 
    a) git remote add origin - To link the git repository in which user wants to push their local code. It helps in creating connections with other repositories.

    b) git remote -v - To list the remote connection user has to other repositories.

 8. push - To push the branch or to push the changes in the branch to the GitHub repo.

 9. log - 
    a) git log - To display all the commits in a repository's history.

    b) git log -p-3 - To display last 3 commits in a repository's history. 

 10. merge - To merge the current branch into the specified branch (main).

 11. restore - To unstage or even discard uncommitted local changes.

 12. reset - To undo the recent changes that are to be committed.

 13. diff - To track the changes that have not been staged. Usually this 
command will compare the files in local area with the files in the staging area.

 14. clone - To point to an existing repo and make a clone or copy of that repo at in a new directory, at another location. 

 15. pull - To pull the new changes from git repository to local machine.


