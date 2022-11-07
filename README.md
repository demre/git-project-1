
- `git init`: initialize current folder as a git repository
- `git clone <URL>`: brings the git repo from <URL> to current folder
- `git status`: tells us what we need to know about our repository

- `git add <FILE>`: adds <FILE> to the stating area
- `git commit`: open a text editor to write commit message
    - `git commit -m "MESSAGE"`: writes MESSAGE as a commit without a text editor

- `git log`: shows the log (history) of our commits
    - `git log --oneline`: shows the shorter online commit

- `git diff`: compare current uncommitted state with last known git state 
    - `git diff --staged`: runs git diff between the staging area and last known state
- `git diff HEAD~<NUMBER>`: compares HEAD with commmit <NUMBER> ago (relative)
- `git diff <HASH>` : compares HEAD with the commmit in <HASH> 
