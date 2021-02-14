# Merging with a Modified Main Branch

It is pretty clen and simple whena repo maintainer is working on a single ```main``` branch and wants to simply add commits.

Even if feature or topicbranches are involved, this remain simple so long as the main branch is not modified while the feature or topic is being worked on.

1. Things can proceed as before. Changes are made and committed.

2. Slowly, it dawns on our maintainer that a new topic is needed.

3. She creates a new ```topic``` branch immediately after committing this change.

4. Having worked a little on the topic-one document, axodyne returnsat this point tomake some changes in the ```main``` branch.

5. These changes are in a different document to those made in the ```topic``` branch and so there are unlikely to be any conflicts.

6. Thus, axodyne plought on in ```main``` without any worries. After a while, it  comes time to bring in the topic and merge it with main. At that time, the recent change in ```main``` is committed and she is ready for the merge. Since the ```main``` branch is the one that ir currently active, it should be safe to simply commit this change and then run ```git merge topic```.

7. When the ```topic``` branch is merged, git cannot simply fast forward the changes on top of the existing ```main``` branch because ```main``` has changed since ```topic``` was created. Instead, a merge commit is created. It should be visible in the histry immediately before the commit for this update.

8. The default message associated with the merge commit will be pretty self-explanatory and will say something like ```Merge branch 'topic' into main```.


