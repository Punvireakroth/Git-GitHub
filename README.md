# Basic Git Workflow

## Introduction

Git allows you to make keep track of the change in our project and also allows us to refer to the version we want.

## git init

`init` mean initialize mean we're ready to keep track changes on the project.

## Git Workflow

Git project have three parts

1. `Working directory` where you creating, editing, deleting, and organizing files
2. `Staging Area` where you making changes and ready to commit
3. `Repository` Where git permanently store those change as different versions of the project.

   Git workflow consists of editing files in the `working directory`, adding files to the `staging area`, and saving changes to a Git `repository`.

## git status

When you making change in a file you can check it with `git status`

Note: when you see `untracked files` it mean Git see the file but has not stated tracking changes yet.

## git add

As I Mention above untracked files are files that git doesn't tracking yet so to make git track those file we need to use `git add "filename"`
