# Git Lesson

This lesson covers the basics of git for version control.

This lesson is for the first day of the MSSE bootcamp (Chem 280).

1. Make changes to you project that you would like to keep.
2. When you have your changes, tell `git` you are ready to create a checkpoint of hte file using the `git add FILENAME` command.
3. Create a checkpoint on your file using `git commit -m "Message about what you did"`.

## Adding Features
Features should be developed on branches.
To create and swtich to a branch, use the command

`git switch -c NEW_BRANCH_NAME`

To switch to an existing branch, use

`git switch BRANCH_NAME`