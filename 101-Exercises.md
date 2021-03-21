# Git-101-Exerceise

How do you see the files changed within each commit from git log?
You can use the command git whatchanged --stat to get a list of files that changed in each commit (along with the commit message).

How do you see the contents of what changed within each file from the git log?
Using git log --follow -p bar will show the file's entire history, including any changes to the file when it was known as foo . The -p option ensures that diffs are included for each change.

What does HEAD refer to in the context of git? (Not to be confused with the "HEAD<<<<" one observes within merge conflict)
HEAD means current branch. When switching branches, the HEAD changes to point to the tip of the new branch.
