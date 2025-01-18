# 1/9/2025: Git

- `git clone`: does a one-time download from github to your local computer
    - make sure the dictionary you are cloning is not already a git repo

`git add` ---> staging ; `git commit`

- `git status`: tells you what is happening in your current git repository
- `git add <FILE>`: adds <FILE> to the staging area
- `git commit -m "message"`: creates a commit (aka snapshot) with the changes in the staging area

- `git push origin main`
    - where(remote): origin; what(branch): main

- `git pull <where> <what>`

- `git config pull.rebase false`: merge the conflict files
- (use `git add <file>...` to mark resolution)
- (use `git -commit -m"..."` to conclude the merge