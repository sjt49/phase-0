How does tracking and adding changes make developers' lives easier?

By saving what you did in the past, things will be easier for future developers! An obvious enefit is if a bug presents itself in the code. Then it's easy to go back and spot where and why it occured simply with the log function. In addition, if new developers are added to the project, and a certain piece of code seems confusing or redundant or weird to them, they can go back 'in time' to the point that change was added. And they can see the message for why it was added! This will either explain why the code is necessary, or reveal that that particular portion became outdated as the rest of the code kept being developed.


What is a commit?

A commit is a save point in the editting process of the repository. A commit exists on a particular branch, i.e. the master branch and a new-branch could be committed (and probably are) in different stages before they are merged. If you edit files in a branch without staging or committing them, they are not yet a 'save point' in the repo.


What are the best practices for commit messages?

Commit messages should be concise, but should still encompass all the changes made during the commit and their reason. It should not be specific, like code, but rather a description of its function.


What does the HEAD^ argument mean?

HEAD is used when you've commited something, and you realize you want to edit it again. Specifically, HEAD^ refers to the previous commit, while HEAD refers to current commit being worked on.


What are the 3 stages of a git change and how do you move a file from one stage to the other?

The 3 stages of a git change are untracked changes, added files, and committed files. An untracked file is when you create a new file in the branch. A modification is similar, but it is an edited version of an already existing file. To proceed to the next step, use the git add <filename> function to stage the files, or simply git add . to stage the whole directory. This prepares the files in question for a commit. If you then edit those files again before committing, those edits are NOT staged. Finally, you can create a save point in the branch by using git commit, including a message with -m or -v.


Write a handy cheatsheet of the commands you need to commit your changes.

git checkout -b <branchname> : creates new branch
git checkout <branchname> : navigates to branch
git add <filename> : stages a file for commit
git commit -m "message here" : commits changes
git push <branchname> origin : pushes commits to GitHub or wherever


What is a pull request and how do you create and merge one?

A pull request will exist on the GitHub repo after you commit a branch on your computer and push it. Using the git push <branchname> origin command, you will add your commit to GitHub. Once there, you will see a pull request, prompting you to merge the branches. If there aren't any conflicts between the branches (often yours and the master branch), then it will merge smoothly and just follow the green buttons.


Why are pull requests preferred when working with teams?

Pull requests make it easier to work in larger numbers, because it minimizes the amount of toe-stepping done on each other. Everyone is able to download the code on their own, make their changes, and then send it back up to the cloud. At this time, it's probably ready to merge with some other branch, and those changes can now be accessed by everyone else on the team. This makes it simpler for everyone, as any conflict between code is sorted out in the merging process, and in between merges many different versions of similar code can exist and be edited without other team members needing to access or run it.