# Git as is

Let's move to the shell terminal/console/command line, if you are on Windows open GitBash.

## Is Git there?
```{unix}
git
```
### Exercise 1
- what is your version of Git?
- what happens when you type `git --help`?
- what happens when you type `git -h`?

## Introduce yourself
When we use Git for the first time, we need to configure a few things.

### Exercise 2
Use your name or nickname and the email associated with your GitHub account, for consistency.

```{unix}
$ git config --global user.name "Sam Claes"
$ git config --global user.email "sclaes@email.com"
```
We can add more options, but these are the two basic ones. You only need to do this the first time that you use Git. You can then check your options with:
```{unix}
git config --list
```

## New Project
Create a folder on your preferred location.
```{unix}
$ mkdir firstGit
$ cd firstGit
```

### Exercise 3
Once inside the folder, initiate a repository where Git can store versions of your files
```{unix}
git init
```
You need this every time you add a new project folder. Repositories should have a top level track of changes.

- Does someone knows how to see hidden files? -
We will find something interesting.

## Thing 1. Let's you tell the story of your project
```{unix}
git status
```

### Exercise 4
We can create one file, using Atom editor.
```{unix}
Atom README.md
```
Check the story of your Project
```{unix}
git status
```
## Track of changes time-stamp
```{unix}
git add
git status
```
- What does the message says?

### Exercise 5
Add some the changes following the message instructions

```{unix}
git commit -m "adding a README.md"
```
Check the story of your Project
```{unix}
git status
```

### Exercise 6
- On the README.md file write your name and the date
- Create a code file in your preferred language
- On the code file add one or two lines of code

Check the story of your Project
```{unix}
git status
```
### Exercise 7
What is our new status?

```{unix}
git commit -a "adding a README.md"
```

## Recap
- `git status`
- `git add`
- `git commit -m`
- `git status`

repeat three times!

# Break 10 min

## Thing 2. Git Let's you travel in time

We can ask Git to show us the project’s history using `git log`

### Exercise 1

- Do you remember what was the name of this long character string?
- Add "# My first Git Project" at the top of your README.md file
- Check the differences before a commit with `git diff`
- Save your changes (Recap)
- Check the differences after the commit with `git diff`
- Check the history using `git log`

## Exercise 2
- Discuss in pairs what's the difference between `git diff`, `git status` and `git log`
