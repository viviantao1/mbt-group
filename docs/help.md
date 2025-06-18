# Help and Resources

## Git Basics
This repository (repo) is public, so that means anyone can view this and use the code. However, if you'd like to be an active contributor to the repo there are some more steps. 

Once you are invited as a collaborator, **clone the repo to your computer** - this becomes the local repo. Your changes are not published to the public remote repo until you push them to the remote repo. Clone the repo: ```git clone https://github.com/viviantao1/mbt-group.git```

Next, every time you'd like to make changes, follow these steps:
1. **Get the most updated version of the remote repo for the local repo** with ```git pull``` in the terminal.
2. **Make any edits!**
3. **Stage changed files** (prepare to push/publish changes) with ```git add [names of changed files, separated by spaces]```
4. **Commit your changes with a commit message** using ```git commit -m "[descriptive commit message]"```. A commit basically takes a local "snapshot" of your files that you've staged. You can view all commits on the remote repo to see past versions and changes.
5. **Send changes to the remote repo** by executing ```git push```.
6. You may encounter a "merge conflict" if another collaborator is making conflicting changes at the same time. Follow the directions in your terminal to resolve the merge conflict.

Disclaimer: This workflow does not utilize git to its full extent. A simple workflow is described here to prioritize ease, especially since the use of this repo won't be very complicated.

## If a library is not able to be imported...
One issue is that your interpreter doesn't have the library installed, so it can't be imported into the program. Open a terminal and execute ```pip install [name of library]```. The full library name should be used; sometimes this is different than the name in the import statement. For example, you should ```pip install scikit-learn``` in your terminal and ```import sklearn``` in your program. This ensures your Python interpreter has the library you are trying to import.
