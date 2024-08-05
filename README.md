# Git Lesson

This lesson covers the basics of git for version control.

This lesson is for the first day of the MSSE bootcamp (Chem 280).

To make a commit ("version" or "checkpoint") of your files, follow this procedure:

1. Make changes to your project that you would like to keep.
2. When you have your changes, tell `git` you are ready to create a checkpoint of t he file uisng the `git add FILENAME` command.
3. Create a checkpoint of your file using `git commit -m "Message about what you did (past tense imperative phrasing)"`.

## Adding Features
Features should be developed on branches.
To create and switch to a branch, use the command

`git switch -c NEW_BRANCH_NAME`

To switch to an existing branch, use

`git switch BRANCH_NAME`
