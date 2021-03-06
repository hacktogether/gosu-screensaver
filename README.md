gosu project
============

This is our first project. It's a learning experience: a little OOP, 
a little refactoring, a little Git.

# On Git and Github

Github has an amazing windows client now, but you'll always need to
know some basic commands, because they're the basic operations that
you need to perform with Git. For instance:

## Saving Changes

Once you've made a change you would like to keep, you need to "commit" it in Git.

It's not difficult to do this in the Windows client, but the following method is
foolproof:

Right-click on the project directory and select "Git Bash here". A prompt will come up, and you can run the commands

    git add .
    git commit -a -m "My descriptive message"

For instance, you just made it scroll in 4 directions. Oh frabjous day! So make a commit with a good commit message:

    git add .
    git commit -a -m "Added 4-direction scrolling to images"

Later on, if you've screwed the pooch, other git commands can help you get back to where everything was working.

This even applies to images -- everything in this folder and its subfolders is tracked, with all changes recorded.

For now, just commit all changes -- later, we can use the GUI to see what's changed, and others can help you rebase, undo, rollback etc.

Some other commands:

    git init            makes a new git project in the current directory
    git status 		like, 'you have untracked files' or 'all good'