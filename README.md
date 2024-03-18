# bbg
2
$ git checkout master
$ git checkout -b feature-branch
$ git add . 
$ git commit -m "Your commit message for feature-branch"
$ git checkout master
$ git merge feature-branch

6
$ git checkout master 
$ git merge feature-branch -m "Your custom commit message here"

8
$git cherry-pick <start-commit>^..<end-commit> 
$ git cherry-pick ABC123^..DEF456

12
$ git revert abc123




