# GitHub

1. Please login to your GitHub account

2. GitHub 10 min tutorial
You have now a bit of advantage for this game!
[https://guides.github.com/activities/hello-world/](https://guides.github.com/activities/hello-world/)

### Exercise 1

Let's discuss

- What is a branch?
- What is a pull request?

### Exercise 2

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
### Exercise 3
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

### Exercise 4
- Make changes online to the README.md file of your hello-world repo. For this you need to look for the pen icon on the top right.
- Once you are on edit mode you can make changes then,
- Save your changes online, add a message and create a pull request
- Get the new changes back to your computer
```{unix}
git pull origin master
```
- check your the README file on your computer

### Exercise 5

- Discuss in pairs the difference between git pull and git push
- Discuss origin and master

### Exercise 6

In pairs, exchange GitHub user names to update each other's repos!

- On GitHub, navigate to your-neighbour/hello-world repository
- In order to make changes in another person's repo you need to create a copy called a **Fork** then make a Pull Request for the owner of the repo to accept or reject your changes. This is because you can not push directly to someone else repo.

There are two ways to do this, depending on the needs:
1. To suggest short/small updates to one file
2. To suggest many changes to multiple files

- In the top-right corner of the page, click **Fork** (this makes a copy of the repo on your own account)
- Now you can repeat steps from Exercise 4 to do changes online (which I will recommend for small changes)

On the other hand, if you are going to suggest many changes to multiple files, I will recommend you make a local copy and change files on your computer. You do not need to do this now, but when you want to do it follow the instructions on Step 3 [https://help.github.com/articles/fork-a-repo/](https://help.github.com/articles/fork-a-repo/)

- On your computer, **clone** this copy of your neighbour's repo, using the command on Exercise 2 (REMEMBER, be sure to check the name of the repo, as it might have a number at the end depending on how many times you copied the repo).
- Make changes on your local copy on your computer.
- Upload the changes to GitHub.
- Then submit
and merge changes (as in the online exercise).
You have to submit a pull request because you can not push directly to someone else repo.
