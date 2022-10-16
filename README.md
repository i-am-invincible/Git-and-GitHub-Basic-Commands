 Git and GitHub Basic Commands
 
Git is a version control system that lets you manage and keep track of your source code history. GitHub is a cloud-based hosting service that lets you manage Git repositories.

version - To display the version of git present on your machine.![git version](https://user-images.githubusercontent.com/92079088/196049493-91bab9ff-4e32-4d8c-99db-56285a0c3270.png)

 1. init - To initialize empty Git repository.
 ![git init](https://user-images.githubusercontent.com/92079088/195949034-36ee4509-427f-4360-89e6-7c31091ee34a.png)

 2. config - To introduce git with username and email id.

     a)  For username - ![2  a) git config](https://user-images.githubusercontent.com/92079088/196049257-e2e7638c-1caf-4ecb-a90b-529c188aa174.png)

     b) For email id - 
     ![2  b) git config email](https://user-images.githubusercontent.com/92079088/196049264-5d967b26-45d8-4720-a6a7-b3ea58dfa9c2.png)

    

 3. status - To display the state of the working directory and the staging area.![3  git status](https://user-images.githubusercontent.com/92079088/196049163-b9d266d5-04d2-4105-b0cc-97e634feb1d0.png)


 4. add - 

    a) git add "filename" - To add files to the staging area to track the files.![4  a) git add filename](https://user-images.githubusercontent.com/92079088/196049182-456100ca-1c14-4f4b-99eb-d7407f4dd7ad.png)


    b) git add . - To add all the files available in the repository.![4  b) git add all files](https://user-images.githubusercontent.com/92079088/196049192-66643507-b7e4-4d44-96df-4098e96a13eb.png)

    

 5. commit - To capture a snapshot of the project's currently staged changes.![5  git commit 1](https://user-images.githubusercontent.com/92079088/196049535-65a64874-0a71-4479-b1c8-7374d7100bc0.png)


 6. branch - 

    a) git branch - To list all the branches and to check the present branch in the Github repo.

    b) git branch developer1 - To create a new branch.

    c) git checkout developer1  - To switch from the new branch and move to the main branch.

 7. remote - 

    a) git remote add origin - To link the git repository in which user wants to push their local code. It helps in creating connections with other repositories.
    ![7  a) git remote](https://user-images.githubusercontent.com/92079088/196049554-5bbccd99-7813-4fd5-8305-5d0fe5e0c7ea.png)


    b) git remote -v - To list the remote connection user has to other repositories.![7  b) git remote -v](https://user-images.githubusercontent.com/92079088/196049589-d5ab8f2b-1cab-4a34-a16f-17fbdcee9073.png)


 8. push - To push the branch or to push the changes in the branch to the GitHub repo.![8  git push](https://user-images.githubusercontent.com/92079088/196049598-d46615b4-800a-4bb8-8bbe-a85557320b7f.png)


 9. log - 
 
    a) git log - To display all the commits in a repository's history.![9  a) git log](https://user-images.githubusercontent.com/92079088/196049618-a674923c-9716-4526-b4a3-6038378b818a.png)


    b) git log -p-3 - To display last 3 commits in a repository's history. 

 10. merge - To merge the current branch into the specified branch (main).

 11. restore - To unstage or even discard uncommitted local changes.

 12. reset - To undo the recent changes that are to be committed.

 13. diff - To track the changes that have not been staged. Usually this 
command will compare the files in local area with the files in the staging area.

 14. clone - To point to an existing repo and make a clone or copy of that repo at in a new directory, at another location. 

 15. pull - To pull the new changes from git repository to local machine.


