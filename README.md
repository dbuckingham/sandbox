sandbox
=======
This is a git repository for learning to use git.

Introduction
============
This is an introduction to the project.
Time to make some conflicts!!!

Script for Learning Git
=======================
- Create GitHub repository.
- Clone GitHub repository to local.
- Due to my OCD, rename remote from origin to github.

	$ git remote rename origin github

- SourceTree should automatically pickup the newly renamed github remote.
- Create a branch called 'development'.  This will create a local branch, not a remote branch in the central repo (github).
- Make some commits. 
- Make some more commits.
- Push changes to github.  Declare the 'development' branch as a "tracking branch".  This will create a remote branch, and correlate 'github/development' and 'development'.