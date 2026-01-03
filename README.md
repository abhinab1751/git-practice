1.'git add <files>' = moves file from working area to staging area

2.'git rm --cached <files>' = moves file from working area to staging area 

3. 'commit' COmmit is a particular version of the project . It captures a snapshot of the projects staged chnages 
and creates a version out of it.

4. 'git commit' = registers staging changes to a commit 

5. 'git log' = list down all the commits of the repository. if you want to exit of the git log promt 
press 'q'.

6. 'git restore <files>' = it remove all the files chnages from the staging area to be committed .this can 
be useful, if we did some dirty piece of code and now no more want it . Istead of deleting every chnage line 
by line ,  we can restore it or you can say restore last clean verion of the file. 

7.'git restore --staged <files>' = it removes file from changes from staging area to the working area.
this only works if changes are inn your staging area

8. Diff between rm and git restore 
ans : if you want to move the whole file back to the untracked state, then we do git rm , 
otherwise if we just want the changes to be moved in working areas or staged area then we do git restore

9. 'git commit -m' = If we want to avoid opening a text editor like vim/nano to add commit mesage we can use this following command

10.'git remote' = list down all the remote connection names

11. Remote connection = It helps you to link two git repositories for uploading and downloading changes 
for each otherwise

12.'git remote add <name of remote> <link of the remote>' = this command helps us to add a new link to the remote repositories
and give a name to it

13. 'git remote rm <name of remote >' = this command deletes a remote connection

14. 'git remote rename <olanme> <newname>' = this command renames rhe remote connection

Note : The name of the remote connection is always used to establish communication between the repositories

15. 'git add <file1> <file2> <file3>' = This command will add multiple file changes together in the staging area

16.'git add .'= this command will add all the files from the working repo to staging area

