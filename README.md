# Lets implement some algorithms

For those are new to open source;

Learning how to make the first step has always been the toughest steps in every journey.
Let this be a good start for your open source contributions.

In GitHub, you can save your code, update them, and work on it as a team.

You can access GitHub from your desktop, by installing git on it. Follow these links to install git on your system.

https://www.atlassian.com/git/tutorials/install-git

For contributing to this repo, you should fork it first. Then it will be like contributing to your own repo.

<img src="https://github.com/firstcontributions/first-contributions/blob/master/assets/fork.png" width="500" height="200"/>

This copies the repository to your account. After that you should download the code to your system, so that you can edit it.

This is done by:

```git clone https://github.com/<your-github-username>/Algorithms-Implementation```

Congratulations!!!
You have successfully downloaded the code to your system.

All the main changes to a repository is supposed to be in master branch. But whenever you fork a repo and update it, you should do it as a seperate branch of the repo, and then ask the maintainer to merge your updates to the master branch of the main repo.

For creating a new branch and working on it,

```git checkout -b <your-new-branch-name>```

_Your branch name can be anything_

Now you have created a new branch and started working on it.
Open a text editor and edit your code now. ( Code editor can be anything like VS Code, Atom, etc.)

After doing your updations, you should add all those changed files for saving.

```git add <file-name>```

But, you can add the changes simply by adding the current folder, like:

```git add .```

Then you should save all these changes locally to the git.

```git commit -m "<give-some-message-here>```

Now upload the changes to the GitHub.

```git push origin <your-branch-name>```

Congratulations!!! You have successfully uploaded all your changes to your forked repository.
Now, for making these changes in the actual repository, you have to ask the maintainer for that. It is called raising a pull request.
After pushing your changes, you can see a button as below, in your repo.

<img src="https://github.com/firstcontributions/first-contributions/blob/master/assets/compare-and-pull.png" width="600" height="200">

Now add a message describing the changes you have made, and send the pull request.

After verifying the changes the maintainer will either merge your pull request or cancel it.