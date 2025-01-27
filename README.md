- `git --version`
- `git config --global user.name "vaibhav"`
- `git config --global user.email "Vaibhav@gmail.com"`
- `git config --list`


-  `git init ` initializes a new Git repository
- `git status` display the current state of your working directory

- git add
    - Add a specific file:`git add filename` 
    - Add multiple files: `git add file1.txt file2.txt`
    - Add all modified files: `git add .`
- `git commit -m "Your commit message"` changes added in staging are 
- `git log` shows the commit history `Commit hash / Author / Date / Commit message `

- `git show` used to display detailed information about specific commit,branch or any other object
    - `git show` Show details of the most recent commit 
    - `git show commitId` Show details of a specific commit


### Add a remote repository to your local Git repository 
- `git remote add <name> <url>`
    - `<name>` name you want to give remote repo default `origin`
    - `<url>` URL of remote repo
- e.g. `git remote add origin https://github.com/username/repository.git`

- `git remote -v` verify the remote repo

- `git push -u origin master/main` used to push your local `(master/main)` branch to the remote repository `(origin)`
    - `-u` ( upstream ) links your branch `(master/main)` ti remote branch `(origin)`
        - This makes future pushes and pulls easier, as you can simply use `git push` and `git pull`
        