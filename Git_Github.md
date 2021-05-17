# Git and GitHub
### Introduction
Now, I will talk about git, github and the git commands that we learned during this first unit of the quarter.

### Development
The major difference between Git and any other VCS (Subversion and friends included) is the way Git thinks about its data. Conceptually, most other systems store information as a list of file-based changes. These other systems think of the information they store as a set of files and the changes made to each file over time (this is commonly described as delta-based version control).

Git doesn’t think of or store its data this way. Instead, Git thinks of its data more like a series of snapshots of a miniature filesystem. With Git, every time you commit, or save the state of your project, Git basically takes a picture of what all your files look like at that moment and stores a reference to that snapshot. To be efficient, if files have not changed, Git doesn’t store the file again, just a link to the previous identical file it has already stored. Git thinks about its data more like a stream of snapshots.
We used the website GitHub to save our repositories, but it is not the only one, there are others like GitLab or Bitbucket, but the teacher told us that he uses GitHub and it is very reliable so we will also use this one. GitHub is a code hosting platform for version control and collaboration. It lets you and others work together on projects from anywhere.

Now I will talk about the most common git commands that we can use when getting started with git.

**git init**

This creates a new subdirectory named .git that contains all of your necessary repository files — a Git repository skeleton.

**git config --global user.name “your_username”**

**git config --global  user.email your_email@hotmail.com**

We use this commands to configure your username and email, so your licenses are confirmed and you have a GitHub account.

**git add filename.txt**

You use this to upload in the cloud any file, it can be with the extension .txt, .md, .py or anyone text files extension.

**git status**

With this command you can check the status or your files, you can enter it after every critical command to check if everything is okay.

**git clone repositorylink**

To copy a git repository from remote source, also sets the remote to original source so that you can pull again. You need to paste the url of the repository you are cloning, it must have a .git extension.

**git commit -m “Name of your commit”**

This command commits your changes, it takes a snapshot of the changes you last made.

**git remote add origin repositorylink**

To remotely add the files to the repository, but it is not completed yet, you need to use the following command.

**git push -u origin main**

If you have added and committed your changes and you want to push them.

**git pull remote branchname**

If your remote has updated and you want those latest changes.

**git branch**

To list all the branches that you have in your repository

**git checkout –b branchname**

To swith from one branch to another

**git merge branchname**

To merge two branches you were working on.

**git log**

It shows you all the changes you have made.

**git fetch**

Fetch branches or tags from one or more other repositories, along with the objects necessary to complete their histories

**git diff**

This command is used to compare the changes or as it names says, the differences between two files.

### Conclusion
I think that this were the main commands in order to get started with git, there are way more commands but this are some very important that you most know to work in git and GitHub.
