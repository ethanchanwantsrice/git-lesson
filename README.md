# Git Lesson

This lesson covers basics of get for version control.

This lesson is for the first day of the MSSE bootcamp.

To make commit ("version" or "checkpoint") of your files, follow this procedure:

1. Make changes to your project you would like to keep.
2. When you have your changes, tell git you are ready to create a checkpoint of the files using `git add filename`
3. Create a checkpoint using `git commit -m "message about what you did"`

## Adding Features

Features shold be developed on branches. To create and switch to a branch, use the command

`git switch -c new_branch_name`

To switch to an existing branch, use

`git switch branch_name`

To submit your feature to be incorporated to the main branch, you should submit a `Pull Request`.
The repository maintiners will review your pull request before accepting your changes.