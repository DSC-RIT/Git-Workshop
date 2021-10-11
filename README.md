# Google Developer Student Club's Git Workshop
This workshop is aimed at equipping beginners with the fundamentals of understanding and using Git, since it’s a tool that you’ll almost definitely have to use as a developer.

This month also happens to present the greatest opportunity for beginners in open source - Hacktoberfest. And here too, Git is a necessity.

## Workshop Outline

- What is Hacktoberfest and why one should contribute towards open source.
- Version control - What and more importantly, Why?
- Some important concepts and terms
- Installing Git
- Setting up a project
- Typical git workflow
- Cloning a repo
- Creating a branch
- Adding files
- Commits
- Creating pull requests
- A few other useful git commands

# Your First Contribution
This project aims to simplify and guide the way beginners make their first contribution. If you are looking to make your first contribution, follow the steps below.

If you don't have git installed on you machine, [download it.](https://docs.github.com/en/get-started/quickstart/set-up-git)

## Fork this repository
Fork this repository by clicking on the fork button on the top right of this page. This creates a copy of this repository on your account.
<p align='center'>
  <img src='https://user-images.githubusercontent.com/55043035/136815003-6a784e21-1edd-466e-8a83-a21de23586c1.png' />
 </p>

## Clone the repository
Now, clone the forked repository to your machine. Go to you GitHub account, open the forked repository, click on the code button and then click the _copy to clipboard_ icon
<p align='center'>
  <img src='https://user-images.githubusercontent.com/55043035/136816209-3cb6585c-bc13-41e5-9b18-468eaf47c4ea.png' />
 </p>
<p align='center'>
  <img src='https://user-images.githubusercontent.com/55043035/136816351-5722025a-af7c-475d-a1db-2e03b4e37471.png' />
 </p>

Open a terminal and run the following command:
```
git clone <url you just copied>
```
where ```<url you just copied>``` is the url you copied from the clone dialog box

For example:
```
git clone https://github.com/your-github-name/Git-Workshop.git
```
where ```your-github-name``` is your github user name. This downloads a copy of the repository onto your computer

## Create a Branch
Change to the repository directory on your computer.
```
cd Git-Workshop
```
Now create a branch using the `git checkout` command 
```
git checkout -b your-branch-name
```
For example,
```
git checkout -b add-firstname-lastname
```
## Make necessary changes and commit those changes
Now, create a .txt file titled `<your-full-name>.txt` where `<your-full-name>` is your full name and in it write your full name and something about yourself.
If you now go to the project directory and execute the command `git status`, you'll see there are changes.
Add those changes to the branch you just created using the `git add` command
```
git add your-full-name.txt
```
Now, commit those changes using the `git commit` command
```
git commit -m "Add <you-full-name> to Git-Workshop"
```
replacing `<your-full-name>` with your full name

## Push changes to GitHub
Push your changes using the command `git push`
```
git push origin <add-your-branch-name>
```
replacing <add-your-branch-name> with the name of the branch you created earlier.

## Submit your changes for review
If you go to your repository on GitHub, you'll see a Compare & pull request button. Click on that button.
<p align='center'>
  <img src='https://user-images.githubusercontent.com/55043035/136821505-21a5cedd-bd6a-4bdc-9dbf-9eb9a408d23a.png' />
 </p>
Now, submit the pull request
<p align='center'>
  <img src='https://user-images.githubusercontent.com/55043035/136821659-ffbd5d96-2fab-48ad-96c3-2b8ce3ac1e65.png' />
 </p>

# Finishing Up
Congratulations! 🙌🏼👏🏼👏🏼 you've done it. You just learnt how to use Git. 
