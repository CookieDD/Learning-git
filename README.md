# Learning-git

This repo was used to learn git from YouTube.

Three stages:
1. git add: we can used "git diff" before add to check the changes. if added, we use "gid diff --cached" (double dashes)
        --git diff only checks the difference between Working Area and Stage.
        --git diff --cached checks the difference between Stage and Local Repo
3. git commit -m "comment"
4. git push

Fourour areas:
1. working area
2. stage
3. local repository
4. remot repository

Five stages:
1. Origin -> unchanged
2. Modified -> as the name
3. Staged -> temp saved
4. commited -> submitted
5. pushed -> just pushed as the name describes.

Undo actions:
1. Before ADD:
      git checkout
      OR
      git reset --hard
2. Once ADDed:
      git reset         only change back to the status before ADD
      git checkout      changes to unedited status
      git reset --hard  change all the way back to unedited status
3. Once COMMITED:
      git reset --heard origin/master (origin/master denotes remot repo)
4. Once PUSHED:
      git reset --heard HEAD^
      git push -f
