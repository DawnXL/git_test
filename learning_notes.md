## Cheatsheet
This is a reference list of the most commonly used Git commands. (You might consider bookmarking this handy page.) Try to familiarize yourself with the commands so that you can eventually remember them all:

**Commands related to a remote repository:**
git clone git@github.com:USER-NAME/REPOSITORY-NAME.git
git push or git push origin main (Both accomplish the same goal in this context)

**Commands related to the workflow:**
git add .
git commit -m "A message describing what you have done to make this snapshot different"

**Commands related to checking status or log history**
git status
git log

The basic Git syntax is program | action | destination.

## Atomic Commits

An atomic commit is a commit that includes changes related to *only one feature or task* of your program. There are two main reasons for doing this: first, if something you change turns out to cause some problems, it is easy to revert the specific change without losing other changes; and second, it enables you to write better commit messages. You’ll learn more about what a good commit message looks like in a future lesson!

## What is Vim?
A command-line text editor that runs directly inside your terminal window. It has no mouse support by default—everything is done using keyboard shortcuts.