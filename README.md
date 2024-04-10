# my-repo

## learn git

### work directory / stage / local repo / remote repo
git add => git commit => git push

### check status
git status

### check versions
git log --oneline

### create remote repo
git remote add origin https://github.com/MessInWind/my-repo.git
git branch -M main
git push -u origin main

### create .gitignore file to filter files
mkdir .gitignore
echo "*.log" > .gitignore

### pull latest files from remote repo
git pull origin main
