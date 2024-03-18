# fix-old-typo
- git start next
- git log
- git rebase -i 98e6b86bbed506a2225aec8f1bc9791b88e5ba8f
> initiates an interactive rebase session starting from the commit specified by the hash 98e6b86bbed506a2225aec8f1bc9791b88e5ba8f. Interactive rebasing allows us to modify the commit history in various ways, such as reordering, editing, squashing, or dropping commits. 
- nano file.txt
- git add .
- git rebase --continue
> This command tells Git to apply the changes we've resolved or made and continue applying the remaining commits in the rebase sequence.
- ls
- nano file.txt
- git rebase --continue
- git commit -am "smth"
- git verify
