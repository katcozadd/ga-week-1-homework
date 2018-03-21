Part 1:
1.) What command do you use to setup a git repository inside of your folder?
git init

2.) What command do you use to ask git to start tracking a file?
git add

3.) What command do you use to ask git to move your file from the staging area to the repository?
git commit - m

Part 2:
1.) What command do you use to pull any changes from the master repository into your local repository?
git pull

2.) What command do you use to unstage a file?
git reset

3.) What command do you use to change your files back to how they were after a commit?
git checkout --

4.) Why is it important to use -- when changing files back to a previous state?
It is important to use -- because it allows you to undo something that you commited and no longer want to have commited.

5.) Why might you want to reset your files back to a previous commit?
Resets allow one to go back to a previous point in the code that things were working well and start from that point again.

Part 3:
1.) What command do you use to create a branch?
git checkout -b

2.) What command do you use to use a different branch?
git checkout 

3.) Why would you want to use a branch other than the default master?
Working on a branch allows one to work in a space that is different than the master branch. Therefore if code is not working or if it is not ready to be commited and pushed for others to work on or see, it does not affect anyone else in the workspace.

Part 4:
1.) Give an example for when you would use git merge and give an example for when it would be better to submit a pull request to have your branch merged.
git merge is helpful in a team setting where there are many other branches that need to be worked with/on in order for the branch that you are working on to function correctly.

2.) What command do you use to send all of the work that you've done locally to your remote repository?
git push orgin master
