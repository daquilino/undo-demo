# undo-demo
undo commit demo repo
change 1
change 2



https://www.youtube.com/watch?v=H2DuJNWbqLw

Push a new commit which reverts the pushed commit
-best for public or shared branches
HISTORY
> git revert HEAD
> git push origin main


Delete the pushed commit
-best for private branches
NO HISTORY
> git reset HEAD~1          (where 1 is number of commits to delete)
alt > git reset -hard HEAD~1    (delete unstaged)

> git push -f origin main     (forced push)


-- to see log of commits
>git log
or
>git log --online