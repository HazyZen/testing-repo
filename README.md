# testing-repo

<h1>Git Command Lines</h1>

`git status`

- Show the working tree status

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

<<<<<<< HEAD
`git pull --rebase origin main`

- Combining changes from a remote repository into your local branch
-
=======
`git something`
>>>>>>> 4b48e3a320529870e624c34027e90487fe83a8a8
