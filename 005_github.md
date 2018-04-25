# GitHub

1. Please login to your GitHub account

2. GitHub 10 min tutorial. You have now a bit of advantage for this game!
[https://guides.github.com/activities/hello-world/](https://guides.github.com/activities/hello-world/)

### Exercise 1

Let's discuss

- What is a branch?
- What is a pull request?

## Break 10 min
Let's have a small break

### Exercise 2

In pairs, exchange GitHub usernames to update each other's repos!

In order to make changes in another person's repo you need to create a copy, called a **Fork** (A **Fork** is a copy of a repo on your own account). Then, make a **Pull Request** for the owner of the repo to accept or reject your changes. This is because you cannot push directly to someone else' repo.

There are two ways to do this, depending on the needs:
1. To suggest short/small updates to one file
2. To suggest many changes to multiple files

We will do only a small suggestion to the README.md on your-neighbour/hello-world repository, this is option 1.

- Navigate to your-neighbour/hello-world repository then on the README.md file find the pen icon (remember the tutorial), pay attention and you will notice that it says : "Edit the file in your fork of this project"
- Read the message about the copy made. This is on top of the file
- Then you can suggest changes, add a message and then click on "Propose file changes".
- If you are happy with the changes, click on "Create Pull Request"

- When you receive a Pull request you can either accept it or request changes :)

Happy Git!

On the other hand, option 2 (do it on your own time after the workshop), if you are going to suggest many changes to multiple files, I will recommend you make a local copy and change files on your computer. You do not need to do this now, but when you want to do it follow these instructions. [https://help.github.com/articles/fork-a-repo/](https://help.github.com/articles/fork-a-repo/)

## Optional

Depending on time we can do the following exercises after exercise 1 and pushing exercise 2 to the end.

### Exercise 1.1 (Optional)

Let's make a copy of our online repo with **clone**,
GitHub includes the string we need to identify the repo. We will use this hello-world repo as testing ground.

```{unix}
git clone https://github.com/yourusername/hello-world.git
```
Check your online repo pointers
```{unix}
git remote -v
```
For the next part you need to type your GitHub username and password. Note: There are ways to automate this, check on [resources](./007_resources) later.

Now, that we have a remote we will always want to verify that we have the latest changes before any new changes, remember to bring changes with **pull**
```{unix}
git pull origin master
```
### Exercise 1.2 (Optional)
- On your computer add some changes to the README.md file of the hello-world repo
- Save your changes locally with a **commit**
- Check your repo
```{unix}
git status
```
- Send your changes to the online repo with **push**
```{unix}
git push origin master
```
- You might need to give your login credentials, for now, but remember this can be automated following steps from [resources](./007_resources)
- Check online that the changes are reflected

### Exercise 1.3 (Optional)

- Discuss in pairs the difference between git pull and git push
- Discuss origin and master

#### [Next: Atom](./006_atom.md)
