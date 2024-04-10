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
git push -u origin main <br>

### create .gitignore file to filter files
mkdir .gitignore <br>
echo "*.log" > .gitignore

### pull latest files from remote repo
git pull origin main

### check remote repo
git remote -v
