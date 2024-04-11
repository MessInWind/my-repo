# my-repo

## learn git

### work directory / stage / local repo / remote repo
git add => git commit => git push

### check status
git status

### check versions
git log --oneline

### link to remote repo
git remote add origin https://github.com/MessInWind/my-repo.git <br>
git branch -M main <br>
git push -u origin main

### create .gitignore file to filter files
mkdir .gitignore <br>
echo "*.log" > .gitignore

### pull latest files from remote repo
git pull origin main

### check remote repo
git remote -v

### check current branch
git branch

### setup new branch
git branch branch_name

### switch to target branch
git switch branch_name <br>
git checkout branch_name

### merge branch A into B
git merge A (current branch is B)

### delete branch
git branch -d branch_name