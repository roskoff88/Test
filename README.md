#Tips


# how to verify local status repository?
git status

# how to create a new branch?
git checkout new-master

#How to change branch to master?
git branch -m master old-master
git branch -m new-master master


# this will force push the current branch to the remote master
git push -f origin HEAD:master

# switch current branch to master
git checkout master

# reset the local master branch to what's on the remote
git reset --hard origin/master

# Revert many commits in git
git checkout -f CommitNumber -- . //Force check­out the com­mit that has the code you want your head to be at
git status 
git commit -m "your commit message"
git push

