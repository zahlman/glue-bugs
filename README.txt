For each new reproducible test case:

1. Make a new branch off the initial commit, labelling it in a way that describes the bug being showcased.

2. For each git-committable step to reproduce the issue, make a new commit and use the commit message to indicate the steps to reproduce.

3. In the last commit on the branch, be sure to modify expected.txt and actual.txt to indicate the expected and actual behaviour.

In the future, I may attempt to include code on the master branch to post bugs automatically (or at least parse the above metadata and format a post).