git clone https://github.com/neledov/xsoar.git content
git branch -v
git remote -v
git show-ref
git checkout -b <branch>
git add <file>
pre-commit run validate
demisto-sdk pre-commit --template-path '.pre-commit-config.yaml' --verbose validate  -g --prev-version main

$HOME/.demisto-sdk/logs

git remote prune
git branch -D <branch>


Since content items run in containers with different Python versions and dependencies, this command matches content items with similar configurations before passing the generated temporary .pre-commit-config.yaml file.