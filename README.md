# How to use Git & GitHub
Hello I'm Lucia and I'm editing this file.

### First Steps
  - `You must create a user in GitHub, You can do GitHub tutorial to know how to create a repository (optional features) `:
  - `Download git`, `if you have a Linux, Windows or Mac, you can download in this web page ->` https://git-scm.com/downloads :
  - `Git is a distributed version control system(DVCS) created by the Linux team. It is a currently used by many version cotrol servers, such as GitHub, BitBucket or GitLab, in this case we are going to use GitHub`:

### Git installation and setup
  - `Git installation depends on the operating system in which we want to install it`:
  - `For Linux systems we just need to run the specified command to install Git. For instance, in Ubuntu systems we need to run this command -> sudo apt-get install git `:
  - `For Windows and Mac, we need to go to Git web site (go to first step for see link of web site)  and download the appropriate version. Regarding Mac, you can also install Git by installing XCode.`:
  - `1.- Git setup`:
      - `1.1 Open Git Bush`:
      - `First of all, let's define our full name through this comand ( replace "Enter your full name here" with your real name`:
      - `Use this comand -> git config --global user.name "Enter your full name here" `:
      - `Next, we specify the e-mail with which we created our GitHub account ( replace "yourEmail@server.com" whith your real Email)`:

### Git commands for your repository
- `git init `(If we want to initialize or create a new local repository, first we need to create the folder in which this project is going to be stored. Then, we can initialize it as a Git repository with this command (from inside project folder)): 
- `git clone <with-name-our-repository> `(git clone is a command to download the existing source code from a remote repository (such as Github, for example).):
- `git branch <branch-name>`(We can use the git branch command to create, list and delete them.)
- `git status`(The git status command gives us all the necessary information about the current branch.): 
- `git add .<name file>`(When we create, modify or delete a file, these changes happen locally and will not be included in the next commit (unless we change the configuration). We need to use the git add command to include the changes to the file(s) in your next commit.):
- `git commit -m "message"`(Git commit is like setting a checkpoint in the development process that you can return to later if necessary. We also need to write a short message to explain what we have developed or modified in the source code.):
- `git show` (this shows the changes made in the last commit):
- `git push`(Git push sends your commits to the remote repository.):
- `git --soft` maintains changes to the staging.
- `git reset --mixed` removes changes from staging but keeps them in the working directory.
- `git reset --hard` removes the changes completely, both in the staging and the working directory.
