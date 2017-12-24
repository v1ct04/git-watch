git-notify
========

Simple bash script for watching a Git repository and executing a specified command.

Based on jakeonrails/git-notify.

Usage:
----------

    ~/code/some-git-repository $ git-wach echo "Hey!"

The script will run in the background. If you want to kill it later, you can do:

    git-watch -k

There are some extra options that I didn't have time to document as well. Check switch-case [here](https://github.com/victorges/git-watch/blame/master/git-watch#L33) for detail 🙈

Installation:
------------
Just download git-watch and put it somewhere in your path.

Victor Elias, victorgelias@gmail.com

Original code from:
Jake Moffatt, jakeonrails@gmail.com

