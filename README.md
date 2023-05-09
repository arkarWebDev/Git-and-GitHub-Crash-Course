# Cheatsheet for git and github absolute beginner

A cheatsheet for git and github absolute beginner .

## Author

- [@arkarWebDev](https://www.github.com/arkarwebdev)

## Resources

[git-scm download](https://git-scm.com)

## Some useful comments

Check installed version:

```bash
 git --version
 git -v
```

Download Code for another repo:

```bash
  git clone <url-from-github>
```

Create new repo:

```bash
  git init
```

Check repo status:

```bash
  git status
```

Add files to repo:

```bash
 git add <filename>
 Example: git add index.html
 Add ALL files with: git add .
```

Discard Changes:

```bash
  git restore <filename>
```

Link a local repo to GitHub:

```bash
  git remote add origin <gh-url>
  git push -u origin master
```

Ignored File :

Files that match a pattern or exact match in .gitignore.
