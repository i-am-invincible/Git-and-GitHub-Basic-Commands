# Git and GitHub Basic Commands
 
Git is a version control system that lets you manage and keep track of your source code history. GitHub is a cloud-based hosting service that lets you manage Git repositories.

Check git version - To display the version of git present on your machine.
```
Example:- git --version
```
![git version](https://user-images.githubusercontent.com/92079088/196049493-91bab9ff-4e32-4d8c-99db-56285a0c3270.png)

 ### 1. init - To initialize empty Git repository.
 ```
Example:- git init
```
 ![git init](https://user-images.githubusercontent.com/92079088/195949034-36ee4509-427f-4360-89e6-7c31091ee34a.png)

 ### 2. config - To introduce git with username and email id.
   a)  For username -
  
     Example:- git config --global user.name "your_username"
        
   ![2  a) git config](https://user-images.githubusercontent.com/92079088/196049257-e2e7638c-1caf-4ecb-a90b-529c188aa174.png)
     

   b) For email id - 
   
      Example:- git config --global user.email "your_email@gmail.com"
          
   ![2  b) git config email](https://user-images.githubusercontent.com/92079088/196049264-5d967b26-45d8-4720-a6a7-b3ea58dfa9c2.png)

 ### 3. status - To display the state of the working directory and the staging area.
 ```
Example:- git status
```
![3  git status](https://user-images.githubusercontent.com/92079088/196049163-b9d266d5-04d2-4105-b0cc-97e634feb1d0.png)

 ### 4. add - 
   a) git add "filename" - To add files to the staging area to track the files.
   
    Example:- git add "filename"
        
   ![4  a) git add filename](https://user-images.githubusercontent.com/92079088/196049182-456100ca-1c14-4f4b-99eb-d7407f4dd7ad.png)


   b) git add . - To add all the files available in the repository.
    
    Example:- git add .
   
   ![4  b) git add all files](https://user-images.githubusercontent.com/92079088/196049192-66643507-b7e4-4d44-96df-4098e96a13eb.png)


 ### 5. commit - To capture a snapshot of the project's currently staged changes.
 ```
Example:- git commit -m "Message"
```
![5  git commit 1](https://user-images.githubusercontent.com/92079088/196049535-65a64874-0a71-4479-b1c8-7374d7100bc0.png)


 ### 6. branch - 
    
  a) check branches - To list all the branches and to check the present branch in the Github repo.
  
      Example:- git branch
    
  ![6  a) git branch](https://user-images.githubusercontent.com/92079088/196051964-cbaf19b4-5529-4522-9291-e6ea89e45eba.png)
  
  Note : If initially your branch is master then change branch name from master to main, so that it can be compactable with 
github.
```
Example:- git branch -M main
```
![git branch name change](https://user-images.githubusercontent.com/92079088/196054674-dc7a2fff-12fd-4a3d-9f89-3dd535f668d4.png)


   b) new branch  - To create a new branch.
   
     Example:- git branch developer2
     
   ![6  b) create new branch](https://user-images.githubusercontent.com/92079088/196054790-138fd5c0-9ea8-4117-8a2a-320e82452a32.png)


   c) switch branch - To switch from the new branch and move to the main branch.
   
      Example:- git checkout developer1
    
   ![6  c) switch branch](https://user-images.githubusercontent.com/92079088/196054300-180c681d-6b89-4e55-914e-6af1ca5b89fb.png)
    
   d) delete branch - To delete a branch from the git repo.
    
      Example:- git branch -d developer2
      
   ![6  d) delete branch](https://user-images.githubusercontent.com/92079088/196054917-b6ecc6c8-ba1f-4a9f-af23-89ce907a878b.png)


 ### 7. remote - 

   a) git remote add origin - To link the git repository in which user wants to push their local code. It helps in creating connections with other repositories.
    
    Example:- git remote add origin <git repo url>
    
   ![7  a) git remote](https://user-images.githubusercontent.com/92079088/196049554-5bbccd99-7813-4fd5-8305-5d0fe5e0c7ea.png)


   b) git remote -v - To list the remote connection user has to other repositories.
     
    Example:- git remote a-v
   
   ![7  b) git remote -v](https://user-images.githubusercontent.com/92079088/196049589-d5ab8f2b-1cab-4a34-a16f-17fbdcee9073.png)


 ### 8. push - To push the branch or to push the changes in the branch to the GitHub repo.
  ```
Example:- git push origin main
```
![8  git push](https://user-images.githubusercontent.com/92079088/196049598-d46615b4-800a-4bb8-8bbe-a85557320b7f.png)


 ### 9. log - To display all the commits in a repository's history.
  
    Example:- git log
  
   ![9  a) git log](https://user-images.githubusercontent.com/92079088/196049618-a674923c-9716-4526-b4a3-6038378b818a.png)

 ### 10. merge - To merge the current branch into the specified branch (main).
 ```
  Example:- git merge
  ```
![10  git merge](https://user-images.githubusercontent.com/92079088/196057637-0528baa1-2b67-479c-98c4-09c03a16445f.png)


 ### 11. restore - To unstage or even discard uncommitted local changes.
  ```
Example:- git restore <filename>
```
![11  git restore](https://user-images.githubusercontent.com/92079088/196057630-d83c728e-6da0-4cb1-b0e9-f04823056fc2.png)


 ### 12. reset - To undo the recent changes that are to be committed.
  ```
Example:- git restore <filename>
```
![12  git reset](https://user-images.githubusercontent.com/92079088/196054423-09c9c438-5428-41ec-89c4-907177bf57d4.png)


 ### 13. stash - To take your uncommitted changes (both staged and unstaged), saves them away for later use, and then reverts them from your working copy
  ```
  Example:- git stash
  ```
  ![13  git stash](https://user-images.githubusercontent.com/92079088/196057618-6ba2e748-fe63-4750-a791-3a735dd10c73.png)


 ### 14. clone - To point to an existing repo and make a clone or copy of that repo at in a new directory, at another location. 
  ```
  Example:- git clone <git repo url>
  ```
  ![14  git clone](https://user-images.githubusercontent.com/92079088/196054406-a68ce8e5-bd28-44aa-8db4-db5c0f69069f.png)


 ### 15. pull - To pull the new changes from git repository to local machine.
  ```
  Example:- git pull
  ```

  ![15  git pull](https://user-images.githubusercontent.com/92079088/196054380-5c3c6607-0e3b-47d2-b6ab-1a28ae536205.png)

 ### THANK YOU !

