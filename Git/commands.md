```
git clone < https_clone_link or ssh_clone_link >
```
By using above command we clone a specific repository ( all the branches and commits will clone )

--------------------------
```
git branch 
```
This command shows list of local branches and the current branch will be suffixed with *

------------
```
git branch -a
```
List all local and remote branches 

-----------------
```
git clone -b branch_name --single-branch < https_clone_link or ssh_clone_link >
```
Above command clones the repo, with only specified branch ( all commits )

-----------

```
git clone --depth 1 -b branch_name --single-branch < https_clone_link or ssh_clone_link >
```

Above command clones the repo, with only specified branch with the latest commit only, which reduces .git folder size

-------------

git 