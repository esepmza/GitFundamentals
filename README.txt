Notes from gitFundamentals

git add -u
git status
git commit -m "Updated README.txt"

git diff <xxxxxx>..<yyyyyyy>
git diff HEAD~1..HEAD
git reset --hard  # resore changes to last commit
git reset --soft HEAD~1

git clean -n|-f #removes tempfiles eg. files that is not added with git add

git log --oneline


git log --oneline --graph
git log --graph --online -all --decorate
git shortlog
git shortlog -sne  # s=summary n=number order e=email

git config --global alias.lga "log --graph --oneline --all --decorate"

new branch
git branch <branch name>
git checkout <branch name>

