Exercise 5: Create a repo on GitHub that contains a markdown file that answers these questions:

1). How do you see the files changed within each commit from git log?

  a.) Within each commit from git log you will see the files that were changed in chronological order.
  
2). How do you see the contents of what changed within each file from the git log?

  a.) In chronological order, you can execute git log to see the files. In addition, you can execute:
  git log --oneline | git log --stat | git log --patch | git log --graph --all --decorate --oneline

3). What does HEAD refer to in the context of git? (Not to be confused with the "HEAD<<<<" one observes within merge conflict)

  a.) HEAD is a reference to the last commit in the currently check-out branch. You can think of the HEAD as the "current branch". When you   switch branches with git checkout, the HEAD revision changes to point to the tip of the new branch. You can see what HEAD points to by doing: cat .git/HEAD.
