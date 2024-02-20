<h1>Git Command Lines</h1>

```
git status
```

- Shows the working tree status

`git diff`

- Show changes between commits, commit and working tree
- Press q to exit

`git log`

- Type q to exit log

`git config user.name "name"`

- Can add --global flag after config if you want all your projects to have same name
- To set/configure your name

`git config user.email "your@email.com"`

- Can add --global flag after config if you want all your projects to have same email
- To set/configure your email related to github

`git restore --staged .`

- Unstage all files

<h2>How to change and save files to github</h2>

1. `git add .`

- To stage all files

  1.1 `git add (file name)`

  - To stage only 1 file

2. `git commit -m "Your message here."` - <strong>Use this</strong>

- Record changes to the repository
- m stands for message

3. Use `git log` to check

4. `git push origin main`

- Push commited files to github

- `git push --force origin main`
  - Only use when you think your file is correct and not the github one

<h2>Pull file from github</h2>

`git pull origin main`

- Make sure branch is upto date before pull

`git pull --rebase origin main`

- Combining changes from a remote repository into your local branch

<h2>Creating a new branch</h2>

`git branch`

- Check branch

`git checkout -b branch-name`

- Create new branch with -b, and name of branch

`git checkout -`

- Move in and out of branch

`git checkout hello`

- Move to hello branch

`git push origin hello`

- Push to hello branch

`git branch -d hello`

- Deletes hello branch

`git push -d origin hello`

- Deletes hello branch on github

<h2>Code Block</h2>

```JS
  let string = "This is a code block";
```

<hr>

- [x] List syntax is required
- [x] This item is complete
- [ ] This item is not complete
