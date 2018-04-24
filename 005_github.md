# GitHub

1. Please login to your [GitHub](https://github.com) account or your [Ugent GitHub](https://github.ugent.be)

2. GitHub 10 min tutorial
You have now a bit of advantage for this game!

[https://guides.github.com/activities/hello-world/](https://guides.github.com/activities/hello-world/)

### Exercise 1

Let's discuss

- What is a branch?
- What is a pull request?

### Exercise 2

Let's make a copy of our online repo
GitHub includes the string we need to identify it the repo. We will use this hello-world repo as testing ground.

```{unix}
git clone https://github.com/yourusername/hello-world.git
```

Check your online repo pointers
```{unix}
git remote -v
```

For the next part you need to type your github user name and password. There are ways to automate this, links on resources.

Now that we have a remote we will always want to verify that we have the latest changes
```{unix}
git pull origin master
```
### Exercise 3
- On your computer add some changes to the README.md file of the hello-world repo
- Save your changes locally
- Save your changes to the online repo
```{unix}
git push origin master
```
- Check online

### Exercise 4
- Online add some changes to the README.md file of the hello-world repo. (look for the pen icon)
- Save your changes online
- Get the new changes back to your computer
```{unix}
git pull origin master
```
- check your local file

### Exercise 5

- Discuss in pairs the difference between git pull and git push
- Discuss origin and master

### Exercise 6
In pairs exchange GitHub user names, decide who will hold the master copy
- Clone the repo of your neighbour make changes submit and merge changes (as in the online exercise).
You have to submit a pull request because you can not push directly to someone else repo.

#### [Next: Atom](./006_atom.md)
