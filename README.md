# hello-world

1. The original, canonical github repository is maintained by the Axodyne account. Only Axodyne is able to write changes to this account.

2. Axodyne works away on the repo. Changes are made, commits are added.

3. In the early days, changes are made directly into the ```main``` branch and pushed up to the github repo as needed.

4. Normally, a meaningful commit message would be used but in this early state, the messages are numbered to correspond with these paragraph numbers.

5. The result is a nice, simple linear sequence of commits that everyone can follow.

## Feature by Axodyne

a. Now Axodyne decides to add a new feature and creates a feature branch for the work. This is the first commit after creating the feature branch.

b. The feature branch allows axodyne to work on the feature without affecting the main branch of the repo.

c. At any time, axodyne could switch back to ```main```. to use the original repository. The only proviso is that all the work on the feature branch is committed before switching branches.

d. When axodyne is happy with the state of the new feature, it can be joined back with the main branch. It is a good idea to do a bit of a tidy before then to make sure everything is as it should be.

e. there are a couple of ways to join the work together and incorporate the new feature. The one used for this feature is a ***merge***

6. todo the nerge, azodyne makes sure all feaure changes are committed and then switches to the ```main``` branch with ```git checkout main```. Next, she will use the command ```git merge feature``` and the changes in feature will incorporated into the ```main``` branch. Assume for now there are no conflicts.

