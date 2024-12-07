git init
git add file_name
git status
git commit
git commit -m "commit_name"  (if you want to enter the details in terminal)
git log    (all the commits shown in chronological order)

##### (if changes are made then add the file and then commit) 

git checkout id_name (if there are 4 commits and u moved to 3rd one - then u wrote git log (only the preceding commit will be shown))
git checkout master (to get to the main branch)
git revert id     
git reset --hard id
git add . (or) git add * ------(to add all files)
git branch <name>
git branch --------- only(list all the branches)
git branch -D <branch_name> --------- (to delete the branch)
git checkout -b <branch_name> ### To create a new branch and automatically checkout ##

#################################
git remote add origin <link> (connect local to cloud)
#################################

git remote set-url origin  https://AKC010110@github.com/AKC010110/github-crash-course
git push
git pull (to download the files from github)
git clone <link> <folder_name>
git remote (we will see a list of all connected repositries)
git remote set-url <repo_name> ---(link of the repo will be shown)