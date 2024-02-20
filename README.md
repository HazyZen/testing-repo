# Git Command Lines

```
git status
```

- Shows the working tree status

```
git diff
```

- Show changes between commits, commit and working tree
- Press q to exit

```
git log
```

- Type q to exit log

```
git config user.name "name"
```

- Can add --global flag after config if you want all your projects to have same name
- To set/configure your name

```
git config user.email "your@email.com"
```

- Can add --global flag after config if you want all your projects to have same email
- To set/configure your email related to github

```
git restore --staged .
```

- Unstage all files

## How to change and save files to github

1. To stage all files

```
git add .
```

- 1.1 To stage only 1 file

```
git add (file name)
```

2. Record changes to the repository

```
git commit -m "Your message here."
```

- m stands for message

3. To check commit

```
git log
```

4. Push commited files to github's main

```
git push origin main
```

- `git push --force origin main`
  - Only use when you think your file is correct and not the github one

## Pull file from github

`git pull origin main`

- Make sure branch is upto date before pull

`git pull --rebase origin main`

- Combining changes from a remote repository into your local branch

## Creating a new branch

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

<hr>

## Adding an image

![Image of cat](https://images.ctfassets.net/l3l0sjr15nav/77yLiDoRKLpzsFnzoNoh3Z/37f52bdeb25a8e72574dd2312817f149/Woman-Yelling-at-Cat-Meme-Generator-Blank-Template.png)

```
![Image of woman yelling at cat meme](https://images.ctfassets.net/l3l0sjr15nav/77yLiDoRKLpzsFnzoNoh3Z/37f52bdeb25a8e72574dd2312817f149/Woman-Yelling-at-Cat-Meme-Generator-Blank-Template.png)
```

<hr>

```JS
  let string = "This is a code block";
```

<hr>

- [x] List syntax is required
- [x] This item is complete
- [ ] This item is not complete

- Syntax is `- [ ]`
- x inside will be a tick, like this `- [x]`
