# Git Overview #
Data is stored as snapshots of files, rather than stored as a file and the changes made to that file over time.

## The Three States ##
A file can reside in one of 3 states:

1. Committed - the data is stored in the local database
2. Modified - the file has been changed but not committed to the local database
3. Staged - the modified file in its current version has been marked to go into the next commit snapshot

## The Three Main Sections of a Git Project ##

![](http://git-scm.com/figures/18333fig0106-tn.png)

1. Git directory - where the metadata and object database for the project is stored. This is what gets copied when you clone a repo.
2. Working directory - a single checkout of one version of the project.
3. Staging area - stores information about what will go into the next commit. Also called the index.

#Dos and Don'ts#

## Dos ##
- Commit often
- Provide meaningful commit messages
- Update your feature branch often
- Learn to use Git from the command-line

## Don'ts ##
- Do NOT create branches
- Do NOT perform tasks directly in GitHub other than working on pull requests (creating, closing, and commenting)

# Links #
- [http://git-scm.com/documentation](http://git-scm.com/documentation "Git Documentation")