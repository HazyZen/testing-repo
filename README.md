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

2. `git commit -m "Your message here."`- Use this

- Record changes to the repository
- m stands for message

3. Use `git log` to check

4. `git push origin main`

- Push commited files to github

<h2>Pull file from github</h2>

`git pull origin main`

- Make sure branch is upto date before pull
