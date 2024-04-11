# my-repo

## learn git

### work directory / stage / local repo / remote repo
git add => git commit => git push

### check status
git status

### check versions
git log --oneline --graph

### check diffrences between versions
git diff HEAD^3 HEAD <br>
git diff version_id_brefore version_id_after

### reset current version to former version
git reset version_id (mixed, remain working file)
git reset --hard version_id (remain nothing)
git reset --soft version_id (remain working file and stage file)

### create .gitignore file to filter files
touch .gitignore <br>
echo "*.log" > .gitignore

### link to remote repo
git remote add origin https://github.com/MessInWind/my-repo.git <br>
git branch -M main <br>
git push -u origin main

### pull latest files from remote repo
git pull origin main

### check remote repo
git remote -v

### check current branch
git branch

### setup new branch
git branch branch_name

### link new branch with remote branch
git push --set-upstream origin branch_name

### switch to target branch
git switch branch_name <br>
git checkout branch_name

### merge branch A into B
git merge A (current branch is B)

### delete branch (already merged)
git branch -d branch_name

### delete branch (not merged)
git branch -D branch_name

### merge conflict
use git status to check conflict files. <br>
modify these files manually to fix conflict. <br>
then commit changes

### abort merge process (before commit)
git merge --abort

### restore deleted branch
git checkout -b branch_name version_num

### use alias to shorten command
alias graph="git log --oneline --graph"

### rebase branch to same root
git switch branch_name
git rebase target_root_branch