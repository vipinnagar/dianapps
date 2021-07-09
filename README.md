# dianapps
practice

# putting random stuff
dsads
# checking git status
git status
# checking the differences
git diff
# adding all changes of current directory
git add .
# commit
git commit -m "updated readme"
# push
git push

# create a new branch
git checkout -b test

# to switch branches
git checkout main
git checkout test

# cherry picking a commit from main to cherr_pick_test branch
git checkout -b cherr_pick_test
git cherry-pick 0799686730cb5a42ebe0786dd14fb0077a398103



# checkout to remove the changes from a particular file
git checkout test.txt

# save stash with name
git stash save "temp test.txt changes"

# list all stash
git stash list

# pops top stash
git stash pop

# check all logs
git log

