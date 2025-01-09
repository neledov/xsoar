git clone https://github.com/neledov/xsoar.git content
git branch -v
git remote -v
git show-ref
git checkout -b <branch>
git add <file>
pre-commit run validate
demisto-sdk pre-commit validate -g --prev-version main
git remote prune
git branch -D <branch>